# Jack package for Sublime Text

This is a [Sublime Text][sublime] package which provides syntax highlighting and a build script for the Jack language used in [Nand2Tetris][n2t] projects and the book [The Elements of Computing Systems][book].

## Installation

### Pre-bundled Package

Clone this repository and move the Jack.sublime-package file into your Sublime Text package folder

If you're on Windows, also replace your JackCompiler.bat file with the supplied, modified one.

Lastly, add the nand2tetris/tools folder to your PATH variable and you're set.

### Move Over Source

Alternately, if you can't or don't want to modify the PATH variable, you can copy the contents of the src folder into the user package folder.
You still need the modified version of JackCompiler.bat if you're on Windows.

You may need to modify the sublime-build file to include a direct path to the executable.

## Features

The package includes basic syntax highlighting and a build script.

[sublime]: http://www.sublimetext.com/
[package_control]: http://wbond.net/sublime_packages/package_control
[n2t]: http://www.nand2tetris.org
[book]: http://www.amazon.com/Elements-Computing-Systems-Building-Principles/dp/0262640686/ref=ed_oe_p
