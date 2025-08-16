# DivergensCiv
A mod based on autociv that presents a few changes in both customization and functionality. On the following versions I plan to fix some known problems in autociv and implement new things that I find useful for the game.

## Current Feature list (same as autociv)
- General
	- Readme: press Shift + F4 to open
	- Player mute
	- Player reminder (show a written note when a certain player joins) ***
	- Link opener (opens URL links from the chat)
	- Help command: type /help to see all available commands
	- Console with autocomplete (Ctrl + C + L)
- Lobby
	- Resize bars
	- Host name mark
	- Remember playerlist state
	- Better performance when reloading lobby
	- Shortcuts to create host, navigate gamelist
	- Write s?search_text_here at the chat input to search lobby chat
- Game setup
	- Auto-assign civilization with chat (only works if host has the mod)
	- Custom population limit
	- Custom starting resources
	- Custom map size
	- Countdown to start the game
- Maps
	- Skirmish:
		- Volcano island (8)
- In Game
	- Hotkeys for (see hotkeys with hotkey viewer)
		- Buildings placement
			- Multiple buildings per hotkey (optional, user.cfg)
				- How to use: Copy the hotkey you want and remove the "hotkey." prefix, next replace the hotkey key for the buildings you want to cycle and separate them by a space.
		- Buildings selection
		- Units selection
		- Formations (selected units)
		- Stances (selected units)
		- Auto-train (selected buildings)
		- Minimap expand
		- Custom selection filters by:
			- health
			- rank
			- class
			- group
			- screen
	- Stats overlay
	- Pause game overlay now shows only in the top area
- Settings
	- Max corpses visible

## Known autociv issues that I plan to fix
- 'autociv' function works also for non-host users, which means a player can visually change their civ by typing it on the chat without actually changing it if the host doesn't have autociv. This problem causes a lot of confusion, as players might not notice this and start the game with the wrong civ.


## Download
There are three ways:
- Download and install from the wildfiregames forum autociv page topic (files on first page)
	- https://wildfiregames.com/forum/topic/28753-autociv-mod-0ad-enhancer/
- Download and install manually the github repository (installation file on the releases section)
	- https://github.com/nanihadesuka/autociv
- Use 0 A.D. mod downloader (not always newest version)
	- https://0ad.mod.io/autociv


## Instructions to install manually
	#### MacOS (thanks @HMS-Surprise):
		https://wildfiregames.com/forum/index.php?/topic/25444-how-to-install-autociv-mod-on-mac/

	#### Linux/Windows:
		Open the downloaded file with (both ways should work):
		- pyromod file (two ways)
			- Double click the file (should autoinstall the mod for you and send  you to the mods page inside 0ad)
			- Right click → Open with → 0 A.D  (or pyrogenesis.exe)
		- zip file: Copy folder inside the zip file into your mods folder
			- https://trac.wildfiregames.com/wiki/GameDataPaths


## Mod compatibility(s)
The mod is compatible with:
- 0 A.D 0.0.27
- Probable to work with the following mods
	- boonGUI mod
	- star mod
	- ffm_visibility mod
	- balanced maps mod
	- spec mod (monitor) mod
	- custom_rating mod
- Should work with all mods that don't have extensive code changes
