# Eighties Black

Omarchy theme. [Chris Kempson](http://chriskempson.com)'s Eighties palette on true black (`#000000`).

## Install

```bash
omarchy theme install https://github.com/j-c-m/omarchy-eighties-black-theme.git
```

Or from this checkout:

```bash
omarchy theme install ~/dev/omarchy-eighties-black-theme
```

`omarchy theme install` names the theme from the repo (`omarchy-eighties-black-theme` → `eighties-black`) and regenerates terminals, Hyprland, and Neovim (aether) from `colors.toml`.

## Palette

| | hex |
|---|---|
| background | `#000000` |
| foreground | `#cccccc` |
| accent | `#6699cc` |
| red / yellow / green / cyan / blue / magenta | `#ee4549` `#c86131` `#59b259` `#37afaf` `#3773af` `#b259b2` |
| bright | `#f2777a` `#ffcc66` `#99cc99` `#66cccc` `#6699cc` `#cc99cc` |
| muted / bright white | `#888888` `#f2f0ec` |

## Optional Neovim colorscheme

`omarchy theme install` does not keep a theme's `neovim.lua`. Generated aether uses this `colors.toml`.

For the hand-tuned Vim/Neovim scheme (same palette, extra highlight groups), copy `extras/eighties-black.lua` to `~/.config/nvim/colors/eighties-black.lua`.
