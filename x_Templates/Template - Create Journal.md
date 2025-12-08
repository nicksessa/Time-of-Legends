---
type: journal
---

Player Turn Sequence

1. [[Luck of the Day]]
2. Movement and Encounters
3. Comrade and Companion Retention
4. Prayers and Requests
5. Healing

## The Party

```dataview
TABLE description as "Description", level as "Level", stats[0] as INI, stats[1] as ATT, stats[2] as STR, stats[3] as DEF, stats[4] as DR, stats[5] as AIM, stats[6] as COU, stats[7] as DIS, stats[8] as A, wounds as Wounds 
FROM "1. The Party"
WHERE contains(type, "NPC") or contains(type, "PC")
SORT filen.name ASC
```

## Turn XXX

Location: 

Luck of the Day: 
Movement: none
Retainers: 
Prayers and [[Prayers and Requests]]: 
Healing: 
