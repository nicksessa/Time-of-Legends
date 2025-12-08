---
type: rules
---

# Military Campaigns

This is an abstract way to handle military campaigns using a few dice rolls.

First, determine the size of the army you are fighting with and then determine your opponent's army.

## Determine Number of Regiments

| Regiment Type | Number of Regiments |
| --- | :---: |
| Infantry | `dice: 1d6+1` |
| Cavalry | `dice: 1d6-4` |


Each regiment has 6 companies.
*Optional* Each regiment has 1d4+2 companies.

or

|Roll 1d6|Number of Companies|
|:---:|:---:|
|1|3|
|2|4|
|3|4|
|4|5|
|5|5|
|6|6|

An army with 3 full infantry regiments will have 18 companies.

## Types of Companies in each Regiment

### Infantry

| dice: 1d6 | Infantry Type |
| :---: | :---: |
| 1 | Artillery/Engineers \* |
| 2 | Crossbowmen |
| 3 | Bowmen |
| 4 | Peasant Militia |
| 5 | Regular |
| 6 | Dismounted Knights |
^infantryType

Random Infantry Type: `dice: [[Military Campaigns#^infantryType]]`

\* **Note:** Max of 2 Artillery/Engineer companies per regiment.  If you roll more than two, roll again until you get something other than a one. Or, substitute Regular troops on all subsequent rolls of a one.

### Cavalry

|dice: 1d6|Cavalry Type|
|:---:|:---:|
|1-5|Regular Cavalry|
|6|Knights|
^cavalryType

Random Cavalry Type: `dice: [[Military Campaigns#^cavalryType]]`

**Example:** To determine the type of companies in a single Regiment of Infantry, roll 1d6, six times.  (5, 4, 2, 4, 4, 6)  Therefore, this infantry regiment has 1 Regular, 3 Peasant, 1 Crossbow and one group of dismounted knights.

Now determine the strength of the army by totaling up all the companies.  Use the following modifiers:

* All companies of knights count double
* In Battles, all cavalry count double
* In Sieges, Artillery/Engineers count double

Here is a sample army that has 3 full strength Infantry regiments and 1 Cavalry regiment.

### Infantry Regiment 1

| Type                 | Strength        |
|----------------------|:---------------:|
| Knights (Dismounted) | 2               |
| Regular              | 1               |
| Peasant Militia      | 1               |
| Peasant Militia      | 1               |
| Crossbowmen          | 1               |
| Artillery/Engineers  | 1 (if siege: 2) |

Total Strength: 7  (Siege: 8)

### Infantry Regiment 2

| Type                 | Strength |
|----------------------|:--------:|
| Knights (Dismounted) | 2        |
| Knights (Dismounted) | 2        |
| Peasant Militia      | 1        |
| Peasant Militia      | 1        |
| Bowmen               | 1        |
| Crossbowmen          | 1        |

Total Strength: 8 

### Infantry Regiment 3

| Type                 | Strength        |
|----------------------|:---------------:|
| Knights (Dismounted) | 2               |
| Knights (Dismounted) | 2               |
| Knights (Dismounted) | 2               |
| Knights (Dismounted) | 2               |
| Regular              | 1               |
| Artillery/Engineers  | 1 (if siege: 2) |

Total Strength: 10  (Siege: 11)

### Cavalry Regiment 1

| Type            | Strength               |
|-----------------|:----------------------:|
| Knights         | 2                      |
| Knights         | 2                      |
| Regular Cavalry | 1 (2 in field battles) |
| Regular Cavalry | 1 (2 in field battles) |
| Regular Cavalry | 1 (2 in field battles) |
| Regular Cavalry | 1 (2 in field battles) |

Total Strength: 8  (Battle: 12)

**Total Army Strength:** 33

**Total Army Strength (Battle):** 37

**Total Army Strength (Siege):** 35

### Roll for the type of campaign:

