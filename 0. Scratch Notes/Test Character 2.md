---
name: Test Character 2
rank: Veteran
INI: 3
ATT: 4
STR: 5
DEF: 4
DR: 11
AIM: 0
MOVE: Medium
LD: 6
num-ATT: 2
COU: 4
DIS: 5
virtue-level: 1
char-name: Knight Templar
wound-level: None
equipment: "Longsword, Shield, Lance, Plate Armor, Crossbow: STR 5"
level: 5
abilities:
stats: "[ 3, 4, 5, 4, 11, 0, 4, 5, 2 ]"
image: z_Assets/Images/KnightWithMace.jpg
type: Knight Templar
---
%%
> [!infobox|right]+ Collapsible Infobox
> # <span query="get(char-name)"></span>Knight Templar<span type="end"></span>
> Rank <span query="get(rank)"></span>Veteran<span type="end"></span>
> ![[KnightWalkingWithTwoHandedSword.jpg|cover hsmall]]
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Move | <span query="get(MOVE)"></span>Medium<span type="end"></span> |
> |Wounds |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]`|
> 
> ###### Combat Stats
> |  Stat  | Value   | 
> |:---:|:---:|
> | INI | <span query="get(INI)"></span>3<span type="end"></span> |
> |ATT|<span query="get(ATT)"></span>4<span type="end"></span> |
> |STR|<span query="get(STR)"></span>5<span type="end"></span> |
> |DEF|<span query="get(DEF)"></span>4<span type="end"></span> |
> |DR|<span query="get(DR)"></span>11<span type="end"></span> | 
> | AIM  | <span query="get(AIM)"></span>0<span type="end"></span>   |
> | COU  | <span query="get(COU)"></span>4<span type="end"></span>   |
> | DIS  | <span query="get(DIS)"></span>5<span type="end"></span>   |
> ###### Equipment
> `INPUT[textArea:equipment]`

%%

***

 ![[KnightWithMace.jpg\|right|250]]
 
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
**Abilities**: [[Brave]]

***



> [!NOTE | left ]- Edit Stats
> | Stat  | Modifier  |
> |---|---|
> |Rank | `INPUT[inlineSelect(option(Irregular), option(Regular), option(Veteran), option(Elite), option(Champion), option(Special)):rank]` |
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
> stats: [ `VIEW[{INI}]`, `VIEW[{ATT}]`, `VIEW[{STR}]`, `VIEW[{DEF}]`, `VIEW[{DR}]`, `VIEW[{AIM}]`, `VIEW[{COU}]`, `VIEW[{DIS}]`, `VIEW[{num-ATT}]` ]
> ***




%%
```meta-bind
INPUT[imageSuggester(optionQuery("z_Assets/Images"), showcase):image]
```
%%





