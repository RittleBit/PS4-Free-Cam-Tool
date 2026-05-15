# PS4-Free-Cam-Tool
External game camera tool for PS4 games.

How to Use
Step 1: Connection

Run PS4 FreeCam Tool.exe
Enter your PS4 IP address Click 🔌 Connect
Click 📋 Refresh Processes
Select your game eboot.bin from the list and click ✅ Attach Selected Process

(Make sure the latest ps4debug.bin is in use.)

Step 2: Camera Addresses Setup
Position (X / Y / Z)
Enter the three addresses for camera position.
Enable "Atomic XYZ Write" if the addresses are consecutive (X, X+4, X+8).

Rotation
Pitch / Yaw: Enter two float addresses.
3×3 Matrix: Switch tab and enter 9 addresses

FOV
Enter the FOV address.

Game Speed 
Enter address to control game speed.

Controls & Features

Controller Layout
Left Stick → Move (forward, back, strafe)
Right Stick → Look around (Pitch + Yaw)
L2 / R2 → Move Up / Down (Height)
X Button → Decrease FOV
Y Button → Increase FOV

Movement & Look Settings
Movement Mode: Camera-Relative (recommended) or World-Axis
Look System: Pitch/Yaw or Matrix
Look Mode: Normal or Swapped

Camera Path Editor
Click 📽️ Show Camera Path Editor
Fly to desired position → Click ⏺ Record Keyframe
Repeat for multiple points
Click ▶ Play Path
You can Save and Load paths 

Tuning Panel
Adjust these for better feel:
Rotation Smoothing
Move Smoothing
Input Smoothing
Deadzone
Speed Multipliers
Base Movement Speed

Tips for Best Results
Use Atomic XYZ whenever possible.
Start with default smoothing values, then tweak.
Record several keyframes for nice cinematic paths.

