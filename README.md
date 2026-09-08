# Dova // Locks

Shared PIN locks and base protection for ICARUS, by Dova.

Lock a door or container, share a four-digit PIN, and decide what other players can do in your base. Link a lock to the connected building to protect the base together, or keep a storage crate private.

[Download the latest release](https://github.com/VariantCreator/Dova-Locks/releases/latest) · [Report a problem](https://github.com/VariantCreator/Dova-Locks/issues) · [Variant Interactive Map](https://variantinteractivemap.org)

*Your base. Your PIN. Your questionable choice of roommates.*

## What's new in 1.0.5

- The Shift + Hold E shortcut now drives the hold-progress circle in the E button.
- Dova Locks includes import information for Icarus Mod Manager.
- The desktop app is now **Variant Mod Organizer, by Dova**. Import PAKs or ZIPs, scan and remove mods, and launch ICARUS with or without your mods.
- New **Dova Locks save tools** let server owners export readable lock records and apply changes with backups.
- Install / Update checks the current release again before installing and verifies the file in your selected game folder. A failed version check stops the update.

Update your server and players together. Your existing locks and access are kept.

## Installation

Choose one download:

- [**Variant-Mod-Organizer-Installer.exe**](https://github.com/VariantCreator/Dova-Locks/releases/latest/download/Variant-Mod-Organizer-Installer.exe) installs the desktop app. Let it find ICARUS, check the displayed game folder, then click **Install / Update**. It downloads the current Dova Locks release and backs up files it replaces. An internet connection is needed for the version check.
- [**Dova-Locks_P.pak**](https://github.com/VariantCreator/Dova-Locks/releases/latest/download/Dova-Locks_P.pak) is the mod file for a manual or hosted-server install.

Close the game and stop the server before installing or updating. For a manual install, put **Dova-Locks_P.pak** in `Icarus/Content/Paks/mods`. Create `mods` if it does not exist.

The host or dedicated server and **every player** need the same release. Players without the mod, or with an incompatible version, cannot join. Keep only one Dova Locks PAK installed. Replace the old file when updating.

## Variant Mod Organizer

Use **Add / remove mods** to import a PAK or ZIP, scan your mods folder, or remove selected mods. Removed and replaced files are backed up.

**Launch vanilla** keeps your mods outside the game's Paks folder. **Launch modded** restores them and starts the game. Opening Add / remove mods or updating Dova Locks also restores your modded setup. Close ICARUS before switching.

The organizer manages files; it doesn't merge conflicting mods. Use Icarus Mod Manager when your mods need merging. Mods that replace the same menus or interactions may still conflict.

## Editing lock saves

On the host, the usual location is `%LOCALAPPDATA%\Icarus\Saved\SaveGames`. Look for `DovaLocks_<world ID>_A.sav` and `_B.sav`. Server hosts may put the Saved folder elsewhere.

Stop the game or server and keep both files together. In **Dova Locks save tools**, choose either file and export an editable copy. Remove a player entry to block their access, or set `removeLock` to `true` to clear that lock. Apply the edited file to update both saves. The originals are backed up first.

For a remote server, download both saves before editing and upload both replacements afterwards. Steam IDs identify players; changing a displayed name alone doesn't remove access.

## Using locks

1. Look at a supported door, window, container or bench, then hold **Shift + E** to open Lock controls. The hint beside the lock icon shows the shortcut.
2. Enter four digits and choose **Install lock**. You can paste a PIN or use **Show PIN** to check it.
3. Share the PIN with the people you want to invite. Entering it grants **Associate** access by default.
4. The owner can select a player in **Player access** and assign their role.

Use **Link connected base** to protect the connected building and its equipment with one PIN. Newly connected pieces are included automatically, including equipment linked by water pipes or electrical cables.

The owner or a co-owner can put a separate private lock on storage inside the base. That storage uses its own access list. Press **Esc** to close a menu.

## Access levels

| Role | What they can do |
| --- | --- |
| Guest | Enter a PIN to request access. |
| Associate | Use doors, windows and crafting benches. No storage access, building, pickup or dismantling. |
| Member | Use shared storage, build, pick up items and modify the base. |
| Co-owner | Member access, plus managing locks and removing or restoring access for Members and Associates. |
| Owner | Full control, including assigning roles and removing co-owners. |

Access is remembered, so players don't have to enter the PIN every time. Removing someone's access prevents them from using that PIN again until an owner or co-owner restores their access. Private storage has its own permissions.

## Base protection

Players without permission cannot pick up, dismantle or directly damage protected objects. The same restrictions apply to building-hammer actions and removing connected cables or pipes. Weather and wildlife can still damage the base.

Locks and player access are saved between sessions and kept when you update the mod. Removing the mod disables its protection.

## Compatibility

Dova Locks is designed for dedicated servers and player-hosted games. Player-hosted support has had limited testing.

Other mods that change the same game features may conflict. Indirect damage, such as spreading fire, may still damage protected objects.

## Updating after a game patch

Download the latest release and replace the old Dova PAK on the host/server and every player PC. Keep your existing lock saves. A game update may require a new mod release.

## More from Dova

Visit [Variant Interactive Map](https://variantinteractivemap.org) for ICARUS and Valheim map tools.

This is an unofficial community mod. ICARUS belongs to RocketWerkz; Unreal Engine belongs to Epic Games.
