# Bash Scripting Utils

## Purpose
I find myself repeating boiler-plate code when creating bash scripts.
I therefore grouped the most common functions I use into the scripts in this repository for re-use in other bash scripts.

They are by no means complete, and subject to constant change depending on my needs.
However, I am still making this public for the case someone finds this helpful.

Summary:
- `execution`: <br>
  Contains a wrapper to execute bash commands. Also makes it possible to execute commands in dry-run mode (useful for debugging). In that case, make sure you have enabled debug-level logging (see `logging` below).
- `logging`: <br>
  Small logging library. It is possible to toggle the display of datetime information and of debug-level messages.
- `validation`: <br>
  Set of validation functions for checking inputs, etc...
  These functions all follow the same paradigm: as soon as a check fails, print an error message and exit.

## Usage
1. Clone this repository (or add it as a submodule to your project).
1. `source` the files of this repository at the top of your bash scripts.
1. You can now use the functions contained within these files.

## Issues/Suggestions
If you have suggestions or want to report a bug:
- Open an issue.
- Alternatively, add/fix it yourself and open a pull request.
