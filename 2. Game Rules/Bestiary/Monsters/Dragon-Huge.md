---
layout: Time of Legends v01
name: Huge Dragon
image: z_Assets/Images/DragonHuge.jpg
char-name: Huge Dragon
statblock: true
level: 2
type: Huge Dragon
rank: Creature
virtue-level: 0
divine-favor: 0
wound-level: None
MOVE: Long
LD: 2d6
INI: 4
ATT: 9
STR: 20
DEF: 6
DR: 17
AIM: 4
COU: 12
DIS: 4
num-ATT: 3
equipment: Claws and Bite
weapons: Claws and Bite
armor: Dragon Hide (13)
abilities: Fear, Enormous, Born Killer, Hard Boiled, Flight, Implacable (1), Dragon Breath STR 10
luck-of-the-day: "(1d6): `dice: 1d6`"
stats: [4, 6, 13, 4, 13, 4, 9, 4, 3]
---

***

> [!BLANK | right ]+
> ![[DragonHuge.jpg\|right|profile|175]]
 
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
> |MOVE | `INPUT[inlineSelect(option(Short), option(Huge), option(Long)):MOVE]` |
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
