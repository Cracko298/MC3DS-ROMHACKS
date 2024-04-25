## Several Patches for MC3DS

### CrashGame
- Crashes the Game when attempting to load Worlds.

### AddFunction
- Adds a function Directly too the Game to retrive Coordinates from the Game Stack.
- Puts them in a free'd memory address 16-Bytes in length, traditionally `0x01E81000`, but can vary.
- Untested on 3DS Console itself.
