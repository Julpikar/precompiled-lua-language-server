Precompiled lua-language-server (https://github.com/sumneko/lua-language-server) for Windows.

Extracted from https://marketplace.visualstudio.com/items?itemName=sumneko.lua

Instruction to minimum setting nvim-lspconfig sumneko_lua (https://github.com/neovim/nvim-lspconfig#sumneko_lua) for Windows.
```lua
require'lspconfig'.sumneko_lua.setup{
  cmd = {"path to /precompiled-lua-language-server/bin/Windows/lua-language-server.exe", "E", "-e", "Lang=en","path to /precompiled-lua-language-server/main.lua"};
  ...
}
```
