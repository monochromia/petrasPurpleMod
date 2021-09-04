**IMPORTANT** Installing mods through this method requires Python. Install it for free at python.org

**IMPORTANT**: When the mod is installed, type in one of the following at the character select screen to choose one of four modded heros (backtick [`] opens and closes the dev console):

`selecthero olexa`
`selecthero petrasPurpleHero2` (character name hidden to preserve genuine reactions)
`selecthero reto`
`selecthero petrasPurpleHero4` (character name hidden to preserve genuine reactions)

Installation Guide is copied and pasted from the Mods readme in %APPDATA%/Roaming/Playsaurus/PokerQuest/mods
=====

BASIC INSTALLATION:

1) Place a mod folder in %APPDATA%/Playsaurus/PokerQuest/mods (DO NOT PLACE MOD IN STEAMAPPS MOD FOLDER, ONLY APPDATA -Petra)

	PokerQuest/mods/testMod

2) Add the name of the mod folder to a new line in PokerQuest/mods/mods.txt

	testMod

3) Run modLoader.py from your PokerQuest install directory (where PokerQuest.exe is located) (for me, this is in C:\Program Files (x86)\Steam\steamapps\common\Poker Quest\ -Petra)

4) ... Profit!?

Note: You should start a new run after installing, updating, or unistalling mods, and not resume one that is already in progress.

Note 2: If multiple mods replace the same line or image, the version of the line or image that is in the mod furthest down the list will be the one used by the game.

=====

UPDATING THE GAME:

**IMPORTANT** If you have ever run modLoader.py, you need to run modUnloader.py from your PokerQuest install directory BEFORE updating your game. After updating, run modLoader.py to re-install mods. You need to do this even if you have removed all mods by deleting them from the mods.txt file.

Alternative: 
If you forgot to run modUnloader.py before updating and have NOT run modLoader.py yet, delete the entire backup_csvs folder from the %APPDATA%\Playsaurus\PokerQuest folder and then run modLoader.py

If you forgot to run modUnloader.py before updating and HAVE already run modLoader.py, run modUnloader.py, reinstall the game, and then run modLoader.py again to install your mods.

This process will be made less of a hassle in future updates.


UPDATING MODS:

Put the updated mod folder in the mods directory and edit the mods.txt file if the folder name changed, then re-run modLoader.py.


UNINSTALLING MODS:

To add or remove individual mods, add or delete the names of the mods you want to add or remove from the PokerQuest/mods/mods.txt file and re-run modLoader.py.

To remove all mods, run modUnloader.py. This will restore the game to an unmodded state, but leave your mods.txt file intact.

=====

NOTE: Mod developer commentary can be found in the mod deve commentary folder. This does not affect game function and should not be placed in the mods folder.
Said commentary is included to provide bonus information about the mod behind-the-scenes, and is otherwise entirely ignorable.

Aug 26 21 - Sep 3 21
