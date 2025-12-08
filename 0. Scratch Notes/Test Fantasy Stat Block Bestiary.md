
## Find the Man-at-Arms in the bestiary

```dataviewjs
// change this to your desired substring (case-insensitive)
const nameFilter = "Man";

const monstersAsDvArray = dv
  .array(Array.from(FantasyStatblocks.getBestiary().values()))
  // only those with a CR
  .filter(m => m.cr)
  // only CR = '1'
  .where(m => m.cr == '21')
  // only names containing our filter term
  .filter(m => 
    m.name && 
    m.name.toLowerCase().includes(nameFilter.toLowerCase())
  );

// cap at 20 entries
const limitedMonsters = monstersAsDvArray.slice(0, 20);

dv.table(
  ["Name", "HP", "AC", "CR", "Source"],
  limitedMonsters.map(monster => [
    dv.fileLink(monster.name),
    monster.hp,
    monster.ac,
    monster.cr,
    monster.source
  ])
);
```



## Find the Trolls in the bestiary

```dataviewjs
// change this to your desired substring (case-insensitive)
const nameFilter = "Troll";

const monstersAsDvArray = dv
  .array(Array.from(FantasyStatblocks.getBestiary().values()))
  // only those with a CR
  .filter(m => m.level)
  // only CR = '1'
  .where(m => m.level >= '5')
  // only names containing our filter term
  .filter(m => 
    m.name && 
    m.name.toLowerCase().includes(nameFilter.toLowerCase())
  );

// cap at 20 entries
const limitedMonsters = monstersAsDvArray.slice(0, 20);

dv.table(
  ["Name", "LV", "M", "I", "ATT", "S", "DEF", "DR", "COU", "DIS", "A", "Wounds"],
  limitedMonsters.map(monster => [
    dv.fileLink(monster.name),
    monster.level,
    monster.MOVE,
    monster.stats[0],
    monster.ATT,
    monster.STR,
    monster.DEF,
    monster.DR,
    monster.COU,
    monster.DIS,
    monster.num_ATT,
    monster.wounds
  ])
);
```