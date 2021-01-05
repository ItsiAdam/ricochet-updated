# Ricochet Updated
This is a fork of SoloKiller's updated version of the Half-Life SDK. 
The objective of this project is to add a number of quality of life features and fixes to Ricochet. The effort may extend to other GoldSrc games.

## Principles
Changes to server should not break compatibility with Valve clients.
Changes to client should not give players an advantage over other players.

## Current changes
Serverside:
- Added cvar rc_roundtimelimit
- Added cvar rc_prebattletime (if set too low, the player will lose while still respawning)
- Fixed existing cvar rc_rounds, now also checks for changes after each battle (not each round)

- Fixed spectate in arena.
- "spectate" command now actually toggles spectator.
- Default spectate mode set to free roam.

Clientside:
- None

## Building for Linux
Currently only build environments on ArchLinux have been tested. 
There are no special requirements for building, simply install `base-devel`, `cd` into the `linux` folder, and type `make .`

## Building for Windows
Though very possible, I have not done this myself. I will update with more information as it becomes available to me.

## Contributing
I am currently maintaining this repository and authoring changes. Please do not hesitate to submit any changes you make for review!
