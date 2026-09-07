# Dova // Locks

Shared PIN locks and base protection for ICARUS, by Dova.

Lock a door or container, share a four-digit PIN, and decide what other players can do in your base. Link a lock to the connected building to protect the base together, or keep a storage crate private.

[Download the latest release](https://github.com/Bauler123/Dova-Locks/releases/latest) · [Report a problem](https://github.com/Bauler123/Dova-Locks/issues) · [Variant Interactive Map](https://variantinteractivemap.org)

*Your base. Your PIN. Your questionable choice of roommates.*

## Installation

Choose one download:

- [**Dova-Locks-Installer.exe**](https://github.com/Bauler123/Dova-Locks/releases/download/v1.0.0/Dova-Locks-Installer.exe) finds local ICARUS installations and installs the mod after you choose the destination. It creates the Mods folder if needed. You don't need to download the PAK separately.
- [**Dova-Locks_P.pak**](https://github.com/Bauler123/Dova-Locks/releases/download/v1.0.0/Dova-Locks_P.pak) is the mod file for a manual or hosted-server install.

Close the game and stop the server before installing or updating. For a manual install, put **Dova-Locks_P.pak** in `Icarus/Content/Paks/Mods`. Create `Mods` if it does not exist.

The host or dedicated server and **every player** need the same release. A server running Dova Locks disconnects clients that are missing it or running an incompatible version. Keep only one Dova Locks PAK installed. Replace the old file when updating.

## Using locks

1. Hold **E** on a supported door, window, container or bench to open Lock controls.
2. Enter four digits and choose **Install lock**. You can paste a PIN or use **Show PIN** to check it.
3. Share the PIN with the people you want to invite. Entering it grants **Associate** access by default.
4. The owner can select a player in **Player access** and assign their role.

Use **Link connected base** to share the lock across the connected structure. Membership refreshes automatically as the base changes, including supported stacked deployables and connected water/electric networks.

The owner or a co-owner can put a separate private lock on storage inside the base. That storage uses its own access list. Press **Esc** to close a menu.

## Access levels

| Role | What they can do |
| --- | --- |
| Guest | Enter a PIN to request access. |
| Associate | Use doors, windows and crafting benches. No storage access, building, pickup or dismantling. |
| Member | Use shared storage and carry out building, pickup and modification within the base. |
| Co-owner | Member access plus lock management and access removal/restoration for lower roles. |
| Owner | Full control, including assigning roles and removing co-owners. |

Private storage keeps its own permissions. Removing someone's access blocks their known PIN until an owner or permitted co-owner restores them. Access is remembered using their Steam ID; character and Steam names are shown when available.

## Protection and saved data

Protected objects reject unauthorized pickup, dismantling, building-hammer actions and direct player damage, including fists and weapons. Connected cables and pipes are guarded against unauthorized tool removal. Weather and wildlife can still damage the base.

Lock data is stored separately on the host. Replacing the PAK does not erase it. Keep backups of the prospect and the host's DovaLocks saves, especially before moving a world between hosts. Removing the mod disables its protection; retaining those saves lets a later install find the lock data again.

## Compatibility

Release **1.0.0** was built against Steam build **25030066**. Dedicated-server testing has been carried out during development. Player-hosted sessions are supported by the design, but have had less live testing.

Other mods that replace the same game assets or data tables can conflict. The checked Rada Cheat Menu package has no overlapping PAK paths. Player attribution can be lost for indirect damage such as spreading fire, so this is not a guarantee against every possible griefing method.

## Updating after a game patch

Download the latest release and replace the old Dova PAK on the host/server and every player PC. Keep your existing lock saves. A game update may require a new mod release.

## More from Dova

Visit [Variant Interactive Map](https://variantinteractivemap.org) for ICARUS and Valheim map tools.

This is an unofficial community mod. ICARUS belongs to RocketWerkz; Unreal Engine belongs to Epic Games.
