BAGUAL GAME

This project was developed as a final assignment for my college semester.

It is a terminal-based game where the player navigates through maps, avoiding obstacles and trying to reach the goal.

The project also includes a map system with a list of maps and a built-in map editor.

FEATURES

Terminal-based gameplay using curses
Multiple maps loaded from files
Map selection menu
Map editor (create and save custom maps)
Basic movement system with collision
Win and lose conditions

GAMEPLAY

Move using arrow keys
Avoid obstacles (#)
Traps ($) end the game
Goal (%) completes the level

MAP SYSTEM

Maps are stored as text files
Each map includes size, start position and layout
Maps are loaded dynamically from a folder
Maps are sorted and listed in a menu

MAP CREATOR

The project includes a simple editor to create maps directly in the terminal:

Choose map size
Place elements manually
Save maps to files

STRUCTURE

main.c: program entry and main loop
play.c: game loop and player interaction
mapreader.c: reads maps from files
maplist.c: displays available maps
mapcreator.c: map editor system
menu.c: main menu interface

HOW TO RUN

Compile with:

gcc *.c -o game -lncurses

Run:

./game

WHAT I LEARNED

Working with file I/O in C
Dynamic memory allocation (2D arrays)
Structuring a larger project with multiple modules
Building a simple editor inside the terminal
Handling input and rendering with curses

NOTES

This project was developed for academic purposes, so there are areas that could be improved in terms of structure and optimization.

The focus was on functionality and learning how to manage a more complete system with multiple components.
