---
type: NPC
name: Lady Lynet
location: Scotland
faction:
class: Lady
enchantress: Y
virtue-level: 3
seduction: -2
beauty: 6
description: A beautiful enchantress.
---

| Attribute   |         Value          |
| ----------- |:----------------------:|
| Name:       |     `VIEW[{name}]`     |
| Enchantress | `VIEW[{enchantress}]`  |
| Virtue      | `VIEW[{virtue-level}]` |
| Seduction   |  `VIEW[{seduction}]`   |
| Beauty      |    `VIEW[{beauty}]`    |
| Location    |   `VIEW[{location}]`   |


# Service Rewards

|Gifts | Result|
|---|---|
|1|+1 TOUGH|
|2|+1 TOUGH|

|Favor|
|---|
|Garter 5|

%%
[[Lady in Service Rewards]]
## Random Service Reward Generator

If a random lady is chosen, roll on the following tables to determine virtue, gifts and favors.

| Gifts | Result |
| ----- | ------ |
| 1     | `dice: [[Lady in Service Rewards#^serviceGiftTable]]\|Gifts` |
| 2     | `dice: [[Lady in Service Rewards#^serviceGiftTable]]\|Gifts` |

| Favor                                                  |
| ------------------------------------------------------ |
| `dice: [[Lady in Service Rewards#^favorTable]]\|Token / Re-Rolls` |


## Virtue Level

| Roll 1d6 | Virtue Level | Number of Gifts |
|:--------:|:------------:|:---------------:|
|    1     |      1       |        1        |
|    2     |     2-3      |        2        |
|    3     |     4-5      |        2        |
|    4     |     6-7      |        2        |
|    5     |     8-9      |        2        |
|    6     |      10      |        3        |

## Service Gifts

| Roll 1d6 |     Gifts     |
|:--------:|:-------------:|
|    1     |    +1 ATT     |
|    2     |    +1 DEF     |
|    3     |    +1 STR     |
|    4     |   +1 TOUGH    |
|    5     | +1 COU or DIS |
|    6     | +1 Virtue LV  | 
^serviceGiftTable


## Favors

| Roll 1d6 | Token / Re-Rolls |
|:--------:|:-----------------:|
|    1     |    Veil      1    | 
|    2     |   Wimple     2    |
|    3     |   Kirtle     3    |
|    4     |   Girdle     4    |
|    5     |   Garter     5    |
|    6     |   Tress      6    |
^favorTable


%%