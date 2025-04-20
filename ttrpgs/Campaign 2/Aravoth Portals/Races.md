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
description: Portal of all major races
publish: true
modified: 21 October 2024, at 01:48 (EST)
---
# [[Races]]
There are six races, seven if you include the [[Nexomancy#Automatons|Automatons]]:

%% DATAVIEW_PUBLISHER: start
```dataview
TABLE description as "Description" from "ttrpgs/Aravoth"
WHERE contains(lower(type),"race")
```
%%

| File                                               | Description                                           |
| -------------------------------------------------- | ----------------------------------------------------- |
| [[Automatons\|Automatons]] | Nonorganic, metallic lifeforms created with Nexomancy |
| [[Dwarves\|Dwarves]]       | Short, stocky people from Nidavellir                  |
| [[Elves\|Elves]]           | Tall, long-lived people from the Silver Havens        |
| [[Halflings\|Halflings]]   | Short, tranquil people native to Ophiri & Meridiem    |
| [[Humans\|Humans]]         | Diverse and adaptable people, dominant race           |
| [[Kitsune\|Kitsune]]       | Charismatic, shapechanging people from Kisia          |
| [[Orcs\|Orcs]]             | Proud, strong people from Abaddon                     |
| [[Precursors\|Precursors]] | First inhabitants of Aravoth                          |

%% DATAVIEW_PUBLISHER: end %%

---
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
"This page was last edited on " + modified + "." as "Last Edited"
WHERE file = this.file
```
%%

| Last Edited                                                   |
| ------------------------------------------------------------- |
| This page was last edited on 21 October 2024, at 01:48 (EST). |

%% DATAVIEW_PUBLISHER:  end %%