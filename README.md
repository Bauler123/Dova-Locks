# Dova // Locks

Shared PIN locks and base protection for ICARUS, by Dova.

Lock a door or container, share a four-digit PIN, and decide what other players can do in your base. Link a lock to the connected building to protect the base together, or keep a storage crate private.

[Download the latest release](https://github.com/VariantCreator/Dova-Locks/releases/latest) · [Report a problem](https://github.com/VariantCreator/Dova-Locks/issues) · [Variant Interactive Map](https://variantinteractivemap.org)

*Your base. Your PIN. Your questionable choice of roommates.*

## Installation

Choose one download:

- [**Dova-Locks-Installer.exe**](https://github.com/VariantCreator/Dova-Locks/releases/download/v1.0.0/Dova-Locks-Installer.exe) finds ICARUS on your PC. Choose your game and click **Install / Update**; it handles the files for you. The PAK is included.
- [**Dova-Locks_P.pak**](https://github.com/VariantCreator/Dova-Locks/releases/download/v1.0.0/Dova-Locks_P.pak) is the mod file for a manual or hosted-server install.

Close the game and stop the server before installing or updating. For a manual install, put **Dova-Locks_P.pak** in `Icarus/Content/Paks/Mods`. Create `Mods` if it does not exist.

The host or dedicated server and **every player** need the same release. Players without the mod, or with an incompatible version, cannot join. Keep only one Dova Locks PAK installed. Replace the old file when updating.

## Using locks

1. Hold **E** on a supported door, window, container or bench to open Lock controls.
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
