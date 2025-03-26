
![[-systems-ptu-css-images-icons-edge_icon.png|150]]

```Item
name: Acrobat
system:
  origin: ''
  effect: Increase your Jump and Long Jump Capabilities by +1 each.
  snippet: ''
  rules:
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.modifiers.capabilities.highJump
      predicate: []
      phase: applyAEs
    - key: ActiveEffectLike
      mode: add
      value: 1
      path: system.modifiers.capabilities.longJump
      predicate: []
      phase: applyAEs
  enabled: true
  slug: acrobat
  schema:
    version: 0.11
    lastMigration: null
  referenceEffect: ''
  source:
    value: PTR Compendiums
  stackSlugs: false
  keywords: []
  prerequisites:
    - Novice Acrobatics
  notes: ''
  free: false
  name: Acrobat
  useCount: 0
type: edge
img: /systems/ptu/css/images/icons/edge_icon.png
effects: []
flags:
  ptu:
    prereqBackup: Novice Acrobatics
_stats:
  systemId: ptu
  systemVersion: 4.1.4
  coreVersion: '12.327'
  createdTime: 1683367953775
  modifiedTime: 1707761797684
  lastModifiedBy: ODt7FhFvbVjW9f1k
folder: null
```
