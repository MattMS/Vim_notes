# Enter visual mode

Each command will enter visual mode after the action is done.

Once in visual mode, you can navigate the same as normal mode.


## Character

Select character at cursor.
: `v`

Select word from any character.
: `viw`

Select to end of word.
: `ve`


## Visual Line (row)

Select current line.
: `V`
: `Shift+v`


## Visual Block (column)

If you enter insert mode (`a` or `i`) with a selection then your changes
will apply to each line at the selected column.

Select character at cursor.
: `Ctrl+v`
