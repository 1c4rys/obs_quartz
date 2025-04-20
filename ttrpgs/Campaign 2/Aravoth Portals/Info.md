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
description: Portal of all info
publish: true
modified: 21 October 2024, at 01:48 (EST)
---
# [[Info]]
All documents with information about how [[Aravoth]] functions: 
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE description as "Description" from "ttrpgs/Aravoth"
WHERE contains(lower(type),"info")
```
%%

| File                                                                 | Description                                              |
| -------------------------------------------------------------------- | -------------------------------------------------------- |
| [[1st Epoch\|1st Epoch]]                     | Chronology of the first bit of history                   |
| [[3rd Epoch\|3rd Epoch]]                     | Chronology of the third bit of history                   |
| [[2nd Epoch\|2nd Epoch]]                     | Chronology of the second bit of history                  |
| [[Abominations\|Abominations]]               | Info on the Abominations                                 |
| [[Cosmology of Eynsof\|Cosmology of Eynsof]] | Info on how the universe functions                       |
| [[Edenic Mechanics\|Edenic Mechanics]]       | Info on how Eden functions                               |
| [[Nexomancy\|Nexomancy]]                     | Pseudo-magic form of engineering that created Automatons |

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