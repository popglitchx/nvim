# My Neovim Config

Based on Kickstart.nvim with some customizations.

## What's Included

- **LSP Servers**: pyright (Python), gopls (Go), clangd (C/C++)
- **Completion**: blink.cmp with luasnip
- **Snippets**: friendly-snippets (VSCode-style)
- **Formatter**: ruff (Python), stylua (Lua)
- **Treesitter**: Syntax highlighting for multiple languages
- **Autopairs**: Auto-closing brackets and quotes

## Keymaps

- `Space + ;` - Enter command mode
- `jk` (insert mode) - Exit insert mode
- `Space + pv` - Open file explorer
- `Space + r` - Run current file in terminal
- `Ctrl + h/j/k/l` - Switch between windows
- `Space + f` - Format code

## First Time Setup

1. Open nvim and run `:Lazy` to install plugins
2. Run `:Mason` to install LSP servers (pyright, gopls, clangd, ruff)

~~3. Run `:TSInstall all` to install Treesitter parsers~~ Don't mind the stupid AI

## Running Code

- `Space + r` opens a terminal at the bottom to run the current file
- Works for: Python, Go, C, C++, JavaScript, Lua, Bash, Rust

## Customizations Made

- Added LSP servers: pyright, gopls, clangd
- Added ruff formatter for Python
- Added friendly-snippets
- Added autopairs
- Custom keymaps for running files and file explorer
