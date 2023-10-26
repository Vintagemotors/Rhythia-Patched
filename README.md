# Sound Space Plus

Official Repo here: https://github.com/krmeet/sound-space-plus (Godot 3)

Nightly Next-Gen repo: https://github.com/Rhythia/Rhythia (Godot 4)

# Credits 
  kermeet and Frezby helping with my stupid questions 
  
  kermeet and kiwie doing 99.99% of the work 

  Frezby debugging and sharing some specific findings 
  
Compiled binaries might be here: https://github.com/Vintagemotors/Rhythia-Patched/releases
# Development <a href="dev-title" id="dev"/>
After cloning the repository download the Discord Game SDK and put the following files into addons/discord_game_sdk:  
- `discord_game_sdk.dll`  
- `discord_game_sdk.dylib`  
- `discord_game_sdk.so` (__rename to `libdiscord_game_sdk.so`__)\
  
  When you inevitably find bugs... if you can fix them please submit a PR Thanks 


When building for MacOS you have to make an exception to allow it to run by running this command in the terminal: 

 Open Terminal.app (press Cmd + Space and enter Terminal).

 Navigate to the folder containing the target application.

 Use the cd path_to_the_app_folder command, e.g. cd ~/Downloads/ if it's in the Downloads folder.
    
 `sudo xattr -cr "/Location/Of/App/appName.app"`

