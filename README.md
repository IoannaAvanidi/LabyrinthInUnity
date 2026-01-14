# Project 2 - Treasure Bob (Unity 3D)

A 3D interactive game developed using the **Unity3D** platform for the "Computer Graphics and Interaction Systems" course (Academic Year 2024-2025).

## 🎮 Game Overview
The player controls **Treasure Bob**, a sphere-shaped character navigating through a maze to collect treasures while avoiding deadly traps.

### Gameplay Mechanics
* **Objective**: Navigate the maze and collect "treasures" (cubes with fruit textures) to achieve a high score.
* **Treasures**: Three types of treasures appear randomly (Cherries, Oranges, Lemons). When Bob touches a treasure, it visibly shrinks and disappears.
* **Traps**: Spheres with a "death" texture appear randomly. Touching them results in an immediate Game Over.
* **Environment**: A $100\times100$ unit floor maze with blue walls made of $10\times10\times10$ cubes.

## ⌨️ Controls

### Treasure Bob Movement
* **X-Axis**: Use keys `<j>` and `<l>`.
* **Z-Axis**: Use keys `<i>` and `<k>`.

### Camera Controls
* **Movement**: Use the **Arrow Keys** to move the camera along the X and Z axes.
* **Height**: Use the `<+>` and `<->` keys to change camera altitude (Y-axis).
* **Rotation**: Use the `<r>` key to rotate the camera around its vertical (Y) axis.

## 🛠️ Technical Specifications
* **Resolution**: Fixed at $1024\times768$.
* **Asset Serialization**: Configured to "Force Text" for Git compatibility.
* **Version Control**: Visible meta files enabled.
* **Collision Detection**: Implemented to prevent Bob from passing through walls or leaving the maze boundaries.

## 🚀 Key Features
* **Dynamic Spawning**: Treasures and traps appear and disappear at random intervals and locations.
* **Scale Animations**: Smooth shrinking effect applied to collected items.
* **Physics Configuration**: Gravity is disabled for the player character to ensure movement remains on a fixed horizontal plane.

## 📋 Execution Instructions
1.  Open the project in **Unity Hub** (Version: 6).
2.  Ensure all textures (`bob.jpg`, `floor.jpg`, `death.jpg`, etc.) are in the `Assets/Textures` folder.
3.  Press **Play** in the Unity Editor or run the provided `.exe` build.
