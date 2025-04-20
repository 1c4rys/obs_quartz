---
noteType: pf2eMonster
tags: 
statblock: true
statblock-link: "#Azâzêl"
name: Azâzêl
hp: 320
ac: 20
modifier: 
level: 8
modified: 16 February 2025, at 16:18 (EST)
---
### Azâzêl
```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
statblock: true
source: "Homebrew"
name: "Azâzêl"
level: "Creature 8"
rare_02: "Unique"
alignment: "CE"
size: "Gargantuan"
trait_03: "Celestial"
trait_04: "Dragon"
perception:
  - name: "Perception"
    desc: "Perception +18; __darkvision__, __true seeing__;"
languages: "Celestial, Draconic; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +16 (1d20+16); __Athletics__: +20 (1d20+20); "
abilityMods: [6, 2, 5, -1, 4, 3]

abilities_top:
  - name: "Phase Triggers"
    desc: "Azâzêl gains new abilities at 75%, 50%, 25%, and 10% HP. When a phase triggers, all creatures take 2d10 electricity (DC 22 Reflex)."

abilities_mid:
  - name: "Chainburst"
    desc: "⬲ ([[reaction]]); __Trigger__ Azâzêl is hit. __Effect__ 1d12 slashing (DC 22 Reflex) in 20-ft burst."
  - name: "Lightning Teleport"
    desc: "⬻ ([[conjuration]], [[teleportation]]); Azâzêl vanishes and reappears anywhere, dealing 2d6 electricity (DC 22 Reflex) in 10-ft burst."

abilities_bot:
  - name: "Phase 1 (100–75% HP): Shackled Fury"
    desc: |
      - **Skyrend Dive** ⬻ ([[move]]): Flies upward, then crashes for 2d10 bludgeoning (DC 22 Reflex).
      - **Shield Block** ⬲: Reduces damage by 10; knocks attacker prone (DC 22 Reflex).
  - name: "Phase 2 (75–50% HP): Storm of Blame"
    desc: |
      - **Corrupted Chains** ⬻ ([[ranged]]): 1d8+3 slashing + Corrupted 1 (-1 Will, death at 6 stacks).
      - **Thunderstorm Aura** ([[aura|aura 30 ft.]]): 1d4 electricity at start of turn.
  - name: "Phase 3 (50–25% HP): Unshackled Desperation"
    desc: |
      - **Nightingale’s Onslaught**: Quickened (1 extra action for Strikes/Strides).
      - **Heavenly Descent Sweep** ⬺: 3d10 slashing (DC 22 Reflex) in 30-ft cone.
  - name: "Phase 4 (10% HP): Eternal Banishment"
    desc: |
      - **Apocalyptic Lightning Storm** ⬻ (3 actions): Channels for 1 round. On completion, 5d10 electricity (DC 24 Reflex).
      - **Final Chainburst**: On death, 4d10 force damage (DC 22 Reflex) to all.
  - name: "Celestial Anchors (Lair)"
    desc: |
      At initiative count 10:
      <ul class='inner-bullet-list'>
      <li>**Phoenix**: Fire heals Azâzêl.</li>
      <li>**Leviathan**: Difficult terrain (DC 22 Acrobatics).</li>
      <li>**Unicorn**: Fast Healing 10.</li>
      <li>**Kraken**: Pulls creatures 10 ft (DC 22 Fort).</li>
      </ul>

speed: 40 feet, fly 60 feet (hover);

ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__: +18 (1d20+18); __Ref__: +16 (1d20+16); __Will__: +14 (1d20+14);"
health:
  - name: HP
    desc: "320; __Immunities__ critical hits, mental; __Weaknesses__ force 10, corrupted 15;"

attacks:
  - name: Melee
    desc: "⬻ glaive +20 ([[reach|reach 15 feet]]); __Damage__ 1d12+4 slashing + 1d4 force"
  - name: Ranged
    desc: "⬻ chains +18 ([[range|range 30 feet]]); __Damage__ 1d8+3 slashing + Corrupted 1"

spellcasting:
  - name: "Divine Innate Spells"
    desc: "DC 22; __Constant__ __(6th)__ [[true seeing]];"
sourcebook: "ME!"

columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
```

### Encounter
```encounter-table
name: Aasimar Redeemer
creatures:
  - 1: Aasimar Redeemer
```