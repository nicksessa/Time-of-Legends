---
type: NPC
note: based on the Confrontation Mounted Knight
---

## Paladin
WFB Base point cost: 60
Confrontation cost: 64

| Name   |  INI  | ATT | STR | DEF | DR | AIM | LD | A | Wounds  |
| ---- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-------:|
| Paladin |  4  |  6  |  7/15  |  5/7  |  4/11/14  |  0  |  8  |  3  | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]` |

| Armor                | Weapons            | Shield        |
| -------------------- | ------------------ | ------------- |
| Plated Chain - DR 7 | Hammer, Lance | Medium Shield |

%%
| Armor     | Weapons       | Shield    | 
| ----------- | ----------------- | --- |
| `dice: [[Create Paladin#^armorTable]]` | `dice: [[Create Paladin#^weaponLoadout]]]` | `dice: [[Create Paladin#^shieldTable]]`    |
%%

Skills: [[Charging Strength (15)]]
Special Abilities: 

### Horse
[[Items#Warhorse\|Warhorse]], [[Armor#Plate Barding\|Plate Barding]]

| Special Ability                                      |
| ---------------------------------------------------- |
| `dice: [[Special Abilities#^specialAbilitiesTable]]` |



%%
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

%%