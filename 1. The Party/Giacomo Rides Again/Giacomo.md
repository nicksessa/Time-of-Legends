---
type: PC
name: Knight Errant
level: 3
location: London
homeland: Lothian
lord: King Lot
socialClass: Knight
description: Knight Errant
tags:
  - knight
virtueLevel: 1
wounds: None
stats:
  - "3"
  - 3
  - 3/5
  - "3"
  - 7/8
  - "0"
  - "3"
  - "4"
  - "1"
specialAbilities: "[[Special Abilities#Item Cloak of the Dragon|Cloak of the Dragon]]"
skills:
  - "[[Brutal]]"
  - "[[Fealty]]"
  - "[[Horseman (1) - Trained]]"
  - "[[Hard Boiled]]"
  - "[[Feel No Pain]]"
  - "[[Duelist]]"
cost: 14
---


## Sir Giacomo

> [!infobox|right]+ Collapsible Infobox
> ![[Pasted image 20251130175439.png|150]]


|Name|INI|ATT|STR|DEF|T/DR|AIM|COU|DIS|A|Wounds|
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Sir Giacomo | 3 | 3 | 3/5 | 3 | 2(4)/8 | 0 | 3 | 4 | 2 |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]`   |

| Level | Virtue Level | Social Class |      Homeland      |  Lord   |      Lady      |
|:-----:|:------------:|:------------:|:------------------:|:-------:|:--------------:|
|   3   |      1       |    Knight    | `VIEW[{homeland}]` | [[Lot]] | [[Lady Lynet]] |

|  Current Location  |     Money     |
|:------------------:|:------------- |
| `VIEW[{location}]` | GP: 0 <br/>SP: 191 <br/>CP: 33 | 

| Experience Points | Virtue Points |
| ----------------- | ------------- |
| `boxes: 1/10`     | `boxes: 1/10` |

| [[Divine Favor]] | Fate Points  |
| ---------------- | ------------ |
| `boxes: 5/10`    | `boxes: 8/8` |

## Service Rewards

|Gifts | Result|
|---|---|
|1|+1 TOUGH|
|2|+1 TOUGH|

|Favor|
|---|
|Garter (5 Fate Points)|

## Stat Block

| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :----: |:------:|
| Sir Giacomo    |  `VIEW[{stats[0]}]`   |  `VIEW[{stats[1]}]`   |  `VIEW[{stats[2]}]`   |  `VIEW[{stats[3]}]`   |  `VIEW[{stats[4]}]`   |  `VIEW[{stats[5]}]`   |   `VIEW[{stats[6]}]`  |   `VIEW[{stats[7]}]`  |  `VIEW[{stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |

[[Weapon & Armor Tables]]: [[Armor#Scale\|Scale]], [[Armor#Medium Shield\|M. Shield]], [[Weapons#Longsword\|Longsword]], [[Weapons#Battle Axe\|Battle Axe]], [[Weapons#Mace\|Mace]], [[Weapons#Lance\|Lance]], [[Armor#Leather Barded Warhorse\|Leather Barding]], [[Items#Cavalry Horse\|Cavalry Horse]]

Bandages (6): `boxes: 6/6`

[[Skills]] : `VIEW[{skills}][link]`
[[Special Abilities]] :  `VIEW[{specialAbilities}][link]`





%%
| Special Ability                                      |
| ---------------------------------------------------- |
| `dice: [[Special Abilities#^specialAbilitiesTable]]` |
%%

%%
| Random Skill                                      |
| ---------------------------------------------------- |
| `dice: [[Skill-Table#^skillTable]]` |
%%

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


## Character Creation

At creation, Giacomo rolled a 3 for how many rolls to make on the [[Advancement]] table.
First roll: +1 STR
Second roll: New Skill ->  [[Brutal]]
Third roll: New Skill -> [[Fealty]]

Special ability rolled: "Item: Cloak of the Dragon - This cloak mysteriously confers the ability for the wearer to be immune to non-magical missile fire."

## Level 2
Rolled and got 3 advancements
1. Skill:  [[Hard Boiled]]
2. ATT + 1
3. Skill: [[Skills#Feal No Pain]]


## Level 3
Rolled and got 3 advancements
1. Number of Attacks +1
2. INI +1
3. [[Duelist]]

Adventure Completed: 6 Virtue, 5 EXP



## About Giacomo

| Character Attributes |                                                                                                                                                                                  |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Age                  | 18                                                                                                                                                                               |
| Motivation           | Zeal: God has called this character to battle.                                                                                                                                   |
| Family Status        | Unmarried                                                                                         |
| Extended Family      | Small Brood: A small, tight-knit clan, thinned out by time. Perhaps your parents still survive, along with an uncle or other distant relatives.                                  |
| Martial Prowess      | Professional Soldier                         |
| Stewardship          | Ignorant: You prefer drinking or brawling to picking over the minutiae of managing your money or the day to day running of your estates. -1 Wealth per turn, -1 starting Wealth. |
| Background           | Professional Soldier:  The unending conflict needs a steady supply of hardened men. The professional soldier serves his master and himself, whatever his station.                |
| Military Experience  | Bloodied: A few skirmishes has given the character an appreciation of how awful the battlefield can be.                                                                          |

| Quirks  |                                                                                   |
| ------- | --------------------------------------------------------------------------------- |
| Quirk 1 | 3,3 \| Pompous:  The character has an inflated sense of self-importance.          |
| Quirk 2 | 6,3 \| Duelist:  The character is a master of single combat.                      |
| Quirk 3 | 1,4 \| Salt of the Earth:  The character is at home among commoners and peasants. |

| Contacts  |                                                                   |
| --------- | ----------------------------------------------------------------- |
| Contact 1 | Outlaw: A local criminal, exiled onto the fringes of society.     |
| Contact 2 | Soldier from the same household: Another soldier in your retinue. |
| Contact 3 | Minor Noble: A count, baron or similarly titled figure            |





%%
| Character Attributes |  |
| --- | --- |
| Age | `dice: [[Character Background#^character-age]]` |
| Motivation | `dice: [[Character Background#^character-motivation]]` |
| Family Status | `dice: [[Character Background#^family-status]]` |
| Extended Family | `dice: [[Character Background#^extended-family]]` |
| Martial Prowess | `dice: [[Character Background#^martial-prowess]]` |
| Stewardship | `dice: [[Character Background#^stewardship]]` |
| Background | `dice: [[Character Background#^background]]` |
| Military Experience | `dice: [[Character Background#^military-experience]]` |

| Quirks |  |
| --- | --- |
| Quirk 1 | `dice: [[Character Background#^quirks]]` |
| Quirk 2 | `dice: [[Character Background#^quirks]]` |
| Quirk 3 | `dice: [[Character Background#^quirks]]` |

| Contacts |  |
| --- | --- |
| Contact 1 | `dice: [[Character Background#^contacts]]` |
| Contact 2 | `dice: [[Character Background#^contacts]]` |
| Contact 3 | `dice: [[Character Background#^contacts]]` |

%%


