---
type: NPC
name: Knight Errant
level: 1
location:
homeland:
virtueLevel:
description: Warhammer Knight Errant
tags:
  - knight
cost: 14 (Stats mostly based on Confrontation Swordsman)
---

## Knight Errant
Base point cost: 20

| Name   |  INI  | ATT | STR | DEF | T/DR | AIM | LD | A | Wounds  |
| ---- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-------:|
| Knight Errant |  3  |  3  |  4/12  |  3/5  |  2/6  |  0  |  7  |  1  | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]` |


| Armor              | Weapons            | Shield        |
| ------------------ | ------------------ | ------------- |
| Heavy (Chain) DR 4 | Hand Weapon, Lance | Medium Shield |

Skills: [[Charging Strength (12)]]
Special Abilities: 

### Horse
[[Items#Cavalry Horse\|Cavalry Horse]], [[Armor#Leather Barding\|Leather Barding]]

| Special Ability                                      |
| ---------------------------------------------------- |
| `dice: [[Special Abilities#^specialAbilitiesTable]]` |



## Random Armor


| dice: 1d10 | Armor Type               |
|:----------:| ------------------------ |
|    1-3     | Partial Plate - DR 6     |
|    4-7     | Plated Chain - DR 7      |
|    8-9     | Full Plate - DR 8        |
|     10     | Gothic Full Plate - DR 9 | 
^armorTable

## Random Weapons

| Weapons                                        |
| ---------------------------------------------- |
| `dice: [[Create Paladin#^weaponLoadout]]]` | 


| dice: 1d6 | Weapons Carried                                 |
| --------- | ----------------------------------------------- |
|   1-4        | `dice: [[Create Paladin#^handWeaponTable]]` |
|   5-6        | `dice: [[Create Paladin#^handWeaponTable]]`, `dice: [[Create Paladin#^twoHandedWeaponTable]]`     
^weaponLoadout

| dice: 1d10 | Hand Weapons                                 |
|:----------:| -------------------------------------------- |
|    1-2     | Axe                                          |
|    3-4     | Mace                                         |
|    5-6     | Hammer                                       |
|    7-9     | Sword                                        |
|     10     | `dice: [[Create Paladin#^weirdWeapons]]` | 
^handWeaponTable


| Two Handed Weapons |
| ------------------ |
| Halberd            |
| Great Axe          |
| Great Sword        |
| Warhammer          |
| Long Spear         | 
^twoHandedWeaponTable


| Weird Weapons |
| ------------- |
| Flail         |
| Morning Star  | 
^weirdWeapons


| Shield        |
| ------------- |
| None          |
| Small Shield  |
| Medium Shield |
| Large Shield  | 
^shieldTable

