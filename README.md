SublimeLinter-coffee
=========================

[![Build Status](https://travis-ci.org/szhu/SublimeLinter-contrib-cjsx.svg?branch=master)](https://travis-ci.org/szhu/SublimeLinter-contrib-cjsx)

This linter plugin for [SublimeLinter](http://sublimelinter.readthedocs.org) provides an interface to the [coffee-react compiler](https://github.com/jsdf/coffee-react). It will be used with files that have the “CJSX” syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If SublimeLinter 3 is not installed, please follow the instructions [here](http://sublimelinter.readthedocs.org/en/latest/installation.html).

### Linter installation
Before installing this plugin, you must ensure that `cjsx` is installed on your system. To install `cjsx`, do the following:

1. Install [Node.js](http://nodejs.org) (and [npm](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) on Linux).

1. Install `cjsx` by typing the following in a terminal:
   ```
   npm install -g coffee-react
   ```

1. If you are using `nvm` and `zsh`, ensure that the line to load `nvm` is in `.zshenv` and not `.zshrc`.

**Note:** `cjsx` 1.5 or later is required for use with this plugin.

### Linter configuration
In order for `cjsx` to be executed by SublimeLinter, you must ensure that its path is available to SublimeLinter. Before going any further, please read and follow the steps in [“Finding a linter executable”](http://sublimelinter.readthedocs.org/en/latest/troubleshooting.html#finding-a-linter-executable) through “Validating your PATH” in the documentation.

Once `cjsx` is installed and configured, you can proceed to install the SublimeLinter-coffee plugin if it is not yet installed.

### Plugin installation
Please use [Package Decontrol](https://github.com/jfromaniello/Sublime-Package-Decontrol) to install the linter plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Decontrol, do the following:

1. Within Sublime Text, bring up the [Command Palette](http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html) and type `install`. Among the commands you should see `Package Decontrol: Install from Github`. If that command is not highlighted, use the keyboard or mouse to select it.

2. Type `szhu/SublimeLinter-contrib-cjsx` and press Enter.

## Settings
For general information on how SublimeLinter works with settings, please see [Settings](http://sublimelinter.readthedocs.org/en/latest/settings.html). For information on generic linter settings, please see [Linter Settings](http://sublimelinter.readthedocs.org/en/latest/linter_settings.html).

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. Be patient.  ;-)

Please note that modications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
