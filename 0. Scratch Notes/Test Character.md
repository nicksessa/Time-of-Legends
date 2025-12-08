---
name: Test Character
type: character
wound-level: Serious
INI: 4
ATT: 4
STR: 8
DEF: 4
ARMOR: 4
MISSILE: 4
---

Initiative: <span query="get(INI)"></span>4<span type="end"></span>
Attack: <span query="get(ATT)"></span>4<span type="end"></span>
Strength: <span query="get(STR)"></span>8<span type="end"></span>



> [!infobox|right]+ Collapsible Infobox
> # Name
> ![[Archer.jpg|cover hsmall]]
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Move | Medium |
> | Initiative |`4` |
> | Armor | `5` |
> | Leadership | `8` |
> 
> ###### Stats 2
> | Type | Stat | Stat |
> | ---- | ---- |---|
> |  ⚔️  | 5 | 5 |
> |  🛡️ |  5  | 5 |


## Alahel the Messenger


Move: Medium
INI: 4
Armor: 5
Leadership: 7

| Weapon            | ATT | Def | DMG |
| ----------------- | --- | --- | --- |
| Longsword & Spear | 5   | 5   | 5   |
| Dagger            | 2   | 1   | 1   |
| Long bow          | 4   | -   | 3   |

Equipment: Spear, Longsword, Light Armor
Skills/Abilities: [[Ambidextrous]], [[Brave]], Sharp shooter
Rank: Lion Regular Champion

need some filler
more filler

more filler

***
> [!infobox|right]+ Collapsible Infobox
> # Name
> ![[Archer.jpg|cover hsmall]]
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Move | Medium |
> | Initiative | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):INI]` |
> | Armor | 5 |
> | Leadership | 8 |
> |Wounds |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]`|
> 
> ###### Melee Attack
> |  ATT  | 5    | STR | 4 |
> |:---:|:---:|:---:|:---:|
> 
> ###### Melee Defense
> |  DEF  | 5    | DR | 5 |
> |:---:|:---:|:---:|:---:|
> 
> ###### Ranged Attack
> |  ATT  | 4    | STR | 3 |
> |:---:|:---:|:---:|:---:|




Longsword +5 to Hit, +4 Damage, +5 Defense

| Longsword | +5 to Hit, +4 Damage, +5 Defense    |
| --------- | --- |

| Longbow | +4 to Hit, +3 Damage    |
| --------- | --- |

`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]`

`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):INI]`

|     |     |
|:---:|:---:|
| INI | MOV |
|  4  |  M  |
| ATT | STR |
|  5  |  5  |
| DEF | DR  |
|  5  |  5  |

|       |     |
|:-----:|:---:|
|  INI  |  4  |
| MOVE  |  M  |
|  ATT  |  5  |
|  STR  |  5  |
|  DEF  |  5  |
|  DR   |  5  |
| Range |  4  |

| MOVE | INI | ATT | STR | DEF | ARMOR | Range | R STR | LD  |
|:----:|:---:|:---:|:---:|:---:|:-----:|:-----:|:-----:|:---:|
|  M   |  4  |  5  |  5  |  5  |   5   |   4   |   3   | 8    |

wound-level: Serious
INI: 4
ATT: 5
STR: 5
DEF: 4
ARMOR: 4
MISSILE: 4

```dataview
	TABLE WITHOUT ID link(file.name) AS "Character Name", INI, ATT, STR, DEF, ARMOR, MISSILE 
from "0. Scratch Notes/Test Character"
where (type = "character")
```

```dataview
table ATT, STR
from "0. Scratch Notes/Test Character"
where (type = "character")
```


- [ ] Need to create lots of NPCS
- [ ] Need to eat lunch

My dataview:

```dataview
task
```

