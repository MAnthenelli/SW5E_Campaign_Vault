---
type: character
name: Galen Zullari
species: Chagrian
alignment: Lawful Balanced
class: Operative
level: 5
xp: 6500
credits: 0
str: 13
dex: 14
con: 12
int: 14
wis: 8
cha: 12
initiativeBonus: 3
background: Agent
backgroundFeat: Alert
skillsProficient:
  - Stealth
  - Sleight of Hand
  - Acrobatics
  - Deception
  - Investigation
  - Technology
featureNames:
  - Sharpshooter Mastery
  - "[[Placed Shots]]"
  - Disarming Shot
  - Penetrating Shot
  - Suppressive Shot
  - Assume the Position
  - Sharpshooter Style
  - Skill's Exploit - Aim (Stealth)
equipmentNames:
  - Sniper rifle
  - Combat suit
equippedNames:
  - Sniper rifle
  - Combat suit
backstory: SIS agent in charge of Coruscant Lower Levels
id: 50d7d4f8-7e73-4cb3-b2c7-fa369cc9dbb5
userId: 07de9f3a-e2f8-4ab2-b1bf-43733e56d9ed
builderVersion: 0.7.6
createdAt: 1750987558779
changedAt: 1750990427639
localId: temp-2dsrfz47m
---

```dataview
TABLE file.link AS Character, feat AS Feature, feat.summary AS Summary

FROM "Characters"

FLATTEN featureRefs AS feat

SORT file.name ASC
```