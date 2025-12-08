---
layout: Time of Legends v01
name: Template - Character
image: z_Assets/Images/KnightWithMace.jpg
char-name: Template - Character
statblock: true
level: 1
type: Fighter
rank: Regular
virtue-level: 1
divine-favor: 0
wounds: None
INI: 0
ATT: 0
STR: 0
DEF: 0
DR: 0
AIM: 0
MOVE: Medium
LD: 2d6
num-ATT: 1
COU: 0
DIS: 0
equipment: Dagger
weapons: Sword, Medium Shield, Lance
armor: Chain (DR 4)
abilities:
stats:
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 1
luck-of-the-day: "(1d6): `dice: 1d6`"
---

***

 ![[KnightWithMace.jpg\|right|250]]
 
|       |                                                                        |
| ----- | ---------------------------------------------------------------------- |
| **Type**  | `VIEW[{type}]`  |
| **Rank**  | `VIEW[{rank}]`          |
| **Level** | `VIEW[{level}]`                |
| **Virtue Level** |  `VIEW[{virtue-level}]` |
| **Move**  | `VIEW[{MOVE}]`   |

| Wounds  | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]`    |
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
> Type: `VIEW[{type}]` 
> Rank: `VIEW[{rank}]` 
> Level: `VIEW[{level}]`
> Virtue Level: `VIEW[{virtue-level}]`
> Move: `VIEW[{MOVE}]`   
> Initiative: `VIEW[{INI}]` 
> Attack: `VIEW[{ATT}]`  
> Strength: `VIEW[{STR}]` 
> Defense: `VIEW[{DEF}]`  
> DR: `VIEW[{DR}]` 
> AIM: `VIEW[{AIM}]` 
> Courage: `VIEW[{COU}]` 
> Discipline: `VIEW[{DIS}]` 
> Num-ATT: `VIEW[{num-ATT}]` 
> stats: [`VIEW[{INI}]`,`VIEW[{ATT}]`,`VIEW[{STR}]`,`VIEW[{DEF}]`,`VIEW[{DR}]`,`VIEW[{AIM}]`,`VIEW[{COU}]`,`VIEW[{DIS}]`,`VIEW[{num-ATT}]`]
> ***




%%
```meta-bind
INPUT[imageSuggester(optionQuery("z_Assets/Images"), showcase):image]
```
%%


```statblock
monster: Template - Character
```



***

