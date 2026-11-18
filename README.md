# Grand Tour Racing '98 Plus

A fan-made mod of *Car and Driver Presents: Grand Tour Racing '98* (PlayStation, USA) that adds new levels, AI tuning, weather and surface changes.

This repository contains **only a patch**. You need your own copy of the original game. No game data is distributed here.

## What you need

The original USA disc, data track only (Track 1):

| | |
|---|---|
| File | `Car and Driver Presents - Grand Tour Racing '98 (USA) (Track 1).bin` (your filename may differ) |
| Size | 145,838,112 bytes |
| CRC32 | `786b5cca` |
| MD5 | `10140832732e45b5ff5529823263207c` |
| SHA-1 | `afc574208da8d9207ca0863cc93b8fcbbd1c6093` |

If your hashes don't match, the patch will refuse to apply.

## How to patch

Download `GTR98_Plus_v1.2.xdelta` from the [Releases](../../releases) page. Then use one of these:

- **In a browser:** [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/). Choose your Track 1 BIN as the ROM and the `.xdelta` file as the patch, then apply.
- **Windows:** Delta Patcher. Choose your Track 1 BIN as the original file, the `.xdelta` as the patch, then apply.
- **Command line:** `xdelta3 -d -s "original (Track 1).bin" GTR98_Plus_v1.2.xdelta "Car and Driver Presents - Grand Tour Racing '98 Plus (Track 1).bin"`

The patched file should match:

| | |
|---|---|
| Size | 145,838,112 bytes |
| CRC32 | `93bd8682` |
| MD5 | `a3ca6165168569539507ef0c034f42a0` |
| SHA-1 | `c6fc60258ad3aec0df630abae81a23a8d2f791f8` |

### Music / CUE sheet

The patch only changes Track 1, so the audio tracks stay as they are. Copy your original `.cue`, then change the `FILE` line for Track 1 to the patched BIN's name. Keep the audio track lines unchanged.

Tested in PCSX-R. DuckStation is recommended.

## Changelog

### v1.2

- **Moscow Z:** added half-road barrier inside the first tunnel, similar to Moscow 6.
- **Patched Scotland Z graphics:** additional roadside areas are now covered in snow.
- **Patched Easter Island X graphics:** texturural inconsistencies on the walls inside the tunnel and in the S-turn area are resolved.
- **AI changes:** Minor adjustments to the AI speeds and behaviors in Moscow Y, Easter Island X, Switzerland Z, Scotland Z, Egypt Y, and Egypt 8.


### v1.1

- **Added extra levels.** Each locale now has a secret extra level, reached by finding and driving through a hidden portal somewhere in that locale's levels.
- **Added full standings.** Press L2 + R2 together during a race to switch the HUD between the normal display and a full list of every driver and their gap. Press L2 + R2 again to switch back.
- **Patched manual transmission.**
- **Patched Scotland Z graphics:** the grassy patch at the roadside is now covered with snow.
- **Egypt Z:** adjusted airborne handling so cars clear the ramp.

## Disclaimer

This is an unofficial fan project and is not affiliated with or endorsed by the game's publisher or developer. All rights to the original game belong to their respective owners. Please use a copy of the game you own.
