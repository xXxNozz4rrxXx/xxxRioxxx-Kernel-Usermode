# kernel-BypassMethod For Faceit and EAC (its old you must update it) 

#### Simple kernel cheat with hook for communication
##Is it tested ?
- Yes its tested we was use this in a past to bypass faceit 
- Can be detected ofc
- Project name that we test it (AeonCheats)
## How to use
- download and compile in Visual Studio 2019 (with driver dev kit)
- manual map the kernel-csgo.sys driver using [kdmapper](https://github.com/xxxrioxxx/kdmapperDriver)
- run Counter-Strike: Global Offensive
- run kernel-csgo-usermode.exe and enjoy :)

## Features
- hooks a function for communication
- get_module_base / read_memory / write_memory all inside the driver
- implemented a basic triggerbot for PoC (mouse_event)
- easy to add other cheat features

## Make it safer by
- doing dynamic function imports
- encrypting strings
- changing the hook function
- not using kdmapper but making your own mapper
- not using mouse_event() haha
