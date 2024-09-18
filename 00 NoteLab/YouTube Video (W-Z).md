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
WHERE file.name >= "W" AND file.name <= "Z"
AND file.name != "FromSergio"
SORT file.name ASC
```
