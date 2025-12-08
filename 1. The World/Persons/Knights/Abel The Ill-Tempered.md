---
layout: Time of Legends v01
name: Abel the Ill-Tempered
image: z_Assets/Images/AbelTheIllTempered.jpg
char-name: Abel the Ill-Tempered
statblock: true
level: 6
type: Griffin Templar Hero
rank: Regular
virtue-level: 3
divine-favor: 0
wound-level: None
MOVE: Medium
LD: 2d6
INI: 4
ATT: 4
STR: 7
DEF: 5
DR: 7
AIM: 0
COU: 4
DIS: 6
num_ATT: 1
equipment: Bastard Sword
weapons: Bastard Sword
armor: Partial Plate (DR 6)
abilities: Fanaticism, Leadership (10)
luck-of-the-day: "(1d6): `dice: 1d6`"
stats:
  - 6
  - 4
  - 7
  - 5
  - 7
  - 0
  - 4
  - 6
  - 1
---

***
%%
> [!BLANK | right ]+
> ![[AbelTheIllTempered.jpg\|profile|200]]

%%

> [!recite | right ]+ Image
> ![[AbelTheIllTempered.jpg\|200]]



%%
 ![[AbelTheIllTempered.jpg\|right| 300]]

%%


|       |                                                                        |
| ----- | ---------------------------------------------------------------------- |
| **Type**  | `VIEW[{type}]`  |
| **Rank**  | `VIEW[{rank}]`          |
| **Level** | `VIEW[{level}]`                |
| **Virtue Level** |  `VIEW[{virtue-level}]` |
| **Move**  | `VIEW[{MOVE}]`   |

INI: `VIEW[{stats[0]}]`
Update INI: `INPUT[number:stats[0]]`

| INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `VIEW[{stats[0]}]`  | `VIEW[{stats[1]}]`  | `VIEW[{stats[2]}]`  | `VIEW[{stats[3]}]`  | `VIEW[{stats[4]}]`  | `VIEW[{stats[5]}]`  | `VIEW[{stats[6]}]`  | `VIEW[{stats[7]}]` | `VIEW[{stats[8]}]`  |


| Wound Level  | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]`    |
| --- | --- |







 
| INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `VIEW[{INI}]`  | `VIEW[{ATT}]`  | `VIEW[{STR}]`  | `VIEW[{DEF}]`  | `VIEW[{DR}]`  | `VIEW[{AIM}]`  | `VIEW[{COU}]`  | `VIEW[{DIS}]` | `VIEW[{num_ATT}]`  |


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
> |Num ATT | `INPUT[inlineSelect(option(1), option(2), option(3)):num_ATT]` |
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
monster: Abel the Ill-Tempered
```



***

***

***

***
