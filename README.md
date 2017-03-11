# VimCheatSheet



Mapping		|	Summary
----------------|------------------
<esc>		| Exit out of any mode back into normal mode
:q or :quit	| Quit out of Vim
:w or :write	| Write the current file
j, k		| Move the cursor down / up
h, l		| Move the cursor left / right
i		| Go into "insert mode" to enter text
x		| Delete the character under the cursor
h, l		| move left/right by character
w		| move forward one (w)ord
b		| move (b)ackward one word
e		| move forward to the (e)nd a word
f<char>		| (f)ind a character forward in a line and move to it
t<char>		| find a character forward in a line and move un(t)il it (one character before)
F<char>		| (f)ind a character backward in a line and move to it
T<char>		| find a character backward in a line and move un(t)il it
;		| repeat last f, t, F, or T command
,	 	| repeat last f, t, F, or T command, but in opposite direction
j, k	  	| move up/down one line
H, M, L	  	| move (H)igh, (M)iddle, or (L)ow within the viewport
/	 	| search
n		| repeat last search
N	        | repeat last search in opposite direction
C-u, C-d	| move (u)p or (d)own
<NN>G,:<NN>	| (G)o to line number NN (useful if you have a failing test on a given line)
