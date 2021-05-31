# fabric-jpl-witherskeleton-mod

## About
This is a simple mod request from MrDPL.  It modifies WitherSkeleton entities using a Mixin inject to the HEAD of dropEquipment().  The injection replaces the item in their main hand (usually a stone sword) with ItemStack.EMPTY.  This way you don't get "junk" from a WitherSkeleton factory since what we really want are these: Items.WITHER_SKELETON_SKULL.

## Setup
This mod was created for Fabric Loader (i.e. FabricMC), so you need Fabric installed. This has been tested under Fabric Loader 0.11.3 and fabric-api-0.34.2+1.16.

To use the mod, copy the .jar (mod) to your minecraft instance 'mods' folder. Note: the mod will also require fabric-api-0.34.x for Minecraft 1.16.

Fabric Installer 0.7.3:

https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.7.3/fabric-installer-0.7.3.jar

Get Fabric API:

https://github.com/FabricMC/fabric/releases/download/0.34.6%2B1.16/fabric-api-0.34.2+1.16.jar


## License
This mod is provided under the CC0 license. Feel free to learn from it and incorporate it in your own projects.

