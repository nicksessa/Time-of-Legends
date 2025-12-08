---
type: place
location: text
name: text
description: text
fief-lord: text
fief-balance-of-power: 0
fief-troop-max: 0
fief-troops-heroes: 0
fief-troops-henchmen: 0
fief-wealth: 0
fief-dissent: 0
fief-next-mission: text
fief-armor: text
fief-weapons: text
fief-horses: text
---


# PLACE

## Lord


## Fief

| Fief Attributes  | Number |
| ---------------- | :------: |
| Force Pool Max   |        |
| Heroes        |        |
| Henchmen             |        |
| Balance of Power |        |
| Wealth           |        |
| Dissent          |        |

---

## Equipment


## Horses


## Notable Characters at this Location

```dataview
table description as "Description" from "1. The World/England" or "1. The Party" or "1. The World/Persons"
WHERE contains(type, "NPC") or contains(type, "PC") and contains(location, "Lothian")
SORT filen.name ASC
```

## Starting Fief

### Defense

`dice: [[Fief#^fief-defense-table]]|Result`

### Influence

`dice: [[Fief#^fief-influence-table]]|Result`

### Holdings

`dice: [[Fief#^fief-holdings-table]]|Result`

### Rule of Law

`dice: [[Fief#^fief-law-table]]|Result`

### Power

`dice: [[Fief#^fief-power-table]]|Result`

### Wealth

`dice: [[Fief#^fief-wealth-table]]|Result`

### Recent Events

`dice: [[Events#^fiefEvents]]|Result`

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




## The Lord's Warband

### Heroes (Retainers)
1: `dice: [[Retinue#^heroTable]]`
2: `dice: [[Retinue#^heroTable]]`
3: `dice: [[Retinue#^heroTable]]`


### Henchmen (Militia)
1: `dice: [[Retinue#^henchmenTable]]`
2: `dice: [[Retinue#^henchmenTable]]`
3: `dice: [[Retinue#^henchmenTable]]`
4: `dice: [[Retinue#^henchmenTable]]`
5: `dice: [[Retinue#^henchmenTable]]`

