---
type: NPC
name: Knight of the Realm
level: 3
virtueLevel: 
location:
description: Warhammer Knight of the Realm
tags:
  - knight
k1_wounds: None
k1_stats:
  - "3"
  - "3"
  - 4
  - "4"
  - "6"
  - "0"
  - "4"
  - "5"
  - "1"
skills:
specialAbilities: 
cost: 14
---

## Knight
| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Knight 1    |  `VIEW[{k1_stats[0]}]`   |  `VIEW[{k1_stats[1]}]`   |  `VIEW[{k1_stats[2]}]`   |  `VIEW[{k1_stats[3]}]`   |  `VIEW[{k1_stats[4]}]`   |  `VIEW[{k1_stats[5]}]`   |   `VIEW[{k1_stats[6]}]`  |   `VIEW[{k1_stats[7]}]`  |  `VIEW[{k1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):k1_wounds]` |

Armor & Weapons: [[Armor#Scale\|Scale]], [[Armor#Medium Shield\|M. Shield]], [[Weapons#Longsword\|Longsword]], [[Weapons#Battle Axe\|Battle Axe]], [[Weapons#Mace\|Mace]], [[Weapons#Lance\|Lance]], Barded [[Items#Cavalry Horse\|Cavalry Horse]]

Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:k1_stats[0]]` |
| ATT  | `INPUT[number:k1_stats[1]]` |
| STR  | `INPUT[number:k1_stats[2]]` |
| DEF  | `INPUT[number:k1_stats[3]]` |
| DR   | `INPUT[number:k1_stats[4]]` |
| AIM  | `INPUT[number:k1_stats[5]]` |
| COU  | `INPUT[number:k1_stats[6]]` |
| DIS  | `INPUT[number:k1_stats[7]]` |
| A    | `INPUT[number:k1_stats[8]]` |


