---
type: class
game: Antiquary
primary_mechanic: Wounds
secondary_mechanics:
  - Combo 
  - Drawing Cards
setup_speed: Medium
scaling_type: Snowball / Burst
difficulty: Medium / High
burst_potential: High
engine_dependency: Medium
design_status: concept
description: Builds up Wounds on the enemies to deal massive damage later on
---
## Overview

The **Cultist** focuses on building up [[Wound]] stacks on her enemies and utilizing them to gain advantages for herself. They synergize with her cards and allow her to deal devastating damage to her enemies if given ample time to set up. 

She is also armed with an arsenal of cards enabling a combo playstyle centered around her *Wound*stacks, with a secondary focus around card draw and probability manipulation


## Core Mechanics

### Primary Mechanic:

- [[Wound]] 
	- Applied through Cultist cards
	- Stacking modifier
	- Enables synergies of Cultist cards
### Secondary Themes

- Card draws
- Probability and pile manipulation:
	- [[Foretell]]

## Gameplay Identity

- **Setup Speed:** Medium - Slow
- **Scaling Type:** Snowball / Burst 
- **Difficulty:** Medium

**Strengths:**
- Devastating damage if given time to set up
- Deck building is simple

**Weaknesses:**
- Needs time to set up *Wound* stacks
- Needs combo pieces to unlock her win condition


# Card List

## Starter Cards

<!--  QueryToSerialize:
TABLE cost, card_type, tags, exhaust
FROM "02_AntiquaryGame/02_Cards/Cultist"
WHERE type = "card"
AND class = this.file.name
AND rarity = "Starter"
SORT cost ASC
-->
<!-- SerializedQuery: TABLE cost, card_type, tags, exhaust FROM "02_AntiquaryGame/02_Cards/Cultist" WHERE type = "card" AND class = this.file.name AND rarity = "Starter" SORT cost ASC -->

| File      | cost | card_type | tags                                      | exhaust |
| --------- | ---- | --------- | ----------------------------------------- | ------- |
| [[Parry]] | 1    | Skill     | <ul><li>Starter</li><li>Defense</li></ul> | false   |
| [[Stab]]  | 1    | Attack    | <ul><li>Starter</li><li>Attack</li></ul>  | false   |

<!-- SerializedQuery END -->

## Common Cards

<!-- QueryToSerialize:
TABLE cost, card_type, tags, exhaust
FROM "02_AntiquaryGame/02_Cards/Cultist"
WHERE type = "card"
AND class = this.file.name
AND rarity = "Common"
SORT cost ASC
-->
<!-- SerializedQuery: TABLE cost, card_type, tags, exhaust FROM "02_AntiquaryGame/02_Cards/Cultist" WHERE type = "card" AND class = this.file.name AND rarity = "Common" SORT cost ASC -->

| File                   | cost | card_type | tags      | exhaust |
| ---------------------- | ---- | --------- | --------- | ------- |
| [[Cautious Advance]]   | 0    | Skill     | <ul></ul> | false   |
| [[Foretell]]           | 0    | Skill     | <ul></ul> | false   |
| [[Sanguine Spikes]]    | 0    | Attack    | <ul></ul> | false   |
| [[Dodge and Counter]]  | 1    | Skill     | <ul></ul> | false   |
| [[Dance of Knives]]    | 1    | Attack    | <ul></ul> | false   |
| [[Disengage]]          | 1    | Skill     | <ul></ul> | false   |
| [[Eviscerate]]         | 1    | Skill     | <ul></ul> | false   |
| [[Reckless Stab]]      | 1    | Attack    | <ul></ul> | false   |
| [[Sanguine Barrage]]   | 1    | Skill     | <ul></ul> | false   |
| [[Vital Stab]]         | 1    | Attack    | <ul></ul> | false   |
| [[Deflect]]            | 2    | Power     | <ul></ul> | false   |
| [[Dust Pouch]]         | 2    | Attack    | <ul></ul> | false   |
| [[Preparation]]        | 2    | Power     | <ul></ul> | false   |
| [[Sanguine Sensation]] | 2    | Skill     | <ul></ul> | true    |
| [[Sanguine Sacrament]] | 2    | Power     | <ul></ul> | false   |
| [[Sanguine Sense]]     | 2    | Skill     | <ul></ul> | false   |
| [[Swansong]]           | 3    | Skill     | <ul></ul> | false   |
| [[From the Shadows]]   | 4    | Attack    | <ul></ul> | false   |

<!-- SerializedQuery END -->
