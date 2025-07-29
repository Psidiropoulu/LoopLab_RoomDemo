LoopLab Room Demo 🎮

A looping puzzle room prototype built with Unreal Engine 5.  
This project is part of LoopLab, a hands-on C++ and Blueprint learning experience for teens (ages 14–17), introducing core Unreal concepts like triggers, timelines, doors, and pressure plates.

--------------------------------------------------

🏗 Project Overview

- Engine: Unreal Engine 5.6  
- Language: Blueprint + C++  
- Goal: Build a resettable maze experience where players solve timed challenges in a confined environment.
- Features:
  - Pressure plates and doors
  - Timed resets
  - Looping mechanic logic
  - Trigger volumes for event control
  - Clean component-based Blueprint setup

--------------------------------------------------

📦 Getting Started

⚠️ This project is not complete out of the box.  
You must manually add missing assets from Fab (Unreal’s asset library) to avoid errors.

1. Clone the Repository

   git clone https://github.com/Psidiropoulu/LoopLab_RoomDemo.git

2. Add Required Content from Fab

   Content Pack        | How to Add
   --------------------|-------------------------------------------------
   ✅ Starter Content   | Open Fab → Search for "Starter Content" → Add
   ✅ Old West Pack     | Open Fab → Search for "OldWest" → Add

These must be installed to the project’s Content/ folder to fully load maps and Blueprints.

--------------------------------------------------

🧩 Folder Structure

LoopLab_RoomDemo/
├── Content/
│   ├── Blueprints/          # All core logic Blueprints
│   ├── Maps/                # Demo levels and loop testing scenes
│   ├── OldWest/             # External assets (add via Fab)
│   └── StarterContent/      # Epic's default material and mesh pack
├── Source/                  # (If C++ code is added)
├── LoopLab_RoomDemo.uproject
└── README.md

--------------------------------------------------

🎯 Educational Use

This project is designed to:

- Teach foundational game logic
- Bridge the gap between Blueprints and C++
- Build a reusable library of mechanics for game jams or school projects

--------------------------------------------------

🚧 Known Limitations

- ❌ No .exe packaged build (due to local SDK restrictions)
- 🔧 Requires manual content import from Fab
- 🔄 Ongoing improvements — this is an educational WIP

--------------------------------------------------

💡 Credits

Project lead and initial logic by @Psidiropoulu  
Assets courtesy of Epic Games and community content via Fab

--------------------------------------------------

📬 Feedback / Contributions

Pull requests are welcome!  
Issues, suggestions, and forks are encouraged.

--------------------------------------------------