| Roll | Situation           |
|:----:|---------------------|
| 1    | Siege\*             |
| 2    | Battle              |
| 3    | Under Siege         |
| 4    | Repeated Skirmishes |
| 5    | Attack              |
| 6    | Battle              |

\* **Note:** Sieges were often comical affairs at least initially. The besieging army would ride around the city walls hurling insults, then have a feast, celebrations, playing music through the night, running races, hold tournaments, and hang animals in effigy; all for psychological effect.

Add up the army strength of the opposing army.

Each Campaign takes three rounds to resolve. Each army then rolls 2d6 and then adds their army strength to that roll.  Characters who have any sort of Strategy skill can then attempt to make a *Brilliant Maneuver*.  A character with skills related to Strategy or Leadership can roll a d6.  A roll of a 6 is a success.  If a character has their Leadership skill greater than 8, gain a +1 to that roll.

Success means an additional +1 to the army strength which is modified by the rank of the character making the roll.

For example, if a PC Captain were to make a successful Strategy roll, the total army strength would be increased by +2.  One for the roll and one for being a Captain.  (Since each company is commanded by a Captain, It’s probably not a good idea to roll for each NPC captain since this would lead to a ton of extra rolls.  Just assume that they all cancel each other out and only use PC’s for this roll.)

| Rank                        | Addition to Army Strength |
|-----------------------------|:-------------------------:|
| Captain / Knight Banneret   | +1                        |
| Major or Lt Colonel / Baron | +2                        |
| Colonel  / Duke             | +4                        |
| Brigadier and Above / King  | +6                        |

### Desperate Attack

The leader of the army can make a Desperate Attack which will add a +1 to the Battle Score at the cost of one company.

---

Once the totals are done, subtract the lower army total from the higher.  The difference is the number of companies that the loser lost in the phase of the campaign.  If a tie, both sides lose one company.  This process is repeated for each of the three phases of the campaign.  The side who lost the least number of companies is the winner of the campaign.

Companies lost are rolled randomly.  If any player characters are in a company that was destroyed, they are captured or can attempt a Bold Escape.  If a Bold Escape is attempted, roll on the following table until the character escapes, is captured again or killed/taken out of action.

## Bold Escape

| Roll d12 | Result                      |
|:--------:|-----------------------------|
| 1        | Captured                    |
| 2        | Captured                    |
| 3        | Encounter - Hard            |
| 4        | Encounter - Medium          |
| 5        | Encounter - Easy            |
| 6        | Light Wound                 |
| 7        | Light Wound                 |
| 8        | Light Wound                 |
| 9        | Light Wound                 |
| 10       | Escape with a Serious Wound |
| 11       | Escape with a Light Wound   |
| 12       | Escape                      |

---

## Personal Results of a Campaign

When on Campaign, a PC must roll for the possibilities of injury, special events, booty, field promotion, and decoration.

Characters with horses need to state if they are bringing them or not.  Members of Cavalry regiments must of course bring their horses.

During each of the three encounters of the Campaign, characters must roll for injury and special events.  All characters must decide how they are going to act in each phase of the encounters prior to determining the results.  Options are: cowardly, average, heroic.  Chance of injury is rolled on 2d6 and modified by Rank, company type, attitude and the results of that encounter.

| Rank        | Modifier |
|-------------|:--------:|
| Sergeant / Man-at-Arms    | -1       |
| Lieutenant / Knight Bachelor  | -2       |
| Captain / Knight Banneret    | -3       |
| Baron / Major       | -4       |
| Duke / Lt. Colonel | -4       |
| King / Colonel     | -5       |

### Company Type

| Company Type | Modifier |
|--------------|:--------:|
| Knights      | +1       |
| Cavalry      | +1       |
| Artillery    | -1       |

### Attitude

| Attitude | Modifier |
|----------|:--------:|
| Cowardly | -4       |
| Heroic   | +4       |

### Result of the Encounter

