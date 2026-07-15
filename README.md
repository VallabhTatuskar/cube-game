# Grid Mechanics Technical Assessment

## Overview

This project is a Unity implementation of a grid-based mechanics system created as part of a technical assessment.

The project demonstrates grid generation, cell selection, data-driven cube variants using ScriptableObjects, cube spawning, and simultaneous grid-based movement while respecting boundary constraints.

---

## Features

- Inspector-driven grid generation (configurable width and height)
- Grid cell selection using mouse input
- Visual highlight for the selected cell
- Spawn cubes using the Space key
- One cube per grid cell
- ScriptableObject-based cube variants
- Mouse wheel to cycle through cube types
- Simultaneous movement of all spawned cubes using W/A/S/D
- Boundary checking to prevent cubes from leaving the grid

---

## Unity Version

Unity 6.3.x

---

## Controls

| Action | Input |
|--------|-------|
| Select Cell | Left Mouse Button |
| Change Cube Type | Mouse Scroll Wheel |
| Spawn Cube | Space |
| Move Cubes | W / A / S / D |

---

## Project Structure

```
Assets/
├── Materials/
├── Prefabs/
├── Scenes/
├── Scripts/
└── ScriptableObjects/
```

---

## Third-Party Assets

None

---

## Assumptions

- Grid dimensions are configurable through the Inspector.
- Only one cube can occupy a grid cell.
- Cube variants differ by color/material.
- Movement occurs one grid cell at a time.

---

## Known Limitations

- Cube movement is instantaneous (no animation).
- No UI indicator for the currently selected cube type.

---

## Future Improvements

- Smooth movement animations
- UI displaying the active cube type
- Object pooling for spawned cubes
- Save/Load functionality
- Additional cube properties and behaviors

---

## Author

Developed by **<Vallabh Tatuskar>**
