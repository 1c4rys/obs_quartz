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
description: Portal of all events throughout history
publish: true
modified: 21 October 2024, at 01:48 (EST)
---
# [[Events]]
All events that have occurred throughout the history of the universe:
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE description as "Description" from "ttrpgs/Aravoth"
WHERE contains(lower(type),"event")
```
%%

| File                                                                     | Description                                                               |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| [[Brothers' War\|Brothers' War]]                 | War between Orcs and the Dawn Kingdoms that ended the latter              |
| [[Duel of Giants\|Duel of Giants]]               | War between Orcs and the Dawn Kingdoms that formed the latter             |
| [[Meridiem's Second War\|Meridiem's Second War]] | Mult-year war that led to founding of Esrith                              |
| [[Nexus\|Nexus]]                                 | Event 100,000 years ago that enabled Abominations and Nexusborns to exist |
| [[The Splintering\|The Splintering]]             | Biblical event in Genesis                                                 |
| [[The Sundering\|The Sundering]]                 | \-                                                                        |

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