---
type: system_index
system_name: Status Effect
game: Antiquary
---

# Status Effects

## Purpose

**Status Effect** are modifications to the Players/Enemies stats and abilities

---

## Rules

- Most are stackable, although some are not
- Durations vary from permanent or this encounter only
- Can be gained and removed using cards

---
## List of Status Effects

<!-- QueryToSerialize:
TABLE description as Description
WHERE file.folder = this.file.folder
AND type = "status"
SORT file.name ASC
-->
<!-- SerializedQuery: TABLE description as Description where file.folder = this.file.folder and type = "status" sort file.name asc -->

| File                                                               | Description                                                                                                    |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------- |
| [[Block]]             | Reduces incoming damage by stack amount. Remove an equal amount of stacks                                      |
| [[Brittle]]         | Reduce Block gain by 35%                                                                                       |
| [[Energized]]     | Gain Energy equal to the stack amount at the start of the Players' turn                                        |
| [[Fleeting]]       | Remove all stacks of Fleeting status effects at the beginning of the Players' next turn                        |
| [[Fortify]]         | Gain Block equal to the stack amount at the start of the Players' next turn                                    |
| [[Indomitable]] | Reduces incoming damage to 1. Remove 1 stack at the end of the Players' turn                                   |
| [[Leech]]             | Heal equal to the damage dealt                                                                                 |
| [[Poisoned]]       | Take varying damage at the end of each turn                                                                    |
| [[Prepared]]       | Reduce the cost of the left most card in the Players' hand to 0. Remove 1 stack when discounted card is played |
| [[Rage]]               | Gain Strength equal to damage received                                                                         |
| [[Strength]]       | Increase damage dealt by stack amount                                                                          |
| [[Weak]]               | Reduce damage dealt to enemies by 25%                                                                          |
| [[Wound]]             | Increase unblocked attack damage by stack amount, then remove 1 stack amount                                   |

<!-- SerializedQuery END -->
