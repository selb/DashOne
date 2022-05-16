## What is this?

This is Hetuw mod, adapted for 2HOL.

## How to install?

- Download the latest version of Hetuw_with_minitech.exe here: https://github.com/risvh/OneLife-1/releases
- Put Hetuw_with_minitech.exe alongside OneLife.exe in your 2HOL game folder
- Double click Hetuw_with_minitech.exe to play

## What does this do?

- Better Zoom (FOV)
- Keyboard Control
  - WASD movement, Shift + WASD for left click, Ctrl + WASD for right click
  - Space, shift/ctrl + space to interact with the tile you are in
  - E to eat
  - Q for backpack
  - You can see the full list of keys in Help menu (press H in game)
- Display your Age
- Show Coordinates
- Show Player Names

Read more via links below:
  - https://github.com/hetuw/OneLife
  - https://onehouronelife.com/forums/viewtopic.php?pid=53465#p53465

## What is Town Planner?

Town planner helps you design your town. Put TownPlanner.exe alongside OneLife.exe to work. Your maps, the scene files, are saved in the scenes folder.

## Key Control in Town Planner?

```
Move view - Ctrl + L 
Move view - Click / Shift + WASD
Move view - E to hide UI first, then left click on map
Hide UI - E

Left Click - To place what you picked
Clear object - Right Click
Clear floor - Ctrl + Right Click
Clear object and floor - Shift + Right Click
Z - Undo
X - Redo
C - Copy Cell
V - Paste Cell
Shift + C - Copy 6x6 Area
Shift + V - Paste 6x6 Area
Q - Clear Cell
Shift + Q - Clear 6x6 Area
F - Pick Object
Shift + F - Pick Floor
Ctrl + F - Pick Biome
Shift + Left Click if cell has container - Put Object in Container
Shift + Left Click if biome is picked - Flood Fill Biome

Space - Focus Search Box
Enter - Search and Unfocus Search Box
Tab - Next Search Page
Shift + Tab - Previous Search Page
```

## Can I copy my town from the actual game, to be edited in Town Planner?

Yes, you need to create the ini file below in the settings folder, with the value specified to enable it, then run Hetuw:
```
outputMapOn.ini, 1 = enabled, 0 = disabled
```

Below are more settings to fiddle around. Again, create the ini files if they don't exist in the settings folder:
```
outputMapID.ini, -1 = a new map is generated every time you start hetuw, any other values means that the scene/map with that ID will continue to be explored (empty area will get filled in)
outputMapMapSizeX.ini, default map size is 400x400, it's not recommended to go above this size
outputMapMapSizeY.ini, see above
outputMapInitCenterX.ini, where origin should be in the map, default is (200, 200)
outputMapInitCenterY.ini, see above
```

## Other Settings for Town Planner?

```
townPlannerMapSizeX.ini, size of new map created in Town Planner, default is 200
townPlannerMapSizeY.ini, see above
townPlannerInitCenterX.ini, where origin is on the map, default is (100, 100)
townPlannerInitCenterY.ini, see above
townPlannerQueueCapacity.ini, how many times you can undo, default is 8
```
