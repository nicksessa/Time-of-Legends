---
name: Test Character 1
rank: Veteran
INI: 1
ATT: 3
STR: 5
DEF: 2
DR: 5
AIM: 2
MOVE: Medium
LD: 6
"#ATT": 0
COU: 3
DIS: 5
virtue-level: 1
char-name: Crusader
wound-level: None
equipment: "Longsword, Shield, Lance, Plate Armor, Crossbow: STR 5"
---

> [!infobox|left]+ Collapsible Infobox
> # <span query="get(char-name)"></span>Crusader<span type="end"></span>
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
> | INI | <span query="get(INI)"></span>1<span type="end"></span> |
> |ATT|<span query="get(ATT)"></span>3<span type="end"></span> |
> |STR|<span query="get(STR)"></span>5<span type="end"></span> |
> |DEF|<span query="get(DEF)"></span>2<span type="end"></span> |
> |DR|<span query="get(DR)"></span>5<span type="end"></span> | 
> | AIM  | <span query="get(AIM)"></span>2<span type="end"></span>   |
> | COU  | <span query="get(COU)"></span>3<span type="end"></span>   |
> | DIS  | <span query="get(DIS)"></span>5<span type="end"></span>   |
> ###### Equipment
> `INPUT[textArea:equipment]`



> [!infobox|right]+ Collapsible Infobox
> # Knight 
> ## Rank: Veteran
> ![[KnightWalkingWithTwoHandedSword.jpg|cover hsmall]]
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Move | Medium  |
> |Wounds |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]`|
> 
> ###### Combat Stats
> |  Stat  | Value   | 
> |:---:|:---:|
> | INI | `2` |
> |ATT|<span query="get(ATT)"></span>3<span type="end"></span> |
> |STR|<span query="get(STR)"></span>5<span type="end"></span> |
> |DEF|<span query="get(DEF)"></span>2<span type="end"></span> |
> |DR|<span query="get(DR)"></span>5<span type="end"></span> | 
> | AIM  | <span query="get(AIM)"></span>2<span type="end"></span>   |
> | COU  | <span query="get(COU)"></span>3<span type="end"></span>   |
> | DIS  | <span query="get(DIS)"></span>5<span type="end"></span>   |
> ###### Equipment
> `INPUT[textArea:equipment]`







> [!note]+ Character Card
> 
> Name: <span query="get(char-name)"></span>Crusader<span type="end"></span>
> Rank: <span query="get(rank)"></span>Veteran<span type="end"></span>
>
>| MOVE | INI | ATT | STR | DEF | DR | AIM | COU | DIS  |
>|:----:|:---:|:---:|:---:|:---:|:-----:|:-----:|:-----:|:---:|
>|  <span query="get(MOVE)"></span>Medium<span type="end"></span>   |  <span query="get(INI)"></span>1<span type="end"></span>  |  <span query="get(ATT)"></span>3<span type="end"></span>  |  <span query="get(STR)"></span>5<span type="end"></span>  |  <span query="get(DEF)"></span>2<span type="end"></span>  |   <span query="get(DR)"></span>5<span type="end"></span>   |   <span query="get(AIM)"></span>2<span type="end"></span>   |   <span query="get(COU)"></span>3<span type="end"></span>   | <span query="get(DIS)"></span>5<span type="end"></span>    |
>
>Equipment: <span query="get(equipment)"></span>Longsword, Shield, Lance, Plate Armor, Crossbow: STR 5<span type="end"></span>
>Abilities: [[Brave]]

***

The Name: <span query="get(char-name)"></span>Crusader<span type="end"></span>
Rank: <span query="get(rank)"></span>Veteran<span type="end"></span>
Move: <span query="get(MOVE)"></span>Medium<span type="end"></span>
Initiative: <span query="get(INI)"></span>1<span type="end"></span>
Attack: <span query="get(ATT)"></span>3<span type="end"></span>
Strength: <span query="get(STR)"></span>5<span type="end"></span>
Defense: <span query="get(DEF)"></span>2<span type="end"></span>
Damage Resistance: <span query="get(DR)"></span>5<span type="end"></span>
AIM: <span query="get(AIM)"></span>2<span type="end"></span>
Courage: <span query="get(COU)"></span>3<span type="end"></span>
Discipline: <span query="get(DIS)"></span>5<span type="end"></span>

***

> [!NOTE | left ]- Edit Stats
>
>Rank: `INPUT[inlineSelect(option(Irregular), option(Regular), option(Veteran), option(Elite), option(Champion), option(Special)):rank]`
>
>MOVE: `INPUT[inlineSelect(option(Short), option(Medium), option(Long)):MOVE]`
>
>INI: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):INI]`
>
>ATT: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):ATT]`
>
>STR: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):STR]`
>
>DEF: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):DEF]`
>
>DR: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):DR]`
>
>AIM: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):AIM]`
>
>COU: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):COU]`
>
>DIS: `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):DIS]`
>
>Equipment: `INPUT[text:equipment]`




