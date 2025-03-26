---
title: "Defensive Hacking"
icon: ":luggage:"
aliases: "Defensive Hacking"
foundryId: Compendium.ptu.edges.Item.zixXV4XTysXtm8vK
tags:
  - Item
---

# Defensive Hacking
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Defensive Hacking
system:
  origin: ''
  effect: >-
    You may add your Focus Ranks as additional Damage Reduction while in digital
    battles. You may apply this Damage Reduction to Technology Education
    attacks.
  snippet: ''
  rules:
    - key: FlatModifier
      predicate:
        - tech-attack
      hideIfDisabled: false
      selectors: damage
      value: '@actor.system.skills.focus.value.total'
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
    - Adept Technology Education
    - Novice Focus
    - Datajack Augmentation
  notes: ''
  free: false
  name: Defensive Hacking
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: Adept Technology Education, Novice Focus, Datajack Augmentation
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953792
  modifiedTime: 1707761797684
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
