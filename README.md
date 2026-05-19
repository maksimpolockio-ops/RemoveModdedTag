# RemoveModdedTag

**Removes the `[Modded]` tag from your lobby.**

When you host a lobby with mods, Lethal Company normally shows a `[Modded]` tag next to your lobby name. This makes many players filter out your lobby.

This mod **removes that tag** — your lobby will appear as a normal vanilla lobby, but all your mods still work!

## How it works

The mod patches the `ModdedCheck.GetModdedState()` method and forces it to return `Vanilla` instead of `Modded`.

## Installation

1. Install **BepInExPack** (if you haven't already)
2. Drop `RemoveModdedTag.dll` into `BepInEx/plugins/`
3. Launch the game

## Usage

- **No configuration needed** — just install and play
- Works automatically when you host a lobby

## Compatible with

- Any client-side mods (graphics, cosmetics, UI, etc.)
- AntiCheat mods
- Gameplay mods (may still work, but other players without those mods might experience issues)

## Technical details

| Item | Value |
|------|-------|
| Target method | `ModdedCheck.GetModdedState()` |
| Patch type | Harmony Prefix |
| Forced return | `ModdedState.Vanilla` |

## Changelog

### v1.0.0
- Initial release
- Removes `[Modded]` tag from all lobbies


## Донат

Поддержать автора мода:
Сбербанк
89994532421

