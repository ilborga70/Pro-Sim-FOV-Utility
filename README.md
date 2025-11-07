## <img width="2560" height="1449" alt="Pro-Sim FOV Utility v7 0 0" src="https://github.com/user-attachments/assets/3c10b058-ab51-4cf2-a418-343b9a051f26" />
\
<a href="[xyz.html](https://youtube.com/shorts/4EMFu5LgZe8?si=GXFyHLvqX8ve4zpp)" target="_blank"> PRO-SIM FOV UTILITY Fix the “False” Feeling of Speed Assetto Corsa Rally and RBR </a>

## ✨ New Features: Profile Management
To improve usability and configuration speed, profile management has been implemented. Users can now save and load different setup configurations (e.g., "Desk Rig", "Main Sim Rig") without having to re-enter all data manually.

## 💾 Save Profile
The "Save Profile" button has been added.

When pressed, the application opens a SaveFileDialog window.

The current configuration is serialized into a PSCustomObject and saved to a .json file chosen by the user.

## 📂 Load Profile
The "Load Profile" button has been added.

It allows the user to select a .json file via an OpenFileDialog.

The application reads the file, deserializes it, and automatically repopulates all controls (sliders, checkboxes, comboboxes) with the saved values.

After loading, a recalculation (Calculate-FOV) and a diagram update (Update-PreviewDiagram) are immediately performed to reflect the loaded profile.

## 🎨 UI Changes
The three action buttons ("Load Profile", "Save Profile", "Save Image Report") are now aligned at the bottom of the window for quick and organized access.

## Screenshot Feature - Text Results with Custom Background
Overview
Enhanced screenshot functionality that generates professional 1280x720 images containing only FOV calculation results overlaid on a custom car background.

## Features
🖼️ Custom Background Support
Template Integration: Automatically loads img\cockpit_template.png as background

Car Styling: Displays FOV results over custom car imagery

Image Requirements: 1280x720 PNG format recommended

## 📊 Comprehensive Data Display
Two-Column Layout: Clean separation of input parameters and calculated results

Input Parameters: Screen size, ratio, distance, bezel, curvature settings

FOV Results: Complete calculation outputs for all supported racing sims

Unit Conversion: Automatic cm to inches conversion for distance

## 🎨 Professional Styling
Semi-Transparent Background: Dark overlay ensures text readability

Consistent Theme: Matches application color scheme (blue/cyan accents)

Decorative Border: Professional framing with application branding colors

## Usage
Click "Save Image Report" button

System automatically:

Loads custom background template

Renders all FOV data in organized layout

Applies professional styling and transparency

Saves as 1280x720 PNG with custom filename

## Output
Filename: FOV_Results.png (customizable)

Dimensions: 1280×720 pixels

Content: Text-only FOV calculations over custom car background

Format: PNG with transparency support

Perfect for sharing setup details with clean, branded presentation that maintains your custom automotive styling.

### 🚀 Dynamic Preview Refinements

This update focuses on cleaning up the dynamic FOV preview diagram, improving readability, and fixing a synchronization bug.

#### 🆕 New Features: Cleaner Diagram and Live Conversions
* **Distance in Inches (Live Conversion):** The distance measurement line now displays the value in **inches** ('') instead of centimeters (cm). This provides a real-time conversion from the main input slider and declutters the chart while offering immediate utility.
* **Central Text Removal:** All angle and mode labels have been removed from the crowded center of the dynamic diagram to prevent overlapping when the virtual pilot's head is close to the screen(s).
* **Left-Aligned Label Column:** All essential metadata (Triple Screen Angle, Bezel, Curve Radius, Screen Mode) has been moved to a new, clean column in the **top-left corner** of the diagram, ensuring readability regardless of the FOV settings.

#### 🐛 Bug Fixes
* **Triple Screen Angle Synchronization Fix:** Resolved a critical bug where toggling input options (like "Curved Screen," "Screens," "Distance," or "Bezel") could cause the dynamic diagram to display an outdated or inverted Triple Screen Angle value. The calculation (`Calculate-FOV`) now runs reliably **before** the drawing routine (`Update-PreviewDiagram`) to ensure the preview always reflects the current settings.

👁️ FOV Visualization: Dashed lines showing the field of view angle

🎯 Dynamic Head Position: Representation of head that moves based on distance

📏 Real-time Distance: Red dotted line with actual distance label

