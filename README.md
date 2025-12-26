# 🌊 MacroFlow

**MacroFlow** is a professional companion application designed for custom HID macro pads. It provides a seamless interface for users to visually remap keys, manage multiple functional layouts, and configure rotary encoders in real-time, eliminating the need for manual firmware flashing.



## ✨ Key Features

* **Visual Key Remapping**: Intuitive graphical interface allows for instant assignment of custom actions to 12 physical keys and 2 rotary encoders.
* **Rotary Encoder Support**: Dedicated logic for Volume Up/Down and Scroll functions via hardware rotation events.
* **Layout Management**: Create and switch between 'Gaming', 'Productivity', and 'Coding' profiles with a single click.
* **Real-time Sync**: Changes apply instantly to the device EEPROM via Raw HID communication.
* **Modern Interface**: High-performance UI featuring smooth-scroll animations and a responsive design.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, and Vanilla JavaScript.
* **Backend**: Python 3.x with the PySide6 (Qt for Python) framework.
* **Communication**: QWebChannel (JS-Python Bridge) and `hidapi` for hardware interaction.
* **OS Integration**: Windows User32 API for global keystroke and input injection.

## 📂 Project Structure

As organized in the core repository:
* `app.py`: Main application entry point and System Tray logic.
* `backend.py`: Core logic for layout management and hardware synchronization.
* `device.py`: Low-level HID communication and real-time event listening.
* `input_engine.py`: Windows-specific key injection and QMK mapping codes.
* `ui/`: Web-based interface files including `index`, `script`, and `style`.

## 🚀 Installation & Setup

1. **Hardware**: Connect your QMK-powered macro pad (VID: `0xFEED`, PID: `0x4043`).
2. **Software**: Download the `MacroFlow_Setup.exe` installer from the latest GitHub release.
3. **Run**: Launch MacroFlow and start remapping your workflow immediately.

---

**Developed by Malik K. as a Final Year Project.**
