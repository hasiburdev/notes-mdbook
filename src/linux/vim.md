# Vim

## Vim Motions

One of the main part of vim is it's motions.

### Horizontal Motion

- `_` => Move to the starting character of current line.
- `$` => Move to the end of current line.
- `0` => Move to the beginning of the current line.

`f` + `any character` moves to that character forward. `;` and `,` are the keys to navigate forward and backward.
`F` + `any character` moves to that character backward.

### Vertical Motion

- `{` move up by paragraph.
- `}` move down by paragraph.

- `Ctrl` + `d` => Jump half page down.
- `Ctrl` + `u` => Jump half page up.
- `gg` => Move to the top of the page.
- `G` => Move to the bottom of the page.

## Searching

Searching something in vim.

- Typing `/` in command mode with start searching whatever is typed after it. Typing `n` will go to the next search result. `N` will go to the reverse direction.
- Typing `?` will start a backward search where `n` will go to the previous results.
- Typing `*` will search the word the cursor is currently in.
- Typing `#` will search the current word in reverse order.

## Files

- `%` on the file tree page to create a new file.

### Saving files in Vim

There are multiple ways to save files and exit vim.

- `:wq`
- `:x`
- `Shift+zz`

## Additional Features

### Spell Checker

- To enable spell checker, use the following command.
`:set spell`
- To disable spell checker, use the command:

### Change letter casing

To change a letter from uppercase to lowercase or reverse, use `~`.

---

Lsp commands

- `gd` => Goto definition.

- Telescope
  - `<leader>ws` => Workspace symbols.
  - `<Space>ds`  => Document symbols.
