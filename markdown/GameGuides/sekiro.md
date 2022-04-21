![Sekiro](\Images\sekiro_header.png "Shot by jim2point0"){.shadowed .autosize}
##Summary

Feature | Supported
--|--
Vanilla Photo Mode | No
Ansel | No
Hotsampling | No
DSR | Yes
Custom Aspect Ratios | Yes*
Reshade | Yes
Graphics API | DirectX 11

\* Requires an altered EXE or a CE script. [Use DSR](https://framedsc.github.io/GeneralGuides/custom_dsr_resolutions.htm) for different resoluitions and aspect ratios.
 
## Tools

* [CE Table by Jim2point0](..\CheatTables\sekiro_photoModeUpdated.CT)  
**Features**: Camera Coordinates, FOV, Timestop, PlayersOnly, Hud Toggle. Aspect Ratio Unlocker
* [Unlocked Aspect Ratio, remove stretching of HUD textures (by Jackfuste)](https://www.wsgf.org/phpBB3/viewtopic.php?p=176159#p176159)  
**Features**: Removed the 16:9 aspect ratio restriction. Any and all aspect ratios will work. Fixes overlay stretching. Extremely useful for screenshots as these overlays 
can get in the way of screenshots even if you're in 16:9.

## Using The CE Table

Start out by clicking the box next to "Enable Screenshotting." This fetches AOBS and pointers required for the table features. 

* **F1** will enable the "free camera." This gives you control over the coordinates, though it will not be normal WASD camera movement. The hotkeys display when you enable the script. 
* **F2** will hide the HUD and F3 will show it. Though bear in mind that once you timestop the game, the hud toggle doesn't function quite right. So turn it off before freezing the game for best results.
* **F4** will toggle the "PlayersOnly" script. This is similar to the Unreal Engine 3 cheat which freezes all non-player characters. You can toggle this to try and freeze an enemy in the middle of an animation in order to try and set up an action shot. You can try and position yourself while your enemies are frozen, then use the proper timestop to freeze your character and effects.
* **Numpad 0** will freeze the game. **Numpad .** (period) will resume. Numpad 5 is super slow motion.

## Fix the ReShade depth buffer

Reshade has problems to get the right depth buffer, so make sure to select the right one in the DX11 tab.

![screenshot](https://i.imgur.com/uuX20Vp.png)
