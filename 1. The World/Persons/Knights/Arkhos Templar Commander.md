---
layout: Time of Legends v01
name: Arkhos Templar Commander
image: z_Assets/Images/ArkhosTemplarCommander.jpg
char-name: Arkhos Templar Commander
statblock: true
type: NPC
location: Camelot
faction: Griffin
description: Grandmaster of the Templars
level: 6
class: Templar Commander
rank: Elite Champion
virtue-level: 5
divine-favor: 0
wound-level: None
MOVE: Medium
LD: 2d6
INI: 6
ATT: 6
STR: 9
DEF: 7
DR: 10
AIM: 0
COU: 7
DIS: 9
num-ATT: 2
equipment: Bastard Sword, Dagger, Medium Shield
weapons: Bastard Sword, Medium Shield
armor: Full Plate (DR 8)
abilities: Fanaticism, Bravery, War Fury, Leadership (10)
luck-of-the-day: "(1d6): `dice: 1d6`"
stats: [6, 6, 9, 7, 10, 0, 7, 9, 2]
---

***

> [!BLANK | right ]+
> ![[ArkhosTemplarCommander.jpg\|right|profile|175]]
 
|       |                                                                        |
| ----- | ---------------------------------------------------------------------- |
| **Type**  | `VIEW[{type}]`  |
| **Rank**  | `VIEW[{rank}]`          |
| **Level** | `VIEW[{level}]`                |
| **Virtue Level** |  `VIEW[{virtue-level}]` |
| **Move**  | `VIEW[{MOVE}]`   |


| Wound Level  | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]`    |
| --- | --- |

 
| INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `VIEW[{INI}]`  | `VIEW[{ATT}]`  | `VIEW[{STR}]`  | `VIEW[{DEF}]`  | `VIEW[{DR}]`  | `VIEW[{AIM}]`  | `VIEW[{COU}]`  | `VIEW[{DIS}]` | `VIEW[{num-ATT}]`  |


**Equipment**: `VIEW[{equipment}]` 
**Abilities**: 

***



> [!NOTE | left ]+ Edit Stats
> | Stat  | Modifier  |
> |---|---|
> |Rank | `INPUT[inlineSelect(option(Irregular), option(Regular), option(Veteran), option(Elite), option(Champion), option(Special)):rank]` |
> |Level | `INPUT[inlineSelect(option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):level]` |
> |MOVE | `INPUT[inlineSelect(option(Short), option(Medium), option(Long)):MOVE]` |
> |Wound Level|`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]` |
> |INI| `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):INI]` |
> |ATT| `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):ATT]` |
> | STR | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):STR]` |
> | DEF | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):DEF]` |
> | DR | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15)):DR]` |
>| AIM | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):AIM]` |
> |COU | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):COU]` |
> | DIS | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):DIS]` |
> |Num ATT | `INPUT[inlineSelect(option(1), option(2), option(3)):num-ATT]` |
> | Equipment | `INPUT[textArea:equipment]` |
> |Stats |  `INPUT[text:stats]` |


> [!note|right]+ Character Card - Plain Text
> ***
> Type: `VIEW[{type}]` 
> Rank: `VIEW[{rank}]` 
> Level: `VIEW[{level}]`
> Virtue Level: `VIEW[{virtue-level}]`
> Move: `VIEW[{MOVE}]`   
> Initiative: `VIEW[{INI}]` 
> Attack: `VIEW[{ATT}]`  
> Strength: `VIEW[{STR}]` 
> Defense: `VIEW[{DEF}]`  
> DR: `VIEW[{DR}]` 
> AIM: `VIEW[{AIM}]` 
> Courage: `VIEW[{COU}]` 
> Discipline: `VIEW[{DIS}]` 
> Num-ATT: `VIEW[{num-ATT}]` 
> stats: [`VIEW[{INI}]`, `VIEW[{ATT}]`, `VIEW[{STR}]`, `VIEW[{DEF}]`, `VIEW[{DR}]`, `VIEW[{AIM}]`, `VIEW[{COU}]`, `VIEW[{DIS}]`, `VIEW[{num-ATT}]`]
> ***

> [!blank|left]+
> ### EDIT STATS
> stats: `VIEW[{stats}]`
> ```meta-bind
> INPUT[list:stats]
>  ```


%%
```meta-bind
INPUT[imageSuggester(optionQuery("z_Assets/Images"), showcase):image]
```
%%


```statblock
monster: Fred
```



***

***

***

***
