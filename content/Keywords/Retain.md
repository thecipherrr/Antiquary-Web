---
type: keyword
keyword: true
interacts_with: []
design_status: active
description: Cards with this keyword are not discarded during end of turn
---
## Definition

- Cards with this keyword are not discarded at the end of the Player's turn

## Rules Clarification

- The cards stay in the hand

## Used By

```dataview
LIST
FROM "02_AntiquaryGame/02_Cards"
WHERE retain = true
```

## System Role

- Introduce a way to keep important cards in hand
- Improves consistency of hands