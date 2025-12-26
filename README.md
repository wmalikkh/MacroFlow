# 🌊 MacroFlow

**MacroFlow** is a **complete macro pad system** that combines custom HID hardware with a real-time desktop companion application.

It is designed to give users full control over **keys, rotary encoders, and layouts** through a visual interface — eliminating firmware reflashing and reducing workflow friction. Hardware and software are developed together as one cohesive system.

---

## ✨ Key Capabilities

- **Visual Key Remapping**  
  Instantly assign actions to physical keys through a graphical interface — no code, no firmware edits.

- **Rotary Encoder Control**  
  Native support for rotary encoders with real-time handling for volume, scrolling, zooming, and custom actions.

- **Layout Management**  
  Create and switch between multiple layouts (e.g. Gaming, Productivity, Coding) with a single click.

- **Real-Time Synchronization**  
  Changes are applied immediately via Raw HID communication and stored directly on the device.

- **Modern Desktop Interface**  
  High-performance, responsive UI built for power users who value speed and clarity.

---

## 🧩 System Architecture

MacroFlow is built as a **hardware + software system**, not a firmware-only solution.

- Custom HID macro pad firmware handles low-level input  
- Desktop application manages logic, layouts, and mappings  
- Real-time communication removes the need for reflashing  
- Persistent mappings are stored on-device  

This approach ensures flexibility without sacrificing stability.

---

## 🛠️ Tech Stack

- **Frontend**  
  HTML5, CSS3, Vanilla JavaScript (embedded via Qt WebEngine)

- **Backend**  
  Python 3.x using PySide6 (Qt for Python)

- **Device Communication**  
  QWebChannel (JS ↔ Python bridge)  
  `hidapi` for Raw HID communication

- **OS Integration**  
  Windows User32 API for global keystroke and input injection

---

## 🚀 Installation & Setup

1. **Hardware**  
   Connect the MacroFlow macro pad (QMK-based HID device).

2. **Software**  
   Download `MacroFlow_Setup.exe` from the latest GitHub release.

3. **Run**  
   Launch MacroFlow and begin configuring keys, encoders, and layouts in real time.

---

## 🎯 Design Philosophy

- Hardware and software should be designed together  
- Real-time control should not require firmware reflashing  
- Configuration tools should be visual, fast, and reliable  
- A macro pad should adapt to the user — not the other way around  

---

## 👤 About

MacroFlow was originally developed by **Malik K.** as a final year engineering project and has since evolved into a fully realized macro pad system.
