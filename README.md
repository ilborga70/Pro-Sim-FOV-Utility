<img width="2540" height="1426" alt="Pro-Sim FOV Utility v9 0 0 0" src="https://github.com/user-attachments/assets/e1143dda-5351-44f3-8acc-f70de4c0b1b3" />

<img width="1882" height="797" alt="New FOV Values Assetto Corsa Rally" src="https://github.com/user-attachments/assets/af21e73b-3d97-44ae-961e-a7d7522f4449" />

[![PRO-SIM FOV UTILITY Fix the “False” Feeling of Speed](https://img.shields.io/badge/YouTube-Watch%20Fix-red?style=for-the-badge&logo=youtube)](https://youtube.com/shorts/4EMFu5LgZe8?si=GXFyHLvqX8ve4zpp)

* **🏁  Why Pro-Sim FOV Utility Is Superior**
* **🔍  Beyond Geometry**
Traditional calculators rely only on a distance ÷ width formula.
Pro-Sim integrates human physiology and spatial perception, ensuring realism that pure math cannot achieve.
* **👀  120° Binocular Vision Reference**
Human vision spans 200°–220°, but binocular overlap (both eyes working together) is ~120°.
This is the critical zone where the brain fuses depth and perspective.
Pro-Sim’s choice: Align FOV with binocular vision → a 1:1 “Royal Flush” simulation.
Result: Eliminates fisheye distortion (too wide) and tunnel vision (too narrow).
* **🌀  Peripheral Vision Correction***
Central vision (~60°) handles detail, but peripheral vision drives speed perception.
Pro-Sim ensures that edge-of-screen cues are processed naturally, so drivers feel velocity without staring at the speedometer.
Triple-screen setups especially benefit from this correction.
* **🏎️  Precision for Richard Burns Rally (RBR)**
RBR’s graphics engine uses a nonlinear FOV calculation, unlike most modern sims.
Standard calculators misinterpret this, producing distorted results.
Pro-Sim applies a custom mathematical transformation tailored to RBR’s code.
Guarantees perfect geometry on 16:9 and 21:9 monitors, restoring cockpit realism.
* **🎯  The Bottom Line**
Pro-Sim FOV Utility is not just a calculator — it’s a vision simulator.By combining monitor geometry + biology of vision, it ensures that every millimeter of asphalt displayed matches the distance your brain expects in reality.
Pro-Sim FOV Utility is a portable, high-precision tool designed to calculate the correct Field of View (FOV) and angles for Sim Racing setups.
Whether you use a single monitor or a triple-screen configuration, this tool ensures accurate perspective for titles like *Assetto Corsa*, *iRacing*, *Automobilista 2*, and more.

---

## 📢 Latest Updates

### New FOV Values Assetto Corsa Rally
* **New ACR Dashboard View**
* **New ACR Cockpit View**

## 📢 Updates

### `fix(calc)`: Assetto Corsa Rally Correction
* **Horizontal FOV Adjustment:** Corrected the FOV calculation for *Assetto Corsa Rally* to use **Horizontal FOV (hFOV)** instead of Vertical FOV (vFOV). The value now aligns correctly with other hFOV-based titles like AMS2 and iRacing.

### 🚀 Dynamic Preview Refinements
* **Live Inch Conversion:** The distance measurement line now displays values in **inches** alongside centimeters for immediate utility.
* **Cleaner Interface:** Angle and mode labels have been moved from the center to a dedicated column in the **top-left corner**. This prevents text overlap when the virtual pilot's head is close to the screens.
* **Sync Fixes:** Resolved a bug where toggling inputs (Curved Screen, Bezel, etc.) caused the Triple Screen Angle to display outdated values. Calculations now run strictly before the drawing routine.

---

## ✨ Key Features

### 💾 Profile Management
Save time by storing different setup configurations (e.g., "Desk Rig" vs. "Main Sim Rig").
* **Save Profile:** Serializes current configuration to a `.json` file.
* **Load Profile:** Deserializes the file and automatically repopulates all sliders, checkboxes, and values. The preview diagram instantly updates to reflect the loaded profile.

### 📊 Professional Image Reports
Generate shareable, professional screenshots of your setup data.
* **Custom Backgrounds:** Automatically overlays text results on a custom car cockpit background (`img\cockpit_template.png`).
* **Clean Layout:** 1280x720 PNG output with a two-column design separating input parameters from calculated results.
* **Styling:** Features a dark, semi-transparent overlay for readability and branding-consistent borders.

### 👁️ Dynamic Visual Diagram
A real-time visual representation of your rig that updates instantly as you adjust sliders.
* **Triple Screen Logic:** Accurately visualizes side screens tilted at specific angles (defaulting to 30°) and joined to the center screen.
* **Bezel Integration:** Visually represents bezel thickness between screens.
* **Head Position:** An oval represents the user, moving dynamically based on distance settings.
* **FOV Lines:** Yellow dashed lines indicate the actual Field of View angle.

---

## 🛠️ Installation & Usage

This is a **Portable Application**—no installation is required.

### System Requirements
* **OS:** Windows 10 / 11 (64-bit)
* **Framework:** .NET Framework 4.8 (usually pre-installed)
* **Permissions:** **Administrator privileges** are required for full functionality.

### How to Run
1.  **Download** the `.exe` from the Releases page.
2.  **Place it** anywhere (Desktop, USB drive, Game folder).
3.  **Right-click** `Pro-Sim FOV Utility.exe` and **Run as Administrator**.
4.  *Note:* Since this is a community tool, Windows SmartScreen may warn you. Click **"More info" → "Run anyway"**.

### Portability Benefits
* **USB Ready:** Carry your settings to LAN parties or tournaments.
* **No Conflicts:** Runs safely alongside other gaming software.
* **Easy Cleanup:** Simply delete the executable to remove the tool.

---

## 🏎️ Supported Simulators
Calculates accurate FOV for a wide range of titles, including:
* Assetto Corsa & Assetto Corsa Competizione / EVO / Rally
* iRacing
* Automobilista 1 & 2
* rFactor 1 & 2
* Le Mans Ultimate
* DiRT Rally / Richard Burns Rally (RBR)

---

## 🎓 Why Calculate FOV?

**Correct FOV means better lap times.**

1.  **Speed Perception:** A properly set FOV ensures objects appear at the correct size and distance relative to your real-world perspective. This fixes the "false" feeling of speed often caused by overly wide default settings.
2.  **Spatial Awareness:** Improves judgment for braking points, corner apexes, and distance to other cars.
3.  **Consistency:** While a mathematically correct FOV might feel "zoomed in" at first, adapting to it typically leads to greater consistency and faster lap times.

> **Note for Triple Screens:** Pay close attention to the "Triple Screen Horizontal FOV" and angle values in the results. These ensure a seamless transition across all three monitors.

---


*Last Update: 2024 | Compatible with PowerShell 5.1+*






