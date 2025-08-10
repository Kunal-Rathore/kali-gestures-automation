# Kali Touchpad Gestures

Custom `libinput-gestures` configuration for **Kali Linux** with productivity-focused touchpad gestures.
Includes a complete installation and configuration guide to enable advanced swipe and pinch actions on GNOME X11.

---

## ✨ Features
- **3-Finger Gestures:**
  - Swipe down → Minimize current window
  - Swipe up → Maximize current window
  - Swipe left → Previous window
  - Swipe right → Next window
  - Swipe left_down → Close current window
  - Swipe right_down → Open VS Code
  - Swipe left_up → Open Google Chrome
  - Swipe right_up → Open SnapTube Audio folder
  - Pinch in/out → Volume control

- **4-Finger Gestures:**
  - Swipe down → Show Activities Overview
  - Swipe up → Show Dock / Applications
  - Swipe left → Snap window to left
  - Swipe right → Snap window to right
  - Swipe left_down → Minimize current window
  - Swipe left_up → Switch to previous workspace
  - Swipe right_up → Switch to next workspace
  - Swipe right_down → Take a screenshot (interactive)
  - Pinch in/out → Screen brightness control

---

## 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kunal-Rathore/kali-gestures-automation.git
   cd kali-gestures-automation
   ```

2. **Follow the setup guide**:
   ```bash
   gedit kali-gestures-setup.txt
   ```
   Copy-paste commands into your terminal to install dependencies, configure gestures, and enable auto-start.

---

## 📂 Files
- **`kali-gestures-setup.txt`** – Complete copy-paste guide to set up gestures from scratch.

---

## 🛠 Requirements
- Kali Linux (GNOME X11 session)
- `libinput-gestures`
- `xdotool`, `wmctrl`
- Visual Studio Code, Google Chrome installed for mapped gestures

---

## 📜 License
This project is licensed under the MIT License – feel free to modify and share.
