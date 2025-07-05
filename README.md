# Grid Scene Editor Object Model

This document outlines the primary classes used in the `grid-scene-editor.html` application.

### `AppState`

The `AppState` class acts as a central repository for the application's state. It holds data that needs to be accessed globally, such as the list of all scenes, available block types, and the currently selected tool. This centralization simplifies state management and ensures consistency across different parts of the editor.

### `Scene`

The `Scene` class represents a single level or grid map. Each `Scene` object contains the grid's dimensions (width and height), the size of its cells, and a 2D array that stores the layout of block types. It also includes methods for modifying the grid, such as setting a cell's type, resizing the grid, and duplicating the scene.

### `BlockType`

The `BlockType` class defines the properties of the various blocks or tiles that can be placed on the grid. Each `BlockType` object has a unique ID, a name, a visual representation (color and optional image), and gameplay-related properties like collision behavior and interactivity. This class allows for the creation of a diverse palette of building blocks for level design.

## Firebase reference

## How to login to firebase in codespaces?

```
npm install -g firebase-tools
firebase login --no-localhost
firebase init
```

## References for Unity 3D

Absolutely, Michael! If you're aiming for a classic *Legend of Zelda*-style dungeon crawler in Unity3D, there’s a treasure trove of beginner-friendly tutorials that walk you through everything from tilemaps to combat systems. Here’s a curated list to get you started:

---

### 🧱 2D Dungeon Crawler Foundations

1. **[Unity Dungeon Crawler Tutorial 2D Game - Code and Assets](https://www.youtube.com/watch?v=DBPr00T2Tbw)**  
   This tutorial kicks off with tile palette setup, sorting layers, and basic movement. It’s perfect for laying the groundwork of a top-down dungeon crawler.

2. **[Unity Dungeon Crawler Tutorial 2D Game - Part 2 - Automated Combat](https://www.youtube.com/watch?v=xkz0veVavrM)**  
   A continuation that adds enemy interactions, knockback effects, weapon animations, and collider-based combat—ideal for mimicking Zelda’s swordplay.

---

### 🧭 Procedural Dungeon Generation

3. **[Procedural Dungeon Generator in Unity [TUTORIAL]](https://www.youtube.com/watch?v=gHU5RQWbmWE)**  
   Learn how to generate dungeon rooms dynamically using grid-based algorithms. Great for creating replayable levels.

4. **[Dungeon Crawler Using Procedural Generation in Unity](https://www.youtube.com/watch?v=rfKcpp8UDQ0)**  
   Offers a breakdown of dungeon generation logic, prefab setup, and validation—useful if you want to build randomized layouts like rogue-lites.

---

### 🕹️ Full Game Build & First-Person Variants

5. **[Make Complete Unity 3D Dungeon Game In 2 Hours With Free Assets](https://www.youtube.com/watch?v=pNlXlhJr2Y4)**  
   A rapid-fire tutorial that builds a complete dungeon game using AnyRPG. It’s 3D, but you can adapt the logic to 2D.

6. **[First Person Grid Based Dungeon Crawler Controller in Unity](https://www.youtube.com/watch?v=QTSWm1RsvzY)**  
   If you’re curious about old-school first-person dungeon crawlers (think *Eye of the Beholder*), this shows how to build a grid-based movement system.

