# Local Map Overhaul
<p align="center">
    <img height="500px" src="https://i.imgur.com/8kmb3nA.png">
</p>

## Overview
- Overhauls the information shown on the Fallout New Vegas local map.
- Adds dynamic icons indicating the position/status of NPCs, Items, and interactables.
- Adds high resolution texture support to the local/world map player cursor.

### Lite Version
- Slim & Efficient
- Actor Icons (NPC/Creatures)
- Limited Configuration

### Full Version
- Full Icon Suite
- ySI - Sorting Icon Integration
- KEYWORDs Support
- Fully Configurable
- Includes all of the features described below

## Configuration
- Configurable via the included LocalMapOverhaul.ini

### General
- Set icon visibility distance
- Toggle perception based visibility distance
- Toggle icon distance fade
- Toggle icon height indicator
- Toggle which icons to display

### Actor Icons
- Show NPCs, creatures or both
- Hide empty corpses
- Shade icon color based on actor hostility
- Add dynamic icons to vendors
- Set NPC name visibility mode

### Object Icons
- Crafting Stations - Workbenches, Reloading Benches, and Cooking Stations
- Locked Containers - Shows lock level and if you have the appropriate key
- Terminals - Shows lock level and if you have the appropriate key
- Mines - Shows NPC placed armed mines

### Click Actions
- Terminals - Remotely access

### Item Icons
- Skill Books
- Skill Magazines
- Notes
- Keys
- Unique Items
- Quest Items

### Collectables
- Snow Globes - Fallout NV
- Caravan Cards - Fallout NV
- Sunset Sarsaparilla Star Bottle Caps - Fallout NV
- Dean's Stashes - Dead Money
- Survivalist Caches - Honest Hearts
- Warheads - Lonesome Road
- Ralphie Posters - Lonesome Road
- Bobbleheads - Fallout 3
- Steel Ingots - The Pitt
- Intel Briefcases - Anchorage

## Adding Map Icons

Requires the *Full* version of Local Map Overhaul.

Adding Local Map icons to any Item, Activator, Container, or Projectile is as simple as adding the ***LocalMapIcon*** Keyword to the appropriate form. See the [KEYWORDs](https://www.nexusmods.com/newvegas/mods/83088) mod page for detailed instructions on the different ways you can manage Keywords.

Icons will be automatically assigned based on the ySI - Sorting Icons framework.
Every inventory item will already have assigned ySI - Sorting Icons textures, but Activators, Containers, and Projectiles will not.

You can assign icons to any game form using the same .JSON framework that ySI - Sorting Icons uses for items. Check the Local Map Overhaul installation directory for an example Activator.json, where I have assigned icons to the forms supported by default.

Here is an [in depth guide](https://www.nexusmods.com/newvegas/mods/76521) on the ySI .JSON framework, the information provided can be applied to any form type, not just items.

## Recommended
- [High Res Local Maps](https://www.nexusmods.com/newvegas/mods/77963)
- [Colorful Inventory Ycons](https://www.nexusmods.com/newvegas/mods/78674)
- [ySI - Colorful Icons Support](https://www.nexusmods.com/newvegas/mods/85075)

## Requirements
- [xNVSE](https://www.nexusmods.com/newvegas/mods/67883) (6.3.3+)
- [JIP LN NVSE](https://www.nexusmods.com/newvegas/mods/58277)
- [JohnnyGuitar NVSE](https://www.nexusmods.com/newvegas/mods/66927)
- [ShowOff xNVSE](https://www.nexusmods.com/newvegas/mods/72541)
- [User Interface Organizer](https://www.nexusmods.com/newvegas/mods/57174)
- [yUI - User Ynterface](https://www.nexusmods.com/newvegas/mods/74357) (Full Version Only)
- [ySI - Sorting Ycons](https://www.nexusmods.com/newvegas/mods/74358) (Full Version Only)

## Installation
Installs with a mod manager via the FOMOD installer.