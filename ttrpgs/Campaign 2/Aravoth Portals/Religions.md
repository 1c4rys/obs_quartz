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
description: Portal of all major religions
publish: true
modified: 21 October 2024, at 01:48 (EST)
---
# [[Religions]]
There are many major religions across [[Aravoth]], although most are situated in specific locations:
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE description as "Description" from "ttrpgs/Aravoth"
WHERE contains(lower(type),"religion")
```
%%

| File                                                                 | Description                                                      |
| -------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [[Dawnism\|Dawnism]]                         | Polytheistic language of Dawn Kingdoms, most followed on Aravoth |
| [[Elohim\|Elohim]]                           | Primary religion in Tarsis, similar to Dawnism                   |
| [[Fornsidr\|Fornsidr]]                       | Primary religion of the Dwarves of Nidavellir                    |
| [[Helladism\|Helladism]]                     | Religion followed by most of the Drachmi                         |
| [[Kyushimago religion\|Kyushimago religion]] | The religion of the Kitsune                                      |

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