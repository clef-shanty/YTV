up: [[YouTube]]
- See also [[YouTube Database]]

![[YouTube#^myYouTubeWatchList]]

```dataview
TABLE without ID
  Rating AS "Rating",
  Video-URL AS "Video URL",
  file.link AS "File",
  Topics as "Topic",
  Creator as "Creator",
  tags AS "Tags",
  status AS "Status",
  date-added AS "Date Added"
FROM "04 Vault/YouTube"
WHERE file.name >= "0" AND file.name <= "9" 
OR (file.name >= "A" AND file.name <= "L")
AND file.name != "How to be happier in 5 steps - Laurie Santos"
AND file.name != "How to make change and learn - Dr K"
AND file.name != "HealthyGamerGG"
SORT file.name ASC
```


> [!example] NAV
> [[YouTube Videos (L-V)|NEXT]] ▶️