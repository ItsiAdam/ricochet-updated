# Ricochet Updated
This is a fork of SoloKiller's updated version of the Half-Life SDK. The objective of this project is to add a number of quality of life features to the Ricochet server, perhaps expanding the effort to the client in the future.

## Principles
Changes to the server should not break compatibility with the original client.
Changes to the client should only be visual improvements, for example, hud elements relating to tournaments, improved ammo indicators, redesigned scoreboard, etc.

## Current changes
- Fixed spectate in arena.
- "spectate" command now actually toggles spectator.
- Default spectate mode set to free roam.
- Respects rc_rounds, also checks for changes after each battle (not each round)
- Added cvar rc_roundtimelimit
- Added cvar rc_prebattletime (if set too low, the player will lose while still respawning)

## Building for Linux
Currently only build environments on ArchLinux have been tested. 
There are no special requirements for building, simply install `base-devel`, `cd` into the `linux` folder, and type `make .`

## Building for Windows
Though very possible, I have not done this myself. I will update with more information as it becomes available to me.

## Contributing
I am currently maintaining this repository and authoring changes. Please do not hesitate to submit any changes you make for review!
