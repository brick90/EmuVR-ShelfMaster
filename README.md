
# 🎮 ShelfMaster for EmuVR

*The ultimate ROM shelf organizer for EmuVR collectors, tinkerers, and nostalgia junkies alike.*

**ShelfMaster** lets you auto-place your disc-based games into a perfectly aligned virtual shelf in EmuVR. Customize case styles, define precise 3D positioning, and export directly to your `bedroomState.json`. No more fiddling with janky placement—just clean, effortless curation.

---

## 🚀 Features

- 🗂 **Multi-ROM Picker** — Choose specific `.cue`, `.iso`, `.bin`, `.3ds`, `.nds` files manually
- 🎛 **Per-ROM Customization** — Set case type, position, rotation, and scale for each game
- 🧭 **Auto Layout Presets** — Stack or shelf your games effortlessly using built-in patterns
- 🖱️ **Visual GUI** — Built with Python's `tkinter` for simplicity and no dependencies
- 📦 **Exports to EmuVR Format** — Outputs EmuVR-compatible JSON ready for use

---

## 📁 How to Use

1. Launch `ShelfMaster.exe`
2. Choose your preferred ROM extension and select your games
3. Customize layout settings (position, rotation, spacing)
4. Use layout presets or tweak manually
5. Click `Export JSON` and place the file in your EmuVR folder

---

## 🛠 Build It Yourself

To build from source:

```bash
pip install pyinstaller
pyinstaller --noconsole --onefile --icon=shelfmaster.ico shelfmaster.py
