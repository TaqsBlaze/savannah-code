![icon](https://raw.githubusercontent.com/TaqsBlaze/savannah-code/refs/heads/main/assets/banner.png)

![GitHub stars](https://img.shields.io/github/stars/TaqsBlaze/savannah-code?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/TaqsBlaze/savannah-code?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/TaqsBlaze/savannah-code?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/TaqsBlaze/savannah-code?style=for-the-badge)
![VS Code Installs](https://img.shields.io/visual-studio-marketplace/i/TanakaChinengundu.savanah-code?style=for-the-badge)
![VS Code Rating](https://img.shields.io/visual-studio-marketplace/r/TanakaChinengundu.savanah-code?style=for-the-badge)
![VS Code Version](https://img.shields.io/visual-studio-marketplace/v/TanakaChinengundu.savanah-code?style=for-the-badge)
[![VS Code Marketplace](https://img.shields.io/badge/Marketplace-Savannah%20Code-orange?style=for-the-badge&logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=TanakaChinengundu.savanah-code)
# 🐘 Savannah Code

> *"Code under the African sky."*

A Visual Studio Code theme inspired by the African safari landscape — warm sunsets, golden savannah grass, acacia trees, red earth, night skies, and the timeless beauty of wildlife.

---

## ✨ Theme Variants

| Variant | Type | Inspiration |
|---|---|---|
| **Savannah Sunset** | Dark | The golden hour over the Serengeti |
| **Savannah Dawn** | Light | Morning mist over golden savannah |
| **Safari Midnight** | Deep Dark | A moonless African night sky |

---

## 🎨 Color Palette

The palette draws directly from the African landscape:

| Name | Hex | Inspiration |
|---|---|---|
| Safari Night | `#1C1A17` | Deep night sky |
| Dusk Brown | `#2A2622` | Twilight earth |
| Ember Soil | `#3B2F2F` | Red African soil |
| Baobab Bark | `#4A3F35` | Ancient tree bark |
| Lion Gold | `#E0A458` | Lion's mane at sunset |
| Savannah Grass | `#A3B18A` | Golden green grassland |
| Elephant Grey | `#CFCFCF` | Elephant hide |
| Fire Ember | `#E36414` | Campfire glow |
| Sunset Orange | `#F4A261` | Horizon at dusk |
| Acacia Green | `#588157` | Acacia leaves |
| Sky Dusk Blue | `#3A5A74` | African twilight sky |
| Flamingo Pink | `#E5989B` | Flamingo feathers |

---

## 📦 Installation

### Via VS Code Marketplace

1. Open VS Code
2. Press `Ctrl+P` (or `Cmd+P` on macOS)
3. Run: `ext install your-name.savannah-code`

### Manual Installation

1. Download the `.vsix` file from the [releases page](https://github.com/your-name/savannah-code/releases)
2. Open VS Code and press `Ctrl+Shift+P`
3. Select **Extensions: Install from VSIX...**
4. Choose the downloaded file

### From Source

```bash
git clone https://github.com/your-name/savannah-code.git
cd savannah-code-theme
npm install -g @vscode/vsce
vsce package
code --install-extension savannah-code-1.0.0.vsix
```

---

## 🚀 Activating the Theme

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P`)
2. Type **Color Theme**
3. Select one of:
   - `Savannah Sunset` — warm dark theme
   - `Savannah Dawn` — warm light theme
   - `Safari Midnight` — deep dark, high contrast

---

## 🧠 Design Philosophy

**Savannah Code** was designed around five core principles:

1. **Warm Earth Tones** — every color is drawn from nature, not neon
2. **Natural Contrast** — readable without harshness
3. **Balanced Saturation** — vibrant but never overwhelming
4. **Token Hierarchy** — different syntax elements are visually distinct and intuitive
5. **Calm but Expressive** — comfortable for long coding sessions

The theme intentionally avoids the cool blues and electric greens that dominate most developer themes, offering instead the warmth of a sunset fire and the depth of an African night.

---

## 🌐 Language Support

Savannah Code has been carefully tuned for:

- **JavaScript / TypeScript** — full semantic token support
- **Python** — decorator and built-in highlighting
- **Rust** — lifetime and macro colors
- **Go** — built-in function colors
- **C / C++** — macro and type distinctions
- **HTML / CSS / SCSS** — tag, attribute, property, selector colors
- **JSON / YAML** — key/value differentiation
- **Markdown** — heading, bold, italic, link, blockquote styles
- **Shell / Bash** — variable and built-in command colors

---

## ♿ Accessibility

- WCAG AA minimum contrast ratios maintained across all variants
- No reliance on color alone for conveying meaning
- Colorblind-friendly palette avoiding red/green conflicts in critical UI elements
- Comment colors are subdued but remain readable

---

## 📁 Project Structure

```
savannah-code-theme/
│
├── package.json             # Extension manifest
├── README.md                # This file
├── CHANGELOG.md             # Version history
├── LICENSE                  # MIT License
│
├── themes/
│   ├── savannah-sunset.json # Dark theme
│   ├── savannah-dawn.json   # Light theme
│   └── safari-midnight.json # Deep dark / high contrast
│
└── assets/
    ├── logo.png
    ├── banner.png
    └── screenshots/
        ├── sunset-js.png
        ├── sunset-py.png
        ├── dawn-ts.png
        └── midnight-rust.png
```

---

## 🤝 Contributing

Contributions are welcome! To maintain the Savannah Code identity:

- **Do not** introduce neon or electric colors
- **Do not** add cool blues as primary tones
- All additions must maintain the African safari identity
- Submit PRs with before/after screenshots
- Ensure accessibility compliance (WCAG AA minimum)
- Test across all three theme variants

---

## 🌍 Credits & Inspiration

This theme is a tribute to the natural beauty of the African continent. Color inspiration drawn from:

- The Serengeti at golden hour
- The Okavango Delta at dawn
- Kilimanjaro silhouetted against a sunset
- Baobab trees under a Milky Way sky
- The red soils of the Maasai Mara

---

## 📜 License

MIT License — see [LICENSE](./LICENSE) for details.

---

## 🔮 Future Plans

- Custom African inspired file icon pack
- Neovim port
- Community palette voting for variant colors
- Matching terminal profile presets

---
