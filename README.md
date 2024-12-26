# Platform Game Maker Engine
This repository provides the starting point for a Platform Game Maker Engine that allows users to create custom platformer game maps using a graphical interface. The engine is built using Pygame for game development, PyQt5 for GUI elements, and JSON for saving and loading maps. It's designed to be intuitive and easy to use, providing a simple environment where you can create levels by placing tiles like platforms, coins, keys, and doors on a grid.

###Key Features:
Grid-based map editor: Easily place tiles on a 2D grid to create game levels.
Multiple tile types: Includes tiles for platforms, coins, keys, and doors.
Undo functionality: Undo your last action with a simple click.
Save and Load maps: Save your map designs to a JSON file and load them later.
Customizable tiles: You can modify existing tiles or add new ones by adjusting the code.
This project is a starting point for a platform game maker engine, and it offers a flexible base for further expansion into a full-fledged game editor.

###How It Works:
Pygame handles the game development logic, including rendering tiles and managing the game loop.
PyQt5 is used to build the graphical user interface (GUI), integrating a Pygame surface into a PyQt window.
JSON format is used to save and load the level maps, allowing users to easily export and import their game designs.

###Tile Types:
Platform (Green)
Coin (Yellow)
Key (Neon Pink)
Door (Red)
Empty (White)
These tiles represent various elements of a platformer game level, and you can customize them as per your needs.
