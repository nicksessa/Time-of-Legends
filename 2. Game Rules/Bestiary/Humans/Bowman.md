---
type: npc
name: Bowman
level: 1
virtueLevel: 
location: 
tags: 
  - archer
  - bowman
b1_wounds: None
b2_wounds: None
b1_stats:
  - "2"
  - "2"
  - "2"
  - "2"
  - "4"
  - "3"
  - "4"
  - "2"
  - "1"
---


### Bowmen

| Name | INI | ATT | STR | DEF | DR | AIM | COU | DIS | # ATT | Wounds |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| ----- |
| Edberg | 2 | 2 | 2 | 2 | 4 | 3 | 4 | 2 | 1 |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]` |

[[Weapon & Armor Tables]]: [[Armor#Padded Gambeson\|Padded]], [[Weapons#Regular Bow\|Regular Bow]], [[Weapons#Axe\|Axe]],  [[Armor#Small Shield\|Small Shield]]
Special Abilities:


### Editable Bowman

| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Bowman 1    |  `VIEW[{b1_stats[0]}]`   |  `VIEW[{b1_stats[1]}]`   |  `VIEW[{b1_stats[2]}]`   |  `VIEW[{b1_stats[3]}]`   |  `VIEW[{b1_stats[4]}]`   |  `VIEW[{b1_stats[5]}]`   |   `VIEW[{b1_stats[6]}]`  |   `VIEW[{b1_stats[7]}]`  |  `VIEW[{b1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b1_wounds]` |

[[Weapon & Armor Tables]]: [[Armor#Padded Gambeson\|Padded]], [[Weapons#Regular Bow\|Regular Bow]], [[Weapons#Axe\|Axe]],  [[Armor#Small Shield\|Small Shield]]
Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:b1_stats[0]]` |
| ATT  | `INPUT[number:b1_stats[1]]` |
| STR  | `INPUT[number:b1_stats[2]]` |
| DEF  | `INPUT[number:b1_stats[3]]` |
| DR   | `INPUT[number:b1_stats[4]]` |
| AIM  | `INPUT[number:b1_stats[5]]` |
| COU  | `INPUT[number:b1_stats[6]]` |
| DIS  | `INPUT[number:b1_stats[7]]` |
| A    | `INPUT[number:b1_stats[8]]` |


%% ## Bowman
| Name     | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| -------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| ----- | ------------------------------------------------------------------------------------------------------------------ |
| Bowman 1 |  2  |  2  |  2  |  2  |  4  |  3  |  4  |  2  |   1    | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b1_wounds]` |
| Bowman 2 |  2  |  2  |  2  |  2  |  4  |  3  |  4  |  2  |   1    | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b2_wounds]` |
Equipment: Dagger. Light armor. Longbow / STR 3, range 20-40-60.
Abilities: %%