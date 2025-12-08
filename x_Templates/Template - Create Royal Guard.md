---
type: npc
name: Royal Guard
location:
tags:
rg1_wounds: None
rg2_wounds: None
rg3_wounds: None
rg1_stats:
  - 4
  - "4"
  - 6
  - 4
  - 10
  - "0"
  - 6
  - 4
  - "1"
rg2_stats:
  - 4
  - "4"
  - 6
  - 4
  - 10
  - "0"
  - 6
  - 4
  - "1"
rg3_stats:
  - 4
  - "5"
  - 7
  - 4
  - 10
  - "0"
  - 7
  - 4
  - "1"
abilities:
  - "[[Hard Boiled]]"
  - "[[Fanaticism]]"
  - "[[Brave]]"
cost: 40
---

## Royal Guard
| Name          |          INI           |          ATT           |          STR           |          DEF           |           DR           |          AIM           |          COU           |          DIS           |         # ATT          |                                                            Wounds                                                             |
| ------------- |:----------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| Royal Guard 1 | `VIEW[{rg1_stats[0]}]` | `VIEW[{rg1_stats[1]}]` | `VIEW[{rg1_stats[2]}]` | `VIEW[{rg1_stats[3]}]` | `VIEW[{rg1_stats[4]}]` | `VIEW[{rg1_stats[5]}]` | `VIEW[{rg1_stats[6]}]` | `VIEW[{rg1_stats[7]}]` | `VIEW[{rg1_stats[8]}]` | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):rg1_wounds]` |
| Royal Guard 2 | `VIEW[{rg2_stats[0]}]` | `VIEW[{rg2_stats[1]}]` | `VIEW[{rg2_stats[2]}]` | `VIEW[{rg2_stats[3]}]` | `VIEW[{rg2_stats[4]}]` | `VIEW[{rg2_stats[5]}]` | `VIEW[{rg2_stats[6]}]` | `VIEW[{rg2_stats[7]}]` | `VIEW[{rg2_stats[8]}]` | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):rg2_wounds]` |
| Royal Guard 3 | `VIEW[{rg3_stats[0]}]` | `VIEW[{rg3_stats[1]}]` | `VIEW[{rg3_stats[2]}]` | `VIEW[{rg3_stats[3]}]` | `VIEW[{rg3_stats[4]}]` | `VIEW[{rg3_stats[5]}]` | `VIEW[{rg3_stats[6]}]` | `VIEW[{rg3_stats[7]}]` | `VIEW[{rg3_stats[8]}]` | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):rg3_wounds]` |

Equipment: Sacred halberd / All Exceptional Wounds become KILLED OUTRIGHT. Sacred armor / Immunity (Exceptional Wounds).
Special Abilities: `VIEW[{abilities}][link]`
Note: Royal Guard 3 has [[Fearless]] instead of [[Brave]]

## Edit Stats

| STAT |            Value            | 
| ---- |:---------------------------:|
| INI  | `INPUT[number:rg1_stats[0]]` |
| ATT  | `INPUT[number:rg1_stats[1]]` |
| STR  | `INPUT[number:rg1_stats[2]]` |
| DEF  | `INPUT[number:rg1_stats[3]]` |
| DR   | `INPUT[number:rg1_stats[4]]` |
| AIM  | `INPUT[number:rg1_stats[5]]` |
| COU  | `INPUT[number:rg1_stats[6]]` |
| DIS  | `INPUT[number:rg1_stats[7]]` |
| A    | `INPUT[number:rg1_stats[8]]` |


%% stats: `VIEW[{stats}]`%%

%%
```meta-bind
INPUT[list:rg1_stats]
```
%%
