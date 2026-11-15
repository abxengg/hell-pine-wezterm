# Hell Pine for WezTerm

A darker, higher-contrast take on Rosé Pine, born inside tmux, for WezTerm.

![Hell Pine in Neovim, the terminal and tmux](https://raw.githubusercontent.com/abxengg/hell-pine.nvim/main/assets/hero.png)

## Install

```sh
mkdir -p ~/.config/wezterm/colors
curl -fsSL https://raw.githubusercontent.com/abxengg/hell-pine-wezterm/main/hell-pine.toml -o ~/.config/wezterm/colors/hell-pine.toml
```

Then in `wezterm.lua`:

```lua
config.color_scheme = "Hell Pine"
```

## Palette

![The Hell Pine palette](https://raw.githubusercontent.com/abxengg/hell-pine.nvim/main/assets/palette.png)

## Other ports

Hell Pine comes from the [VS Code theme](https://github.com/abxengg/hell-pine). Every port is made from the one
palette in [hell-pine.nvim](https://github.com/abxengg/hell-pine.nvim) by its `scripts/extras.py`, so the colours stay the
same everywhere: [Neovim](https://github.com/abxengg/hell-pine.nvim),
[Ghostty](https://github.com/abxengg/hell-pine-ghostty), [kitty](https://github.com/abxengg/hell-pine-kitty), [Alacritty](https://github.com/abxengg/hell-pine-alacritty), [tmux](https://github.com/abxengg/hell-pine-tmux), [Starship](https://github.com/abxengg/hell-pine-starship), [btop](https://github.com/abxengg/hell-pine-btop), [fish](https://github.com/abxengg/hell-pine-fish), [Zed](https://github.com/abxengg/hell-pine-zed), [fzf](https://github.com/abxengg/hell-pine-fzf).

To change a colour, edit the palette there and run the script; do not edit `hell-pine.toml` by hand.

## Licence

MIT, see [LICENSE](LICENSE).
