# Sobrio theme for Zellij

![Screen shot](./images/screenshot.png)

## About this theme

This is a theme for **Zellij**, the terminal multiplexer. It uses the colors from the Sobrio theme to make your experience more unique.

---

## Instalation

Installing this theme for Zellij is quite simple, just editing the `config.kdl` will be enough.
This file is located in different places, depending on your OS:

- Linux: `~/.config/zellij`
- MacOS: `~/Librar/Application Support/org.Zellij-Contributors.Zellij`

If it is not already there, create one using the command:

```bash
mkdir ~/.config/zellij
zellij setup --dump-config > ~/.config/zellij/config.kdl
```

1. Paste the contents of the file `sobrio.kdl` at the end of your `config.kdl`.
2. Add the line `theme "sobrio"` or `theme "sobrio_light"` to your `config.kdl` and save the file.
3. ???
4. Profit!