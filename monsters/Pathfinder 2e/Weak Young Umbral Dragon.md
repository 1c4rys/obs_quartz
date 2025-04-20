---
noteType: pf2eMonster
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/level/7
statblock: true
statblock-link: "#Weak Young Umbral Dragon"
name: Weak Young Umbral Dragon
hp: 115
ac: 22
modifier: 16
level: 7
modified: 16 February 2025, at 16:06 (EST)
---
### Weak Young Umbral Dragon
```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
statblock: true
source: "B2"
name: "Weak Young Umbral Dragon"
level: "Creature 7"
alignment: "NE"
size: "Large"
trait_03: "Shadow"
trait_04: "Dragon"

perception:
  - name: "Perception"
    desc: "Perception +16; __greater darkvision__, __scent (imprecise) 60 feet__"

languages: "Common, Draconic, Shadowtongue"

skills:
  - name: "Skills"
    desc: "__Acrobatics__: +13 (1d20+13); __Athletics__: +16 (1d20+16); __Deception__: +15 (1d20+15); __Intimidation__: +15 (1d20+15); __Nature__: +14 (1d20+14); __Stealth__: +14 (1d20+14); __Survival__: +15 (1d20+15); "

abilityMods: [5, 2, 4, 2, 4, 2]

abilities_top:
  - name: "Attack of Opportunity"
    desc: "[reaction] Jaws only."
  
abilities_mid:
  - name: "Frightful Presence"
    desc: " ([[aura]], [[emotion]], [[fear]], [[mental]]); 60 feet, DC 21."
  - name: "Draconic Momentum"
    desc: "  When the dragon scores a critical hit with a [[Strike]], it recharges its Breath Weapon."
  - name: "Ghost Bane"
    desc: " An umbral dragon’s Strikes affect incorporeal creatures as though they had a ghost touch property rune, and its jaws deal an additional 2d6 force damage to undead."

abilities_bot:
  - name: "Breath Weapon"
    desc: "⬺ ([[necromancy]], [[negative]], [[primal]]); The dragon breathes a blast of darkness that deals 1 (8d6) negative energy in a 30-foot cone (DC 24 basic Reflex save). It can't use Breath Weapon again for 1 (1d4) rounds. **Special**: Undead creatures take 1 (10d6) force damage instead of negative damage."
  - name: "Draconic Frenzy"
    desc: "⬺  The dragon makes two claw [[Strike|Strikes]] and one wing [[Strike]] in any order."

speed: 40 feet, fly 100 feet

ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__: +16 (1d20+16); __Ref__: +14 (1d20+14); __Will__: +16 (1d20+16);"
health:
  - name: HP
    desc: "115;  __Immunities__ negative, paralyzed, sleep;"

attacks:
  - name: Melee
    desc: "⬻ jaws +18 ([[negative]], [[reach|reach 10 feet]]); __Damage__ 1 (2d10+7) piercing plus 1 (1d6) negative"
  - name: Melee
    desc: "⬻ claw +18 ([[agile]]); __Damage__ 1 (2d8+7) slashing"
  - name: Melee
    desc: "⬻ tail +16 ([[reach|reach 15 feet]]); __Damage__ 1 (2d8+7) slashing"
  - name: Melee
    desc: "⬻ wing +16 ([[reach|reach 10 feet]]); __Damage__ 1 (1d8+7) slashing"

spellcasting:
  - name: "Primal Innate Spells"
    desc: "DC 24; __4th__ [[darkness]] (3); Cantrips (4th) [[detect magic]] (at will)"
sourcebook: "_Bestiary 2_, page 96."
```

```encounter-table
name: Weak Young Umbral Dragon
creatures:
  - 1: Weak Young Umbral Dragon
```

