
# UE-Crossyroad-3D 🐔🚗

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-5.x-blue?style=flat-square&logo=unrealengine)


A 3D arcade hopper recreation inspired by the classic mobile game *Crossy Road*, built entirely in **Unreal Engine**. Navigate through procedurally generated environments, dodge traffic, cross rivers, and see how far you can survive!

## 🎮 Features

* **Procedural Level Generation:** Endless, dynamically generated terrain ensuring no two runs are ever exactly the same.
* **Grid-Based Movement:** Snappy, arcade-style hopping mechanics faithful to the original game.
* **Dynamic Hazards:** 
  * 🚗 **Traffic:** Dodge cars and trucks speeding across multi-lane roads.
  * 🚂 **Trains:** Watch out for the warning signals before high-speed trains rush by.
  * 🌊 **Rivers & Logs:** Carefully time your jumps across floating logs to avoid falling into the water.
  * 🦅 **The Eagle:** Don't stay still for too long, or the eagle will catch you!
* **High Score Tracking:** Automatically tracks your current distance and saves your best runs.

## ⚙️ Prerequisites

To run or edit this project, you will need:
* **Unreal Engine** (Version 4.27 or 5.0+)
* **Git LFS** (Large File Storage) - *Crucial for downloading the 3D assets, textures, and audio files properly.*

## 🚀 Getting Started

1. **Clone the repository:**
   Ensure you have Git LFS installed, then run the following commands in your terminal:
   ```bash
   git lfs install
   git clone https://github.com/Exene9/UE-Crossyroad-3D.git
   ```

2. **Open the Project:**
   * Launch the Unreal Engine Editor.
   * Click on **Browse** and navigate to the folder where you cloned the repository.
   * Select the `UE-Crossyroad-3D.uproject` file.

3. **Play the Game:**
   * Open the Main Menu or Gameplay map located in the `Content/Maps` directory.
   * Hit the **Play** button (PIE - Play In Editor) to start hopping!

## 🕹️ Controls

| Action | Keyboard |
| :--- | :--- |
| **Move Forward** | `W` or `Up Arrow` |
| **Move Backward** | `S` or `Down Arrow` |
| **Move Left** | `A` or `Left Arrow` |
| **Move Right** | `D` or `Right Arrow` |
| **Pause/Menu** | `Esc` or `P` |

## 📁 Project Structure

```text
UE-Crossyroad-3D/
├── Content/
│   ├── Blueprints/    # Core logic (Player, Spawners, GameMode)
│   ├── Maps/          # Levels and UI scenes
│   ├── Meshes/        # 3D Voxel Models (Characters, Vehicles, Environment)
│   ├── Materials/     # Textures and Materials
│   ├── Audio/         # Sound effects and music
│   └── UI/            # Menus, HUD, and Score widgets
└── UE-Crossyroad-3D.uproject
```

