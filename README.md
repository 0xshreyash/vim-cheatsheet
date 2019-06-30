# vim-cheatsheet

### Commands for insert mode

```
ESC - Leave insert mode to go into command mode
```

### Commands for normal (command) mode

```
h, j, k, l - Move left, down, up and right respectively

i - go into insert mode at the current cursor position

a - go into insert mode to the right of the current cursor position

:w - to save the file

:q! - to close the file (quit)

w - move to the start of the next word

b - move to the start of the previous word

e - move to the end of the next word

A - insert at the end of the current line

I - insert at the start of the current line

v - enter visual mode (allows for selection of text) by moving around using h, j, k, l

x - delete the character at the current cursor position

X - delete the character to the left of the current cursor position

r - Replace character at the current position with new character. rb is equivalent to using x and then going into insert mode with i and typing in a b

o - Add a line after the current line and insert at the start of this new line

O - Add a line before the current line and insert at the start of this new line

$ - Go to the end of the current line without entering insert mode

g_ - Go to last char in line

0 - Go the the start of the current line without entering insert mode

CTRL-c - Go to first char in line

dw - Delete a word

dd - Delete a line

yy - Copy a line

cw - Change a word to another word. Equivalent to doing a dw followed by an insert

p - Paste whatever was last copied/deleted

zz - Move the page such that the cursor position is at the middle of the visible window

zt - Move the page such that the cursor position is at the top of the visible window

zb - Move the page such that the cursor position is at the bottom of the visible window

% - Go to matching brace

gi - Go into insert mode at the position where insert mode was last active

u - Undo previous command

CTRL-r - Redo previous command

. - Perform previous command again

f -

t - 

F -

T -

/word - Find the occurance of "word" in the file

n - Go to the next occurance of a word in the file

N - Go to the previous occurance of a word in a file

V_u - Selecting something in visual mode and making the selected text lowercase

V_U - Selecting something in visual mode and making the selected text uppercase

V_~ - Selecting something in visual mode and flipping the case

:reg - Show all registers

"[reg-name][y|d] - to interact with a specific register

:ls     - Show all buffers

:b{n}   - Go to buffer n

:b[p|n] - Go to the previous/next buffer

m{m} - set mark on register m

`{m} - go to mark set in register m
```
### Miscellaneous
```
* - this register represents the system clipboard
```


### Advanced commads

Commands useful for modifying variables of the form: this_is_a_variable_name

```
ct_ - change word till the first underscore you encounter (not including the underscore)

cf_ - change word till the first underscore you encounter including the underscore

dt_ - delete word till the first underscore you encounter (not including the underscore)

df_ - delete word till the first underscore you encounter including the underscore

f_ - move to the next underscore

```














