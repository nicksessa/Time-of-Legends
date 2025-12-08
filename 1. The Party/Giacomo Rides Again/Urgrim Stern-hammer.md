---
type: NPC
name: Urgrim Stern-hammer
level: 1
description: Dwarf
location: London
homeland: Lothian
lord: King Lot
tags:
  - dwarf
virtueLevel: 2
wounds: None
stats:
  - "1"
  - "1"
  - 2
  - "1"
  - 3
  - "0"
  - "2"
  - "2"
  - "1"
specialAbilities:
skills:
cost: 10
---

[[Urgrim Stern-hammer]] joined [[Giacomo]] as his faithful dwarf companion.



### Dwarf

| Name       |  INI  | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| ---------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:| ------------------------------------------------------------------------------------------------------------------ |
| Dwarf | 1 | 1 | 2 | 1 | 3 | 0 | 2 | 2 | 1 | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]` |

Equipment: Light armor. S. Shield. Short sword.
Special Abilities: 

## Dwarf

| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :----: |:------:|
| Dwarf    |  `VIEW[{stats[0]}]`   |  `VIEW[{stats[1]}]`   |  `VIEW[{stats[2]}]`   |  `VIEW[{stats[3]}]`   |  `VIEW[{stats[4]}]`   |  `VIEW[{stats[5]}]`   |   `VIEW[{stats[6]}]`  |   `VIEW[{stats[7]}]`  |  `VIEW[{stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |


| Equipment     | Number       | --- | Equipment     | Number       |
| ------------- | ------------ |:---:| ------------- | ------------ |
| Lance         | `boxes: 2/2` |     | Casks of Beer | `boxes: 4/4` |
| Longsword     | `boxes: 2/2` |     | Iron Rations  | `boxes: 5/5` |
| Shield        | `boxes: 1/1` |     | Rope          | `boxes: 1/1` |
| Riding horses | `boxes: 2/2` |     |               |              |
| Chainmail     | `boxes: 1/1` |     |               |              |


## Edit Stats

| STAT |            Value            |
| ---- |:---------------------------:|
| INI  | `INPUT[number:stats[0]]` |
| ATT  | `INPUT[number:stats[1]]` |
| STR  |  `INPUT[text:stats[2]]`  | 
| DEF  | `INPUT[number:stats[3]]` |
| DR   |  `INPUT[text:stats[4]]`  |
| AIM  | `INPUT[number:stats[5]]` |
| COU  | `INPUT[number:stats[6]]` |
| DIS  | `INPUT[number:stats[7]]` |
| A    | `INPUT[number:stats[8]]` |
