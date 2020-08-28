# 2D-PCG-Shooter
Final Year Project

My final year project was a look into PCG vs manually created gameplay.
For this reason there are 4 builds of the game which gradually add new procedural elements.
As this was a research project the game is relatively barebones and has been hard-coded in places due to its small scale.

The first iteration of the game includes a playable character that can move and shoot, with a few weapons that can be picked up,
as well as a small preset level using some basic instances of game design theory.

The second iteration of the game functions the same as the first but now includes procedurally generated levels,
this works by creating a diamond shape of possible locations for "rooms", then a number is generated for how many rooms there should be (up to 25),
rooms are then created to fill that number and any inaccessible rooms are destroyed. Each room is then populated with a premade level "tile",
and a goal is created in one of the rooms.

The third iteration of the game adds procedurally generated weapons, which generates random values for various aspects of the weapons,
these include, number of shots per trigger pull, accuracy and fire rate.

The fourth iteration of the game adds procedurally generated enemies, this simply gives the enemies a small variance in health and speed based on the type of enemy,
as well as often giving the enemies a procedurally generated weapon.

Controls:
W, A, S, D - Move
E - Pick up weapon (while stood on top of the weapon)
Mouse1 - Shoot
