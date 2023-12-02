# More Suits v1.3.1
### Adds more suits to choose from, and allows you to customize them!

## Instructions
Place the ```XioTeam Suits``` folder in your ```BepInEx/Plugins``` folder. Make sure the ```moresuits``` folder is in the same folder as ```MoreSuits.dll```.

## Customize
You can add .png files to the ```moresuits``` folder to add new suits as long as both the host and clients have the same files.

## Advanced
You can add a .json file in the ```advanced``` folder with the same name as your .png file in the ```moresuits``` folder to enable additional features like emission. Place additional texture maps in the ```advanced``` folder.

For a list of supported features, see:
https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@14.0/manual/Lit-Shader.html

## Add Suits to Store
Add a "PRICE" key to your advanced .json to put a suit in the store rotation. See ```Glow.json``` for an example of adding a suit with emission that must be purchased from the store.

## Making your own More Suits mod
Upload your own package with a ```moresuits``` folder in it and add ```XioTeam Suits``` as a dependency, and this mod will automatically load your .png files as suits. If you don't want the suits that originally come with my mod, add a file called ```!less-suits.txt``` to your ```moresuits``` folder in your mod.

## Changelog
	- v1.3.0
		- More Suits can now be used as a library for other suit mods
	- v1.2.1
		- Fixed suits being in a different order on the rack for each player
	- v1.2.0
		- Added support for adding suits to the store rotation
	- v1.1.0
		- Added new suits by Graelyth and Curt
		- Added support for advanced features (normal maps, emission, etc)
	- v1.0.0
		- Release