# 🐟 Fish Gruvbox Theme

Gruvbox theme plugin for fish shell 🐟🐚

---

# ⬇️ Install

> [!NOTE]
> You must have [fisherman](https://github.com/fisherman/fisherman) installed for easy [fish](http://fishshell.com/)
plugin management.

With `fisherman`:

```fish
fisher install AndroidGeeksYT/fish-gruvbox
```

or manual installation:

```fish
git clone https://github.com/AndroidGeeksYT/fish-gruvbox.git && mv fish-gruvbox/functions/theme_gruvbox.fish ~/.config/fish/functions/ && rm -rf fish-gruvbox/
```

This will expose the function called `theme_gruvbox`.
It is a simple function that takes two arguments.
The first is the mode, either `light` or `dark`.
The second is the contrast, `soft`, `medium` or `hard`.
The defaults are `light` and `medium`.

---

# ⚙️ How to Use

To automatically apply this theme, call `theme_gruvbox` from your `config.fish`.

```fish
theme_gruvbox dark hard # choose your mode light, dark and for contrast soft, medium, hard
```

---

# 📲 Android / Termux

> [!WARNING]
> Please do not use [termux-styling](https://github.com/termux/termux-styling) the two colorscheme will be conflicting with each other. In this case we will let the fish shell handle the colorscheme instead of using [termux-styling](https://github.com/termux/termux-styling).

If you used the [termux-styling](https://github.com/termux/termux-styling) it is recommended to remove it's properties from `~/.termux/` folder.

```fish
rm ~/.termux/colors.properties
```

---

# 🙏🏼 Donate or Subscribe

- YouTube:

<div>
    <img src="https://github.com/AndroidGeeksYT/AndroidGeeksYT/blob/main/assets/img/Android%20Geeks.png"/>
</div>

- Gcash:

<div>
    <img src="https://github.com/AndroidGeeksYT/AndroidGeeks-Kickstart-Nvim/blob/main/img/donate.jpg"/>
</div>

---

# ❤️Credits

- [gruvbox](https://github.com/morhetz/gruvbox)
- [fish shell](http://fishshell.com/)
- [fisherman](https://github.com/fisherman/fisherman)
