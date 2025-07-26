## Project Document: Tongue Fury – Project Overview (Revised)

Game Title: Tongue Fury
Genre: Arcade, Action, Defense
Platform: PC (Initially)
Target Audience: Casual gamers, fans of arcade-style games, players who enjoy humorous action.
Core Mechanic: The frog's tongue moves directly where the mouse clicks, colliding with bugs. The tongue's movement is controlled by the mouse. Collisions result in the bug being pulled down for consumption (or exploding, depending on the bug type).
Engine: Godot Engine (Latest Stable Version)
Visual Style: Pixel art 2D – Utilizing a retro arcade aesthetic.
Assets: Prototype will utilize simple primitive shapes (squares, circles, triangles) as placeholder assets.

## Project Structure

```
tongue_fury/
├── assets/                    # All visual and audio assets
│   ├── sprites/              # 2D sprite images
│   │   ├── characters/       # Character sprites (frog, bugs)
│   │   │   ├── frog/         # Frog character sprites
│   │   │   └── bugs/         # Bug enemy sprites
│   │   ├── ui/               # User interface elements
│   │   ├── effects/          # Visual effects and particles
│   │   └── backgrounds/      # Background images and tilesets
│   ├── audio/                # Sound files
│   │   ├── music/            # Background music tracks
│   │   ├── sfx/              # Sound effects
│   │   └── voice/            # Voice acting files
│   └── fonts/                # Custom fonts
├── scenes/                    # Godot scene files (.tscn)
│   ├── levels/               # Game level scenes
│   ├── ui/                   # User interface scenes
│   └── effects/              # Visual effect scenes
├── scripts/                   # GDScript files
│   ├── autoload/             # Singleton scripts (game managers)
│   ├── classes/              # Reusable class scripts
│   └── utils/                # Helper functions and utilities
├── resources/                 # Game resources
│   ├── materials/            # Material files
│   ├── shaders/              # Custom shaders
│   └── data/                 # Game data files
└── addons/                    # Godot addons and plugins
```

## File Naming Conventions

- **Sprites**: Use snake_case (e.g., `frog_idle_32x32.png`)
- **Scenes**: Use PascalCase (e.g., `Level_01.tscn`, `MainMenu.tscn`)
- **Scripts**: Use snake_case (e.g., `frog_controller.gd`, `game_manager.gd`)

## Development Guidelines

- Keep scripts focused on single responsibilities
- Use inheritance for shared functionality
- Document complex functions with comments
- Organize assets by type and purpose
- Follow the established folder structure for consistency
