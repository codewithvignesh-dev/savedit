# savedit

**savedit** is a lightweight **binary `.sav` file editor** built for **Termux**.  
It allows you to **inspect, edit, and safely modify** integer and float properties inside `.sav` files using a colorful TUI.

> Designed for reverse-engineering, modding, and learning binary save formats.

---

## ✨ Features

- 📦 Binary `.sav` parser
- 🎨 Colorful TUI (Rich-based)
- ✏️ Editable `int` & `float` values
- 🛡️ Automatic `.bak` backup before modification
- ⚡ Fast & offline (no runtime dependencies)
- 📱 Fully compatible with **Termux**

---

## 📥 Installation (Termux)

> **Single-line setup command**

```sh
pkg install -y wget && wget -q https://github.com/codewithvignesh-dev/savedit/releases/latest/download/savedit && chmod +x savedit && mv savedit $PREFIX/bin/
