# Village Simulation with OpenGL

This project is a C++ OpenGL-based simulation of a village, featuring day and night transitions, moving boats, birds, clouds,  and dynamic sun positioning. The scene adjusts visual elements like color, and background music based on day and night.

## Features

- **Day/Night Cycle:** Changes visual elements like colors, and background music based on the time of day.
- **Moving Elements:** Boats, birds, clouds, and the sun/moon move dynamically within the scene.
- **Interactive Controls:** Switch between day and night modes using the keyboard.
- **Music:** Plays different background music tracks for day and night.

## How to Run

### Step 1: Open the Project in Code::Blocks or Compatible IDE
### Step 2: Link Required Libraries
- windows.h
- mmsystem.h (for sound)
- gl.h (OpenGL)
- glut.h (OpenGL Utility Toolkit)
- cmath (for mathematical operations)
- winmm.lib (for multimedia functions)
Also, go to **Settings > Compiler > Linker settings** and add the following flag:
```bash
-lwinmm
```
Click **OK** to apply the changes.


### Step 3: Build and Run the Project
Press *F9* or go to **Build > Build** and Run to compile and run the project.

## Controls
- (`d/D` key): Switch to Day Mode.
- (`n/N` Key): Switch to Night Mode.
- (`←/→` Keys): Navigate the small boat between the left and right land areas.

## Dependencies
This project requires the following libraries and components:

- OpenGL: Provides the graphics rendering functionality.
- GLUT (OpenGL Utility Toolkit): Used for windowing, input, and other tasks.
- GLU: OpenGL Utility Library for advanced rendering operations.
- C++: The project is written in C++, with specific dependencies on windows.h for multimedia handling (sound and music).

## Demo Video
![Demo Video](https://github.com/Sajjad2108/village-visualization-GLUT/commit/7e07684179fb012dc54b2be4db21786db5390d8a)


