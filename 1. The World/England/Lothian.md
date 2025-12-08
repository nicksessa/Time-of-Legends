---
type: place
location: England
name: Lothian
description: text
patronSaint: St. Willebald
fief-lord: [[Lot]]
fief-balance-of-power: 0
fief-troop-max: 12
fief-troops-retainers: 3
fief-troops-levy: 0
fief-wealth: 3
fief-dissent: 2
fief-next-mission: text
fief-armor: text
fief-weapons: text
fief-horses: 
  - Cavalry Horse
  - Cavalry Horse
  - Warhorse
  - Warhorse
  - Warhorse
  - Warhorse
---


# Lothian

## Ruled by King Lot


## Fief

| Fief Attributes  | Number |
| ---------------- |:------:|
| Force Pool Max   |   12   |
| Heroes           |   3    |
| Henchmen         |   5    |
| Balance of Power |   0    | 
| Wealth           |   3    |
| Dissent          |   2    |

---

## Equipment


## Horses


## Notable Characters at this Location

```dataview
TABLE description as "Description", type as "Type", level as "Level" 
FROM "1. The World/England" or "1. The Party" or "1. The World/Persons"
WHERE contains(type, "NPC") or contains(type, "PC") and contains(location, "Lothian")
SORT filen.name ASC
```

## The Lord's Warband

### Heroes (Retainers)

| Heroes              |     |
| ------------------- | --- |
| [[Knight Errant]]       | [[Weapon & Armor Tables]]: [[Armor#Scale\|Scale]], [[Armor#Medium Shield\|M. Shield]], [[Weapons#Longsword\|Longsword]], [[Weapons#Battle Axe\|Battle Axe]], [[Weapons#Mace\|Mace]], [[Weapons#Lance\|Lance]], [[Armor#Leather Barded Warhorse\|Leather Barding]], [[Items#Cavalry Horse\|Cavalry Horse]]    |
| [[Knight of the Realm]] | [[Armor#Partial Plate\|Partial Plate]], [[Armor#Medium Shield\|M. Shield]], [[Weapons#Longsword\|Longsword]], [[Weapons#Battle Axe\|Battle Axe]] or [[Weapons#Lucerne Hammer\|Lucerne Hammer]], [[Weapons#Mace\|Mace]], [[Weapons#Lance\|Lance]], Barded [[Items#Warhorse\|Warhorse]]    |
| [[Knight of the Realm]] | [[Armor#Partial Plate\|Partial Plate]], [[Armor#Medium Shield\|M. Shield]], [[Weapons#Longsword\|Longsword]], [[Weapons#Battle Axe\|Battle Axe]] or [[Weapons#Lucerne Hammer\|Lucerne Hammer]], [[Weapons#Mace\|Mace]], [[Weapons#Lance\|Lance]], Barded [[Items#Warhorse\|Warhorse]]    |

### Henchmen (Militia)

| Henchmen    | Number | Equipment                                     |
| ----------- |:------:| --------------------------------------------- |
| [[Bowman]]  |   3    | Regular bow, Short Sword, Padded Jack         |
| [[Crossbowman]] |   3    | Light Crossbow, Short Sword, Padded Jack      |
| [[Men-at-Arms]] |   2    | Spear, Short Sword, Padded Jack, Small Shield |
| [[Men-at-Arms]] |   2    | Glaive, Hand Axe, Padded Jack, Small Shield   |
| Rabble **   |   9    | Club                                          |





### Defense

A lone keep has tamed the wilderness around it, defending a key road or strategic location within your holdings. This might be your seat of power, a secure location from which you can begin regaining control

### Influence

As a minor landed knight, your holdings were acquired either by force, or the generosity of someone of higher status.

### Holdings

A swathe of farmland populated with scattered hamlets and isolated farmhouses. Starting force pool of 2d4+4

### Rule of Law

Your holdings are completely lawless. You have no authority over the land or the people residing on them. +2 Dissent

### Military Power

A couple of loyal household retainers and a warband of part-time warriors. Start with 1d4 retainer figures and 1d4+2 Levy figures.

### Wealth

Your family has little excess. Starting wealth: 3

### Recent Events

Campaign Veterans: Your soldiers are the veterans of numerous conflicts. +1 skill for all figures.

### Next Battle

#### Balance of Power  3+

| Type of Battle                                    | 
| ------------------------------------------------- |
| `dice: [[Fief#^balanceOfPowerA]]\|Result\|nodice` |

#### Balance of Power -2 to +2

| Type of Battle                                    | 
| ------------------------------------------------- |
| `dice: [[Fief#^balanceOfPowerB]]\|Result\|nodice` |

#### Balance of Power -3 to -5

| Type of Battle                                    | 
| ------------------------------------------------- |
| `dice: [[Fief#^balanceOfPowerC]]\|Result\|nodice` |




%%
### Heroes (Retainers)

| Heroes                         | 
| ------------------------------ |
| `dice: [[Retinue#^heroTable]]` |
| `dice: [[Retinue#^heroTable]]` |
| `dice: [[Retinue#^heroTable]]` |


### Henchmen (Militia)

| Henchmen                           | 
| ---------------------------------- |
| `dice: [[Retinue#^henchmenTable]]` |
| `dice: [[Retinue#^henchmenTable]]` |
| `dice: [[Retinue#^henchmenTable]]` |
| `dice: [[Retinue#^henchmenTable]]` |
| `dice: [[Retinue#^henchmenTable]]` |

%%

