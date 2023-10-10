# [DREDGE Mods](https://dredgemods.com)

This organization contains repos for the [Dredge](https://store.steampowered.com/app/1562430/DREDGE/) modding infrastructure. 

## Infrastructure

- The [mod database](https://github.com/DREDGE-Mods/DredgeModDatabase) is where modders can submit new mods to be displayed on the website and made available on the mod manager. 
The database itself is a single file with pertinent mod info which is updated periodically.

- The [mod website](https://github.com/DREDGE-Mods/DredgeModsWebsite) is built based off of the database and contains information on each mod. This information comes from the database and from the README files of each mod.

- The [mod manager](https://github.com/DREDGE-Mods/DredgeModManager) is an application which can install, update, and enable mods from the database.

- The [game libraries](https://github.com/DREDGE-Mods/DredgeGameLibs) publishes stripped and publicized game libraries from DREDGE to a Nuget package. 
Using this, DREDGE mods can take advantage of automatic building in GitHub actions, and modders can access private fields/properties/methods without needing to use reflection.

## Community

- The [branch watcher](https://github.com/DREDGE-Mods/DredgeBranchWatcher) monitors the branches for DREDGE on Steam and reports any updates to the modding community Discord.

## Winch Mod Loader
The infrastructure here all makes use of a modified version of the [Winch](https://github.com/DREDGE-Mods/Winch) mod loader created by [Hacktix](https://github.com/Hacktix)
