#  3D Raycaster
> A pseudo-3D engine built from scratch using raycasting techniques.

##  Project Overview
This project is a 3D rendering engine that simulates a three-dimensional environment using **2D raycasting**. It was developed for the **NMB Tech Fair** to demonstrate how early 3D games created immersive worlds with limited hardware.

## Key Features
*   **Real-time 3D Rendering**: Converts a 2D grid map into a 3D perspective.
*   **3D Model Integration**: Includes a custom **PC** file (341KB) rendered within the environment.
*   **Dynamic Movement**: Smooth keyboard/mouse controls to navigate the space.

##  Technical Implementation
### The Raycasting Logic
The engine calculates "hits" by casting rays from the player's position. For every vertical strip on the screen:
1.  **Cast a Ray**: Calculate the angle based on the player's Field of View (FOV).
2.  **Distance Calculation**: Measure the distance to the nearest wall on the 2D grid.
3.  **Draw Walls**: The height of the drawn wall is inversely proportional to its distance (closer = taller).

##  How to Use
1.  Use **W, A, S, D** or **Arrow Keys** to move.
3.  Observe how the **PC** interacts with the environment.

Created by **Om Patel** for the 2026 Tech Fair.
