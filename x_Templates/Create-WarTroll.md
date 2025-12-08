---
type: NPC
name: War Troll
location:
description: It's a troll
tags:
  - Goblin
  - Creature
wounds: None
stats:
  - 1
  - 5
  - 12
  - 4
  - 12
  - 0
  - 8
  - 0
  - 2
abilities:
  - "[Fear]"
  - "[Survival Instinct]"
  - "[Regeneration (5+)]"
  - "[Stupid]"
cost: 80
---

## War Troll
| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Black Troll 1    |  `VIEW[{stats[0]}]`   |  `VIEW[{stats[1]}]`   |  `VIEW[{stats[2]}]`   |  `VIEW[{stats[3]}]`   |  `VIEW[{stats[4]}]`   |  `VIEW[{stats[5]}]`   |   `VIEW[{stats[6]}]`  |   `VIEW[{stats[7]}]`  |  `VIEW[{stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |

Equipment: Combat Blades
Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:stats[0]]` |
| ATT  | `INPUT[number:stats[1]]` |
| STR  | `INPUT[number:stats[2]]` |
| DEF  | `INPUT[number:stats[3]]` |
| DR   | `INPUT[number:stats[4]]` |
| AIM  | `INPUT[number:stats[5]]` |
| COU  | `INPUT[number:stats[6]]` |
| DIS  | `INPUT[number:stats[7]]` |
| A    | `INPUT[number:stats[8]]` |
