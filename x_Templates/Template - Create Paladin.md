---
type: npc
name: Paladin
location:
tags:
p1_wounds: None
p2_wounds: None
p3_wounds: None
p1_stats:
  - "3"
  - "4"
  - "5"
  - "3"
  - "7"
  - "0"
  - "5"
  - "3"
  - "1"
p2_stats:
  - "3"
  - "4"
  - "5"
  - "4"
  - "7"
  - "0"
  - "5"
  - "3"
  - "1"
p3_stats:
  - "3"
  - "4"
  - "6"
  - "3"
  - "7"
  - "0"
  - "6"
  - "3"
  - "1"
abilities:
  - "[[Brave]]"
cost: 25
---

## Paladin
| Name      | INI | ATT | STR | DEF | DR  | AIM | COU | DIS | # ATT |                                                            Wounds                                                            |
| --------- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:-----:|:----------------------------------------------------------------------------------------------------------------------------:|
| Paladin 1 |  3  |  4  |  5  |  3  |  7  |  0  |  5  |  3  |   1   | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):p1_wounds]` |
| Paladin 2 |  3  |  4  |  5  |  4  |  7  |  0  |  5  |  3  |   1   | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):p2_wounds]` |
| Paladin 3 |  4  |  4  |  6  |  3  |  7  |  0  |  6  |  3  |   1   | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):p1_wounds]` | 

Equipment: Plate armor. Sacred sword / All Exceptional Wounds are KILLED OUTRIGHT.
Special Abilities: `VIEW[{abilities}][link]`

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:p1_stats[0]]` |
| ATT  | `INPUT[number:p1_stats[1]]` |
| STR  | `INPUT[number:p1_stats[2]]` |
| DEF  | `INPUT[number:p1_stats[3]]` |
| DR   | `INPUT[number:p1_stats[4]]` |
| AIM  | `INPUT[number:p1_stats[5]]` |
| COU  | `INPUT[number:p1_stats[6]]` |
| DIS  | `INPUT[number:p1_stats[7]]` |
| A    | `INPUT[number:p1_stats[8]]` |


%% stats: `VIEW[{stats}]`%%

%%
```meta-bind
INPUT[list:p1_stats]
```
%%
