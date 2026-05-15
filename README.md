## How to Use

### Step 1: Connection
1. Run `PS4 FreeCam Tool.exe`
2. Enter your **PS4 IP address**
3. Click **🔌 Connect**
4. Click **📋 Refresh Processes**
5. Select your game process (`eboot.bin`) and click **✅ Attach Selected Process**

> Make sure the latest **ps4debug** payload is running on your PS4.

### Step 2: Camera Addresses Setup

#### Position (X / Y / Z)
- Enter the three memory addresses for the camera position.
- Enable **"Atomic XYZ Write"** if the addresses are consecutive (`X`, `X+4`, `X+8`).

#### Rotation
- **Pitch / Yaw** (most common): Enter the two float addresses.
- **3×3 Matrix**: Switch to the Matrix tab and enter all 9 float addresses.

#### Additional Addresses
- **FOV** – Enter the Field of View address.
- **Game Speed** – (Optional) Enter address to control game speed.

## Controls

### Controller Layout
- **Left Stick** → Move (forward, strafe)
- **Right Stick** → Look (Pitch + Yaw)
- **L2 / R2** → Move Up / Down (Height)
- **X Button** → Decrease FOV
- **Y Button** → Increase FOV

### Movement & Look Settings
- **Movement Mode**: `Camera-Relative` (recommended) or `World-Axis`
- **Look System**: `Pitch/Yaw` or `Matrix`
- **Look Mode**: `Normal` or `Swapped`

## Camera Path Editor
1. Click **📽️ Show Camera Path Editor**
2. Fly to a desired position and click **⏺ Record Keyframe**
3. Repeat for multiple points
4. Click **▶ Play Path** to playback the smooth cinematic path
5. Use **Save** / **Load** to store paths as `.json` files

## Tuning Panel
Fine-tune the feel of the camera:
- Rotation Smoothing
- Move Smoothing
- Input Smoothing
- Deadzone
- Speed Multipliers
- Base Movement Speed
