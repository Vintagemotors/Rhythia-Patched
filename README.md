# Sound Space Plus

Official Repo here: https://github.com/krmeet/sound-space-plus (Godot 3)

Nightly Next Gen repo: https://github.com/Rhythia/Rhythia (Godot 4)

# Development <a href="dev-title" id="dev"/>
After cloning the repository download the Discord Game SDK and put the following files into addons/discord_game_sdk:  
- `discord_game_sdk.dll`  
- `discord_game_sdk.dylib`  
- `discord_game_sdk.so` (__rename to `libdiscord_game_sdk.so`__)  


When building for MacOS you have to make an exception to allow it to run by running this command in the terminal: 
- `sudo xattr -dr com.apple.quarantine "replace_this_with_whatever_the_app_is_called.app"`
