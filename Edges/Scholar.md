---
title: "Scholar"
icon: ":luggage:"
aliases: "Scholar"
foundryId: Compendium.ptu.edges.Item.gfL6Y9zvI5Ub5Ye0
tags:
  - Item
---

# Scholar
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Scholar
system:
  origin: ''
  effect: >-
    You gain a +1 Bonus to Skill Checks with General Education, Medicine
    Education, Occult Education, Pokémon Education, Technology Education, and
    Survival.
  snippet: ''
  rules:
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.skills.generalEd.modifier.mod
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.skills.medicineEd.modifier.mod
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.skills.occultEd.modifier.mod
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.skills.pokemonEd.modifier.mod
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.skills.techEd.modifier.mod
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.skills.survival.modifier.mod
  enabled: true
  slug: ''
  schema:
    version: 0.11
    lastMigration: null
  referenceEffect: ''
  source:
    value: PTR Compendiums
  stackSlugs: false
  keywords: []
  prerequisites:
    - Expert General Education
  notes: ''
  free: false
  name: Scholar
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: Expert General Education
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953797
  modifiedTime: 1707761797684
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
