---
type: NPC
name: Berwyn
level: 1
location: London
homeland: Lothian
lord: King Lot
description: Man-at-Arms
tags:
  - Man-at-Arms
virtueLevel: 2
wounds: None
stats:
  - "2"
  - "3"
  - 3/5
  - 2/3
  - 6/7
  - "0"
  - "4"
  - "2"
  - "1"
specialAbilities:
skills:
  - - - Horseman (1) - Trained
cost: 14
---


# Berwyn

Social Class: Yeoman
Occupation: Men-at-Arms

| Name       |  INI  | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT | Wounds                                                                                                             |
| ---------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:| ------------------------------------------------------------------------------------------------------------------ |
| Berwyn | 2 | 3 | 3/5 | 2/3 | 6/7 | 0 | 4 | 2 | 1 | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead))]` |

Equipment: Light armor. Shield. Spear. Short sword.  [[Armor#Leather Barded Warhorse\|Leather Barding]], [[Items#Cavalry Horse\|Cavalry Horse]]
Skills: [[Horseman (1) - Trained]]

Money: 200 CP

## Man-At-Arms

| Name    | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                       Wounds                                                       |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:| :----: |:------:|
| Berwyn    |  `VIEW[{stats[0]}]`   |  `VIEW[{stats[1]}]`   |  `VIEW[{stats[2]}]`   |  `VIEW[{stats[3]}]`   |  `VIEW[{stats[4]}]`   |  `VIEW[{stats[5]}]`   |   `VIEW[{stats[6]}]`  |   `VIEW[{stats[7]}]`  |  `VIEW[{stats[8]}]`     | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |

## Edit Stats

| STAT |            Value            |
| ---- |:---------------------------:|
| INI  | `INPUT[number:stats[0]]` |
| ATT  | `INPUT[number:stats[1]]` |
| STR  |  `INPUT[text:stats[2]]`  | 
| DEF  | `INPUT[text:stats[3]]` |
| DR   |  `INPUT[text:stats[4]]`  |
| AIM  | `INPUT[number:stats[5]]` |
| COU  | `INPUT[number:stats[6]]` |
| DIS  | `INPUT[number:stats[7]]` |
| A    | `INPUT[number:stats[8]]` |
