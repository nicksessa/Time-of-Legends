


Roll 1d6:  `dice: 1d6`
Roll 1d6 but don't show the die icon:  `dice: 1d6 |nodice`

Roll 3d4 + 3:  `dice: 3d4 + 3`

Roll 1d12 + 1d10 + 5:  `dice: 1d12 + 1d10 + 5`

Roll Something Complicated:  `dice: 3d4+3d4-(3d4 * 1d4) - 2^1d7`

Roll 1d27: `dice: 1d27`

Roll 4d6 keep highest three: `dice: 4d6kh3`

Roll a d6 and Explode on a 6:  `dice: 1d6!`

Roll a d6 and keep Exploding on a 6:  `dice: 1d6!i`

For those great Warhammer d66 tables: `dice: 1d66%`

For a one time roll that will show the result and remove the dice do this: dice-mod: 3d6 + 4
One shot roll of 3d6 + 4: 17

Use a range: `dice: 1d[25-45]`


| dice:1d% | Result                                 |
| -------- | -------------------------------------- |
| 01–50    | Nothing                                |
| 51–60    | `dice: [[Testing Dice Roller^easy-encounters]]` |
| 61–100   | `dice: [[Testing Dice Roller^hard-encounters]]` |

^encounter

`dice: [[Testing Dice Roller#^encounter]]`

| 1d8 | Encounter       |
| --- | --------------- |
| 1   | Damaged Walls   |
| 2   | Treasure        |
| 3   | Pit Trap        |
| 4   | Troglodytes     |
| 5   | Skeletons       |
| 6   | The Lost Knight |
| 7   | Goblins         |
| 8   | Trolls          |
^easy-encounters

| 1d8 | Encounter       |
| --- | --------------- |
| 1   | Dragon   |
| 2   | Giant        |
| 3   | Vampire        |
| 4   | Death Knight     |
| 5   | Giant Skeleton       |
| 6   | T-Rex |
| 7   | Mind Flayer         |
| 8   | Demon          |
^hard-encounters

Roll 3 times on the Hard Encounter table:   `dice: 3[[Testing Dice Roller^hard-encounters]]`

Sir Fred left town and had an encounter with `dice: [[Testing Dice Roller^easy-encounters]]|Encounter` . 