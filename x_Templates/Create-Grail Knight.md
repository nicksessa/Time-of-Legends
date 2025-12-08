---
type: npc
name: Questing Knight
location:
description: Warhammer Grail Knight
tags: 
  - "test"
k1_wounds: None
k1_stats:
  - "4"
  - "6"
  - "7"
  - "4"
  - "10"
  - "0"
  - "7"
  - "6"
  - "2"
abilities:
cost: 14
---

## Knight
| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Knight 1    |  `VIEW[{k1_stats[0]}]`   |  `VIEW[{k1_stats[1]}]`   |  `VIEW[{k1_stats[2]}]`   |  `VIEW[{k1_stats[3]}]`   |  `VIEW[{k1_stats[4]}]`   |  `VIEW[{k1_stats[5]}]`   |   `VIEW[{k1_stats[6]}]`  |   `VIEW[{k1_stats[7]}]`  |  `VIEW[{k1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):k1_wounds]` |

Equipment: Armor. Bastard sword. Shield.
Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:k1_stats[0]]` |
| ATT  | `INPUT[number:k1_stats[1]]` |
| STR  | `INPUT[number:k1_stats[2]]` |
| DEF  | `INPUT[number:k1_stats[3]]` |
| DR   | `INPUT[number:k1_stats[4]]` |
| AIM  | `INPUT[number:k1_stats[5]]` |
| COU  | `INPUT[number:k1_stats[6]]` |
| DIS  | `INPUT[number:k1_stats[7]]` |
| A    | `INPUT[number:k1_stats[8]]` |


