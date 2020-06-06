A-new-keyboard-level-via-capslock

The main aim of this file is to create a keyboard layout that satifies the following two principles:
	- Intrduce as little changes as possible to the existing layout.
	- Make the inky finger of the left hand move as little as possible while programing, typing in latex and using vim.

This file was created based on the us layout but something similar can be easily reproduced for any other layout.
Just type 'xmodmap -pke' into the terminal.

The apostrophe key is now Shift. The Capslock key when pressed gives access to the following layout:

qwert/=+-';  instead of qwertyuiop
asdfg0<Enter><Backslash>$\' instead of asdfghjkl;°
zxcvb({[ instead of zxcvbnm,

Run the comand xmodmap no_caps.xmodmap in the terminal.

For the future I would like to add a further level accessible though Tab to obtain vim navigation key-bindings.
Also using X keyboard extension might be more convenient.
