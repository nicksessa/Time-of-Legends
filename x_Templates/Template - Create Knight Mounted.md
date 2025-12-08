---
type: npc
name: Knight - Mounted
location:
tags:
wounds: None
stats:
  - 4
  - 6
  - 7
  - "5"
  - 13
  - "0"
  - 7
  - 7
  - "1"
abilities:
  - "[[Fearless]]"
  - "[[Furious Charge]]"
  - "[[Charging Strength (15)]]"
---

## Knight (mounted)
| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Knight 1    |  `VIEW[{stats[0]}]`   |  `VIEW[{stats[1]}]`   |  `VIEW[{stats[2]}]`   |  `VIEW[{stats[3]}]`   |  `VIEW[{stats[4]}]`   |  `VIEW[{stats[5]}]`   |   `VIEW[{stats[6]}]`  |   `VIEW[{stats[7]}]`  |  `VIEW[{stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):km1_wounds]` |

Equipment: Barded war-horse. Cavalry lance. Knight's armor. Long shield. Long sword.
Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |          Value           |
| ---- |:------------------------:|
| INI  | `INPUT[number:stats[0]]` |
| ATT  | `INPUT[number:stats[1]]` |
| STR  | `INPUT[number:stats[2]]` |
| DEF  | `INPUT[number:stats[3]]` |
| DR   | `INPUT[number:stats[4]]` |
| AIM  | `INPUT[number:stats[5]]` |
| COU  | `INPUT[number:stats[6]]` |
| DIS  | `INPUT[number:stats[7]]` |
| A    | `INPUT[number:stats[8]]` | 