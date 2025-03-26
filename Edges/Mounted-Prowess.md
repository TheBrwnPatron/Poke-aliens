---
title: "Mounted Prowess"
icon: ":luggage:"
aliases: "Mounted Prowess"
foundryId: Compendium.ptu.edges.Item.e5w4Szs2uY8PdgNa
tags:
  - Item
---

# Mounted Prowess
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Mounted Prowess
system:
  origin: ''
  effect: >-
    You automatically succeed at Acrobatics and Athletics Checks made to mount a
    Pokémon, and you gain a +3 Bonus to all Acrobatics and Athletics Checks made
    to remain Mounted.
  snippet: ''
  rules:
    - key: FlatModifier
      predicate:
        - check:mount:save
      selectors:
        - skill-athletics
        - skill-acrobatics
      hideIfDisabled: false
      value: 3
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
    - Novice Acrobatics or Athletics
  notes: ''
  free: false
  name: Mounted Prowess
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: Novice Acrobatics or Athletics
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953816
  modifiedTime: 1707761797684
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
