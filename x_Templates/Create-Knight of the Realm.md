---
type: npc
name: Knight of the Realm
location:
description: Warhammer Knight of the Realm
tags:
  - test
wounds: None
stats:
  - "3"
  - "3"
  - 4
  - "4"
  - "6"
  - "0"
  - "4"
  - "5"
  - "1"
abilities:
cost: 14
---

## Knight
| Name | INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Knight 1    |  `VIEW[{stats[0]}]`   |  `VIEW[{stats[1]}]`   |  `VIEW[{stats[2]}]`   |  `VIEW[{stats[3]}]`   |  `VIEW[{stats[4]}]`   |  `VIEW[{stats[5]}]`   |   `VIEW[{stats[6]}]`  |   `VIEW[{stats[7]}]`  |  `VIEW[{stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |

Armor & Weapons: [[Armor#Scale\|Scale]], [[Armor#Medium Shield\|M. Shield]], [[Weapons#Longsword\|Longsword]], [[Weapons#Battle Axe\|Battle Axe]], [[Weapons#Mace\|Mace]], [[Weapons#Lance\|Lance]], Barded [[Items#Cavalry Horse\|Cavalry Horse]]

Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |         Value          | 
| ---- |:----------------------:|
| INI  | `INPUT[text:stats[0]]` |
| ATT  | `INPUT[text:stats[1]]` |
| STR  | `INPUT[text:stats[2]]` |
| DEF  | `INPUT[text:stats[3]]` |
| DR   | `INPUT[text:stats[4]]` |
| AIM  | `INPUT[text:stats[5]]` |
| COU  | `INPUT[text:stats[6]]` |
| DIS  | `INPUT[text:stats[7]]` |
| A    | `INPUT[text:stats[8]]` |




## Test



| Name     | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds |
| -------- | --- | --- | --- | --- | --- | --- | --- | --- | ----- | ------ |
| Knight 1 | 3   | 3   | 4   | 4   | 6   | 0   | 4   | 5   | 1     |        |


