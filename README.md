<p align="center">
  <h2 align="center">DeepWhite</h2>
</p>

## About

This is fork of [DeepWhite.nvim](https://github.com/Verf/deepwhite.nvim/tree/main).

## Installation

```lua
-- for packer.nvim
use {
    'Tsuyopon-1067/deepwhite.nvim',
    config = function()
        vim.cmd [[colorscheme deepwhite]]
    end,
}

-- for lazy.nvim
{
    'Tsuyopon-1067/deepwhite.nvim',
    config = function()
    lazy = false,
    priority = 1000,
    config = function()
        vim.cmd [[colorscheme deepwhite]]
    end,
}
```
