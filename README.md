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
- To add entity from package into your hotbar, use player_lib:set_hotbar_slot(slot : int, prototype_name : string) in the in-game console
###
- player_lib
  
  ```lua
    player_lib:set_position(new_position: table)
    player_lib:get_position() -> table

    player_lib:set_hotbar_slot(slot: int, prototype_name: string)
    player_lib:get_hotbar_slot(slot: int) -> string
  ```
###
- core_lib
  ```lua
    core_lib:__new_prototype(prototype : string, copy_name : string) -> userdata
  ```

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
