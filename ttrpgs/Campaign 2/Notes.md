---
title: title
draft: false
tags:
  - 
type: 
faction: 
location: 
world: Aravoth
campaign: Campaign 2
owned: false
owner: 
description: ""
publish: false
date: 11 February 2025, at 19:08 (EST)
modified: 11 February 2025, at 19:53 (EST)
---
%%
```dataview
TABLE publish from "ttrpgs/Aravoth/Notes"
WHERE publish=false AND
!contains(type, "rune") 
```
%%
```dataview
LIST length(file.inlinks)
FROM "ttrpgs/Aravoth/Notes"
SORT length(file.inlinks) DESC
LIMIT 50
```