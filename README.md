<div align="center">
  <img src="https://github.com/sxyazi/yazi/blob/main/assets/logo.png?raw=true" alt="Yazi logo" width="20%">
</div>

## nightfly Flavor for [Yazi](https://github.com/sxyazi/yazi)

nightfly.yazi is based on [nightfly](https://github.com/bluz71/vim-nightfly-guicolors)'s colors and [fly16](https://github.com/bluz71/fly16-bat) .tmTheme template. It is usable standalone or with associated terminal themes found in nightfly's [extras section](https://github.com/bluz71/vim-nightfly-colors#extras).

## 👀 Preview

<img src="preview.png" width="600" />

## 🎨 Installation

```sh
ya pkg add tkapias/nightfly
```

## ⚙️ Usage

To set it as your dark flavor, change the content of your `theme.toml` to:

```toml
[flavor]
dark = "nightfly"
```

Make sure your `theme.toml` doesn't contain anything other than `[flavor]`, unless you want to override certain styles of this flavor.

See the [Yazi flavor documentation](https://yazi-rs.github.io/docs/flavors/overview) for more details.

## 📜 License

The flavor is MIT-licensed, and the included tmTheme is also MIT-licensed.

Check the [LICENSE](LICENSE) and [LICENSE-tmtheme](LICENSE-tmtheme) file for more details.
