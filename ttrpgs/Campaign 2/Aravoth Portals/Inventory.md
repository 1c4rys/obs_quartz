---
title: title
draft: false
tags:
  - 
type: portal
faction: 
location: 
world: Aravoth
campaign: Aravoth
date: 2024-08-03
description: Inventory of player characters
publish: true
modified: 09 February 2025, at 16:11 (EST)
---
# [[Inventory]]
## Runes
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  runeslots AS "Energy",
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "rune")
```
%%

| File                                                               | Energy | Level |
| ------------------------------------------------------------------ | ------ | ----- |
| [[Bleeding\|Bleeding]]                     | 5      | 4     |
| [[Energy-Resistant\|Energy-Resistant]]     | 4      | 3     |
| [[Flaming\|Flaming]]                       | 3      | 2     |
| [[Fortification\|Fortification]]           | 4      | 3     |
| [[From Shadow\|From Shadow]]               | 8      | 5     |
| [[Gabriel's Atrocity\|Gabriel's Atrocity]] | 6      | 5     |
| [[Ghost Strike\|Ghost Strike]]             | 6      | 4     |
| [[Ghost Touch\|Ghost Touch]]               | 3      | 2     |
| [[Haniel's Message\|Haniel's Message]]     | 6      | 5     |
| [[Raphael's Burden\|Raphael's Burden]]     | 6      | 5     |
| [[Shadow (Greater)\|Shadow (Greater)]]     | 2      | 3     |
| [[ttrpgs/Campaign 2/Notes/Shadow\|Shadow]]                         | 2      | 3     |
| [[Shifting\|Shifting]]                     | 4      | 3     |
| [[Subtle Dampeners\|Subtle Dampeners]]     | 3      | 1     |

%% DATAVIEW_PUBLISHER: end %%
## Fruits 
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  archetype AS "Archetype", 
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "fruit")
```
%%

| File                                                                 | Archetype         | Level |
| -------------------------------------------------------------------- | ----------------- | ----- |
| [[Azâzêl's Banishment\|Azâzêl's Banishment]] | unique            | 5     |
| [[Azâzêl's Blame\|Azâzêl's Blame]]           | kusarigama        | 5     |
| [[Azâzêl's Fall\|Azâzêl's Fall]]             | glaive            | 5     |
| [[Azâzêl's Freedom\|Azâzêl's Freedom]]       | buckler           | 5     |
| [[Azâzêl's Sins\|Azâzêl's Sins]]             | breastplate       | 5     |
| [[Cloak of Sariel\|Cloak of Sariel]]         | leather armor     | 6     |
| [[Janus's Gift\|Janus's Gift]]               | unique            | 0     |
| [[Nhekaush's Journal\|Nhekaush's Journal]]   | unique            | 0     |
| [[Skyreaver\|Skyreaver]]                     | kukri             | 4     |
| [[Skyking\|Skyking]]                         | greatsword        | 6     |
| [[Tiniathuil\|Tiniathuil]]                   | Elven Curve Blade | 6     |

%% DATAVIEW_PUBLISHER: end %%
## Party
### [[Aule]]
#### Runes
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  runeslots AS "Energy",
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "rune") AND
  owner AND
  contains(owner, "Aule")
```
%%

| File                                                           | Energy | Level |
| -------------------------------------------------------------- | ------ | ----- |
| [[Ghost Strike\|Ghost Strike]]         | 6      | 4     |
| [[Raphael's Burden\|Raphael's Burden]] | 6      | 5     |
| [[Shadow (Greater)\|Shadow (Greater)]] | 2      | 3     |
| [[ttrpgs/Campaign 2/Notes/Shadow\|Shadow]]                     | 2      | 3     |
| [[Subtle Dampeners\|Subtle Dampeners]] | 3      | 1     |

%% DATAVIEW_PUBLISHER: end %%
#### Fruits
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  archetype AS "Archetype", 
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "fruit") AND
  owner AND
  contains(owner, "Aule")
```
%%

| File                                                     | Archetype         | Level |
| -------------------------------------------------------- | ----------------- | ----- |
| [[Azâzêl's Sins\|Azâzêl's Sins]] | breastplate       | 5     |
| [[Tiniathuil\|Tiniathuil]]       | Elven Curve Blade | 6     |

