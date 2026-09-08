# Dova Locks

A little privacy for your ICARUS base, by Dova.

Add a PIN, let your friends in, and decide who can use what. You can protect a connected base with one lock or keep a chest private. Someone has to look after the snacks.

[Get the latest version](https://github.com/VariantCreator/Dova-Locks/releases/latest) · [Report a problem](https://github.com/VariantCreator/Dova-Locks/issues) · [Variant Interactive Map](https://variantinteractivemap.org)

## What's new in 1.0.5

- The little circle in the E button now fills while you hold Shift + E for Lock controls.
- The download includes import info for Icarus Mod Manager.
- The app is now **Variant Mod Organizer, by Dova**. Add or remove mods and launch ICARUS with or without them.
- Server owners can edit lock saves through the app, with backups before anything changes.
- Updating checks the latest release and the installed file. If the check fails, the app stops instead of falling back to an older download.

Your locks and player access stay in place when you update. Update the server and everyone playing on it together.

## Getting started

Close ICARUS first, then pick whichever works for you.

**Let the app handle it:** Download [Variant-Mod-Organizer-Installer.exe](https://github.com/VariantCreator/Dova-Locks/releases/latest/download/Variant-Mod-Organizer-Installer.exe), install it, and open Variant Mod Organizer. Check the ICARUS folder it found and click **Install / Update**. It downloads Dova Locks and backs up any files it replaces. You'll need an internet connection.

**Install it yourself:** Download [Dova-Locks_P.pak](https://github.com/VariantCreator/Dova-Locks/releases/latest/download/Dova-Locks_P.pak) and put it in:

`Icarus/Content/Paks/mods`

Create the `mods` folder if it's missing. When updating, replace the old PAK and keep just one copy.

For a hosted server, stop it first and upload the PAK through your host's file manager. The full path usually looks like:

`Server folder/Icarus/Content/Paks/mods/Dova-Locks_P.pak`

**The server and every player need the same release.** The app gets the latest published version, so check that your server has updated too.

## Using your locks

1. Look at a supported door, window, container or bench. Hold **Shift**, then hold **E** to open Lock controls.
2. Enter a four-digit PIN and choose **Install lock**.
3. Use **Link connected base** if you want that lock to cover the connected building and its equipment.
4. Share the PIN with friends. Use **Player access** to choose what each person can do.

The usual E controls still work when you're not holding Shift, including turning equipment on and off. You can paste a PIN, use **Show PIN** to check it, and press **Esc** to close the menu.

Connected pieces join the base lock automatically, including supported stacked items and equipment linked by pipes or cables. Owners and co-owners can also give a chest its own private lock.

## Who can do what?

- **Associate:** Use doors, windows and benches. This is what someone gets when they first enter your PIN.
- **Member:** Use shared storage, build, pick up items and make changes to the base too.
- **Co-owner:** Do everything a Member can, plus manage locks and remove or restore access for Members and Associates.
- **Owner:** Full control, including choosing roles and removing co-owners.

Access is remembered, so your friends don't have to keep typing the PIN. Remove someone's access and that PIN won't let them back in until you restore it. Private chests have their own access lists.

Players without permission can't pick up, dismantle or directly damage protected objects. Building-hammer actions and removing connected pipes or cables are covered too. Weather, wildlife and spreading fire can still cause trouble.

## Variant Mod Organizer

**Add / remove mods** lets you import PAKs or ZIPs, scan the mods folder, and remove selected mods. Removed and replaced files are backed up.

**Launch vanilla** puts your mods aside and starts ICARUS without them. **Launch modded** brings them back. Opening Add / remove mods or updating Dova Locks also brings your mods back, so close the game before switching.

The organizer doesn't merge mods. Use Icarus Mod Manager if your mods need merging. Mods that change the same menus or interactions can still clash.

Install the new organizer setup to get these app features. If you already have the older Dova Locks app, it can still download mod updates.

## For server owners

Lock saves are usually here on the host:

`%LOCALAPPDATA%\Icarus\Saved\SaveGames`

Look for `DovaLocks_<world ID>_A.sav` and `_B.sav`. Some server hosts use a different Saved folder.

Stop the game or server and keep both files together. Open **Dova Locks save tools** in the organizer, choose either save, and export an editable copy. Remove a player entry to block their access. To clear a whole lock, set `removeLock` to `true`.

Apply the edited copy to update both saves. The app backs up the originals first. For a remote server, download both saves before editing and upload both replacements afterwards. Steam IDs identify players, so changing a name alone won't remove access.

## Good to know

Dova Locks is made for dedicated servers and player-hosted games. Player-hosted games have had less testing. Other mods can conflict, and game updates may need a new Dova Locks release.

Updating keeps your locks and access. Removing the mod turns off its protection, so keep your lock saves if you might reinstall it.

Found a problem? Tell me what happened, which versions you're using and what other mods you have. A screenshot helps. Just keep PINs and private server details out of it.

You can also check out my [Variant Interactive Map](https://variantinteractivemap.org) for ICARUS and Valheim.

Dova Locks is an unofficial community mod. ICARUS belongs to RocketWerkz and Unreal Engine belongs to Epic Games.
