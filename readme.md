# Description
This repository contains Python scripts for Blender that will fix rigs ripped from `Risk of Rain 2`.
The main usage for this is creating skins with custom models for vanilla characters.

For now, there's no script for `Huntress` I have some issues with it.
Also, I will definitely add Engi turrets later.

# What is fixed by script

* Removing excessive bones and meshes

* Reordering bones as they are in a game

* Scaling bones and meshes as they are in a game

* Moving all to (0, 0, 0) position

* Disabling deform for bones that are not used in vertex groups

* Hiding IK bones

# Getting characters to Blender
## Rip assets
For ripping assets use [AssetStudio](https://github.com/Perfare/AssetStudio/releases/tag/v0.14.0).

Once you have launched AssetStudio you should load RoR2 folder in it and you will be present with something like this:

![](/GuideScreenshots/OpenAssetStudio.jpg?raw=true)

Find and select assets of characters that you want:

![](/GuideScreenshots/SelectAssets.jpg?raw=true)

Here's the table of asset names for characters:

| Character name | Asset name   |
|:--------------:|:------------:|
| Acrid          | CrocoBody    |
| Artificer      | MageBody     |
| Commando       | CommandoBody |
| Engineer       | EngiBody     |
| Huntress       | HuntressBody |
| Loader         | LoaderBody   |
| Mercenary      | MercBody     |
| MUL-T          | ToolbotBody  |
| Rex            | TreebotBody  |

Export assets as FBX files:

![](/GuideScreenshots/ExportAssets.jpg?raw=true)

AssetStudio will open folder once it's done exporting:

![](/GuideScreenshots/AssetsFolder.jpg?raw=true)

## Blender
Open blender, create a new file (it's important as a script can corrupt other things it there are any), and clear the scene from default stuff.
Now import FBX file of a character:

![](/GuideScreenshots/ImportFBX.jpg?raw=true)

Then you go to the `Scripting` tab and open `Fix Character.py` file for a character you selected:

![](/GuideScreenshots/ScriptingTab.jpg?raw=true)

Last step you simply press `run script` button:

![](/GuideScreenshots/RunScript.jpg?raw=true)

Now you can switch back to the `Layout` tab, you should see the end result:

![](/GuideScreenshots/EndResult.jpg?raw=true)

# Creation of skin with custom model
## Blender
## Unity
## Visual studio
