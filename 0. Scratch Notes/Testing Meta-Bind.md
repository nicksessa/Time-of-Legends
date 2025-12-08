---
my-date: 2025-11-15
my-date2: 11-11-2025
my-time: 15:00
my-editor: |-
  # abc

  ## Heading

  |col1|col2|
  |---|---|
  |fred|flintstone|
image: z_Assets/Images/Archer1.jpg
image-list:
  - z_Assets/Images/ArmoredSkeletonWithSwordAndShield.jpg
my-list:
  - aaa
  - bbb
another-list:
  - xxxx
  - xxxx
  - zzzz
MOVE: M
INI: 1
ATT: 2
STR: 3
DEF: 5
ARMOR: 5
MISSILE: 3
Text1: ""
selectedMonster: ""
list:
  - 1
  - 2
  - 3
index: 0
options:
  - "1"
  - "2"
  - "3"
  - "6"
selected: 1
---

> [!infobox|right]+ Collapsible Infobox
> # Name
> ![[Archer.jpg|cover hsmall]]
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Test | Testing |
> | Test | Testing |
> 
> ###### Stats 2
> | Type | Stat | aaa |
> | ---- | ---- |---|
> | `VIEW[{my-date}]` | Testing | bb|
> | Test | Testing |cc |



## Input Examples

### Date
`INPUT[date:my-date]`
`VIEW[{my-date}]`

### Date Picker
`INPUT[datePicker:my-date2]`
`VIEW[{my-date2}]`

### Time
`INPUT[time:my-time]`
`VIEW[{my-time}]`


### Editor
```meta-bind
INPUT[editor:my-editor]
```


### Image Suggester (Pick 1 Image)
`INPUT[imageSuggester(optionQuery("z_Assets/Images")):image]`
`VIEW[{image}]`

### Multiple Image Suggester (Pick 1 or More Images)
```meta-bind
INPUT[imageListSuggester(optionQuery("z_Assets/Images")):image-list]
```


### inlineSelect

`INPUT[inlineSelect(option(apple), option(banana), option(lemon))]`

### inlineListSuggester
`INPUT[inlineListSuggester(option(abc), option(xxxx), option(zzzz)):another-list]`

### inlineList

`INPUT[inlineList:my-list]`

### inline number

`INPUT[number:ARMOR]`


MOVE: M
INI: 1
ATT: 2
STR: 3
DEF: 5
ARMOR: 5
MISSILE: 3

| Column 1 | Column 2 |
| -------- | -------- |
|   `INPUT[inlineSelect(option(apple), option(banana), option(lemon))]`       |   `INPUT[inlineSelect(option(apple), option(banana), option(lemon))]`     |


%%
### Text Box - with showcase (defaultValue doesn't do shit)
```meta-bind
INPUT[text(class(meta-bind-full-width), defaultValue(Test), placeholder(Enter your text), showcase, title(Enter your text), limit(10)):Text1]
```
%%

### Text Box (without showcase)
```meta-bind
INPUT[text(class(meta-bind-full-width), placeholder(Enter your text), title(Enter your text), limit(10)):Text1]
```


> [!cards]
> **[[Link]]**
> ![Image link|sban htiny ctr](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&w=1200)
> 
> **[[Link]]**
> ![[z_Assets/Images/Grunwald_1410.jpg|sban htiny ctr]]





View Man-at-Arms level: `VIEW[{Man-at-Arms#level}]`

View Ancient Black Dragon level: `VIEW[{Ancient Black Dragon#level}]`

View Adult Blue Dragon level: `VIEW[{Adult Blue Dragon#level}]`

View Spearman level: `VIEW[{Spearman#level}]`

***

Index: `INPUT[inlineSelect(option(0), option(1), option(2)):index]`
```meta-bind-js-view
{index} as index
---
const str = `\`INPUT[number:list[${context.bound.index}]]\``;
return engine.markdown.create(str)   
```


***


Options: `INPUT[inlineList:options]`

```meta-bind-js-view
{options} as options
---
const options = context.bound.options.map(x => `option(${x})`).join(", ");
const str = `\`INPUT[inlineSelect(${options}):selected]\``;
return engine.markdown.create(str);
```

