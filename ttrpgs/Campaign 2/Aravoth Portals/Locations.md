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
description: Portal of all natural locations
publish: true
modified: 19 April 2025, at 21:37 (EST)
---
# [[Locations]]
All natural locations within [[Aravoth]]: 
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE description as "Description" from "ttrpgs/Aravoth"
WHERE contains(lower(type),"location")
```
%%

| File                                                                           | Description                                                |
| ------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| [[Abaddon\|Abaddon]]                                   | Volcanic region in east Meridiem composed entirely of Orcs |
| [[Cyndra\|Cyndra]]                                     | Former Dawn Kingdom recently annexed by Drachma            |
| [[Dûdâêl\|Dûdâêl]]                                     | First location within Eden                                 |
| [[Eden\|Eden]]                                         | Magical continent that appeared in 2639 TE                 |
| [[Empyr\|Empyr]]                                       | Capital of the Dawn Kingdoms, destroyed                    |
| [[Evemerus\|Evemerus]]                                 |                                                            |
| [[Indigo Strait\|Indigo Strait]]                       | Strait between Meridiem and Ophiri                         |
| [[Isles of the Blessed\|Isles of the Blessed]]         | Automaton-infested islands south of Meridiem               |
| [[Meridiem\|Meridiem]]                                 | The continent in southwestern Aravoth                      |
| [[Nidavellir\|Nidavellir]]                             | Homeland of the Dwarves, deep in the north                 |
| [[Ophiri\|Ophiri]]                                     | The continent in northwestern Aravoth                      |
| [[Pangaia\|Pangaia]]                                   |                                                            |
| [[Pytheae\|Pytheae]]                                   | Drachma fortress in Nidavellir                             |
| [[Realm at the End of Time\|Realm at the End of Time]] | Realm of Death; home of the Forsaken                       |
| [[Tarsis\|Tarsis]]                                     | Desert region in western Ophiri                            |
| [[The Silver Havens\|The Silver Havens]]               | Homeland of the Elves, north of Ophiri and isolationist    |
| [[The Splintered Sea\|The Splintered Sea]]             | Large ocean in the east                                    |
| [[The Wall\|The Wall]]                                 | Large wall built to deter Abaddon                          |

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