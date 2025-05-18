# dmenu-dracula

A personal fork of [dmenu](https://tools.suckless.org/dmenu/) — patched, styled, and tuned to integrate seamlessly with my Dracula-themed Qtile setup.

This version is designed to sit beautifully in my top bar, with:

- 💀 Dracula color palette
- 🎯 Precise placement via `-x`, `-y`, and `-z` (xyw patch)
- 🧱 Clean bar alignment using the line height patch
- 🧛 Minimalist prompt with 5 suggestions and no dropdown clutter
- 🔧 Manually configured to match my 2560x1440 primary display

---

## ⚙️ Patches Included

This fork includes the following dmenu patches:

- [xyw](https://tools.suckless.org/dmenu/patches/xyw/) – for precise screen positioning
- [line-height](https://tools.suckless.org/dmenu/patches/line-height/) – for bar-aligned appearance
- (_TBD:_ [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch/)) - Coming Later

---

## 📦 Usage

```bash
git clone https://github.com/C-Garrett16/dmenu.git
cd dmenu-dracula
sudo make clean install
