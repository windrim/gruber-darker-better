# gruber-darker.nvim

_A Neovim port of a deftheme [adaptation][gruber-darker] of an Emacs [port][gruber-darker]
of a BBEdit [colorscheme][gruber-dark]_

## Installation

### Packer

```lua
use {
  name = "",
  config = function()
    require("gruber-darker").setup()
  end
}
```

[gruber-darker-theme]: https://github.com/rexim/gruber-darker-theme
[gruber-darker]: https://jblevins.org/projects/emacs-color-themes/gruber-darker-theme.el.html
[gruber-dark]: http://daringfireball.net/projects/bbcolors/schemes/
