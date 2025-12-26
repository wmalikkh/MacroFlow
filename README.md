# 🌊 MacroFlow

**MacroFlow** is a professional-grade companion application designed for custom HID macro pads. It provides a seamless interface for users to visually remap keys, manage multiple functional layouts, and configure rotary encoders in real-time, eliminating the need for manual firmware flashing.



## ✨ Key Features

* **Visual Key Remapping**: An intuitive graphical interface allows users to assign custom actions to 12 physical keys and 2 rotary encoders instantly.
* **Rotary Encoder Support**: Includes dedicated logic for Volume Up/Down, Page Scrolling, and Zoom functions via hardware rotation events.
* **Layout Management**: Effortlessly create, switch, and manage up to 3 custom profiles, such as 'Gaming', 'Productivity', and 'Coding'.
* **Real-time Hardware Sync**: Changes are applied immediately to the device EEPROM using Raw HID communication protocols.
* **Windows Integration**: Features native Windows support including automatic startup options and system tray minimization.
* **Modern Interface**: A high-performance UI featuring custom smooth-scroll animations and a responsive design.

## 🛠️ Technical Stack

* **Frontend**: Developed using HTML5, CSS3, and Vanilla JavaScript.
* **Backend**: Powered by Python 3.x and the PySide6 (Qt for Python) framework.
* **Communication**: Utilizes `QWebChannel` for the JavaScript-Python bridge and `hidapi` for low-level hardware interaction.
* **OS Integration**: Employs Windows User32 API for global keystroke and input injection.

## 📂 Project Structure

* `app.py`: Main application entry point containing the UI initialization and System Tray logic.
* `backend.py`: Core business logic responsible for layout management and hardware synchronization.
* `device.py`: Handles low-level HID communication and real-time event listening.
* `input_engine.py`: Manages Windows-specific key injection and QMK mapping codes.
* `ui/`: Directory containing all web-based interface assets including `index.html`, `landing.css`, and `landing.js`.

## 🚀 Installation & Setup

1.  **Hardware**: Connect your QMK-powered macro pad (Compatible with VID: `0xFEED`, PID: `0x4043`).
2.  **Software**: Download the `MacroFlow_Setup.exe` installer from the latest GitHub release.
3.  **Run**: Launch MacroFlow and begin customizing your hardware workflow immediately.

---

**Developed by Malik K. as a Final Year Project.**
