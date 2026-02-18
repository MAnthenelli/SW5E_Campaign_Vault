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

## PCs
```dataview
TABLE species, class, AC, passive_perception, max_hp

FROM "Characters"

WHERE type = "character" AND character_type = "PC"

SORT character_type ASC, file.name ASC
```


```dataview
TABLE character_type, level, species, class

FROM "Characters"

WHERE type = "character" AND character_type = "NPC"

SORT character_type ASC, file.name ASC
```