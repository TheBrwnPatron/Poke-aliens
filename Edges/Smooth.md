---
title: "Smooth"
icon: ":luggage:"
aliases: "Smooth"
foundryId: Compendium.ptu.edges.Item.JLsJ4Jvqw9NcIZIr
tags:
  - Item
---

# Smooth
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Smooth
system:
  origin: ''
  effect: >-
    You gain +4 Evasion against Moves with the Social keyword, and gain a +2
    Bonus on Save Checks against Rage and Infatuation.
  snippet: ''
  rules:
    - key: FlatModifier
      predicate:
        or:
          - condition:save:rage
          - condition:save:infatuation
      hideIfDisabled: false
      selectors: save-check
      value: 2
  enabled: true
  slug: smooth
  schema:
    version: 0.11
    lastMigration: null
  referenceEffect: ''
  source:
    value: PTR Compendiums
  stackSlugs: false
  keywords: []
  prerequisites:
    - Expert Charm or Focus
  notes: ''
  free: false
  name: Smooth
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: Expert Charm or Focus
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953766
  modifiedTime: 1707826316448
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
