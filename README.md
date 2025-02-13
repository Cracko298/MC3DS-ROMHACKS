## Several Patches for MC3DS

### CrashGame
- Crashes the Game when attempting to load Worlds.

### AddFunction
- Adds a function Directly too the Game to retrive Coordinates from the Game Stack.
- Puts them in a free'd memory address 16-Bytes in length, traditionally `0x01E81000`, but can vary.
- Untested on 3DS Console itself.

### EnhancedPart32b
- Fixes some partical lag, and overall enhances certain stuff.
- Upgraded a Buffer from 2-Bytes (16-Bits) of Data to 4-Bytes (32-Bits), making the game take less time for some stuff.

## Repo has Moved here:
- [MC3DS Community GitHub](https://github.com/Minecraft-3DS-Community/GamePatches)
