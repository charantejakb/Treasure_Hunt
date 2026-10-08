# Treasure Hunt

This project is a Unity-based game prototype focused on a treasure-hunting gameplay loop. It was created as a Unity project structure and includes the default Unity setup, scene assets, prefab files, and project settings needed to open and run the game in the Unity Editor.

## Project Details
- Project name: `Treasure hunt`
- Unity version: `6000.0.60f1`
- Solution file: `Treasure hunt.sln`
- Primary scene: `Assets/Scenes/SampleScene.unity`
- Default generated prefab: `Assets/Cube.prefab`

## Overview
The project currently appears to be in its early stage and includes a basic Unity scene setup that can serve as a foundation for gameplay development. The generated folder structure is typical for a Unity 6 project and includes:

- editable scenes in `Assets/Scenes`
- prefab assets in `Assets`
- engine and package settings in `ProjectSettings`
- local editor data in `UserSettings`
- package definitions in `Packages`

## Requirements
Before opening the project, make sure you have:

- Unity Hub installed
- Unity Editor version `6000.0.60f1` or a compatible version for this project
- A working desktop environment for Unity development

## Getting Started
1. Open Unity Hub.
2. Add the project folder to Unity Hub by selecting this repository root.
3. Open the project with Unity version `6000.0.60f1`.
4. Allow Unity to import the project and regenerate necessary metadata files.
5. Open the scene in `Assets/Scenes/SampleScene.unity` to begin modifying or extending the game.
6. If needed, use the Unity Play button to run the scene in the editor.

## Folder Structure
- `Assets/` – core game content such as scenes, prefabs, input settings, resources, and project-specific assets
- `Assets/Scenes/` – Unity scenes, including the default sample scene
- `Assets/Editor/` – editor-specific scripts and project utilities
- `Packages/` – Unity package manifest and dependency configuration
- `ProjectSettings/` – project-wide Unity configuration and build settings
- `UserSettings/` – local editor-specific preferences and configuration
- `Library/` – generated Unity library files and cached metadata
- `Logs/` – editor log files
- `Temp/` – temporary generated files

## Recommended Development Workflow
- Keep the Unity project structure intact when adding new scenes, prefabs, or scripts.
- Prefer organizing scripts under dedicated folders in `Assets/`.
- Use `Assets/Scenes` for gameplay scenes and `Assets/Resources` for shared runtime data.
- Avoid editing generated Unity metadata files manually unless necessary.
- Keep backups before changing major project settings or reimporting assets.

## Notes
- This project is a Unity-generated template and may not yet contain complete gameplay logic.
- If the project fails to open or behaves inconsistently, verify that Unity is using the correct version and that the project folder is not moved or renamed outside the Unity workflow.
- The editor may regenerate `Library/`, `Temp/`, and metadata files during the first import.

## Next Steps
Typical next steps for this project would include:

- creating the core gameplay loop for collecting treasure items
- designing a player controller and camera system
- adding obstacles, collectibles, UI, and win/lose logic
- implementing audio, effects, and polish for the final experience

This README is intended as a starting point and can be expanded as the game grows in complexity.
