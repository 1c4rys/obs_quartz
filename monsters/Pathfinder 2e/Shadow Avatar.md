---
noteType: pf2eMonster
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/level/8
statblock: true
statblock-link: "#Shadow Avatar"
name: Shadow Avatar
hp: 140
ac: 22
modifier: 16
level: 8
modified: 16 February 2025, at 16:06 (EST)
---
### Shadow Avatar
```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
statblock: true
source: "Custom"
name: "Shadow Avatar"
level: "Creature 8"
alignment: "NE"
size: "Medium"
trait_03: "Incorporeal"
trait_04: "Undead"
trait_05: "Unholy"
perception:
  - name: "Perception"
    desc: "Perception +16; __darkvision__"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +18 (1d20+18); __Stealth__: +22 (1d20+22);"
abilityMods: [3, 4, 0, 0, 3, 0]
abilities_top:
  - name: "Light Vulnerability"
    desc: "Attacks against the Shadow Avatar are treated as magical if made by a creature standing in magical light or wielding an object in magical light."
abilities_mid:
  - name: "Slink in Shadows"
    desc: "The shadow can Hide or end its Sneak in a creature’s or object’s shadow."
  - name: "Steal Shadow"
    desc: "([[divine]]); __Requirements__ The Shadow Avatar hit a living creature with a shadow hand Strike on its previous action. __Effect__ The shadow pulls at the target's shadow, making the creature [[enfeebled|enfeebled 2]] (or enfeebled 3 on a critical hit). This is cumulative with other enfeebled conditions from shadows, to a maximum of enfeebled 4. If this increases a creature's enfeebled value to 3 or more, the target’s shadow is separated from its body, creating 1d4+1 [[shadow|Shadow]] spawn under the Shadow Avatar’s control."
  - name: "Shadow Spawn"
    desc: "When a creature’s shadow is stolen via __Steal Shadow__, 1d4+1 Shadows are created and act immediately after the Shadow Avatar’s turn. They last until destroyed or the encounter ends."
abilities_bot:
  - name: "Shadow Surge"
    desc: "⬺ (1/round) The Shadow Avatar can take an extra action to use its __shadow hand__ attack or to use __Slink in Shadows__."
  - name: "Master of Shadows"
    desc: "⬺ (1/round) The Shadow Avatar can command all of its Shadows to take an immediate action."
speed: fly 30 feet
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__: +10 (1d20+10); __Ref__: +17 (1d20+17); __Will__: +14 (1d20+14);"
health:
  - name: HP
    desc: "140;  __Immunities__ bleed, death effects, disease, paralyzed, poison, precision, unconscious; __Resistances__ all 10 (except [[force]], [[ghost touch]], [[spirit]], or [[vitality]]; double resistance vs. non-magical); __Weaknesses__ light vulnerability;"
attacks:
  - name: Melee
    desc: "⬻ shadow hand +18 ([[finesse]], [[magical]]); __Damage__ 1 (1d12+3) void"
spellcasting:
  - name: "Divine Innate Spells"
    desc: "DC 24; __2nd__ [[darkness]] (at will)"
sourcebook: "_Custom"
```
