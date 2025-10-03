# nvim-statusline

A Neovim statusline plugin scaffold.

## Layout
```
nvim-statusline/
├─ .stylua.toml
├─ .luarc.json
├─ README.md
└─ lua/
   └─ nvim-statusline/
      └─ init.lua      # Implementation (copied verbatim from your uploaded statusline.lua)
```

## Install (Neovim 0.12+ vim.pack)
```lua
vim.pack.add({ url = 'https://github.com/<you>/nvim-statusline' })
```

## Setup/Usage
If your module exposes a `setup` function:
```lua
require('nvim-statusline').setup({
  -- your options here
})
```

Or just:
```lua
require('nvim-statusline')  -- if it self-initializes
```

## Dev Notes
- Code style is controlled by `.stylua.toml` at the repo root.
- lua-language-server settings live in `.luarc.json`.
