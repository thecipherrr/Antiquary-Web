---
type: keyword
keyword: true
interacts_with: []
design_status: active
description: Cannot discard / play cards with this keyword
---
## Definition

- Cards with this keyword cannot be played or discarded by natural means

## Rules Clarification

- This keyword can be overridden if the cards allows itself to be played/discarded 

## Used By

```dataview
LIST
FROM "02_AntiquaryGame/02_Cards"
WHERE card_type = "Curse"
```

## System Role

- For negative effects that could brick the Player's hand
- Potential downsides of powerful cards
