---
type: NPC
name: Edberg
location: London
level: 1
homeland: Lothian
lord: King Lot
description: Bowman
virtueLevel: 2
tags:
  - Bowman
wounds: None
stats:
  - "2"
  - "2"
  - 2/3
  - "2"
  - 2/4
  - "3"
  - "4"
  - "2"
  - "1"
cost: 14
---



| Name | INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT | Wounds |
| ---- |:---:|:---:|:---:|:---:|:--:|:---:|:---:|:---:|:-----:|:------:|
| Edberg | `VIEW[{stats[0]}]` | `VIEW[{stats[1]}]` | `VIEW[{stats[2]}]` | `VIEW[{stats[3]}]` | `VIEW[{stats[4]}]` | `VIEW[{stats[5]}]` | `VIEW[{stats[6]}]` | `VIEW[{stats[7]}]` | `VIEW[{stats[8]}]` | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |


Equipment: Dagger. Light armor. Longbow / STR 3, range 20-40-60.[[Armor#Leather Barded Warhorse\|Leather Barding]], [[Items#Cavalry Horse\|Cavalry Horse]]
Skills: [[Horseman (1) - Trained]]

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:stats[0]]` |
| ATT  | `INPUT[number:stats[1]]` |
| STR  | `INPUT[text:stats[2]]` |
| DEF  | `INPUT[text:stats[3]]` |
| DR   | `INPUT[text:stats[4]]` |
| AIM  | `INPUT[number:stats[5]]` |
| COU  | `INPUT[number:stats[6]]` |
| DIS  | `INPUT[number:stats[7]]` |
| A    | `INPUT[number:stats[8]]` |


%% ## Bowman
| Name     | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| -------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| ----- | ------------------------------------------------------------------------------------------------------------------ |
| Bowman 1 |  2  |  2  |  2  |  2  |  4  |  3  |  4  |  2  |   1    | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b1_wounds]` |
| Bowman 2 |  2  |  2  |  2  |  2  |  4  |  3  |  4  |  2  |   1    | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b2_wounds]` |
Equipment: Dagger. Light armor. Longbow / STR 3, range 20-40-60.
Abilities: %%



### Bowmen

| Name | INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT | Wounds |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| ----- |
| Edberg | 2 | 2 | 2/3 | 2 | 2/4 | 3 | 4 | 2 | 1 |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]` |

[[Weapon & Armor Tables]]: [[Armor#Padded Gambeson\|Padded]], [[Weapons#Regular Bow\|Regular Bow]], [[Weapons#Axe\|Axe]],  [[Armor#Small Shield\|Small Shield]]
Special Abilities: