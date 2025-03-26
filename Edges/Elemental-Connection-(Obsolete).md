---
title: "Elemental Connection (Obsolete)"
icon: ":luggage:"
aliases: "Elemental Connection (Obsolete)"
foundryId: Compendium.ptu.edges.Item.XxZi60wKIfEl35W9
tags:
  - Item
---

# Elemental Connection (Obsolete)
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Elemental Connection (Obsolete)
system:
  origin: ''
  effect: >-
    Choose an Elemental Type. You gain a +2 bonus to Charm, Command, Guile,
    Intimidate, and Intuition Checks targeting Pokémon of that Type. You may not
    take Elemental Connection if you have the Mystic Senses Edge, and you may
    not take Mystic Senses if you have Elemental Connection.
  snippet: ''
  rules:
    - key: ChoiceSet
      flag: elementalConnection
      adjustName: true
      choices:
        - label: Bug
          value: target:types:bug
        - label: Dark
          value: target:types:dark
        - label: Dragon
          value: target:types:dragon
        - label: Electric
          value: target:types:electric
        - label: Fairy
          value: target:types:fairy
        - label: Fighting
          value: target:types:fighting
        - label: Fire
          value: target:types:fire
        - label: Flying
          value: target:types:flying
        - label: Ghost
          value: target:types:ghost
        - label: Grass
          value: target:types:grass
        - label: Ground
          value: target:types:ground
        - label: Ice
          value: target:types:ice
        - label: Normal
          value: target:types:normal
        - label: Poison
          value: target:types:poison
        - label: Psychic
          value: target:types:psychic
        - label: Rock
          value: target:types:rock
        - label: Steel
          value: target:types:steel
        - label: Water
          value: target:types:water
    - key: FlatModifier
      predicate:
        and:
          - '{item|flags.ptu.rulesSelections.elementalConnection}'
          - or:
              - skill:charm
              - skill:command
              - skill:guile
              - skill:intimidate
              - skill:intuition
      hideIfDisabled: false
      selectors: skill-check
      value: 2
      label: Elemental Connection
  enabled: true
  slug: elemental-connection
  schema:
    version: 0.11
    lastMigration: null
  referenceEffect: ''
  source:
    value: PTR Compendiums
  stackSlugs: false
  keywords:
    - Obsolete
  prerequisites: []
  notes: ''
  free: false
  name: Elemental Connection
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: '-'
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953808
  modifiedTime: 1707826382403
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
