---
type: npc
name: Spearman
location: 
tags: 
s1_wounds: None
s1_stats:
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
abilities: 
---

## Spearman
| Name       |  INI  | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| ---------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:| ------------------------------------------------------------------------------------------------------------------ |
| Spearman 1 |  `VIEW[{s1_stats[0]}]`   |  `VIEW[{s1_stats[1]}]`   |  `VIEW[{s1_stats[2]}]`   |  `VIEW[{s1_stats[3]}]`   |  `VIEW[{s1_stats[4]}]`   |  `VIEW[{s1_stats[5]}]`   |   `VIEW[{s1_stats[6]}]`  |   `VIEW[{s1_stats[7]}]`  |  `VIEW[{s1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):s1_wounds]` |

Equipment: Light armor. Shield. Short sword. Spear.
Special Abilities: `VIEW[{abilities}][link]`


## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:s1_stats[0]]` |
| ATT  | `INPUT[number:s1_stats[1]]` |
| STR  | `INPUT[number:s1_stats[2]]` |
| DEF  | `INPUT[number:s1_stats[3]]` |
| DR   | `INPUT[number:s1_stats[4]]` |
| AIM  | `INPUT[number:s1_stats[5]]` |
| COU  | `INPUT[number:s1_stats[6]]` |
| DIS  | `INPUT[number:s1_stats[7]]` |
| A    | `INPUT[number:s1_stats[8]]` |

