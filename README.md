# SOAP DM MEDIC

> Fork of the standard SOAP DM Plugin but for Medic Crossbow training only.

All changes are in the "soap_dm_medic.sp" file in `addons/sourcemod/scripting`. New additions are placed at the bottom, other additions which had to be integrated into the original code are commented as such.


# SOAP DM 

> Team DeathMatch gameplay plugins for Team Fortress 2

For more info on SOAP DM, see [here](http://comp.tf/wiki/DM).

## Downloading

- Get the latest version [here](https://github.com/sapphonie/SOAP-TF2DM/releases/latest). Extract the `cfg/` and `addons/` folders from the zip to your root `/tf/` folder.

## Spawn points/deathmatch not starting

If a specific version of a map does not have spawn points, deathmatch mode does not start.

### Creating spawn points

- Check [addons/sourcemod/configs/soap](https://github.com/sapphonie/SOAP-TF2DM/tree/master/addons/sourcemod/configs/soap) for an existing older/newer version of the map.
- Create a copy of the closest version of the map you need or create a new cfg file.
- Test the spawn points in-game. Use `setpos <x> <y> <z>; setang <pitch> <yaw> <roll>;` to teleport to each spawn point.
- To add new spawn points, move to the desired spawn point and use `getpos` to get your current position and angle.
- Finally, test on a server with SOAP-TF2DM to make sure SOAP-TF2DM can parse the file.
- Submit a pull request 🙂

## Known issues

- Not an issue, but, this plugin requires [SourceMod 1.10](https://www.sourcemod.net/downloads.php) or newer to function. If you are using an older version, __it will not load__.

Report other issues [here](https://github.com/sapphonie/SOAP-TF2DM/issues/new).

## What happened to the old repo?
- The developer, [Alex](https://github.com/alvancamp), privated all of their GitHub repositories a while ago, including MGE and SOAP-DM. This necessitated a new repository, aka this one.

They have unprivated them, and you can find the original unmaintained version of SOAP-DM [here](https://github.com/alvancamp/SOAP-TF2DM).