| Result  | Modifier |
|---------|:--------:|
| Victory | -4       |
| Loss    | +4       |

Once the total of the roll and modifiers is computed, consult the injury table below:

## Personal Injury Table

| Modified Roll | Result                                 |
|:-------------:|----------------------------------------|
| 7 or less     | No injury                              |
| 8             | Cuts & bruises (1 pt damage)           |
| 9-10          | Minor arrow wound (Light Wound)        |
| 11            | Minor sword wound (Light Wound)        |
| 12-13         | Minor polearm wound (Light Wound)       |
| 14            | Minor crossbow bolt wound (Light Wound) |
| 15-16         | Serious ax wound (Serious Wound)              |
| 17            | Serious sword wound (Serious Wound)           |
| 18-19         | Serious polearm wound (Serious Wound)         |
| 20-21         | Serious wound from something big (Critical Wound) |

Immediately after rolling for injury, roll for special events; there is no time for rest or healing.  The chance for special events is also rolled on 2d6 and modified by Rank, company type, attitude and Brilliant Maneuvers.  There are three special event tables, one for victory, draw and loss.  The modifiers are shown below:

### Rank

| Rank            | Mod |
|-----------------|:---:|
| Captain / Knight Banneret        | -1  |
| Major/Baron and above | -2  |

### Attitude

| Attitude | Mod |
|----------|:---:|
| Cowardly | -4  |
| Heroic   | +4  |

### Company Type

| Company Type | Mod |
|--------------|:---:|
| Elite        | +2  |
| Knights      | +1  |
| Cavalry      | +1  |
| Artillery    | -3  |

+2 if the character has made a Brilliant Maneuver this encounter.

### Special Event Table - Victory

| Modified Roll | Special Event |
|:---:|---|
| 8 or less | No special event |
| 9 | Personal Encounter with enemy footsoldier; character must fight one-on-one, at close range with an enemy footsoldier. |
| 10 | Personal Encounter with a single mounted opponent; character must fight one-on-one, at close range with an mounted Man-at-Arms. |
| 11-12 | Fight to gain strategic position; character takes part in an attack on an enemy position; this includes a Personal Encounter with a footsoldier, as listed above, and another roll on the injury table. |
| 13 | Personal Encounter with an enemy Knight. The Character must fight one-on-one, at close range with an enemy Knight.  If reduced to half hit points or less, roll 1d6.  On a 1-5 the Character is offered the chance to surrender.  On a roll of a 6, the Knight fights to the death. |
| 14-17 | Chance to take the enemy flag. This includes a Personal Encounter with a knight and two more rolls on the injury table. |

### Special Event Table - Draw

| Modified Roll | Special Event |
|:---:|---|
| 9 or less | No special event |
| 10-11 | Personal Encounter with enemy footsoldier; character must fight one-on-one, at close range with an enemy footsoldier. |
| 12-13 | Personal Encounter with a single mounted opponent; character must fight one-on-one, at close range with a mounted Man-at-Arms. |
| 14-17 | Personal Encounter with an enemy Knight. The Character must fight one-on-one, at close range with an enemy Knight.  If reduced to half hit points or less, roll 1d6.  On a 1-5 the Character is offered the chance to surrender.  On a roll of a 6, the Knight fights to the death. |

### Special Event Table - Loss

| Modified Roll | Special Event |
|:---:|---|
| 7 or less | No special event |
| 8-10 | Personal Encounter with enemy footsoldier; character must fight one-on-one, at close range with an enemy footsoldier. |
| 11-12 | Personal Encounter with a single mounted knight; character must fight one-on-one, at close range with an enemy knight. |
| 13 | Surrounded! Character must fight his way through an enemy footsoldier, or be captured. |
| 14 | Fight to hold a strategic position. Character takes part in a desperate defense; this includes a Personal Encounter with an enemy footsoldier, and another roll on the injury table. |
| 14-17 | Chance to regain your flag! The character attempts to regain his captured flag; This includes a Personal Encounter with a knight and two more rolls on the injury table. |

