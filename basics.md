## Vim Basics

- `Esc` always brings you back to command mode

### Editing text

- `i` / `a` - Start insert mode at/after cursor
- `I` / `A` - Start insert mode at the beginning/end of the line
- `Esc` or `Ctrl+[` - Exit insert mode
- `d` - Delete
- `dd` - Delete line

### Marking text (visual mode)

- `v` - Start visual mode
- `V` - Start linewise visual mode
- `Ctrl+v` - Start visual block mode
- `Esc` or `Ctrl+[` - Exit visual mode

### Clipboard

- `yy` - Yank (copy) a line
- `p` - Paste after cursor
- `P` - Paste before cursor
- `dd` - Delete (cut) a line
- `x` - Delete (cut) current character
- `X` - Delete (cut) previous character
- `d` / `c` - By default, these copy the deleted text

### Exiting

- `Esc` + `:w` - Write (save) the file, but don't quit
- `Esc` + `:wq` - Write (save) and quit
- `Esc` + `:q` - Quit (fails if anything has changed)
- `Esc` + `:q!` - Quit and throw away changes

### Search/Replace

- `/pattern` - Search for pattern
- `?pattern` - Search backward for pattern
- `n` - Repeat search in same direction
- `N` - Repeat search in opposite direction

### General

- `u` - Undo
- `Ctrl+r` - Redo