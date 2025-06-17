Game World Generation
1. Introduction
A 2D tile-based world generation using Java with a feature that only displays tiles on the screen that are within the line of sight of the avatar. Please email me to view the code.

2. Class Project Site
https://sp24.datastructur.es/projects/proj3/

3. Features
Once the program is launched, a menu window will be displayed.

Screenshot 2024-05-21 at 6 11 29 PM
The following options are available:

• Press 'N' or 'n' to generate a new world.

• Press 'L' or 'l' to load a saved world.

• Press 'Q' or 'q' to quit the world.

After selecting a new world, another window will be displayed, asking the user to enter a seed. The seed is a positive number up to 9,223,372,036,854,775,807 and is used by the random generator to generate a unique game world. If you enter the same seed, an identical world will be generated.

Screenshot 2024-05-21 at 6 12 17 PM Screenshot 2024-05-21 at 6 12 29 PM
Once the seed is entered, press 'S' or 's' to pick the type of world — original, flower, or tree.

Screenshot 2024-05-21 at 6 12 43 PM
After pressing one of the keys to generate the world, only the player avatar (@) and its surroundings are visible, while the rest of the map is covered. Users can press 'W', 'A', 'S', 'D' to move the avatar around the world and ':Q' to quit and save the current state of the world. Also, a status bar is shown on the top left, displaying the type of tile over which a mouse cursor is hovering.

Screenshot 2024-05-21 at 6 20 01 PM
Users can press 'T' to increase the line of sight and view the entire world which consists of uniquely generated rooms and hallways. Below is the same world in different types.

Screenshot 2024-05-21 at 6 12 58 PM Screenshot 2024-05-21 at 6 14 12 PM Screenshot 2024-05-21 at 6 14 49 PM
