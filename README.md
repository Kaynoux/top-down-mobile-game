# Top-Down Mobile Game

A top‑down 2D mobile prototype built with Unity for iOS and Android. It focuses on smooth touch controls, clear visuals on small screens, and a simple structure that can be extended into a full game.

## Features

- **Top‑down 2D movement** with collision handling
- **Touch / virtual joystick controls** optimized for mobile
- **Basic inventory foundation** for collectable items
- **In‑game debug UI** (FPS and playtime display)

## Tech Stack

- **Engine**: Unity (URP 2D)
- **Language**: C#
- **Targets**: iOS & Android

## Project Structure

- `Project/Assets/Scenes` – main scenes and levels
- `Project/Assets/Scripts` – gameplay, UI and utility scripts
- `Project/Assets/Prefabs` – reusable game objects
- `Project/Assets/Sprites` – 2D art and icons
- `Project/Assets/Tilemaps` – level layout

## Controls (Mobile)

- **Movement**: on‑screen virtual joystick
- **Interactions**: context‑sensitive on‑screen buttons (if present)

## Getting Started

1. Clone the repository:
	```bash
	git clone https://github.com/Kaynoux/Top-Down-Mobile-Game.git
	cd Top-Down-Mobile-Game
	```
2. Open the project in **Unity Hub** (use the version from `ProjectSettings/ProjectVersion.txt`).
3. In `File > Build Settings`, select **iOS** or **Android** as the build target.
4. Choose a scene from `Project/Assets/Scenes` as startup scene and press **Play** in the editor.

## Building for Mobile

- **Android**: `File > Build Settings > Android`, configure Player Settings, then **Build** or **Build and Run**.
- **iOS**: `File > Build Settings > iOS`, generate an Xcode project and run it on a device or simulator.
