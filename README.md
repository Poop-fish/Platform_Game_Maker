# Platform Game Maker Engine
This repository provides the starting point for a Platform Game Maker Engine that allows users to create custom platformer game maps using a graphical interface. The engine is built using Pygame for game development, PyQt5 for GUI elements, and JSON for saving and loading maps. It's designed to be intuitive and easy to use, providing a simple environment where you can create levels by placing tiles like platforms, coins, keys, and doors on a grid.

### Key Features:
Grid-based map editor: Easily place tiles on a 2D grid to create game levels.
Multiple tile types: Includes tiles for platforms, coins, keys, and doors.
Undo functionality: Undo your last action with a simple click.
Save and Load maps: Save your map designs to a JSON file and load them later.
Customizable tiles: You can modify existing tiles or add new ones by adjusting the code.
This project is a starting point for a platform game maker engine, and it offers a flexible base for further expansion into a full-fledged game editor.

### How It Works:
Pygame handles the game development logic, including rendering tiles and managing the game loop.
PyQt5 is used to build the graphical user interface (GUI), integrating a Pygame surface into a PyQt window.
JSON format is used to save and load the level maps, allowing users to easily export and import their game designs.

### Tile Types:
Platform (Green)
Coin (Yellow)
Key (Neon Pink)
Door (Red)
Empty (White)
These tiles represent various elements of a platformer game level, and you can customize them as per your needs.

### Prerequisites:
Before you run the code, make sure you have the following installed:

Python (version 3.6 or higher)
Pygame: For game development and rendering tiles.
pip install pygame 
pip install PyQt5 

Using the Map Editor:

### Tile Selection: Use the menu bar at the top to select different tile types (Platform, Coin, Key, Door, Empty).
Placing Tiles: Left-click on the grid to place the selected tile at the clicked position.
Undoing Actions: Use the "Undo" option from the menu to revert your last action.
Saving and Loading Maps: You can save your maps in JSON format and load previously saved maps. To save, go to File > Save Map, and to load, go to File > Load Map.
Customizing Tiles:

You can add new tile types or modify existing ones by editing the Tile class and the MapEditor class.
Update the color and properties of tiles within the Tile class.
Exporting/Importing Maps:

The maps are saved in JSON format, making it easy to export and import different levels. You can open and modify saved maps using a text editor or within the game maker itself.
### Map layout 
[Map_Layout_Github](https://github.com/user-attachments/assets/e2b33f6a-3712-4bea-81b4-8a768e323801)

### Example Video

https://github.com/user-attachments/assets/850ac082-bb93-444f-84c2-325a25f1fbd4

