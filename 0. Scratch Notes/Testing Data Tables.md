

Data view table

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, race, level, Role 
from "1. The Party"
where (Race = "Human")
```

## Creatures

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", level, rank, INI, ATT, STR, DEF, DR, COU, DIS, num-ATT
from "2. Game Rules/Bestiary"
where (rank = "Creature")
```


## Find all with the Veteran Rank

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", level, rank, INI, ATT, STR, DEF, DR, COU, DIS, num-ATT
WHERE contains(rank, "Veteran")
SORT file.name ASC
```

## Find all with the Regular Rank

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", level, rank, INI, ATT, STR, DEF, DR, COU, DIS, num-ATT
WHERE contains(rank, "Regular")
SORT file.name ASC
```

## Find all with the Elite Rank

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", level, rank, INI, ATT, STR, DEF, DR, COU, DIS, num-ATT
WHERE contains(rank, "Elite")
SORT file.name ASC
```




## DVL

> [!cards | dvl  ]
> ```dataview
> TABLE WITHOUT ID link(file.name) AS "Character Name", Player, virtueLevel, level, Role 
> from "2. Game Rules/Bestiary"
>where (name = "Squire")
>```


## Dataview

> [!cards | dataview  ]
> ```dataview
> TABLE WITHOUT ID link(file.name) AS "Character Name", Player, virtueLevel, level, Role 
> from "2. Game Rules/Bestiary"
>where (name = "Squire")
>```

## Notion style (Table is in a small window but has scroll bars)
> [!cards | notion  ]
> ```dataview
> TABLE WITHOUT ID link(file.name) AS "Character Name", Player, virtueLevel, level, Role 
> from "2. Game Rules/Bestiary"
>where (name = "Squire")
>```