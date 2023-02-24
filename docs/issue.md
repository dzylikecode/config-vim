# issue

## wsl 的 nvim 如何与 windows 的 clipboard 互通

`:help clipboard`, `:help clipboard-wsl`

## tab to space

```vim
" Tabs
set expandtab     " Tab transformed in spaces
set tabstop=2     " Sets tab character to correspond to x columns.
                  " x spaces are automatically converted to <tab>.
                  " If expandtab option is on each <tab> character is converted to x spaces.
set softtabstop=2 " column offset when PRESSING the tab key or the backspace key.
set shiftwidth=2  " column offset when using keys '>' and '<' in normal mode.
```
