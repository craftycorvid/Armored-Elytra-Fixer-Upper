# Vanilla Tweaks Data Fixer

A datafixer mod to convert data stored by the [Vanilla Tweaks Armored Elytra Data Pack](https://vanillatweaks.net/picker/datapacks/) from the old NBT format(1.20.4 and below) to the new components format(1.20.5+)

## How to use this mod
1. **MAKE A BACKUP OF YOUR WORLD!**
2. Make SURE you can load that backup of your world if things go sideways
3. I'm serious, it's not my fault if you lose your whole world!
4. Install 1.20.6 or 1.21, fabric and this mod
5. Start the game and optimize your world
    - On a server add `--forceUpgrade`
    - On a client select the save, click Edit, click Optimize World
6. Shut down the server or close your game
7. Delete this mod, its job is done
8. Enjoy!

## Things to note
- For singleplayer it should be as easy as installing the mod and loading the world.
- For multiplayer I had to come up with a workaround to the fact that Minecraft only updates player data when people connect to your server. This mod uses the `usercache.json` file to load, update and save all your player's data. 
- If you copy your world to a client, install the mod and run it things will seem to work for your player, but other player's data won't be updated. You also need to copy `usercache.json` into your `.minecraft` folder for the mod to find all your players and update them.