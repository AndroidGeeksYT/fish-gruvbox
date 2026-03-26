# fish-gruvbox
[gruvbox] theme for [fish shell]

# Install

With [fisherman]

```fish
fisher install AndroidGeeksYT/fish-gruvbox
```

or

```fish
git clone https://github.com/AndroidGeeksYT/fish-gruvbox.git && mv fish-gruvbox/functions/theme_gruvbox ~/.config/fish/functions/
```

This will expose the function called `theme_gruvbox`.
It is a simple function that takes two arguments.
The first is the mode, either `light` or `dark`.
The second is the contrast, `soft`, `medium` or `hard`.
The defaults are `light` and `medium`.

# How to Use

To automatically apply this theme, call `theme_gruvbox` from your `config.fish`.

```fish
theme_gruvbox dark hard # choose your theme light, dark for contrast soft, medium, hard
```

# Credits

[gruvbox]: https://github.com/morhetz/gruvbox
[fish shell]: http://fishshell.com/
[fisherman]: https://github.com/fisherman/fisherman
