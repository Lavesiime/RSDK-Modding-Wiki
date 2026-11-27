# Sonic CD Stage IDs

Every stage

## Presentation Stages

This category contains all the menus for the game. Between the 2011 Steam release, the mobile version, and Sonic Origins, the list varies across the different releases of the game.

| List Pos | Stage Path | Stage Name |
| -- | ------------------ | --------------------- |
| 0  | Title/Act1.bin | Title Screen |
| 1  | Title/Act1.bin | Title Screen |
| 2  | Title/Act1.bin | Title Screen |
| 3  | Title/Act1.bin | Title Screen |
| 4  | Title/Act1.bin | Title Screen |
| 5  | Title/Act1.bin | Title Screen |
| 6  | Title/Act1.bin | Title Screen |
| 7  | Title/Act1.bin | Title Screen |
| 8  | Title/Act1.bin | Title Screen |
| 9  | Title/Act1.bin | Title Screen |
| 10 | Title/Act1.bin | Title Screen |
| 11 | Title/Act1.bin | Title Screen |
| 12 | Title/Act1.bin | Title Screen |

Rather than storing or playing audio in the Retro Engine, [Sonic Origins](../README.md) uses [CRIWARE](https://www.criware.com/en/index.html) middleware to play music and sound effects. To achieve this, RSDK communicates with [Hedgehog Engine 2](../HedgehogEngine2.md) by passing the filename of the audio file attempting to be played to the game's Reflections parameters, stored in the `retro_rfl_param.rfl` file in `raw/rfl/rfl_resident.pac`. From there, HE2 plays the audio file associated with the given filename, if one exists.

This page contains tables listing all of the audio files in Sonic Origins' ACB/AWB audio packs, as well as their associated RSDK filenames in the RFL parameters.

!!! note
    Entries with a blank RSDK filename are unused or only used in the Museum.

!!! note
    The file extensions in the RSDK filenames for sound effects are not present in the actual Reflections parameters. They have been added in this page for the sake of clarity.

| List Pos | Stage Path         | Stage Name                     |
| -------- | ------------------ | ------------------------------ |
| 0        | Title/Act1.bin     | TITLE SCREEN                   |
| 1        | Menu/Act1.bin      | MENU                           |
| 2        | TAttack/Act1.bin   | TIME ATTACK                    |
| 3        | Secrets/Act1.bin   | STAGE SELECT                   |
| 4        | Secrets/Act2.bin   | SOUND TEST                     |
| 5        | DAgdn/Act1.bin     | DA GARDEN                      |
| 6        | Help/Act1.bin      | HELP                           |
| 7        | Credits/Act1.bin   | CREDITS                        |
| 8        | Secrets/Act3.bin   | TAILS UNLOCK SCREEN            |
| 9        | Credits/Act1.bin   | TROPHIES                       |
| 10       | Credits/Act1.bin   | LEADERBOARDS                   |
| 11       | Upsell/Act1.bin    | DOWNLOAD SCREEN                |
| 12       | Help/Act2.bin      | HELP APPLE TV                  |

## Regular Stages

This category contains all the stages seen in the main game. Stage folders follow the format of:

```
R{Zone Number}{Act ID}{Time Period}
```

### Zone Numbers

| Number | Zone Name         |
| ------ | ----------------- |
|  1     | Palmtree Panic    |
|  2     | Desert Dazzle     |
|  3     | Collision Chaos   |
|  4     | Tidal Tempest     |
|  5     | Quartz Quadrant   |
|  6     | Wacky Workbench   |
|  7     | Stardust Speedway |
|  8     | Metallic Madness  |

### Time Periods

| Letter | Time Period |
| ------ | ----------- |
| A      | Present     |
| B      | Past        |
| C      | Good Future |
| D      | Bad Future  |

### Original Stage

| List Pos | Stage Path         | Stage Name                     |
| -------- | ------------------ | ------------------------------ |
| 0        | R11A/Act1.bin      | PALMTREE PANIC ZONE 1 A        |
| 1        | R11B/Act1.bin      | B                              |
| 2        | R11C/Act1.bin      | C                              |
| 3        | R11D/Act1.bin      | D                              |
| 4        | R12A/Act2.bin      | PALMTREE PANIC ZONE 2 A        |
| 5        | R12B/Act2.bin      | B                              |
| 6        | R12C/Act2.bin      | C                              |
| 7        | R12D/Act2.bin      | D                              |
| 8        | R13C/Act3.bin      | PALMTREE PANIC ZONE 3 C        |
| 9        | R13D/Act3.bin      | D                              |
| 10       | R31A/Act1.bin      | COLLISION CHAOS ZONE 1 A       |
| 11       | R31B/Act1.bin      | B                              |
| 12       | R31C/Act1.bin      | C                              |
| 13       | R31D/Act1.bin      | D                              |
| 14       | R32A/Act2.bin      | COLLISION CHAOS ZONE 2 A       |
| 15       | R32B/Act2.bin      | B                              |
| 16       | R32C/Act2.bin      | C                              |
| 17       | R32D/Act2.bin      | D                              |
| 18       | R33C/Act3.bin      | COLLISION CHAOS ZONE 3 C       |
| 19       | R33D/Act3.bin      | D                              |
| 20       | R41A/Act1.bin      | TIDAL TEMPEST ZONE 1 A         |
| 21       | R41B/Act1.bin      | B                              |
| 22       | R41C/Act1.bin      | C                              |
| 23       | R41D/Act1.bin      | D                              |
| 24       | R42A/Act2.bin      | TIDAL TEMPEST ZONE 2 A         |
| 25       | R42B/Act2.bin      | B                              |
| 26       | R42C/Act2.bin      | C                              |
| 27       | R42D/Act2.bin      | D                              |
| 28       | R43C/Act3.bin      | TIDAL TEMPEST ZONE 3 C         |
| 29       | R43D/Act3.bin      | D                              |
| 30       | R51A/Act1.bin      | QUARTZ QUADRANT ZONE 1 A       |
| 31       | R51B/Act1.bin      | B                              |
| 32       | R51C/Act1.bin      | C                              |
| 33       | R51D/Act1.bin      | D                              |
| 34       | R52A/Act2.bin      | QUARTZ QUADRANT ZONE 2 A       |
| 35       | R52B/Act2.bin      | B                              |
| 36       | R52C/Act2.bin      | C                              |
| 37       | R52D/Act2.bin      | D                              |
| 38       | R53C/Act3.bin      | QUARTZ QUADRANT ZONE 3 C       |
| 39       | R53D/Act3.bin      | D                              |
| 40       | R61A/Act1.bin      | WACKY WORKBENCH ZONE 1 A       |
| 41       | R61B/Act1.bin      | B                              |
| 42       | R61C/Act1.bin      | C                              |
| 43       | R61D/Act1.bin      | D                              |
| 44       | R62A/Act2.bin      | WACKY WORKBENCH ZONE 2 A       |
| 45       | R62B/Act2.bin      | B                              |
| 46       | R62C/Act2.bin      | C                              |
| 47       | R62D/Act2.bin      | D                              |
| 48       | R63C/Act3.bin      | WACKY WORKBENCH ZONE 3 C       |
| 49       | R63D/Act3.bin      | D                              |
| 50       | R71A/Act1.bin      | STARDUST SPEEDWAY ZONE 1 A     |
| 51       | R71B/Act1.bin      | B                              |
| 52       | R71C/Act1.bin      | C                              |
| 53       | R71D/Act1.bin      | D                              |
| 54       | R72A/Act2.bin      | STARDUST SPEEDWAY ZONE 2 A     |
| 55       | R72B/Act2.bin      | B                              |
| 56       | R72C/Act2.bin      | C                              |
| 57       | R72D/Act2.bin      | D                              |
| 58       | R73C/Act3.bin      | STARDUST SPEEDWAY ZONE 3 C     |
| 59       | R73D/Act3.bin      | D                              |
| 60       | R81A/Act1.bin      | METALLIC MADNESS ZONE 1 A      |
| 61       | R81B/Act1.bin      | B                              |
| 62       | R81C/Act1.bin      | C                              |
| 63       | R81D/Act1.bin      | D                              |
| 64       | R82A/Act2.bin      | METALLIC MADNESS ZONE 2 A      |
| 65       | R82B/Act2.bin      | B                              |
| 66       | R82C/Act2.bin      | C                              |
| 67       | R82D/Act2.bin      | D                              |
| 68       | R83C/Act3.bin      | METALLIC MADNESS ZONE 3 C      |
| 69       | R83D/Act3.bin      | D                              |

### Anniversary Mode Stages

In Sonic Origins Plus, special Anniversary Mode layouts were introduced to several stages in the game.

| List Pos | Stage Path         | Stage Name                     |
| -------- | ------------------ | ------------------------------ |
| 70       | ANR11A/Act1.bin    | PALMTREE PANIC ZONE 1 A        |
| 71       | ANR11B/Act1.bin    | B                              |
| 72       | ANR11C/Act1.bin    | C                              |
| 73       | ANR11D/Act1.bin    | D                              |
| 74       | ANR12A/Act2.bin    | PALMTREE PANIC ZONE 2 A        |
| 75       | ANR12B/Act2.bin    | B                              |
| 76       | ANR12C/Act2.bin    | C                              |
| 77       | ANR12D/Act2.bin    | D                              |
| 78       | ANR31A/Act1.bin    | COLLISION CHAOS ZONE 1 A       |
| 79       | ANR31B/Act1.bin    | B                              |
| 80       | ANR31C/Act1.bin    | C                              |
| 81       | ANR31D/Act1.bin    | D                              |
| 82       | ANR32A/Act2.bin    | COLLISION CHAOS ZONE 2 A       |
| 83       | ANR32B/Act2.bin    | B                              |
| 84       | ANR32C/Act2.bin    | C                              |
| 85       | ANR32D/Act2.bin    | D                              |
| 86       | ANR33C/Act3.bin    | COLLISION CHAOS ZONE 3 C       |
| 87       | ANR33D/Act3.bin    | D                              |
| 88       | ANR41A/Act1.bin    | TIDAL TEMPEST ZONE 1 A         |
| 89       | ANR41B/Act1.bin    | B                              |
| 90       | ANR41C/Act1.bin    | C                              |
| 91       | ANR41D/Act1.bin    | D                              |
| 92       | ANR42A/Act2.bin    | TIDAL TEMPEST ZONE 2 A         |
| 93       | ANR42B/Act2.bin    | B                              |
| 94       | ANR42C/Act2.bin    | C                              |
| 95       | ANR42D/Act2.bin    | D                              |
| 96       | ANR61A/Act1.bin    | WACKY WORKBENCH ZONE 1 A       |
| 97       | ANR61B/Act1.bin    | B                              |
| 98       | ANR61C/Act1.bin    | C                              |
| 99       | ANR61D/Act1.bin    | D                              |
| 100      | ANR62A/Act2.bin    | WACKY WORKBENCH ZONE 2 A       |
| 101      | ANR62B/Act2.bin    | B                              |
| 102      | ANR62C/Act2.bin    | C                              |
| 103      | ANR62D/Act2.bin    | D                              |
| 104      | ANR63C/Act3.bin    | WACKY WORKBENCH ZONE 3 C       |
| 105      | ANR63D/Act3.bin    | D                              |
| 106      | ANR71A/Act1.bin    | STARDUST SPEEDWAY ZONE 1 A     |
| 107      | ANR71B/Act1.bin    | B                              |
| 108      | ANR71C/Act1.bin    | C                              |
| 109      | ANR71D/Act1.bin    | D                              |
| 110      | ANR72A/Act2.bin    | STARDUST SPEEDWAY ZONE 2 A     |
| 111      | ANR72B/Act2.bin    | B                              |
| 112      | ANR72C/Act2.bin    | C                              |
| 113      | ANR72D/Act2.bin    | D                              |
| 114      | ANR73C/Act3.bin    | STARDUST SPEEDWAY ZONE 3 C     |
| 115      | ANR73D/Act3.bin    | D                              |
| 116      | ANR81A/Act1.bin    | METALLIC MADNESS ZONE 1 A      |
| 117      | ANR81B/Act1.bin    | B                              |
| 118      | ANR81C/Act1.bin    | C                              |
| 119      | ANR81D/Act1.bin    | D                              |
| 120      | ANR82A/Act2.bin    | METALLIC MADNESS ZONE 2 A      |
| 121      | ANR82B/Act2.bin    | B                              |
| 122      | ANR82C/Act2.bin    | C                              |
| 123      | ANR82D/Act2.bin    | D                              |

| List Pos | Stage Path         | Stage Name                     |
| -------- | ------------------ | ------------------------------ |
| 0        | SS1/Act1.bin       | SPECIAL STAGE 1                |
| 1        | SS2/Act2.bin       | 2                              |
| 2        | SS3/Act3.bin       | 3                              |
| 3        | SS4/Act4.bin       | 4                              |
| 4        | SS5/Act5.bin       | 5                              |
| 5        | SS6/Act6.bin       | 6                              |
| 6        | SS7/Act7.bin       | 7                              |
| 7        | SS8/Act8.bin       | 8                              |

| List Pos | Stage Path         | Stage Name                     |
| -------- | ------------------ | ------------------------------ |
| 0        | R21A/Act1.bin      | DD                             |
| 1        | MR11A2/Act1.bin    | M097                           |
| 2        | MR12A/Act2.bin     | M077                           |
| 3        | MR13C/Act3.bin     | M099                           |
| 4        | MR32A/Act2.bin     | M081                           |
| 5        | MR41A/Act1.bin     | M080                           |
| 6        | MR51A/Act1.bin     | M093                           |
| 7        | MR52A2/Act2.bin    | M091                           |
| 8        | MR61A/Act1.bin     | M086                           |
| 9        | MR61A2/Act1.bin    | M096                           |
| 10       | MR62A/Act2.bin     | M095                           |
| 11       | MR71A/Act1.bin     | M079                           |
| 12       | MR81A/Act1.bin     | M094                           |
| 13       | MR82A/Act2.bin     | M087                           |
| 14       | MR11A/Act1.bin     | M100                           |
| 15       | MR11B/Act1.bin     | M100                           |
| 16       | MR11D/Act1.bin     | M100                           |
| 17       | MR52A/Act2.bin     | M083                           |
| 18       | MR52B/Act2.bin     | M083                           |
| 19       | MR52C/Act2.bin     | M083                           |
| 20       | BR1R13C/Act3.bin   |                                |
| 21       | BR2R33C/Act3.bin   |                                |
| 22       | BR3R43C/Act3.bin   |                                |
| 23       | BR4R53C/Act3.bin   |                                |
| 24       | BR5R63C/Act3.bin   |                                |
| 25       | BR6R73C/Act3.bin   |                                |
| 26       | BR7R83C/Act3.bin   |                                |
| 27       | DM83D/Act3.bin     | M110                           |
| 28       | DM71A/Act1.bin     | M111                           |
