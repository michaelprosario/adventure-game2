# Grid Scene Editor Object Model

This document outlines the primary classes used in the `grid-scene-editor.html` application.

### `AppState`

The `AppState` class acts as a central repository for the application's state. It holds data that needs to be accessed globally, such as the list of all scenes, available block types, and the currently selected tool. This centralization simplifies state management and ensures consistency across different parts of the editor.

### `Scene`

The `Scene` class represents a single level or grid map. Each `Scene` object contains the grid's dimensions (width and height), the size of its cells, and a 2D array that stores the layout of block types. It also includes methods for modifying the grid, such as setting a cell's type, resizing the grid, and duplicating the scene.

### `BlockType`

The `BlockType` class defines the properties of the various blocks or tiles that can be placed on the grid. Each `BlockType` object has a unique ID, a name, a visual representation (color and optional image), and gameplay-related properties like collision behavior and interactivity. This class allows for the creation of a diverse palette of building blocks for level design.
