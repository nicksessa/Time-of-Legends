---
type: NPC
name: Men-at-Arms
level: 1
virtueLevel: 2
location: 
tags: 
  - soldier
m1_wounds: None
m1_stats:
  - "2"
  - "3"
  - "3"
  - "2"
  - "6"
  - "0"
  - "4"
  - "2"
  - "1"
cost: 10
specialAbilities: 
skills:
---

## Men-at-Arms
| Name       |  INI  | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| ---------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:| ------------------------------------------------------------------------------------------------------------------ |
| Men-at-Arms 1 |  `VIEW[{m1_stats[0]}]`   |  `VIEW[{m1_stats[1]}]`   |  `VIEW[{m1_stats[2]}]`   |  `VIEW[{m1_stats[3]}]`   |  `VIEW[{m1_stats[4]}]`   |  `VIEW[{m1_stats[5]}]`   |   `VIEW[{m1_stats[6]}]`  |   `VIEW[{m1_stats[7]}]`  |  `VIEW[{m1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):m1_wounds]` |

Equipment: Light armor. Shield. Short sword. Spear.
Special Abilities: `VIEW[{abilities}][link]`


| Name       |  INI  | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| ---------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:| ------------------------------------------------------------------------------------------------------------------ |
| Men-at-Arms 1 | 2 | 3 | 3 | 2 | 6 | 0 | 4 | 2 | 1 | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):m1_wounds]` |


## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:m1_stats[0]]` |
| ATT  | `INPUT[number:m1_stats[1]]` |
| STR  | `INPUT[number:m1_stats[2]]` |
| DEF  | `INPUT[number:m1_stats[3]]` |
| DR   | `INPUT[number:m1_stats[4]]` |
| AIM  | `INPUT[number:m1_stats[5]]` |
| COU  | `INPUT[number:m1_stats[6]]` |
| DIS  | `INPUT[number:m1_stats[7]]` |
| A    | `INPUT[number:m1_stats[8]]` |

