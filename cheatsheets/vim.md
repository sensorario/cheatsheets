# Vim

## Moving

### Normal mode

- `0`: moves the cursor at the beginning of line
- `$`: moves the cursor at the end of line

## Editing

### Normal mode

- `.`: repeat the last changes
- `u`: undo the last change
- `x`: deletes the character under the cursor
- `dd`: deletes an entire line
- `>`: increses the indentation of the current line

## Find and replace

### Normal mode

| Intent                               | Act                    | Repeat | Reverse |
|--------------------------------------+------------------------+--------+---------|
| Make a change                        | `{edit}`               | `.`    | `u`     |
| Scan line for next character         | `f{char}               | `;`    | `,`     |
| Scan line for previous character     | `F{char}`              | `;`    | `,`     |
| Scan document for next match         | `/pattern<CR>`         | `n`    | `N`     |
| Scan document for the previous match | `?pattern<CR>`         | `n`    | `N`     |
| Perform substitution                 | `:s/target/replacement | `&`    | `u`     |


## Switching between models

### Normal --> Insert

- `A`: switch in `Insert mode` and move the cursor to the end of the line (squash `$a` into a single keystroke)
- `a`: appends after current cursor position
- `C`: deletes from the cursor to the end of line (squash `c$`)
- `S`: deletes the current line
- `s`: delete the character under the cursor
- `I`: moves the cursor at the beginning of line
- `o`: create a new line after the current
- `O`: create a new line before the current

