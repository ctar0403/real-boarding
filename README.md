🏂 Splitboarding & Snowboarding Demo – Unity Project

Overview

This Unity project demonstrates a splitboarding and downhill snowboarding experience tailored for Android devices. It features real-world terrain data and smooth transitions between hiking uphill in ski mode and riding downhill on a snowboard. Built using Unity's URP (Universal Render Pipeline) for optimal mobile performance.

🎯 Demo Goals
✅ 1. Splitboarding Functionality
Implemented a mechanic where the player walks uphill with a split snowboard (skis).

At the summit, the board merges back into a snowboard and transitions into downhill riding mode.

✅ 2. Downhill Snowboarding
Integrated:

Simple Snowboarding Physics asset

Snowboard Actions Animation Pack

Supports seamless transition between splitboarding and snowboarding.

✅ 3. Real-World Terrain
Terrain sourced from Google Earth / MapBox.

Focused on a small, high-detail mountain area.

Exploring MapBox SDK, Terrain Tiles, and Real World Terrain options.

✅ 4. Mobile First (Android)
Targeting Android devices.

Built using Unity 2022.3 LTS and URP for better performance.

Uses baked lighting and LOD for optimization.

Avoids HDRP to maintain mobile compatibility.

![capture_Moment](https://github.com/user-attachments/assets/7b95c897-6a2c-4bb6-a4dd-9d626bb6c5a4)


🛠 Development Tasks
✅ Task 1: Base Project Setup
Unity version: 2022.3 LTS or newer

Configured for URP and Android Build Target

Imported:

Simple Snowboarding Physics

Snowboard Actions Animation Pack

Custom Character Controller

✅ Task 2: Character State Machine
Implemented using Animator + FSM (Finite State Machine)

States:

Idle

Walk Uphill

Merge Board

Snowboard

📁 Project Structure (Key Folders)
bash
Copy
Edit
Assets/
├── Animations/              # Snowboard & splitboard animations
├── Scripts/                 # State machine, player control, transitions
├── Terrain/                 # MapBox/real-world terrain data
├── Art/                     # Models, shaders, textures
└── Prefabs/                 # Character, terrain, props
🚀 How to Run
Open project in Unity 2022.3 LTS (or newer).

Set platform to Android via File > Build Settings.

Load the main scene from Assets/Scenes/MainScene.unity.

Build and run on a compatible Android device.

📦 Dependencies
Unity 2022.3 LTS+

Simple Snowboarding Physics

Snowboard Actions Animations

(Optional) MapBox SDK / Terrain Tiles / Real World Terrain

🧊 Notes
Terrain will be refined further using MapBox or Google Earth data.

Future updates may include weather effects, real-time snow deformation, and multiplayer mode.

📌 License
This project is for demo purposes and may use third-party assets under their respective licenses. Check each asset's license before publishing or distributing.
