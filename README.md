# Bash Scripting Utils

This repository contains a set of utility functions for bash scripts.
They are by no means complete, and subject to constant change depending on my needs.
I am making this public in case someone finds this helpful.

- `bash-scripting-utils`: <br>
  Sources all other files listed below.
  Useful for including in your scripts.
- `execution`: <br>
  Makes it possible to execute commands in dry-run mode (useful for debugging).
  Also makes possible to log the output of commands to file, while keeping terminal output quiet (see also `logging` below).
- `logging`: <br>
  Small logging library.
  It is possible to toggle the verbosity level and the display of datetime information.
  It is also possible to log to file.
- `time`: <br>
  Utils for timing execution, ...
- `validation`: <br>
  Set of validation functions.
  They all follow the same paradigm: as soon as a check fails, print an error message and exit.

## Usage
1. Clone this repository (or add it as a submodule to your project).
1. `source` the files of this repository at the top of your bash scripts (sourcing `bash-scripting-utils` will source all files and is therefore a handy shortcut).
1. You can now use the functions contained within these files.

## Examples
Some examples can be found in the `examples` folder.

## Issues/Suggestions
If you have suggestions or want to report a bug, open an issue or add/fix it yourself and open a pull request.
