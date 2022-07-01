# WebDisplays for Minecraft 1.12.2 (RadiatedExodus's fork)
This is my personal fork of the popular [Webdisplays](https://github.com/montoyo/webdisplays) mod created by [montoyo](https://github.com/montoyo).

### Notes
- I do not have experience with Minecraft modding on both Forge or Fabric, so most of the modifications I've done may be incorrect or unefficient or just theres a better way to do it.
- I have upgraded the Forge toolchain from the deprecated ForgeGradle to the newer one.
- I do not know why, but when using the ``runClient`` provided by ``fg_runs``, mods resources are not included. In order to properly test the mod you have to run ``jar`` from ``build`` and copy ``build/reobfJar/output.jar`` into a ``mods`` folder from a Forge 1.12.2 installation (either via Minecraft Launcher, PolyMC, etc) and run it from there.
- This should be compatible with both [MCEF provided by montoyo](https://montoyo.net/wd3/?modid=mcef) and [MCEF provided by ds58](https://github.com/ds58/mcef/releases). (Assuming nothing in the API changes)
- The ComputerCraft API included is the [ComputerCraft: Tweaked](https://github.com/cc-tweaked/CC-Tweaked) version.

### Wiki
* The Wiki that details all blocks/items can be found on montoyo's website: https://montoyo.net/wdwiki/