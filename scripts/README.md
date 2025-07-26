# Scripts Directory

This directory contains all GDScript files organized by purpose.

## Structure:
- **autoload/**: Singleton scripts that are automatically loaded
  - Game managers
  - Global state managers
  - Audio managers
- **classes/**: Reusable class scripts
  - Base classes for characters
  - Utility classes
  - Data structures
- **utils/**: Helper functions and utilities
  - Math utilities
  - File handling
  - Debug helpers

## File Naming Convention:
- Use snake_case for script names
- Use descriptive names that indicate the script's purpose
- Example: `game_manager.gd`, `frog_controller.gd`, `math_utils.gd`

## Best Practices:
- Keep scripts focused on a single responsibility
- Use inheritance for shared functionality
- Document complex functions with comments 