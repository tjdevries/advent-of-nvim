# Package Manager

## Package Manager

Going to use `lazy.nvim`
- https://lazy.folke.io/installation

NOTE: which is different from LazyVim

## Install

(follow instructions)

`:checkhealth lazy`

## Install a colorscheme

- Tokyo Night Color Scheme
    - https://github.com/folke/tokyonight.nvim

```lua
{ "folke/tokyonight.nvim", config = function() vim.cmd.colorscheme "tokyonight" end }
```

## Install `mini`

- Mini.nvim
    - https://github.com/echasnovski/mini.nvim

- Setup statusline

```lua
-- lua/custom/plugins/mini.lua
return {
    {
        'echasnovski/mini.nvim',
        config = function()
            local statusline = require 'mini.statusline'
            statusline.setup { use_icons = true }
        end
    }
}
```
