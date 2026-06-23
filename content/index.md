---
world: Greywatch
campaign: Ghosts of Saltmarsh redux
publish: true
---
# Sessions
```dataview
LIST
FROM "content/sessions"
```
# Factions
```dataview
LIST
WHERE file.frontmatter.type = "faction"
```
# NPCs
```dataview
LIST
WHERE file.frontmatter.type = "NPC"
```



