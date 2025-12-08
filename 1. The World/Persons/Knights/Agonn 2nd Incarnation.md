---
layout: Time of Legends v02
image: "[[Agonn.webp]]"
name: Agonn (2nd)
type: NPC
faction: Lion
location: Camelot
description: One of Arthur's lesser knights.
hero: true
race: Human
class: Knight
rank:
  - Lion
  - " Regular"
  - " Infantry"
level: 3
virtue-level: 5
point-cost: 42
alias:
statblock: true
tags:
  - Lion
  - Regular
  - Champion
  - Infantry
wound-level: None
stats:
  - M
  - 4
  - 6
  - 7
  - 5
  - 8
  - 0
  - 7
  - 4
  - 1
languages: Latin, French
weapons: Longsword, Dagger
armor: Partial Plate, Medium Shield
horse: Heavy Warhorse
abilities:
exampleProperty: ""
---

%%
```statblock
monster: Agonn (2nd)
```
%%



# Agonn the Ardent

> [!NOTE|right]+ Image
> ![[Agonn.webp\|125]]
 

| [[Stats#M\|M]] | [[Stats#INI\|I]] | [[Stats#ATT\|ATT]] | [[Stats#STR\|S]] | [[Stats#DEF\|DEF]] | [[Stats#DR\|DR]] | [[Stats#AIM\|AIM]] | [[Stats#COU\|COU]] | [[Stats#DIS\|DIS]] | [[Stats#A\|#A]] |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `VIEW[{stats[0]}]` | `VIEW[{stats[1]}]` | `VIEW[{stats[2]}]` | `VIEW[{stats[3]}]` | `VIEW[{stats[4]}]` | `VIEW[{stats[5]}]` | `VIEW[{stats[6]}]`  | `VIEW[{stats[7]}]`  | `VIEW[{stats[8]}]`  | `VIEW[{stats[9]}]` | 

Hero: `INPUT[toggle:hero]`
Level: `VIEW[{level}]`
Virtue Level: `VIEW[{virtue-level}]`
[[Weapons]]: [[Weapons#Longsword|Longsword]], [[Weapons#Dagger|Dagger]]
[[Armor]]: [[Armor#Partial Plate|Partial Plate (DR 6)]]
Rank: `VIEW[{rank}]`
Abilities:  [[Brave]], [[Charismatic Leader]]

| Wound Level  | `INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]`    |
| --- | --- |

%%
Troop Type: `VIEW[{type}]`
%%

%%
Weapons: `VIEW[{weapons}]`
Armor: `VIEW[{armor}]`
%%

***

`INPUT[textArea]`

> [!NOTE | left ]+ Edit Stats
> ***
> | Stat  | Modifier  |
> |---|---|
> | Rank | `INPUT[inlineList:rank]` |
> |Tags | `INPUT[inlineList:tags]` |
> |Level | `INPUT[inlineSelect(option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):level]` |
> |MOVE | `INPUT[inlineSelect(option(S), option(M), option(L)):stats[0]]` |
> |Wound Level|`INPUT[inlineSelect(option(None), option(Shock), option(Light), option(Serious), option(Critical), option(Dead)):wound-level]` |
> |INI| `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):stats[1]]` |
> |ATT| `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):stats[2]]` |
> | STR | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15)):stats[3]]` |
> | DEF | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):stats[4]]` |
> | DR | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15)):stats[5]]` |
> | AIM | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):stats[6]]` |
> |COU | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):stats[7]]` |
> | DIS | `INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10)):stats[8]]` |
> | Num ATT | `INPUT[inlineSelect(option(1), option(2), option(3)):stats[9]]` |
> | Weapons | `INPUT[textArea:weapons]` |
> | Armor | `INPUT[textArea:armor]` |
> ***


%%
`INPUT[inlineSelect(option(Irregular), option(Regular), option(Veteran), option(Elite), option(Champion), option(Special)):rank]`
%%







