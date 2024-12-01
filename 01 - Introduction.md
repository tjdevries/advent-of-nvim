# Introduction to Neovim

## Why Do I Use Neovim?

## Why Do I Use Neovim?

- I find it very satisfying to make things just the way I like
- It makes my day more fun - both hacking on it and eliminating frustrations
- I like modal editing - it clicks with my brain.

## How to Use Neovim?

- Download and/or Package Manager:
    - https://neovim.io/doc/
- Build From Source:
    - https://github.com/neovim/neovim/blob/master/BUILD.md

## First Configuration:

- Open `$HOME/.config/nvim/init.lua`
- `print("Hello World")` in `init.lua`
- Re-open Neovim, check `:messages`

## Reload Configuration:

- `:source %`
- `:lua ...` or `:'<,'>lua`
