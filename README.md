# Advanced-Anticamp
An advanced anti-camp plugin for CS:GO

![Downloads](https://img.shields.io/github/downloads/Sarrus1/advanced-anticamp/total) ![Last commit](https://img.shields.io/github/last-commit/Sarrus1/advanced-anticamp "Last commit") ![Open issues](https://img.shields.io/github/issues/Sarrus1/advanced-anticamp "Open Issues") ![Closed issues](https://img.shields.io/github/issues-closed/Sarrus1/advanced-anticamp "Closed Issues") ![Size](https://img.shields.io/github/repo-size/Sarrus1/advanced-anticamp "Size")

## Description ##
Admins can define areas, where, if a player spends more than x minutes in it, he will get slapped until he leaves the area.
Admins can decide how much slap damage will be inflicted, how long the player can stay in the areas, and more.

## Installation ##
This plugin requires Sourcmod and Metamod.
Grab the latest release from the release page and unzip it in your csgo folder.
Restart the server or type `sm plugins load advancedanticamp` in the console to load the plugin.
The config file will be automatically generated in cfg/sourcemod/

## Configuration ##
- You can modify the phrases in addons/sourcemod/translations/advancedanticamp.phrases.txt.
- Once the plugin has been loaded, you can modify the cvars in cfg/sourcemod/advancedantiamp.cfg.
- To add a sound, put it in the sound/misc/anticamp folder. It has to be in the .mp3 format. Then, configure the appropriate convar in cfg/sourcemod/avanced_anticamp.cfg by pointing to the sound file relative to the sound folder. Remember to add the sound file to your FASTDL directory aswell.

## Usage ##
### Creating zones ###
Once the plugin has been loaded, admins can type !campzones in chat to open the zone menu. From there you can create a zone by pointing your cursor at where you want to create the zone.

**IMPORTANT** Be sure to save zones both in main menu and the newly created zone meny, otherwise the changes won't be saved!

### Editing zones ###
Once a zone has been created, you can modifiy it my typing !campzones in chat and selecting "Edit Zones" in the menu.

### Restrict zones ###
If don't want CT to camp in a zone, inclue "AnticampCT" in the name of the zone.
For T, use "AnticampT".
For Both teams, use "AnticampBoth"

### Troubleshooting ###
For some reasons, the zones won't rename themselves sometimes, so you have to edit the names manually in addons/sourcemod/configs/devzones/mapname.zones.txt

## Contacts ##
If you have questions, you can add me on Discord: Sarrus#9090

## To do ##
- ~~Add a Cvar to set slap frequency~~
- ~~Do a cooldown system~~
- ~~Add sound support~~
- Make zones without having to rename them

## Credits ##
- Franc1sco for his amazing zone plugin, on which this plugin is heavily based.
- The Sourmod Discord for their help.


