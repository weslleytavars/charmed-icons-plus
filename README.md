<p align="center">
  <p align="center">
	<img src="assets/icon.png" alt="Logo" width="128" />
  </p>
  <h1 align="center"><b>Charmed Icons Plus</b></h1>
</p>

<div align="center">

[![GitHub License](https://img.shields.io/github/license/littensy/charmed-icons?style=for-the-badge)](LICENSE.md)
![GitHub Stars](https://img.shields.io/github/stars/weslleytavars/charmed-icons-plus?style=for-the-badge&logo=github)

</div>

## 📷 Previews

<details>
  <summary>🫐 Base</summary>
  <img src="assets/base.webp"/>
</details>
<details>
  <summary>🥥 Light</summary>
  <img src="assets/light.webp"/>
</details>
<details>
  <summary>🍇 Soft</summary>
  <img src="assets/soft.webp"/>
</details>
<details>
  <summary>🍓 Warm</summary>
  <img src="assets/warm.webp"/>
</details>

## 🔧 Usage

### Marketplace

You can find the extension on the [Open VSX Registry](https://open-vsx.org/extension/weslleytavars/charmed-icons-plus).

## 🎨 Customization

### Settings

You can customize the icon theme with the following settings:

```jsonc
{
	// Set to `true` to disable folding arrows next to folder icons.
	"charmed-icons-plus.hidesExplorerArrows": false,

	// Set to `when-expanded` to use outlines when the folder is expanded.
	// Set to `always` to always use outlined folder icons.
	// Set to `never` to always use filled folder icons.
	"charmed-icons-plus.outlinedFolders": "when-expanded"
}
```

### Custom icon associations

Charmed Icons Plus also supports custom icon associations (thanks to [Catppuccin Icons](https://github.com/catppuccin/vscode-icons/tree/main?tab=readme-ov-file#custom-icon-associations)):

```jsonc
{
	// Files with the language type `typescriptreact` will have the `react-typescript` icon.
	"charmed-icons-plus.associations.languages": {
		"typescriptreact": "react-typescript"
	},

	// Files with the `spec.ts` extension will have the `test-blue` icon.
	"charmed-icons-plus.associations.extensions": {
		"spec.ts": "test-blue"
	},

	// Files with the name `vite.config.ts` will have the `vite` icon.
	"charmed-icons-plus.associations.files": {
		"vite.config.ts": "vite"
	},

	// Folders with the name `typings/` will have the `folder_types` icon.
	"charmed-icons-plus.associations.folders": {
		"typings": "folder_types"
	}
}
```

> [!NOTE]
> See the [preview images](#-previews) for a list of available icons (Icons might be added, removed or modified at any time).

## ❤️ Gratitude

Charmed Icons draws heavy inspiration from:

- [Catppuccin Icons](https://github.com/catppuccin/vscode-icons): Soothing pastel icons for VSCode.
- [Monospace Theme](https://github.com/keksiqc/monospace-theme): The Monospace Theme from Google's IDX.

Thanks littensy for the amazing pack:

- [Charmed Icons](https://github.com/littensy/charmed-icons)

Free assets credits:
- <a href="https://www.flaticon.com/free-icons/pinwheel" title="pinwheel icons">Pinwheel icons created by Freepik - Flaticon</a>

---

<p align="center">
Charmed Icons Plus is released under the <a href="LICENSE.md">MIT License</a>.
</p>

<div align="center">

[![MIT License](https://img.shields.io/github/license/littensy/charmed-icons?style=for-the-badge)](LICENSE.md)

</div>
