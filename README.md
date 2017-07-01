
# Beginners-documentation

**Beginners-documentation** is a repository of instructions and guidelines for using Linux with a UNIX founded approach inteded primarily for new Linux users.

Directories are divided by related tasks.

### set-up-install/

Set up and install instructions and guidelines.

## Recommendations

There are foundational shell solutions within the application layer to increase computational efficiency. These are the type of solutions [*linux-shell-base*][linux-shell-base] was created for. When creating a custom Linux environment, there are some essential ones to consider. This is a recommendation of them (from *linux-shell-base*) for new Linux users:

#### Solutions for core aspects of the Linux operating system *(file, hardware, networking, x11, etc.)*

##### ... without output

* [Perform one of multiple window actions.](https://github.com/linux-shell-base/linux-shell-base/blob/master/bin/main-no-output/x11/wind)

##### ... modules (scripts used in conjuction with a command)

* [Run a command in the background.](https://github.com/linux-shell-base/linux-shell-base/blob/master/bin/main-modules/shell/runinbg)

#### Solutions for core aspects of the Linux operating system *(file, hardware, networking, x11, etc.)* providing output only *(no actions performed)*

##### ... as single-value for other programs

* [(X11 - all)](https://github.com/linux-shell-base/linux-shell-base/tree/master/bin/output-single-value#x11)

#### Utility modules for command-line programs

* [Return a file for a command by either locating or recursively searching for it.](https://github.com/linux-shell-base/linux-shell-base/blob/master/bin/modules/file/returnfileforcmd)
* [Execute a command and an action on the resulting window.](https://github.com/linux-shell-base/linux-shell-base/blob/master/bin/modules/x11/execmdandwindact)

#### Utilities

* [Open a new terminal and optionally run an initial command in it.](https://github.com/linux-shell-base/linux-shell-base/blob/master/bin/utilities/general/newterm)
* [Execute a given command in (or run the last command of) a terminal emulator.](https://github.com/linux-shell-base/linux-shell-base/blob/master/bin/utilities/keybind/termcommand)

#### Bash utility functions

* [(all)](https://github.com/linux-shell-base/linux-shell-base/tree/master/bin/bash_utilities#bash_utilities)



[linux-shell-base]: https://github.com/linux-shell-base/linux-shell-base