🖥️ Dynamic Multi-Configuration Screen:

Single Screen: Single continuous line

Triple Screens: Three joined screens with side screens tilted towards the user (racing simulator configuration)

🔄 Instant Update: All changes are immediately reflected in the diagram

📐 Bezel Integration: Spaces between triple screens represent bezel thickness

🎮 Simulator Configuration: Side screens tilted at 30 degrees and joined to the center screen for realistic representation

Technical Capabilities:

Visual support for single and triple screens

Automatic adaptation to different aspect ratios

Correct distance visualization (inverted logic)

Curved screen handling

Proportional screen size calculations

Realistic representation of joined and tilted triple screens

Implemented Advanced Features:

✅ Conditional Rendering: Diagram dynamically switches between single/triple screen

✅ Visual Bezels: Proportional spaces between triple screens

✅ Proportional Calculations: Accurate screen sizes in diagram

✅ Real-time Update: Immediate response to all controls

✅ Efficient Resource Management: Automatic graphic memory cleanup

✅ Side Screens Tilt: Realistic 30-degree representation for simulators

✅ Screen Joining: Side screens perfectly joined to the center screen

Controls that Trigger Updates:

🔄 Screen type change (Single/Triple)

🔄 Screen size modification

🔄 Distance adjustment

🔄 Bezel thickness change

🔄 Aspect ratio switch

🔄 Curved screen toggle

Diagram Elements:

🔵 User Head: Oval representing user position

🔷 Screen Line: Blue lines representing the screens (single or triple)

📐 FOV Lines: Yellow dashed lines showing field of view angle

🔴 Distance Line: Red dotted line showing distance

📝 Label: Text indicating distance value

Realistic Setup:

🎯 Optimal Angling: Side screens tilted at 30° towards the user

🔗 Visual Continuity: Perfect transition between center and side screens

👁️ Extended Field of View: FOV lines following screen inclination

📊 Accurate Proportions: Real sizes maintained in diagram

Benefits:

Immediate visual representation of setup

Real-time feedback on changes

Realistic visualization for professional racing setups

*Ultimo aggiornamento / Last update: 2024*
*Compatibile con / Compatible with: PowerShell 5.1+*
*Supporta / Supports: Windows 10/11*
Feature Highlight: Diagramma Dinamico Multi-Schermo Inclinato / Tilted Multi-Screen Dynamic Diagram

Calculate FOV and Angles for Triple Screens
Calculate the correct Field of View (FOV) and angles for triple screen configuration for all Sim Racing games, including Assetto Corsa Rally, Assetto Corsa EVO, iRacing, Automobilista, rFactor, Le Mans Ultimate, DiRT Rally, and Richard Burns Rally.

🏎️ How to Calculate Field of View
Enter your measurements: Input your monitor measurements and viewing distance.

Aspect Ratio: Make sure you know your screen's aspect ratio (this really makes a big difference!).

🎯 Understanding the FOV Result
After entering your monitor measurements and seating position, you'll see a list of FOV (Field of View) values for various sim racing games.

These numbers represent the optimal viewing angle for your configuration, helping to create a more immersive and realistic driving experience. A properly set FOV ensures that objects in the game appear with the correct size and distance relative to your real-world perspective.

Benefits
This can significantly improve your spatial awareness on track, allowing for better judgment of corners, braking points, and overtaking opportunities.

Horizontal vs. Vertical FOV
For most simulators, you'll see a Horizontal FOV (hFOV) value. This is the side-to-side viewing angle and is typically the value you'll need to enter in the game settings.

Some games, like Assetto Corsa Rally, use Vertical FOV (vFOV) instead, which represents the top-to-bottom angle.

Adaptation and Performance
Remember, while a correct FOV might initially feel unusual if you're used to a wider, unrealistic setting, give yourself time to adapt. Many Sim Racers report greater consistency and faster lap times after getting accustomed to a properly calculated FOV.

Correct FOV means better lap times!

🖥️ Triple Screen Configuration
If you have a triple screen setup, pay attention to the "Triple Screen Horizontal FOV" value in the calculator results.

This helps you set the correct angle between your monitors for seamless viewing across all three screens.

Final Note
These calculations provide a strong starting point. Feel free to make small adjustments based on personal preferences, but try to stay close to these values for the most authentic driving experience.

Note: This utility supports calculations for both single and triple screen setups, with special consideration for racing simulator configurations including tilted side screens.








