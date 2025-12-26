# 🌊 MacroFlow

**MacroFlow** is a professional-grade companion application for custom HID macro pads. It allows users to visually remap keys, manage multiple functional layouts, and configure rotary encoders in real-time without manual firmware flashing.

---

## ✨ Features

* **Visual Key Remapping**: Intuitive GUI to assign actions to 12 physical keys and 2 rotary encoders.
* **Rotary Encoder Support**: Dedicated logic for Volume Up/Down and Scroll functions via hardware rotation events.
* **Layout Management**: Create, switch, and delete up to 3 custom profiles (e.g., Gaming, Productivity, Coding).
* **Startup Integration**: Option to automatically run the application minimized in the system tray on Windows boot.
* **Hardware Sync**: Direct communication via Raw HID to update device EEPROM mapping.
* **Theme Support**: Toggle between a sleek Cyberpunk Dark Mode and a clean Light Mode.

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, JavaScript (Vanilla).
* **Backend**: Python 3.x with PySide6 (Qt for Python).
* **Communication**: QWebChannel (JS-Python Bridge) and `hidapi` for hardware interaction.
* **OS Integration**: Windows User32 API for global keystroke injection.

---

## 📂 Project Structure

* `app.py`: Main application entry point and System Tray logic.
* `backend.py`: Core logic for layout management and hardware sync.
* `device.py`: Low-level HID communication and event listening.
* `input_engine.py`: Windows-specific key injection and QMK mapping codes.
* `ui/`: Web-based interface files.

---

## 🚀 Installation & Setup

1. **Download the Installer**: Visit [macroflow.info](http://macroflow.info) to download `MacroFlow_Setup.exe`.
2. **Hardware**: Connect your QMK-powered macro pad (VID: `0xFEED`, PID: `0x4043`).
3. **Run**: Launch MacroFlow and start remapping!

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Developed by **Malik** as a Final Year Project.
