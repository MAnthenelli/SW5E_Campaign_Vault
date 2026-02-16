---
type: home
name: Home
---
# Campaign Vault Home

- [[Index - Sessions]]
- [[Index - Characters]]
- [[Index - Ships]]
- [[Index - Factions]]
- [[Index - Places]]

```dataview
TABLE character_type, level, species, class

FROM "Characters"

WHERE type = "character" AND character_type = "NPC"

SORT character_type ASC, file.name ASC
```