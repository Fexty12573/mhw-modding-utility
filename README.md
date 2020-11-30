# mhw-modding-utility
Utility with various functions for MHW modding

## Install
Put all 3 files in nativePC\plugins, launch game. Exe will launch when game launches.

### Usage
To select a monster click "List Loaded Monsters" and read index of preferred monster. Input that into "Target Monster Index" box and hit Apply.
Everything else should be fairly straight forward as everything is labeled.
Monster List, Player Coords, Action Log etc are logged in the loader console.
Action dumps get created in nativePC\ActionDumps\MonsterName.txt

Obivously don't do any monster stuff while no monsters are loaded.

#### Config
"Monster ID" is the ingame id of the monster, it is listed when using "List Loaded Monsters".
"Action Chain" is the chain of action ids the monster should execute. (It's *not* limited to 5 moves)
To add a new action chain simply copy paste an already existing one and edit it.


![Preview](https://github.com/Fexty12573/mhw-modding-utility/blob/main/ignore/image.jpg?raw=true)
