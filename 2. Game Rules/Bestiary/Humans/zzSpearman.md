---
layout: Time of Legends NPC
image: z_Assets/Images/KnightWithSpear.jpg
statblock: true
name: Spearman
title: Spearman
level: 1
race: Human
class: Spearman
number-encountered: 1
virtue-level: 1
fate-points: 1
divine-favor: 0
luck-of-the-day: "(1d6): `dice: 1d6`"
wounds: Unwounded
move-rate: Medium
INI: 1
ATT: (1d6 +1)
STR: 2
DEF: (1d6 +3)
TOUGH: 1
DR: 4
ACC: 1d6 +0
R-STR: 0
NUM-ATT: 1
LD: 2d6
stats:
  - 1
  - 1
  - 1
  - 1
  - 5
  - 0
  - 0
  - 1
  - 7
languages: English, Latin
weapons: Spear (+1 DMG), Medium Shield (+2 DEF), Short Sword (+1 DMG)
armor: Chain (DR 4)
background:
  - name: Age
    desc: Young
  - name: Motivation
    desc: Adventure. This character enjoys life on the road.
  - name: Family Ties
    desc: Married, with a son.
  - name: Extended Family
    desc: Next to None.  Family has been reduced to a mere handful.
  - name: Martial Prowess
    desc: None to speak of
  - name: Military Experience
    desc: Fresh from the farm
traits-and-quirks:
  - "* Extremely boring."
  - "* Drunkard."
  - "* Smells funny."
contacts:
  - "* Camp Follower. Woman of the evening, tradesman, family members, crooks, etc"
  - "* Soldier from the same household."
  - "* Bartender."
actions:
  - name: Spear Attack
    desc: "Melee Weapon Attack: (1d6+1): `dice: 1d6+1`  to hit."
  - name: Spear Parry
    desc: "Melee Weapon Defense: (1d6+3): `dice: 1d6+3` to defend."
  - name: Short Sword
    desc: "Melee weapon attack: (1d6+1): `dice: 1d6+1` to hit."
  - name: Short Sword Parry
    desc: "Melee weapon attack: (1d6+3): `dice: 1d6+3` to hit."
health-status: Unwounded
---

### Set Wound Status

`INPUT[inlineSelect(option(Unwounded), option(Shock), option(Light), option(Serious), option(Critical), option(Out of Action)):wounds]`

## Select an image for this character

`INPUT[imageSuggester(optionQuery("z_Assets/Images")):image]`



```statblock
monster: Spearman
```



