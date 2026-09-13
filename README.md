# Dova Locks

Your base. Your PIN. Your questionable choice of roommates.

**Version 1.1.1** adds shared PIN locks and Ward protection to ICARUS. Give friends access, keep a chest private, and stop the neighbors helping themselves to everything that isn't nailed down.

[Download 1.1.1](https://github.com/VariantCreator/Dova-Locks/releases/latest) · [Nexus](https://www.nexusmods.com/icarus/mods/325) · [Variant Mod Organizer](https://github.com/VariantCreator/Variant-Mod-Organizer/releases/latest) · [Variant Interactive Map](https://variantinteractivemap.org)

## What's new

- Name your Ward and find it on the map. Show nearby Wards within 150 m.
- Ward and linked-base access now stay in sync. Private storage still gets its own rules.
- Anyone can repair. Upgrades and removing crops need the right access. Helping out is fine; redecorating is not.
- Check nearby protection with see-through green and red highlights that follow the build pieces.
- Clearer Ward controls, boundary colors and access details.
- Fixed dropped Ward pickup and added loot bag protection inside active Wards.
- The Ward now explains when a separate linked base lock is still active after removing its lock.

Update the server and every player with this same PAK. Keep your existing lock saves.

## Get started

Close ICARUS and stop the server. Put `Dova-Locks_P.pak` in `Icarus/Content/Paks/mods`, creating the mods folder if needed. Replace the old PAK and keep one copy. **The server and every player need the same file.** Back up your prospect and both A/B lock saves before updating.

For a regular lock, look at a supported door, window, container or bench. Hold **Shift**, then hold your **Interact key**. That's F by default, or your custom key. Set four digits and use **Link connected base** to protect the connected structure.

## Dova's Ward

Craft it where you craft the Flow Meter, using the same materials. Place it and **tap Interact** to use its screen. A new PIN turns protection on. Owners and co-owners can set its radius from **1 to 60 m**, name it, and show or hide the boundary.

A new Ward on your own linked base reuses its PIN and access. Changes to shared access carry across both. An existing linked base remains protected beyond the Ward radius, and removing the Ward lock does not remove that separate base lock. The menu tells you when it is still active.

Check nearby protection for a 12-second view: **green has an active lock; red has none**. It covers loaded build pieces within 70 m, up to 128 objects. Show nearby Wards displays boundaries within 150 m. Hiding a boundary does not turn protection off.

The Ward covers your base, placed equipment and loot bags. Mining, chopping trees and dealing with wildlife work normally. Storms still get a vote. Players with the right access can damage their own protected stuff.

## Who can do what?

- **Guest:** Repair, but no protected access or building changes.
- **Associate:** Repair and use doors, windows and benches. This is the starting role after entering a PIN.
- **Member:** Shared storage, building, upgrades, pickup and crop removal.
- **Co-owner:** Member access, plus managing locks, Ward settings and access.
- **Owner:** Full control, including assigning roles.

Access is remembered. Owners and co-owners can give storage a private lock inside a shared base or Ward. The snacks are safe. Probably.

## Saves and support

The host holds the world's lock saves, usually under `%LOCALAPPDATA%/Icarus/Saved/SaveGames`. Look for `DovaLocks_..._A.sav` and `_B.sav`. Some server hosts use a different Saved folder.

Stop the server before editing. For a remote server, download both saves, edit them with the Organizer, then upload both replacements. Editing a client's local files does not edit a remote server.

Other mods can conflict if they change the same assets. The Organizer handles PAKs; it does not merge them. Game updates may need a mod update.

[Report a problem](https://github.com/VariantCreator/Dova-Locks/issues) with your version, what happened and any other mods involved. Logs and screenshots help. A screenshot of your PIN helps the wrong people, so leave that out.

Unofficial community mod. ICARUS belongs to RocketWerkz.
