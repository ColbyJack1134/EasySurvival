# EasySurvival

A way to quickly add all of your modded weapons to the survival loot table for Blade and Sorcery: Nomad, can also be used to generate a survival table template for mod authors looking to nativly add their weapons to the survival table.
Survival table format based off of the MMP mod.

# Usage

python3 generateFiles.py [directory] [-tiers]
- Directory is the path to a folder with the mods you want to add to survival, the script will automatically find all of the weapons in each mod. On Windows you can't access the quest directory with Python, so you will have to copy the mods to a folder on your local computer and use that as the directory.
- -tiers is an optional flag to make the suvival tables based off of the tier of each weapon, as you get further in survival higher tiered weapons will spawn more often. By default all weapons have an equal chance of spawning at every wave. 
* Note that with the -tier flag, if any tier does not have at least one weapon it may break survival. 