%% DATAVIEW_PUBLISHER: end %%
### [[Makoto]]
#### Runes
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  runeslots AS "Energy",
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "rune") AND
  owner AND
  contains(owner, "Makoto")
```
%%

| File                                           | Energy | Level |
| ---------------------------------------------- | ------ | ----- |
| [[Bleeding\|Bleeding]] | 5      | 4     |
| [[Shifting\|Shifting]] | 4      | 3     |

%% DATAVIEW_PUBLISHER: end %%
#### Fruits
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  archetype AS "Archetype", 
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "fruit") AND
  owner AND
  contains(owner, "Makoto")
```
%%

| File                                                       | Archetype  | Level |
| ---------------------------------------------------------- | ---------- | ----- |
| [[Azâzêl's Blame\|Azâzêl's Blame]] | kusarigama | 5     |

%% DATAVIEW_PUBLISHER: end %%
### [[Nhekaush]]
#### Runes
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  runeslots AS "Energy",
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "rune") AND
  owner AND
  contains(owner, "Nhekaush")
```
%%

| File                                                               | Energy | Level |
| ------------------------------------------------------------------ | ------ | ----- |
| [[Fortification\|Fortification]]           | 4      | 3     |
| [[From Shadow\|From Shadow]]               | 8      | 5     |
| [[Gabriel's Atrocity\|Gabriel's Atrocity]] | 6      | 5     |
| [[Ghost Touch\|Ghost Touch]]               | 3      | 2     |

%% DATAVIEW_PUBLISHER: end %%
#### Fruits
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  archetype AS "Archetype", 
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "fruit") AND
  owner AND
  contains(owner, "Nhekaush")
```
%%

| File                                                               | Archetype     | Level |
| ------------------------------------------------------------------ | ------------- | ----- |
| [[Azâzêl's Freedom\|Azâzêl's Freedom]]     | buckler       | 5     |
| [[Cloak of Sariel\|Cloak of Sariel]]       | leather armor | 6     |
| [[Janus's Gift\|Janus's Gift]]             | unique        | 0     |
| [[Nhekaush's Journal\|Nhekaush's Journal]] | unique        | 0     |

%% DATAVIEW_PUBLISHER: end %%
### [[Turing]]
#### Runes
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  runeslots AS "Energy",
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "rune") AND
  owner AND
  contains(owner, "Turing")
```
%%

| File                                                           | Energy | Level |
| -------------------------------------------------------------- | ------ | ----- |
| [[Energy-Resistant\|Energy-Resistant]] | 4      | 3     |
| [[Ghost Touch\|Ghost Touch]]           | 3      | 2     |
| [[ttrpgs/Campaign 2/Notes/Shadow\|Shadow]]                     | 2      | 3     |

%% DATAVIEW_PUBLISHER: end %%
#### Fruits
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  archetype AS "Archetype", 
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "fruit") AND
  owner AND
  contains(owner, "Turing")
```
%%

| File                                                                 | Archetype | Level |
| -------------------------------------------------------------------- | --------- | ----- |
| [[Azâzêl's Banishment\|Azâzêl's Banishment]] | unique    | 5     |
| [[Skyreaver\|Skyreaver]]                     | kukri     | 4     |

%% DATAVIEW_PUBLISHER: end %%
### [[Umak]]
#### Runes
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  runeslots AS "Energy",
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "rune") AND
  owner AND
  contains(owner, "Umak")
```
%%

| File                                                           | Energy | Level |
| -------------------------------------------------------------- | ------ | ----- |
| [[Flaming\|Flaming]]                   | 3      | 2     |
| [[Haniel's Message\|Haniel's Message]] | 6      | 5     |

%% DATAVIEW_PUBLISHER: end %%
#### Fruits
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  file.link AS "File",
  archetype AS "Archetype", 
  level AS "Level"
FROM "ttrpgs/Aravoth/Notes"
WHERE
  owned = true AND
  type AND
  contains(type, "item") AND
  contains(type, "fruit") AND
  owner AND
  contains(owner, "Umak")
```
%%

| File                                                     | Archetype | Level |
| -------------------------------------------------------- | --------- | ----- |
| [[Azâzêl's Fall\|Azâzêl's Fall]] | glaive    | 5     |

%% DATAVIEW_PUBLISHER: end %%