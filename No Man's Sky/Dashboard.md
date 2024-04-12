### Celestial Body Counts:
```dataview
TABLE length(rows) AS Number
GROUP by type AS "Celestial Body"
```
---
### Celestial Type Not Listed:
```dataview
LIST
where contains(Type, null)
```
