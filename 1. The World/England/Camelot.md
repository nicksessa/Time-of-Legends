---
type: place
faction: Knights of the Round Table
location: England
description: The King's home.
lord: King Arthur
patronSaint: 
troop-max: 10
troops-retainers: 4
troops-levy: 7
balance-of-power: 2
wealth: 5
wealth-per-turn: 1
dissent: 0
next-mission: Raid
---
# Camelot

## Lord: King Arthur

## Fief

| Fief Attributes  |              Number              |
| ---------------- |:--------------------------------:|
| Force Pool Max   |    `INPUT[number:troop-max]`     |
| Retainers        | `INPUT[number:troops-retainers]` |
| Levy             |   `INPUT[number:troops-levy]`    |
| Balance of Power | `INPUT[number:balance-of-power]` |
| Wealth           |      `INPUT[number:wealth]`      |
| Wealth / Turn    | `INPUT[number:wealth-per-turn]`  | 
| Dissent          |     `INPUT[number:dissent]`      |

---

## Notable Characters Currently at Camelot

```dataview
table description as "Description" from "1. The World/Persons"
WHERE contains(type, "NPC") and contains(location, "Camelot")
SORT file.name ASC
```

## Defense
Between the landscape and the strength of your walls, attacking your holdings would be a costly enterprise. +2 Balance of Power

## Influence
You are a major landed knight, distinguishing yourself at battle or in tournaments.

## Holdings
A scattering of large villages and hamlets. Starting force pool of 2d6+3

> [!NOTE]
> Rolled 7+3 for the starting force pool.

## Rule of Law
Bandits, raiders and outlaws rule the countryside, disrupting trade and generally making a nuisance of themselves. +1 Dissent

## Power
A mix of household retainers, trained soldiers and militiamen. Start with 1d4+1 Retainers, 2d4+1 Levy figures. If a 4 is rolled on any dice, add one additional skill to any figure.

> [!NOTE]
> Rolled 3+1 Retainers and 6+1 Levy

## Starting-wealth
You have the funds to live as dictated by your station. 5 starting wealth, +1 wealth per turn.

## Recent Events
Marriage: You, or a close family member, have managed to find themselves a bride. 
Roll 1d6
  1: Bad match. -1 Wealth a turn, +1 Dissent. 
  2-5:  Happy couple: -1 Dissent. 
  6: Strong Alliance: Gain an additional retainer and 1d4 levy figures.


> [!NOTE] 
> Rolled a 2: Happy couple, -1 Dissent.


## Starting Fief

### Defense

`dice: [[Fief#^fief-defense-table]]|Result`

### Fief Influence

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

`dice: [[Fief#^fief-events-table]]|Result`

### Next Battle

#### Balance of Power A (3+)

`dice: [[Fief#^balanceOfPowerA]]|Result`
`INPUT[text:fief-next-mission]`

#### Balance of Power B (2- to -2)

`dice: [[Fief#^balanceOfPowerB]]|Result`
`INPUT[text:fief-next-mission]`

#### Balance of Power C (-3-)

`dice: [[Fief#^balanceOfPowerC]]|Result`
`INPUT[text:fief-next-mission]`
