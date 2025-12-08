---
type: npc
name: Heavy Spearman
location:
tags:
sh1_wounds: None
sh1_stats:
  - "2"
  - "2"
  - "3"
  - "3"
  - "8"
  - "0"
  - "2"
  - "4"
  - "1"
cost: 13
abilities:
---

## Heavy Spearman
| Name       |  INI  | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| ---------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:| ------------------------------------------------------------------------------------------------------------------ |
| H. Spearman 1 |  `VIEW[{sh1_stats[0]}]`   |  `VIEW[{sh1_stats[1]}]`   |  `VIEW[{sh1_stats[2]}]`   |  `VIEW[{sh1_stats[3]}]`   |  `VIEW[{sh1_stats[4]}]`   |  `VIEW[{sh1_stats[5]}]`   |   `VIEW[{sh1_stats[6]}]`  |   `VIEW[{sh1_stats[7]}]`  |  `VIEW[{sh1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):sh1_wounds]` |

Equipment: Spear. Pavis. Dagger. Plate armor.
Special Abilities: `VIEW[{abilities}][link]`


## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:sh1_stats[0]]` |
| ATT  | `INPUT[number:sh1_stats[1]]` |
| STR  | `INPUT[number:sh1_stats[2]]` |
| DEF  | `INPUT[number:sh1_stats[3]]` |
| DR   | `INPUT[number:sh1_stats[4]]` |
| AIM  | `INPUT[number:sh1_stats[5]]` |
| COU  | `INPUT[number:sh1_stats[6]]` |
| DIS  | `INPUT[number:sh1_stats[7]]` |
| A    | `INPUT[number:sh1_stats[8]]` |

