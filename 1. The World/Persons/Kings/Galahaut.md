---
type: NPC
name: Galahaut
location: Surluise
description: King of Surluise
socialClass: King
wounds: None
virtueLevel: 7
tags:
  - king
move: Medium
stats:
  - 5
  - 6
  - 9
  - 6
  - 11
  - 0
  - 8
  - 1
---

# King Galahaut



> [!infobox|right]+ Collapsible Infobox
> # `VIEW[{name}]`
> ##  `VIEW[{description}]`
> |  |  |
> | :----: |
> | ![[KnightWalkingWithTwoHandedSword.jpg\|cover hsmall]] |
> ###### Stats
> |  |  |
> | ---- | :----: |
> | Virtue Level | `VIEW[{virtueLevel}]` |
> | Move | `VIEW[{move}]` |
> |Wounds |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]`|
> 
> ###### Combat Stats
> |  Stat  | Value   | 
> |:---:|:---:|
> | INI | `VIEW[{stats[0]}]` |
> |ATT| `VIEW[{stats[1]}]` |
> |STR| `VIEW[{stats[2]}]` |
> |DEF|`VIEW[{stats[3]}]` |
> |DR|`VIEW[{stats[4]}]` | 
> | AIM  | `VIEW[{stats[5]}]`   |
> | LD  | `VIEW[{stats[6]}]`   |
> | A | `VIEW[{stats[7]}]` |
> ###### Equipment
> `INPUT[textArea:equipment]`


%%
> [!infobox|center]+ Collapsible Infobox
> # `VIEW[{name}]`
> ##  `VIEW[{description}]`
> ![[KnightWalkingWithTwoHandedSword.jpg|cover hsmall]]
> ###### Stats
> |  |  |
> | ---- | :----: |
> | Virtue Level | `VIEW[{virtueLevel}]` |
> | Move | `VIEW[{move}]` |
> |Wounds |`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]`|
> 
> ###### Combat Stats
> |  Stat  | Value   | 
> |:---:|:---:|
> | INI | `VIEW[{stats[0]}]` |
> |ATT| `VIEW[{stats[1]}]` |
> |STR| `VIEW[{stats[2]}]` |
> |DEF|`VIEW[{stats[3]}]` |
> |DR|`VIEW[{stats[4]}]` | 
> | AIM  | `VIEW[{stats[5]}]`   |
> | LD  | `VIEW[{stats[6]}]`   |
> | A | `VIEW[{stats[7]}]` |
> ###### Equipment
> `INPUT[textArea:equipment]`

%%

> [!NOTE | left ]+
> ## Edit Stats
>
> | STAT |         Value          |
> | ---- |:----------------------:|
> | INI  | `INPUT[text:stats[0]]` | 
> | ATT  | `INPUT[text:stats[1]]` |
> | STR  | `INPUT[text:stats[2]]` |
> | DEF  | `INPUT[text:stats[3]]` |
> | DR   | `INPUT[text:stats[4]]` |
> | AIM  | `INPUT[text:stats[5]]` |
> | LD   | `INPUT[text:stats[6]]` |
> | A    | `INPUT[text:stats[7]]` |



%%
## Galahaut

|Name|Virtue|Chivalry|Home|INI|ATT|STR|DEF|DR|AIM|COU|DIS|# ATT|Special Abilities|
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Galahaut|7|270|Surluise|5|6|9|6|11|0|8|8|1||

## Stat Block

| Name        |        INI         |        ATT         |        STR         |        DEF         |         DR         |        AIM         |        LD         |       # ATT        |                                                          Wounds                                                           |
| ----------- |:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| Galahaut | `VIEW[{stats[0]}]` | `VIEW[{stats[1]}]` | `VIEW[{stats[2]}]` | `VIEW[{stats[3]}]` | `VIEW[{stats[4]}]` | `VIEW[{stats[5]}]` | `VIEW[{stats[6]}]` | `VIEW[{stats[8]}]` | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wounds]` |


%%




