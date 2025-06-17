Game World Generation
1. Introduction
A 2D tile-based world generation using Java with a feature that only displays tiles on the screen that are within the line of sight of the avatar. Please email me to view the code.

2. Class Project Site
https://sp24.datastructur.es/projects/proj3/

3. Features
Once the program is launched, a menu window will be displayed.
<img width="399" alt="Screenshot 2025-06-16 at 10 33 51 PM" src="https://github.com/user-attachments/assets/b21f1176-059d-4e5f-9398-7e1aa94e5e3e" />


The following options are available:

• Press 'N' or 'n' to generate a new world.

• Press 'L' or 'l' to load a saved world.

• Press 'Q' or 'q' to quit the world.

After selecting a new world, another window will be displayed, asking the user to enter a seed. The seed is a positive number up to 9,223,372,036,854,775,807 and is used by the random generator to generate a unique game world. If you enter the same seed, an identical world will be generated.<img width="457" alt="Screenshot 2025-06-16 at 10 34 12 PM" src="https://github.com/user-attachments/assets/fc529224-c634-43b0-ba77-f8beb7ca105b" />



Once the seed is entered, press 'S' or 's' to pick the type of world — original, flower, or tree.
<img width="498" alt="Screenshot 2025-06-16 at 10 34 36 PM" src="https://github.com/user-attachments/assets/3fc0f9a0-7576-4786-a7ab-34a3550eb26d" />


After pressing one of the keys to generate the world, only the player avatar (@) and its surroundings are visible, while the rest of the map is covered. Users can press 'W', 'A', 'S', 'D' to move the avatar around the world and ':Q' to quit and save the current state of the world. Also, a status bar is shown on the top left, displaying the type of tile over which a mouse cursor is hovering.
<img width="504" alt="Screenshot 2025-06-16 at 10 34 49 PM" src="https://github.com/user-attachments/assets/ba00689f-5474-44be-a99b-e4810644d081" />

Users can press 'T' to increase the line of sight and view the entire world which consists of uniquely generated rooms and hallways. Below is the same world in different types.

<img width="815" alt="Screenshot 2025-06-16 at 10 35 08 PM" src="https://github.com/user-attachments/assets/01d65ee6-dfe9-44e6-8895-30cd681ceb55" />

