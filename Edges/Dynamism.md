---
title: "Dynamism"
icon: ":luggage:"
aliases: "Dynamism"
foundryId: Compendium.ptu.edges.Item.XCYP5vlWl3u3s7LS
tags:
  - Item
---

# Dynamism
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Dynamism
system:
  origin: ''
  effect: Your initiative is increased by your Guile Rank.
  snippet: ''
  rules:
    - key: FlatModifier
      predicate: []
      hideIfDisabled: false
      selectors: initiative
      value: '@actor.system.skills.guile.value.total'
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
    - Novice Guile
  notes: ''
  free: false
  name: Dynamism
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: Novice Guile
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953810
  modifiedTime: 1707761797684
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
