---
type: npc
name: Knight - Questing
location:
tags:
kq1_wounds: None
kq1_stats:
  - 4
  - 6
  - 7
  - 4
  - 10
  - "0"
  - 6
  - 5
  - "1"
abilities:
  - "[[Furious Charge]]"
  - "[[Charging Strength (10)]]"
  - "[[Desperate]]"
cost: 50
---

## Knight - Questing
| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Knight Quest 1    |  `VIEW[{kq1_stats[0]}]`   |  `VIEW[{kq1_stats[1]}]`   |  `VIEW[{kq1_stats[2]}]`   |  `VIEW[{kq1_stats[3]}]`   |  `VIEW[{kq1_stats[4]}]`   |  `VIEW[{kq1_stats[5]}]`   |   `VIEW[{kq1_stats[6]}]`  |   `VIEW[{kq1_stats[7]}]`  |  `VIEW[{kq1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):kq1_wounds]` |

Equipment: Armor. Bastard sword. Shield.
Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:kq1_stats[0]]` |
| ATT  | `INPUT[number:kq1_stats[1]]` |
| STR  | `INPUT[number:kq1_stats[2]]` |
| DEF  | `INPUT[number:kq1_stats[3]]` |
| DR   | `INPUT[number:kq1_stats[4]]` |
| AIM  | `INPUT[number:kq1_stats[5]]` |
| COU  | `INPUT[number:kq1_stats[6]]` |
| DIS  | `INPUT[number:kq1_stats[7]]` |
| A    | `INPUT[number:kq1_stats[8]]` |