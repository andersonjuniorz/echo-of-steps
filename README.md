# Echo of Steps | 3D Platformer

<img width="1360" height="768" alt="EchoOfStepsTrailer" src="https://github.com/user-attachments/assets/444d27ec-be5d-4922-bbaf-28a493283942" />

## Description
**Echo of Steps is a stylized 3D platformer** developed in Unreal Engine `5.7`. This project started as an initiative to study and dive deep into the core fundamentals of game development within Unreal Engine.

## Goals
To develop `decoupled` and `modular` systems, following best practices in software development.

## Key Features & Game Quality
The project was developed under the pillars of **Software Engineering** to ensure clean and professional code:

* `Maintainability:` Organized and commented code, facilitating quick fixes and improvements.
* `Portability:` Optimized for entry-level hardware, ensuring accessibility across different setups.
* `Scalability:` Architecture that allows adding new levels and mechanics without overcomplicating the project.
* `Efficiency:` Strict resource management (VRAM/Disk) to maintain high performance.
* `Reusability:` Interaction and collection systems created as independent modules, ready for other projects.


## Project Structure

```text
Content/
├── Characters/           # Main character logic and meshes
├── EchoOfSteps/          # Project core (Blueprints, Maps, and UI)
├── Environment/          # Environment and scenery assets
├── Input/                # Enhanced Input configurations
├── LevelPrototyping/     # Level design blocking and testing
├── ThirdPerson/          # Unreal Engine base templates
└── Variant_Platforming/  # Platform-specific mechanics

```

# 💻 System Requirements

| Component | Minimum Requirement |
| :--- | :--- |
| **OS** | Windows 10/11 (64-bit) |
| **Processor** | Intel Core i3-530 / AMD A6-3650 or better |
| **Memory** | 4 GB RAM |
| **Graphics** | NVIDIA GeForce 920MX (2 GB VRAM) or equivalent |
| **DirectX** | Version 11 / 12 |
| **Storage** | 800 MB available space |

---

# Where to download the build (For Players)?

### Method 1 - Itch.io (Recommended)
Visit the project page for download and see the screenshots and more details:   
`https://andersonjuniorz.itch.io/echo-of-steps`

### Method 2 - GitHub Releases
Download the `EchoOfSteps.zip` build (489MB) directly from this repository's releases section:   
`https://github.com/andersonjuniorz/echo-of-steps/releases/tag/v1.0.0`

# How to open the source code (For Devs)?
Follow these steps to download the project correctly:

1. Clone the repository:
```
git clone https://github.com/andersonjuniorz/echo-of-steps.git
```

2. Install Git LFS:
You need Git Large File Storage for the large assets. Download it at `git-lfs.com`

3. Pull the Assets:
Open the project folder in your terminal and run these commands to download the real files:
```
cd echo-of-steps
git lfs install
git lfs pull
```
4. Open the Project:
Double-click `EchoOfSteps.uproject` to open the project in Unreal Engine 5.

5. Starting Level:
You can find the main menu level at: `EchoOfSteps > Maps > MainMenu > Lvl_MainMenu`


## Gameplay - How to play?

`WASD` - Player Movement   
`Space` - Jump   
`Left Shift` - Dash   
`ESC` - Pause   

