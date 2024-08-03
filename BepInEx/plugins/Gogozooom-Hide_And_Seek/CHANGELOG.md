## v1.1.4 Hotfix
- Added v55 enemies
- Added config options to disable all enemies (Usfull for modded entities)
- Updated dependencies

## v1.1.3 Hotfix
- Fixed the bug promised in the last patch (Bruh, why do I always get to exited)

## v1.1.2 Hotfix
- Finally Fixed LevelLoaded being true despite the level being finished loading on the client (Aka inconsistant teleporting)
- Fixed a few other small things

## v1.1.1 Hotfix
- Hopfully fixed inconsistant player teleporting after round one
- Made the seeker only teleport to the entrance if they are holding at least one item (Preventing a empty handed seeker)
- Made the seeker unable to die from gunshots (More relevant for vr players shooting their hands)
- Fixed a few other small things (Like the game breaking when the seeker jumps off the ship early, etc.)

## v1.1.0 Update Patch + More Config
- Fixed death messages and ship leaving early being inconsistent
- Fixed Turrets and Landmine spawn config options
- Fixed item spawning being inconsistent sometimes
- Added seeker randomizer types (CONFIG: None, NoDouble, Turns)
- Added Tulip Snakes, Butlers, Old Birds, and Spike Traps as config spawn options
- Added teleporting seeker to entrance config options
- Made SeekerImmune config option actually do something (Still can die from a few things)

## v1.0.2 Update Patch
- V50 support!
- Now depends on LethalNetworkingApi
- Reworked the plugin to work with the new version and without LC_API (As it is now deprecated for some reason)

## v1.0.1 Hotfix
- Fixed the item list display in README

## v1.0.0 Release
- Release!
- Config allows changing which items are given to the seeker and the hiders
- Also allows disabling individual hotiles (Including turrets and landmines)