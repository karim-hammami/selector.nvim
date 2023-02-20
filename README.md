# selector.nvim
doing cool neovim stuff (select entire function, select entire function and copy, open netrw in float menu, open netrw in split)

## Installation
```lua
use "karim-hammami/selector.nvim"
```

## Usage
```lua
vim.keymap.set("n", "<A-e>", require "selector".select)
vim.keymap.set("n", "<A-p>", require "selector".selectCopy)
vim.keymap.set("n", "<A-n>", require "selector".float)
vim.keymap.set("n", "<A-m>", require "selector".split)
```

## Credits
- @David-Kunz select implementation [treesitter-unit](https://github.com/David-Kunz/treesitter-unit)
