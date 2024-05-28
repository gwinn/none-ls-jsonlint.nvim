# none-ls-jsonlint.nvim

[jsonlint](https://github.com/zaach/jsonlint) diagnostics source for [none-ls.nvim](https://github.com/nvimtools/none-ls.nvim).

this repository allows to keep using [jsonlint](https://github.com/zaach/jsonlint) with [none-ls.nvim](https://github.com/nvimtools/none-ls.nvim).

**Note:** This plugin is not intended to be used alone, it is a dependency of none-ls.nvim.

## 📦 Installation

This should be used as a dependency of **none-ls.nvim**.

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  {
    "nvimtools/none-ls.nvim",
    dependencies = {
        "gwinn/none-ls-jsonlint.nvim",
    },
  },
}
```

## Setup

Follow the steps in null-ls [setup](https://github.com/nvimtools/none-ls.nvim?tab=readme-ov-file#setup) section.

```lua
local null_ls = require("null-ls")

null_ls.setup {
  sources = {
    require("none-ls-jsonlint.diagnostics.jsonlint"),
    ...
  }
}
```

## Related projects

You can search for sources via the [`none-ls-sources` topic](https://github.com/topics/none-ls-sources).

