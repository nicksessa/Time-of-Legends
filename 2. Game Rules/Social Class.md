---
type: rules
---

## Random Social Class for Characters

| dice: 2d6 | Status                                               |
| --------- | ---------------------------------------------------- |
| 2         | `dice: 1d6` Ex-Slave (1) or Serf (2-6)               |
| 3-4       | Peasant                                              |
| 5-8       | Yeoman                                               | 
| 9-10      | Knight                                               |
| 11        | Lord `dice: [[Social Class#^lordTable]]`             |
| 12        | Aristocrat `dice: [[Social Class#^aristocratTable]]` |
^startingCharacterSocialClass

| Social Class    |
| --- |
| `dice: [[Social Class#^startingCharacterSocialClass]]`    |


| dice: 1d6 | Lord     |
|:---------:| -------- |
|    1-3    | Banneret |
|     4     | Baron    |
|     5     | Viscount |
|     6     | Count    |
^lordTable


| dice: 1d10 | Lord       |
|:----------:| ---------- |
|    1-5     | Marquess   |
|    6-7     | Duke       |
|     8      | Prince     |
|     9      | Grand Duke |
|     10     | Archduke   |
^aristocratTable

## Social Class and Starting Cash

| Social Class    | Starting Money          |
| --------------- | ----------------------- |
| Ex-slave / Serf | `dice: 1d6 * 10` Copper |
| Peasant         | `dice: 3d6 * 10` Copper |
| Yeoman          | `dice: 5d6 * 10` Copper |
| Knight          | `dice: 2d6 * 10` Silver |
| Baronet         | `dice: 3d6 * 5` Silver  |
| Baron           | `dice: 3d6 * 10` Silver |
| Viscount        | `dice: 4d6 * 5` Silver  |
| Count (Earl)    | `dice: 4d6 * 10` Silver |
| Marquess        | `dice: 5d6 * 10` Silver |
| Duke            | `dice: 4d6` Gold        |
| Prince          | `dice: 5d6` Gold        |
| Grand Duke      | `dice: 6d6` Gold        |
| Archduke        | `dice: 10d6` Gold       |
| King            | `dice: 15d6` Gold       |
| Emperor         | `dice: 20d6` Gold       | 


## Random Social Class for Nobility

| Social Class                             |
| ---------------------------------------- |
| `dice: [[Social Class#^npcSocialClass]]` | 


| dice: 1d20 | Social Class |
|:----------:| ------------ |
|    1-6     | Knight       |
|    7-10    | Baronet      |
|   11-14    | Baron        |
|   15-17    | Viscount     |
|     18     | Count        |
|     19     | Marquess     |
|     20     | Duke         |
^npcSocialClass