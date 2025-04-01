# Minishell

## Project Description

This project involves creating a simple Unix shell (minishell) that behaves like the bash shell, supporting various built-in commands, redirections, pipes, environment variables, and signal handling.

### Features:

- **Prompt**: Display a prompt when waiting for a new command.
- **History**: Maintain a working history for previously entered commands.
- **Path Resolution**: Search and launch executables based on the PATH variable or relative/absolute paths.
- **Quoting**: Handle single (' ') and double (" ") quotes to prevent interpretation of meta-characters.
- **Redirections**:
  - `<` redirect input
  - `>` redirect output
  - `<<` here document input
  - `>>` append output
- **Pipes**: Implement pipe (`|`) handling for command chaining.
- **Environment Variables**: Support expansion for `$` followed by variable names and `$?` for the last exit status.
- **Built-in Commands**:
  - `echo` with the `-n` option.
  - `cd` with only relative or absolute paths.
  - `pwd` with no options.
  - `export` with no options.
  - `unset` with no options.
  - `env` with no options or arguments.
  - `exit` with no options.
- **Signal Handling**:
  - Ctrl-C: Display a new prompt.
  - Ctrl-D: Exit the shell.
  - Ctrl-\: Do nothing.

### Usage

To run the shell, use:
```
./minishell
```
