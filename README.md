
# 📦 General Modding Assets

## Tips & Guides

## Graphical Assets

# 🔨 General Modding Tools
Tools, scripts, addons, and other resources to help you to build your mods and assets for your mods:

## Shader tools
- Shader Compiler

## Bash/command line tools and scripts
- FS Build

## Graphics tools
- TBD

## In-game tools & mods (e.g. PowerTools and EasyDevControls)
- PowerTools: A quick and easy to use tool to assist with development and testing of mods, the main benefit is the easy access to all commands via a single hotkey and no need for mouse navigation 
  - `r` console command performs a soft/quick restart of the current save game
  - `rr` console command performs a hard/full restart of the current save game
  - _Restart Game_ in PowerTools ("F12") menu performs the same command as `r` in the console
  - _Fill vehicle_ fills the current vehicle with any filltype
  - _Spawn pallet/log/bale_ spawns pallets for all filltypes, all bales and the most common logs
- PowerTools Developer: Adds console commands to print table contents to log file or save a Lua table to file
  - `dtSaveTable` saves a table to a file in a well formed Lua file, which means you can actually load it in the Lua interpreter and use it as any regular table, perfect for creating dummies/mockups using existing content
  - `dtTable` prints the table contents to the log file, uses a different algorithm than _DebugUtil.printTableRecursively_ which performs better and supports larger tables
- GlobalExplorer: Allows you to browse in-game tables to inspect the FS object model
  - Works best with for quick lookup, smaller tables and/or when you don't really know exactly what you are looking for (exploring the structure)
  - PowerTools Developer is a good complement to save a table to file or print it to the log once found with GlobalExplorer
- EasyDevControls: The classic EDC with tons of useful features for modders
  - A lot more extensive than PowerTools

## Misc. tools and resources
- [Color converter](https://docs.google.com/spreadsheets/d/1E2odstb7WOZlWozdA1wPSVGls0srfNZDrYDQ5TUkfeo/edit?gid=0#gid=0) - Convert between Giants (sRGB), HEX and RGB color codes
- [FS22 Asset browser](https://assets.mantrid.net/?) - Browse base game assets like wheels, tires, lights and much more


