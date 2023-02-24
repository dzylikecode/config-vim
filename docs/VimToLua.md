# convert vim to lua

## use vim script syntax in lua

- [Converting neovim config to lua](https://www.imaginaryrobots.net/posts/2021-04-17-converting-vimrc-to-lua/)

```vim
let g:obj = {}
```

```lua
vim.g.obj = {}
```

```lua
vim.cmd [[
    let g:obj = {}
]]
```

---

```vim
source ~/.config/nvim/lua/config/setting.lua
```

```lua
require('config.setting')
```

```lua
vim.cmd [[
    source ~/.config/nvim/lua/config/setting.lua
]]
```
