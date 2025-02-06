# Not-A-Factory

**Not-A-Factory** is a Factorio-clone game written in C++ and Lua.

## Libraries Used

- SDL2
- SDL2_image
- fmt
- sol2
- ImGui

## Features

- Supports packages (modding)

## Development Status

Feel free to discuss anything about the game.

Source code will be published soon, once everything is organized.

## Notes

- Adding new ores as a resource is not supported currently but can be added via assembling machine recipes.
- To add an entity from a package into your hotbar, use the following command in the in-game console:

  ```lua
  player_lib:set_hotbar_slot(slot : int, prototype_name : string)
  ```
- New ores as a resource not supported right now, but can be added via assembling machine recipe
- To add entity from package into your hotbar, use player_lib:set_hotbar_slot(slot : int, prototype_name : string) in the in-game console


## Prototypes

Prototype:
- Entity\
"MiningDrillPrototype"\
"AssemblingMachinePrototype"\
"FurnacePrototype"\
"InserterPrototype"\
"TransportBeltPrototype"\
"ContainerPrototype"

- Item\
"ItemPrototype"

- Recipe\
"RecipePrototype"