After special events, characters who are badly wounded are taken from the field.  All others go on to the other encounters and regain 3 hit points from aid from field surgeons.

After all three encounters are over, including injury and special events, roll for booty, field promotion and decoration.

### Captured Enemy Rank
| Roll 2d6 | Enemy's Rank     |
|:--------:|------------------|
| 2-6      | Knight Bachelor  |
| 7-8      | Knight Banneret  |
| 9        | Baron            |
| 10       | Count            |
| 11       | Duke             |
| 12       | King             |

### Ransom

Fate of Captured Soldiers and Sergeants

| Roll 2d6 | Fate                       |
|:--------:|----------------------------|
| 2-6      | Executed                   |
| 7-8      | Imprisoned 1d3 years       |
| 9-10     | Imprisoned 1d6 years       |
| 11-12    | Pressed into enemy service |

Knight Bannerets and higher ranks will be ransomed automatically.

| Rank              | Ransom |
| ----------------- |:------:|
| Soldier(Sergeant) |  150   |
| Knight Bachelor   |  150   |
| Knight Banneret   |  200   |
| Baron             |  300   |
| Viscount          |  400   |
| Count             |  500   |
| Marquess          |  750   | 
| Duke              |  1000  |
| King              | 10000  |

---

### Booty
Booty (treasure) is a 2d6 roll plus modifiers:

#### Rank Modifier

| Rank               |Modifier |
|--------------------|:---:|
| Sergeant           | +1  |
| Knight Bachelor    | +2  |
| Knight Banneret    | +3  |
| Baron              | +4  |
| Count              | +5  |
| Duke               | +6  |
| King               | +7  |

#### Company Type Modifier

| Company Type    | Modifier |
|-----------------|:--------:|
| Engineer        | -3       |
| Archer/Crossbow | -1       |
| Mounted         | +1       |
| Knight          | +2       |

#### Attitude Modifier

| Attitude                   | Modifier |
|----------------------------|:--------:|
| For each Cowardly attitude | -3       |
| For each Heroic attitude   | +1       |

#### Type of Campaign Modifier

| Type of Campaign | Modifier |
|------------------|:--------:|
| Seige            | +3       |
| Under seige      | -3       |
| Skirmish         | -2       |

#### Special Event Modifier
| Special Event                                 | Modifier |
|-----------------------------------------------|:--------:|
| Character fought to gain a strategic position | +1       |


### Loot

| Modified Roll | Booty                                           |
|:-------------:|-------------------------------------------------|
| 6 or less     | Nothing                                         |
| 7             | Set of Horse Barding                            |
| 8             | 20 SP                                           |
| 9             | Knightly Weapon(longsword, bec de corbin, etc.) |
| 10            | Missile weapon                                  |
| 11            | Set of Armor (Partial Plate, Full Plate)        |
| 12            | 100 SP                                          |
| 13            | Set of Horse Barding                            |
| 14            | 150 SP                                          |
| 15            | Set of Horse Barding                            |
| 16            | 300 SP                                          |
| 17            | 400 SP                                          |
| 18            | 500 SP                                          |
| 19            | 600 SP                                          |
| 20            | 700 SP                                          |
| 21            | 800 SP                                          |
| 22            | 1000 SP                                         |
| 23            | 1200 SP                                         |
| 24            | 1400 SP                                         |
| 25            | 1600 SP                                         |
| 26            | 1800 SP                                         |
| 27            | 2000 SP                                         |
| 28            | 2200 SP                                         |
| 29            | 2500 SP                                         |
| 30            | 3000 SP                                         |


### Field promotions
Any character who performs a Brilliant Maneuver or takes the Heroic attitude for all three Campaign phases can roll to be knighted.  On above 4+ he is knighted.  If already a knight, then he is awarded a small manor.

