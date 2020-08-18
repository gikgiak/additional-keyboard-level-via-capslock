This layout wants to satisfy the following two principles:
	- Intrduce very little changes as possible to the standard layout (here the us layout is used).
	- Make the inky finger of the right hand travel only short distances while programing, typing in latex and using vim.
	- Create a layout that does not rely on the "symobl keys" too much since those keys tend to be in different places on various laptops.

There are only three differences to the standard us-keyboard:
1) The key with the apostrophe, only when pressed alone, becomes Shift.
2) The space bar and shift when pressed together produce an underscore.
3) The Capslock key becomes a modifier that, when pressed, gives access to the following layer:
	[equal, plus, minus]  on the keys for [u, i, o],
	[0, Enter, Backspace, Dollar, Backslash, apostrophe] on the keys that where for [h, j, k, l, semicolon, apostophe],
	[close parentesis, close square bracket, close curly bracket and bar] on the keys for [n, m, comma, dot].

Notice that this way we can type the apostrophe by pressing the former apostrophe key together with Capslock.

Set your layout to the standard us layout and then run the comand xmodmap save_inky.xmodmap to activate this changes. You might undo this with: 'setxkbmap -layout us'.

For the future I would like to add a further level accessible though Tab to obtain vim navigation key-bindings and implement this keyboard in xkb. While this layout is based on the us layout something similar may be easily archived for any other layout. Just type 'xmodmap -pke' into the terminal to see your current keymappings and modify those where needed.

