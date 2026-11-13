# 🌟PRO-SIM FOV UTILITY🌟

<img width="736" height="1438" alt="1784189238961" src="https://github.com/user-attachments/assets/07956e94-c216-4e6e-b2bd-a1553dc422a0" />

<img width="1575" height="3079" alt="export (8)" src="https://github.com/user-attachments/assets/5c832ca3-f5e5-4155-bd78-07270f1e25a0" />


[![PRO-SIM FOV UTILITY Fix the “False” Feeling of Speed](https://img.shields.io/badge/YouTube-Watch%20Fix-red?style=for-the-badge&logo=youtube)](https://youtube.com/shorts/4EMFu5LgZe8?si=GXFyHLvqX8ve4zpp)


<img width="1442" height="790" alt="Pro-Sim FOV Utility v5 1 0 0++" src="https://github.com/user-attachments/assets/00c99e40-54ab-4e20-b469-802d358aed81" />

---

## 📜 Intellectual Property & Attribution Notice

**Copyright © 2026 ilborga70. All rights reserved.**

**Pro-Sim FOV Utility** is an original utility developed and owned by **ilborga70**.

* 🚫 **No Unauthorized Redistribution:** You may not re-upload, host, or redistribute the binary executable files (`.exe`), plugins (`.dll`, `.asi`), or codebase on any other website, forum, or repository without prior written consent.
* 🏷️ **Attribution & Derivative Concept:** If you develop, publish, or share a similar utility, derivative project, or concept inspired by or built upon the methodologies introduced by *Pro-Sim FOV Utility*, **you must explicitly give clear credit and attribute the original concept and work to ilborga70** with a direct link back to this official repository.
* 🤖 **AI Opt-Out & Mining Prohibition:** Text and data mining, scraping, decompilation, and training of Artificial Intelligence (AI) or Machine Learning (ML) models using any part of this project, executable, or codebase are strictly prohibited without prior written consent from the author.
* 📦 **Mod Packaging:** Modpack creators and community developers must link directly to this official repository rather than bundling the software directly.
* 💼 **Non-Commercial Use Only:** This software is provided free for personal, non-commercial use. Commercial monetization or bundling is strictly prohibited.
* 🛡️ **Disclaimer:** Provided "as is" without warranty of any kind.

---

👨‍💻 **Created by ilborga70** • [Pro-Sim Utilities Hub](https://github.com/ilborga70)

## 🔒 Antivirus False Positives
Since the file was compiled using **Win-PS2EXE**, any alerts are due to the nature of the compiler wrapper.
Don't worry — the code has been reviewed by IT experts and has been found to be completely safe and clean.

> 🔗 **Virus Scan Report:** [Jotti's Malware Scan](https://virusscan.jotti.org/en-US/filescanjob/3idpvw7038)
<img width="1146" height="471" alt="Jotti" src="https://github.com/user-attachments/assets/03a0d170-e986-4878-9ad8-4c3265a29c73" />

## 🆕 What's New in v5.1

### Embedded Image in Help & Monitor Calculator
- The diagonal calculator image is now embedded directly in the script using **Base64 encoding**.
- No more external URL dependencies — the image loads instantly and works completely offline.
- Improved reliability and startup speed for the help window.

### Motion Blur Compensation (-5%)
- Added a new checkbox in the input panel that reduces all calculated FOV values by 5%.
- Compensates for motion blur perception in sim racing.
- Affects all output values: AMS2, iRacing, DiRT, ACRally, Richard Burns Rally, rFactor, LMU, ACEVO, and the triple screen angle.
- State is saved and loaded with JSON profiles (backward compatible with v3.5 profiles).
- Included in the image report export.

### Integrated Help & Monitor Calculator
- Replaced the simple help window with a dual-panel interface accessible via the `?` button.
- **Left panel**: Built-in Monitor Calculator Pro that converts screen diagonal from cm to inches and calculates exact width/height based on aspect ratio.
- **Right panel**: Complete user guide with usage instructions and formulas.
- Monitor calculator supports multiple aspect ratios: `4:3`, `16:9`, `16:10`, `21:9`, `32:9`.
- Bilingual support: Italian and English with one-click language switching.
- A visual reference diagram is included in the calculator.

### Enhanced Image Report
- The "Save Image Report" feature now includes the Motion Blur Compensation status.
- Provides a clear indication of whether the -5% adjustment is active.

## 🔧 Improvements
- Help window size increased to accommodate the new dual-panel layout (820×640).
- Text in the help window no longer auto-selects on opening.
- Improved IE11 compatibility for the embedded WebBrowser control.
- All existing functionality is preserved without changes.

## 📦 Profile Management
- Save/load functionality now includes the new Motion Blur Compensation parameter.
- Existing v3.5 profiles load correctly with the new version.
- The Motion Blur field defaults to unchecked if it's missing from older profiles.

## 🛠️ Installation & Usage
- This is a **Portable Application**—no installation is required.

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

### 🏎️ Supported Simulators
Calculates accurate FOV for a wide range of titles, including:
* Assetto Corsa & Assetto Corsa Competizione / EVO / Rally
* iRacing
* Automobilista 1 & 2
* rFactor 1 & 2
* Le Mans Ultimate
* DiRT Rally / Richard Burns Rally (RBR)

### 🏁  Why Pro-Sim FOV Utility Is Superior
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
Pro-Sim FOV Utility is not just a calculator — it’s a vision simulator.
By combining monitor geometry + biology of vision, it ensures that every millimeter of asphalt displayed matches the distance your brain expects in reality.
Pro-Sim FOV Utility is a portable, high-precision tool designed to calculate the correct Field of View (FOV) and angles for Sim Racing setups.
Whether you use a single monitor or a triple-screen configuration, this tool ensures accurate perspective for titles like *Assetto Corsa*, *iRacing*, *Automobilista 2*, and more.

### New FOV Values Assetto Corsa Rally
* **New ACR Dashboard View**
* **New ACR Cockpit View**
### `fix(calc)`: Assetto Corsa Rally Correction
* **Horizontal FOV Adjustment:** Corrected the FOV calculation for *Assetto Corsa Rally* to use **Horizontal FOV (hFOV)** instead of Vertical FOV (vFOV). The value now aligns correctly with other hFOV-based titles like AMS2 and iRacing.

### 🚀 Dynamic Preview Refinements
* **Live Inch Conversion:** The distance measurement line now displays values in **inches** alongside centimeters for immediate utility.
* **Cleaner Interface:** Angle and mode labels have been moved from the center to a dedicated column in the **top-left corner**. This prevents text overlap when the virtual pilot's head is close to the screens.
* **Sync Fixes:** Resolved a bug where toggling inputs (Curved Screen, Bezel, etc.) caused the Triple Screen Angle to display outdated values. Calculations now run strictly before the drawing routine.

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












