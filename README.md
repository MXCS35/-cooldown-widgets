# Cooldown Widgets

Clickable on-screen cooldown timers for **Guild Wars 2**, made for PvP. Inspired by League of Legends' summoner spell trackers: when you see an enemy use a key skill, click its widget and a countdown starts, so you always know when it's coming back.

A [Nexus](https://raidcore.gg/Nexus) addon.

## Features

- **Skill search** – type a skill name to get its icon and base cooldown from the official GW2 API. Adjust the cooldown for traits or game mode, or use your own images.
- **Easy-to-read timers** – icons grey out while on cooldown with a big, bold countdown: red above 20s, yellow from 20s, green at 8s and below. Under 10s it counts in tenths, just like the game.
- **Click or keybind to toggle** – first press starts the timer, second press puts it back to off cooldown. Keyboard combos and mouse buttons (middle, Mouse 4/5) both work.
- **Profiles** – keep separate widget sets for different opponents, each with its own layout and keybinds.
- **Snap-together layout** – drag widgets around in edit mode; they snap together and move as a group.
- **Click-through** – clicking a widget still reaches the game, so it never gets in your way.
- **Sound feedback** – soft keyboard press/release sounds when toggling, with volume control, or use your own WAV files.
- **Show/hide** – hide single widgets without deleting them, or hide the whole overlay while recording.

## Installation

1. Install [Nexus](https://raidcore.gg/Nexus) if you don't have it yet.
2. Download `CooldownWidgets.dll` from the [latest release](../../releases/latest).
3. Put it in your `Guild Wars 2\addons` folder.
4. Start the game. Nexus will offer future updates automatically.

## Getting started

1. Open Nexus → **Options** → **Cooldown Widgets**.
2. Under **Create a new widget**, press **Download skill list** (one time only), type a skill name and pick it from the results.
3. Check the cooldown, set a size, and press **Create and add to screen**.
4. Turn on **Edit mode** to drag your widgets into place, then turn it off.
5. In a match: click a widget (or press its keybind) when the enemy uses that skill.

## Keybinds

Change these in Nexus → Options → **Keybinds**:

| Action | Default |
|---|---|
| Show / hide overlay | Ctrl+Alt+H |
| Toggle edit mode | Ctrl+Alt+E |
| Reset all timers | Ctrl+Alt+R |
| Switch to next profile | Unbound |

Each widget can also have its own keybind. Set them in the addon's options under **Widget keybinds (by profile)**.

## FAQ

**Does it detect enemy skills automatically?**
No, and it never will. Timers are fully manual: the addon doesn't read game memory or detect enemy actions. It only tracks what you tell it.

**Where are my settings saved?**
In `Guild Wars 2\addons\CooldownWidgets\`. They're kept when you update.

**My icons disappeared after moving my game folder.**
Imported images live in `addons\CooldownWidgets\icons\`. Copy that folder along with your settings.

## Disclaimer

This is a fan-made addon and isn't affiliated with or endorsed by ArenaNet. ArenaNet doesn't officially approve any third-party programs, so use it at your own risk.
