# Blockbench Preview Scenes

This repository hosts the assets for Blockbench Preview scenes. Hosting them in a separate place allows the main program to be leaner. It also makes it easier to clarify the license of all of the assets. All assets in the minecraft directory are licensed under the Minecraft End User License Agreement (see [LICENSE.md](./minecraft/LICENSE.md)).

## Creating scenes
1. Launch Minecraft Java Edition with a new profile, with a resolution of 1024x1024
2. Set the FOV to 90
3. Select a spot to capture
4. Important: Place a barrier below you so you don't float while taking screenshots. Floating distorts the FOV.
5. Use the TP command and F2 to take screenshots from all 6 sides, in this order:
	* `-90 0`
	* `90 0`
	* `-180 -90`
	* `-180 90`
	* `-180 0`
	* `0 0`

Old: * `-180 0` * `-90 0` * `0 0` * `90 0` * `-180 -90` * `-180 90`

Seed: `-9162205240910217246`

## Contribution
Preview Scenes are not intended for contributions at this time.
