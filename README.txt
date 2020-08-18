A-new-keyboard-level-via-capslock

The main aim of this file is to create a keyboard layout that satifies the following two principles:
	- Intrduce as little changes as possible to the previously existing layout.
	- Make the inky finger of the left hand moves as little as possible while programing, typing in latex and using vim.

This file was created based on the us layout but something similar can be easily reproduced for any other layout.
Just type 'xmodmap -pke' into the terminal to see your current keymappings and modify those where needed.

The apostrophe key is now Shift. The Capslock key when pressed gives access to the following layout:

qwert/=+-'  instead of qwertyuiop
asdfg0<Enter><Backslash>$\' instead of asdfghjkl;°
zxcvb({[ instead of zxcvbnm,

Run the comand xmodmap save_inky.xmodmap in the terminal to activate this changes. You can undo this with: 'setxkbmap -layout it' (or any other standard keyboard as 'us' or 'de').

For the future I would like to add a further level accessible though Tab to obtain vim navigation key-bindings.
Also using X keyboard extension might be more convenient.
