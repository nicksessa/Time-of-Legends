---
type: NPC
name: Crossbowman
level: 1
virtueLevel: 
location: 
tags: 
  - archer
  - crossbowman
cb1_wounds: None
cb2_wounds: None
cb1_stats:
  - "2"
  - "2"
  - "2"
  - "2"
  - "4"
  - "3"
  - "4"
  - "2"
  - "1"
abilities:
skills:
---



| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :-----: |:------------------------------------------------------------------------------------------------------------------:|
| Crossbowman 1    |  `VIEW[{cb1_stats[0]}]`   |  `VIEW[{cb1_stats[1]}]`   |  `VIEW[{cb1_stats[2]}]`   |  `VIEW[{cb1_stats[3]}]`   |  `VIEW[{cb1_stats[4]}]`   |  `VIEW[{cb1_stats[5]}]`   |   `VIEW[{cb1_stats[6]}]`  |   `VIEW[{cb1_stats[7]}]`  |  `VIEW[{b1_stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):cb1_wounds]` |

[[Weapon & Armor Tables]]: [[Armor#Padded Gambeson\|Padded]], [[Weapons#Light Crossbow\|Light Crossbow]], [[Weapons#Axe\|Axe]],  [[Armor#Small Shield\|Small Shield]]
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


%% ## Crossbowman
| Name     | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| -------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| ----- | ------------------------------------------------------------------------------------------------------------------ |
| Crossbowman 1 |  2  |  2  |  2  |  2  |  4  |  3  |  4  |  2  |   1    | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b1_wounds]` |
| Crossbowman 2 |  2  |  2  |  2  |  2  |  4  |  3  |  4  |  2  |   1    | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):b2_wounds]` |
Equipment: Dagger. Light armor. L. Crossbow / STR 3, range 20-40-60.
Abilities: %%