# Class Icons

Class icons in the party and group windows.

Class icons next to party and group members. Classes are picked up from the Game Arena, clan and friend lists and remembered, so icons fill in over time. Makes both windows wide enough for a full row of buffs. Switch: Options > UI > Add-ons.

An add-on for [ROSE Mod Launcher](https://github.com/Zurnny/Rose_Mod_Launcher), for the game's **default** UI.

## Install
1. Download this repo (Code > Download ZIP) and open it.
2. Copy the **Class Icons** folder into `Launcher Mods` in your ROSE Online folder.
3. Open the launcher, press **Mods**, tick **Class Icons**, and restart the game.

It updates itself from this repo whenever the launcher opens.

## Works with the other add-ons
Every add-on works on its own, and any mix of them works together. Add-ons
that change the same window (Options, the HUD, the party and group windows)
carry the very same copy of that file, and each part only runs while its own
add-on is installed: each add-on puts a small marker file in
`Data/ui/sp_addons/`, which the launcher removes again with the add-on.
In **Options > UI > Add-ons** each installed add-on adds its own line, one
under the other, in the order they are listed there.

The [Steampunk UI](https://github.com/Zurnny/SteamPunk) theme already has this built in, so it isn't needed with Steampunk (if both are on, Steampunk's files win).

The switches are saved in `sp_addons.txt` in the ROSE Online folder. The Ice UI
theme uses the same file; both keep each other's settings.

## Files it changes
- `Data/ui/themes/rose/game/arena_group.html`
- `Data/ui/themes/rose/game/options_bgfx.html`
- `Data/ui/themes/rose/game/party.html`
- `Data/ui/sp_addons/class_icons.txt` (marker)

Turning it off in the launcher puts the game's own files back.
