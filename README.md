<img width="1376" height="764" alt="ACRally Release 0 2 - Camera Customization (FOV)" src="https://github.com/user-attachments/assets/7ea1a4e9-d89a-4f02-9aa0-052ae4727aba" />

![Il FOV sul Monitor Curvo NON è lo Stesso Ecco il Motivo Reale](https://github.com/user-attachments/assets/e710fac0-7b1b-4b1c-8f32-15bf51aea685)

[![PRO-SIM FOV UTILITY Fix the “False” Feeling of Speed](https://img.shields.io/badge/YouTube-Watch%20Fix-red?style=for-the-badge&logo=youtube)](https://youtube.com/shorts/4EMFu5LgZe8?si=GXFyHLvqX8ve4zpp)

<img width="1947" height="1070" alt="Pro-Sim FOV Utility v3 5" src="https://github.com/user-attachments/assets/761256ef-8d6e-44e6-b12b-04f4864c2910" />

## Online “Antivirus False Positives” Scans:
- Since the file was compiled using Win-PS2EXE, any alerts are due to the nature of the compiler wrapper.
- Don’t worry the code has been reviewed by IT experts and has been found to be completely safe and clean.

# Changelog v3.5

## 🐛 Fix: Resolved FOV calculation bug for curved monitors

**What has changed:**
- Resolved a critical error in calculating the effective width (geometric chord) for curved monitors, which previously resulted in values nearly identical to flat screens.
- The underlying mathematical formula has been corrected in its ratios and optimized for execution.

**Impact:**
- When the "Curved Screen" checkbox is enabled, the script now mathematically accurately calculates the reduction in the panel's horizontal visual width.
- This provides exact FOV values and Triple Screen Angles for racing simulations.

# Changelog v3.0

## 🚀 Main Feature: Half-Inch Support
- Enhanced Precision: Introduced the ability to select screen sizes with 0.5-inch increments (e.g., 24.5", 27.5", 31.5").
- Dynamic UI: The value label next to the slider now correctly displays decimals (e.g., `27.5''`).

## 🛠 Bug Fixes & Improvements
### 💾 Profile Saving System (JSON)
- My_Profile_FOV.json Fix: Resolved an issue where the profile saved the "raw" slider value (e.g., 55) instead of the actual inches (e.g., 27.5).
- Backward Compatibility: The loading system is now "smart": it automatically recognizes both old profiles (integers) and new ones (with decimals), adapting them to the new scale without errors.

### 📊 Image Report (PNG)
- Graphic Report Update: The "Save Image Report" function now prints the exact dimension with decimals in the `FOV_Results.png` file, avoiding rounding errors that could mislead the user.

### 🔧 Code Optimizations
- GDI+ Resource Management: Improved memory handling during FOV diagram drawing to prevent slowdowns after multiple calculations.
- Robust Parsing: Added error handling for the Ratio selector (Standard/16:9) to prevent crashes with custom configurations.

---
Why this update is important:
- Many sim racers use monitors with 24.5" or 27.5" panels (common in modern gaming displays).
- Specifying support for "half-inches" is a key advantage for this utility compared to simpler FOV calculators that only accept whole numbers.

# Changes v2.0 + Fix
- Unzip the img.zip archive into the main Pro-Sim FOV Utility folder, replace when prompted by the warning message.
- Input Controls: Enhanced ComboBox behavior for Screen Ratio and Screens by setting them to DropDownList style, preventing manual text entry and improving stability.
- Result Display: The results box has been streamlined by removing scrollbars and setting the cursor to a default arrow to emphasize its read-only nature.
- Trigonometry Engine: Refined the FOV calculation logic to better handle curved screens and triple-screen angles.

[![PRO-SIM FOV UTILITY Fix the “False” Feeling of Speed](https://img.shields.io/badge/YouTube-Watch%20Fix-red?style=for-the-badge&logo=youtube)](https://youtube.com/shorts/4EMFu5LgZe8?si=GXFyHLvqX8ve4zpp)

# Changes v1.0
- Changelog:
- Now the executable file "Pro-Sim FOV Utility.exe" does not require to be run as administrator.
- Single-File Portability: The application icon is now embedded directly into the script (Base64).
- The utility is now fully standalone and no longer requires the external ico folder to function.
- Changed the monitor ratio value to standard instead of 16:9

## 🏁  Why Pro-Sim FOV Utility Is Superior
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












