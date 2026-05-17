---
type: keyword
keyword: true
interacts_with: []
design_status: active
description: Temporarily remove card from all piles
---
## Definition
- Temporarily removes a card from all draw piles, making it unusable for the rest of the encounter
- The **Exhausted** card returns to the draw pile at the end of the encounter


## Rules Clarification

- 

## Used By

```dataview
LIST
FROM "02_AntiquaryGame/02_Cards"
WHERE exhaust = true
```


## System Role

- Prevent abuse from a single powerful card/effect