# Not-A-Factory

Factorio-clone game written on C++ & Lua
Libaries used:
-SDL2
-SDL2-image
-fmt
-sol2
-imgui

Supports packages (modding)

Feel free to discuss anything about the game

Source code to be published soon, when everything would be organized

New ores as a resource not supported right now, but can be added via assembling machine recipe
To add entity from package into your hotbar, use player_lib:set_hotbar_slot(slot : int, prototype_name : string) in the in-game console

Prototype:
- Entity
"MiningDrillPrototype"
"AssemblingMachinePrototype"
"FurnacePrototype"
"InserterPrototype"
"TransportBeltPrototype"
"ContainerPrototype"

- Item
"ItemPrototype"

- Recipe
"RecipePrototype"
