# StarThief26 Datapacks

### Setup
---
This datapack requires no other datapack dependencies, although it may require a resource pack, and will work with all or nearly all other datapacks created by [StarThief26](https://github.com/StarThief26).

To set up this pack, place the .zip file into the `datapacks` folder of your world. To find this, navigate to your `.minecraft` folder (usually found by searching for the `%appdata%` folder), then find the `saves` folder, and select the world you would like to install the datapack in. Either type `/reload` or relog onto the world again for that datapack to install. 

If the datapack successfully installs you should receive a message similar to this:
```
[INFO] Datapack v0.0 has been installed
```

### Options
---
If you wish to change any options in the datapack or find any commands the datapack has added, first make sure the world has cheats enabled. 

To see the help menu, type in the command `/function datapack:help`. If multiple datapacks by StarThief26 are installed you may have to scroll to the header containing this datapack's name. Under it are listed all user commands added by this datapack. Simply click on the command to automatically suggest it in the chat window. This command is only accessible by server admins with access to commands. For everyday player use, there is an advancement menu that displays all of the installed datapacks, and hovering over a specific datapack will give a brief description as well as list any commands all players can use.

If you wish to change an options the datapack contain, navigate to the help menu and look for the `/function datapack:options` command. This command will pull up the options menu. If no options are available for this datapack, a warning will appear in the chat. Simply click the red or green text to change the option listed. Hovering over the option name will provide a current description of what the datapack is allowing. Click the buttons on the bottom of the options UI to cycle through pages, if there are multiple pages available.

### Updating
---
If you are updating this datapack to a new version, the process is painless and simple. Simply delete the previous version of the datapack from the `datapacks` folder, then place in the new version of the datapack. Either type `/reload` or relog onto the world again for that datapack to update. 

If the datapack successfully updates you should receive a message similar to this:
```
[INFO] Datapack v0.0 is updating from an older version
```

### Bugs
---
If you notice any bugs, please report them by joining the [Discord community](https://discord.gg/8NeC6Gn) and reporting them there.

### Uninstalling
---
If you are uninstalling this datapack, the process is painless and simple. Simply navigate to the help menu (as discussed in the 'Options' section), and select the `/function datapack:uninstall` command. Then, simply delete the datapack from the `datapacks` folder. While simply deleting or disabling the datapack is also a safe option, it may leave some junk data in your world. It is also good to note that not all of the junk data may be cleared upon uninstallation due to unloaded chunks. Do not use the uninstall command lightly: it will delete most saved data that the pack has stored.

If the datapack successfully uninstalls you should receive a message similar to this:
```
[INFO] Datapack v0.0 has been uninstalled
```

### Warnings
---

Warnings are a log that shows when the datapack has encountered an non-critical error. These are errors that have a low chance to actually break something in game, but should be still be fixed if they are problematic. 

##### Downgrading

If you recently updated a datapack without removing the previous version or attempted to downgrade a pack, you may receive this warning. While in certain cases this may case packs to run improperly, it shouldn't point to any game breaking error. Although, it is still not recommended to downgrade a pack. 
```
[WARNING] Datapack v0.0 is downgrading from a newer version
```

##### Uninstalling Scoreboards

This warning is due to scoreboard data becoming corrupt. In order to prevent the datapacks from breaking, certain scoreboards will no longer be removed when uninstalling.
```
[WARNING] All datapacks made by StarThief26 can no longer remove all scoreboards while uninstalling
```

##### Required Resource Pack
If you recently installed a datapack that requires a resource pack or recently disabled a resource pack, you may receive this warning. Simply download and enable the resource pack to fix this error. You may click on the 'StarThief26 Datapack Textures' text to download the latest release.

```
[WARNING] Datapack v0.0 require the 'StarThief26 Datapack Textures' resource pack in order to properly run
```

### Errors
---

Warnings are a log that shows when the datapack has encountered an critical error. These are errors that have a high chance to actually break something in game, and should be still be fixed as soon as possible. 

##### Disabled Datapack
If you recently installed a datapack that shares global resources with another datapack, you may receive this error. This will completely disable the datapack without disrupting the saved data due to a critical error. Simply fix any previous errors before trying anything else. In order to re-enable the datapack, type the commands `/datapack enable ` and press tab to select the correct datapack. 
```
[ERROR] Datapack v0.0 is now disabled
```

##### Unique Global Resources
If you recently installed a datapack that shares global resources with another datapack, you may, on rare occasions, receive this error. This means that two datapacks share competing resources, and one will never work properly. The only fix is to remove one of the packs. 
```
[ERROR] Datapack v0.0 uses unique global resources that conflict with another pack
```

##### Old Global Resources
If you recently installed a datapack that shares global resources with another datapack, you may receive a global resource error. You may also receive this warning if you attempt to downgrade a pack, which is not recommended. To fix this, simply update the offending pack. 

```
[ERROR] Datapack v0.0 uses old global resources and needs to be updated
```
### About
---
These datapacks were created due to the inconsistencies in current MineCraft datapacks, mass lag in some current datapacks, the lack of decent modifiable features that some mod configs allow, and non user friendly instructions. Although datapacks like [Phi](https://github.com/MinecraftPhi/MinecraftPhi-modules) and [Datapack Utilities](https://github.com/ImCoolYeah105/Datapack-Utilities) are being developed to solve the inconsistency problem, they depend on outside sources to be updated and developed. In addition, all efforts to reduce lag in these packs have been made, so that the packs are more accessible to those with lower end computers. Decent in game option's UI, help menu, and pack logging system have also been added, so that all users can easily find what they need from *any* datapack with a maximum of one command to look up in a simply and easy way. 

In order to solve the inconsistency problem, all of these datapacks use custom, shared global resources. These are specific scoreboards, tags, and functions that all of the datapacks can share. In an attempt to make them compatible with other packs, each pack also uses a one to four letter prefix on all of its local resources, and all global resources use the prefix `stdp.`, and all custom models will use the prefix `26xxx`. While these are all good tactics, for any new (or old) datapack developers, going over and integrating the base datapacks of [Phi](https://github.com/MinecraftPhi/MinecraftPhi-modules) and [Datapack Utilities](https://github.com/ImCoolYeah105/Datapack-Utilities) into your work in an attempt to make *all* datapacks cross compatible is recommended; it's simply the easier way. In addition, many datapack conventions, such as those found in the [Minecraft Datapacks Discord](https://discord.gg/DTEC83G), should be followed. This series of datapacks will make every effort to be compatible with [Phi](https://github.com/MinecraftPhi/MinecraftPhi-modules) and [Datapack Utilities](https://github.com/ImCoolYeah105/Datapack-Utilities); however, none of these datapacks have been specifically or extensively tested with those base datapacks.

In order to solve the lag issue, any way lag can be reduced without a major loss in features has been attempted. New and creative ways such as using advancement and loot table triggers over a constant loop have been implemented. Whenever such loops are needed, however, global resources are used. These resources are usually events that will cause some amount of lag (@e calls, @a calls, advancement triggers,...) and are shared between any datapacks that need such event calls.

### License
---
[MIT License](https://choosealicense.com/licenses/mit)
Copyright (c) 2019 [StarThief26](https://github.com/StarThief26)
