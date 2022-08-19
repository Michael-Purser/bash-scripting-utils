# Bash Scripting Utils

This repository contains a set of utility functions for bash scripts.
They are by no means complete, and subject to constant change depending on my needs.
I am making this public in case someone finds this helpful.

Summary:
- `execution`: <br>
  Contains a wrapper to execute bash commands.
  Also makes it possible to execute commands in dry-run mode (useful for debugging).
  In that case, make sure you have enabled debug-level logging (see `logging` below).
- `logging`: <br>
  Small logging library.
  It is possible to toggle the verbosity level and the display of datetime information.
- `validation`: <br>
  Set of validation functions for checking inputs, etc...
  These functions all follow the same paradigm: as soon as a check fails, print an error message and exit.

## Usage
1. Clone this repository (or add it as a submodule to your project).
1. `source` the files of this repository at the top of your bash scripts.
1. You can now use the functions contained within these files.

## Examples
Some examples can be found in the `examples` folder.

## Issues/Suggestions
If you have suggestions or want to report a bug:
- Open an issue.
- Alternatively, add/fix it yourself and open a pull request.
