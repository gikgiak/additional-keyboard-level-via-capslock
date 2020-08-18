The main aim of this project is to create a keyboard layout that satifies the following two principles:
	- Intrduce very little changes as possible to the previously existing layout.
	- Make the inky finger of the right hand travel only short distances while programing, typing in latex and using vim.
	- Create a layout that does not rely on the "symobl keys" too much since those keys tend to be moved to different places in various laptops.

There are only three differences to the standard us-keyboard:
1) The key with the apostrophe, only when pressed alone, becomes Shift.
2) The space bar and shift when pressed together produce an underscore.
3) The Capslock key becomes a modifier that, when pressed, gives access to the following layer:
	=+-p  on the keys for uio
	0<Enter><Backslash>$\' on the keys that where for for hjkl;'
	)]}| on the keys for nm,.

Notice that these way we can type the apostrophe by also pressing Capslock.

Set your layout to the standard us layout and then run the comand xmodmap save_inky.xmodmap to activate this changes. You might undo this with: 'setxkbmap -layout us'.

For the future I would like to add a further level accessible though Tab to obtain vim navigation key-bindings and implement this keyboard in xkb.

While this layout is based on the us layout but something similar may be easily archived for any other layout.
Just type 'xmodmap -pke' into the terminal to see your current keymappings and modify those where needed.

