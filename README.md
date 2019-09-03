# Simple Arcs
This modpack includes 3 mods: 

- pkarcs
- pkarcs_doors
- pkarcs_doors3

Note this is a fork of PEAK's mod Simple Arcs (pkarcs) https://forum.minetest.net/viewtopic.php?f=11&t=14541 which adds arched doors made to work specifically with the mod.

## Requirements
Works with MT/MTG 5.0.0+.

## License
Click [here](https://github.com/TumeniNodes/pkarcs/blob/master/LICENSE) to see the license.

## Installation
- Unzip the archive, rename the folder to pkarcs and
place it in .. minetest/mods/

- GNU/Linux: If you use a system-wide installation place
    it in ~/.minetest/mods/.

- If you only want this to be used in a single world, place
    the folder in .. worldmods/ in your world directory.

For further information or help, see:  
https://wiki.minetest.net/Installing_Mods

## Compatibility with mods
To make arcs from nodes of your mod, add "optional_depends = pkarcs" (**without the quotes**) to your "mod.conf",
and call this function in your `init.lua`:

`if minetest.get_modpath("pkarcs") then
	pkarcs.register_node("your_mod:your_nodename")
end`

## Bugs, suggestions, features & bugfixes.
Report bugs or suggest ideas by [creating an issue](https://github.com/TumeniNodes/pkarcs/issues/new).    
If you know how to fix an issue, or want something to be added, consider opening a [pull request](https://github.com/TumeniNodes/pkarcs/compare).

## Screenshots
![Preview](https://github.com/TumeniNodes/pkarcs/blob/master/pkarcs/screenshot.png)

![Preview](https://github.com/TumeniNodes/pkarcs/blob/master/pkarcs_doors/screenshot.png)

![Preview](https://github.com/TumeniNodes/pkarcs/blob/master//pkarcs_doors3/screenshot.png)

## Provided nodes
- default:cobble
- default:mossycobble
- default:stone
- default:stonebrick
- default:stone_block
- default:desert_cobble
- default:desert_stone
- default:desert_stonebrick
- default:desert_stone_block
- default:sandstone
- default:sandstonebrick
- default:sandstone_block
- default:brick
- default:obsidian
- default:obsidianbrick
- default:obsidian_block
- default:wood
- default:junglewood
- default:pine_wood
- default:acacia_wood

- default:aspen_wood

## Announcing the new doors
TumeniNodes 2017-07-03

Added pkarcs doors. Arched doors which work exclusively with pkarcs.

Basic options for doors are wood and metal types. (sorry, no glass types, you can add if you like)

Acacia Wood

Apple Wood (typically known as just "wood" in Minetest Game)

Aspen Wood

Jungle Wood

Pine Wood

Bronze

Copper

Iron

Steel

Tin

## Additional info
If you want to get additional info about this fork, go to the [Minetest Forums](https://forum.minetest.net/viewtopic.php?f=9&t=22839).  
If you want to go to the original topic of the mod, click [here](https://forum.minetest.net/viewtopic.php?f=11&t=14541).
