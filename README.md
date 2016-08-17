# ColobotSyntaxHighlighting #

Package for Sublime Text 3 adding syntax highlighting for CBOT, Colobot Scene and SatCom help files. See [Colobot](https://github.com/colobot/colobot) project.

## Installation ##

**Note:** The package uses new `sublime-syntax` format, therefore it won't work with Sublime Text version lower than 3084. Especially Sublime Text 2 is not going to be supported by this package.

Use [Package Control](https://packagecontrol.io/) to install the package, if it's available.

If it's not, download or clone the repository to `~/.config/sublime-text-3/Packages/` (in Linux) or `%APPDATA%\Roaming\Sublime Text 3\Packages\User` (in Windows).

## Usage ##

Sublime Text should automatically detect a CBOT, SatCom or Scene file if the first line begins with respectively `extern void object::[...]()`, `\b;` or `Title[...]`. You can also set the syntax manually by pressing Ctrl + Shift + P for the command palette and entering `cbot`, `colo` or `scen` (it will probably match `Set Syntax: CBOT`, etc.).

## Screenshots ##

Screenshots show the default Monokai theme, but the package will probably work with any theme.

### SatCom ###

![screenshot](http://i.imgur.com/OH2XUFG.png)

### CBOT ###

![screenshot](http://i.imgur.com/Ma10tTS.png)

### Scene ###

![screenshot](http://i.imgur.com/BVGBNBz.png)

## License ##

```
    This file is part of ColobotSyntaxHighlighting, a package for Sublime Text 3.
    Copyright (C) 2016  Mateusz Przybył

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
```
