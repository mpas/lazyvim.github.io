# Colorscheme

Example for changing the colorscheme to [Gruvbox](https://github.com/ellisonleao/gruvbox.nvim):

```lua title="lua/plugins/colorscheme.lua" {2,8}
return {
  -- add gruvbox
  { "ellisonleao/gruvbox.nvim" },

  -- Configure LazyVim to load gruvbox
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "gruvbox",
    },
  }
}
```

<!-- plugins:start -->

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

## [tokyonight.nvim](https://github.com/folke/tokyonight.nvim)

 tokyonight


<Tabs>

<TabItem value="opts" label="Options">

```lua
opts = { style = "moon" }
```

</TabItem>


<TabItem value="code" label="Full Spec">

```lua
{
  "folke/tokyonight.nvim",
  lazy = true,
  opts = { style = "moon" },
}
```

</TabItem>

</Tabs>

## [catppuccin](https://github.com/catppuccin/nvim)

 catppuccin


<Tabs>

<TabItem value="opts" label="Options">

```lua
opts = {
  integrations = {
    alpha = true,
    cmp = true,
    gitsigns = true,
    illuminate = true,
    indent_blankline = { enabled = true },
    lsp_trouble = true,
    mason = true,
    mini = true,
    native_lsp = {
      enabled = true,
      underlines = {
        errors = { "undercurl" },
        hints = { "undercurl" },
        warnings = { "undercurl" },
        information = { "undercurl" },
      },
    },
    navic = { enabled = true, custom_bg = "lualine" },
    neotest = true,
    noice = true,
    notify = true,
    neotree = true,
    semantic_tokens = true,
    telescope = true,
    treesitter = true,
    which_key = true,
  },
}
```

</TabItem>


<TabItem value="code" label="Full Spec">

```lua
{
  "catppuccin/nvim",
  lazy = true,
  name = "catppuccin",
  opts = {
    integrations = {
      alpha = true,
      cmp = true,
      gitsigns = true,
      illuminate = true,
      indent_blankline = { enabled = true },
      lsp_trouble = true,
      mason = true,
      mini = true,
      native_lsp = {
        enabled = true,
        underlines = {
          errors = { "undercurl" },
          hints = { "undercurl" },
          warnings = { "undercurl" },
          information = { "undercurl" },
        },
      },
      navic = { enabled = true, custom_bg = "lualine" },
      neotest = true,
      noice = true,
      notify = true,
      neotree = true,
      semantic_tokens = true,
      telescope = true,
      treesitter = true,
      which_key = true,
    },
  },
}
```

</TabItem>

</Tabs>

<!-- plugins:end -->
