# Kali Touchpad Gestures

Custom `libinput-gestures` configuration for **Kali Linux** with productivity-focused touchpad gestures.
Includes a complete installation and configuration guide to enable advanced swipe and pinch actions on GNOME X11.

---

## ✨ Features
- **3-Finger Gestures:**
  - Swipe down → Minimize window
  - Swipe up → Show Activities Overview
  - Swipe left/right → Switch between windows
  - Swipe left_down → Close current window
  - Swipe right_down → Open VS Code
  - Swipe right_up → Open SnapTube Audio folder
  - Swipe left_up → Open Google Chrome
  - Pinch in/out → Volume control

- **4-Finger Gestures:**
  - Swipe down → Show Activities Overview
  - Swipe up → Show Applications/Dock
  - Swipe left/right → Snap window to side
  - Swipe left_down/right_down → Switch workspace
  - Pinch in/out → Screen brightness control

---

## 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/kali-touchpad-gestures.git
   cd kali-touchpad-gestures
   ```

2. **Follow the setup guide**:
   ```bash
   nano kali-gestures-setup.txt
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