Decorated by the King:
If a character does any of the three, he goes up in rank and level.

1. Makes a Brilliant Maneuver
2. Takes the Heroic attitude in all three campaign phases
3. Receives a serious or critical wound
4. Fought to gain or hold a Strategic Position
5. Taken the enemy flag or retaken and held his own flag

### Max Garrison Strength per Stronghold

| Type            | Max Troops |
|-----------------|:----------:|
| Small Mannor    | 15         |
| Medium Mannor   | 20         |
| Border Castle   | 25         |
| Baronial Castle | 50         |


---

### Ideas for Additional Field Events

|Roll|Result|
|:---:|---|
| 1 | Capture the Flag |
| 2 | A Wanted foe |
| 3 | Death From Above. The area the character is in is being pelted with stones, ballista bolts, flaming debris, bodiless heads and/or headless bodies.  Roll 1d6 to determine how many things hit the area, then for each, roll a d6.  On scores of 5+ the character is hit by STR d6 debris. |
| 4 | Fire in the Camp!  Either by sabotage or accident, a fire has broken out in camp.  The character(s) must put it out before it spreads.  Roll a d6 for the number of fires in the camp.  Then roll a d6-1 (minimum of 1) for the level of each fire.  This is the target number that needs to be rolled to put out that fire.  Each turn there is a 1 in 6 chance that each fire spreads. |
| 5 | Assume Command. A captain, lieutenant, sergeant, or some other commander is dead or incapacitated.  It’s up to one of the characters to take command in order to prevent disaster. [1] Artillery Commander, [2] Militia Commander, [3] Archers [4] Sergeant, [5] Lieutenant, [6] Captain. Make at least two out of three Leadership tests to prevent the rout! |
| 6 | A Worthy Foe.  See the other encounters above. |
| 7 | Innocents in Peril.  (1) In the midst of battle, you find 1d4 Children hiding under a wagon.  (2) 2d6 civilians are being dragged away by the enemy. (3) After a warrior’s helm has been knocked off, you recognize that it is one of your allies’ kids. |
| 8 | Hold the Line!  3d6 Enemies are about to break through your line or breach the wall you are guarding.  You have with you 2d6 allied soldiers. |
| 9 | A Friend in Need. One of your friends has been cut off from his unit and is surrounded by 2d6 enemies.  Can you get to him in time? |
| 10 | Spooked! Siege weapons, fire, foul weather, etc have spooked the [1] horses, [2] dogs [3] supply wagon |
| 11 | It Might Be Time to Leg It.  The soldiers with the characters are in low spirits after [1] death of a captain or [2] long drawn out siege, etc.  Can the characters rally them? |
| 12 | Traitors! In the middle of battle, 2d6 traitors hired by the character’s enemies, have taken this opportunity to ambush them in an [1] Old barn, [2] desolate ravine, [3] dry riverbed, [4] burned out building.   |
| 13 | The Bear Pit.  In the midst of the heat of the battle, the characters are assaulted by seemingly endless waves of enemies.  2d6 enemies start and after the 2nd round of combat, roll a d6.  On a 5+ an additional 1d4 join battle.  If all enemies are defeated and no new reinforcements arrive, the battle is won.   |
| 14 | Behind Enemy Lines |
| 15 | Right Place, Right Time |
| 16 | Fall Back! |
| 17 |  |
| 18 |  |
| 19 | It’s Raining Arrows!  An arrow storm descends upon the character’s position.  Take 1d6 STR 4 hits. |
| 20 | Suicide Mission.  Either volunteer for the mission or run for it!  If you run for it, roll a d6.  On a 4+ you make it out alive.  Otherwise, the character takes 2 STR 4 wounds.  If the character volunteers for the mission, roll a d6.  On a [1-5] they die in glorious battle, defending a bridge, hill, tower, etc.  On a 6, they survive and are [1-3] captured or [4-6] left for dead. |

