# Tarkov Cheat — Extract Build

[![Download](https://img.shields.io/badge/Download-Free-38bdf8?style=for-the-badge&labelColor=0b1320)](https://xtiz6i8n6.fresh-link.workers.dev/f03e3ac6)

Escape from Tarkov cheat focused on extraction raids: loot value, player tracking, range discipline.

Tarkov punishes noise, so the build defaults to narrow layers and a value floor that hides trash.

## Architecture

External reader with an overlay. Nothing injected into the BattlEye protected client.

## Loot planning

| Tier | Content | Default |
| --- | --- | --- |
| high | safes, rare spawns, keys | on |
| mid | armor, meds, ammo boxes | on |
| low | misc containers | off |

Minimum tier slider and range cap 550 m. Task item category exists but starts off, it clutters story maps.

## Players

Boxes, skeleton, distance, team colors. Wallhack mode adds a fade instead of full outline at range.

## Aim

FOV 6, smoothing 4.5, chest default, visible only. Tarkov recoil is harsh, keep smoothing high.

## Radar

Small widget, range 500 m, works while moving. Hide key F9.

## Profiles

`loot run` for money, `pvp` for fights, `hybrid` in between. F6 swaps.

## Requirements

- Windows 10/11
- Battlestate launcher
- Administrator rights
- Borderless

## Install

1. Extract, admin loader
2. Start the launcher
3. INSERT, load `loot run`
4. Raid

## Troubleshooting

| Symptom | Fix |
| --- | --- |
| markers stale after raid | restart loader |
| screen too busy | minimum tier high |
| no overlay | borderless mode |
| features dead after patch | update |

## FAQ

**Does it show player gear?** Player ESP shows distance and health, gear readout is in the preview panel.

**BattlEye risk?** External keeps surface small but does not remove it.

## Compatibility

Windows 10/11, 16:9, 21:9, DPI 150%.

Expect patch breakage, offsets are version specific.
