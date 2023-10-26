# Rhythia (Sound Space Plus) 

Official Repo here: https://github.com/krmeet/sound-space-plus (Godot 3)

Nightly Next-Gen repo: https://github.com/Rhythia/Rhythia (Godot 4)

Compiled binaries might be here: https://github.com/Vintagemotors/Rhythia-Patched/releases

# Credits 
  kermeet and Frezby helping with my stupid questions 
  
  kermeet and kiwie doing 99.99% of the work 

  Frezby debugging and sharing some specific findings 
  

# Development <a href="dev-title" id="dev"/>
After cloning the repository download the Discord Game SDK [Example project that should have the files](https://github.com/samsface/godot-discord-game-sdk/archive/refs/heads/master.zip) and put the following files into addons/discord_game_sdk:  
- `discord_game_sdk.dll`  
- `discord_game_sdk.dylib`  
- `discord_game_sdk.so` (__rename to `libdiscord_game_sdk.so`__)

  [Readme](https://github.com/Vintagemotors/Rhythia-Patched/tree/main/addons/discord_game_sdk#readme)
  
  When you inevitably find bugs... if you can fix them please submit a PR Thanks 


When building for MacOS you have to make an exception to allow it to run: 

 Open Terminal.app (press Cmd + Space and enter Terminal).
 
 Then run this command 
    
 `sudo xattr -cr "/Location/Of/App/appName.app"`

