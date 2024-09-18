---
cssclasses:
  - cards
  - cards-cols-5
Source: https://minimal.guide/cards
---

![[YouTube#^myYouTubeWatchList]]

```dataview
TABLE Video-URL as "Video URL"
FROM "04 Vault/YouTube"
WHERE file.name != "YouTube Database"
      AND file.name != "How to be happier in 5 steps - Laurie Santos"
      AND file.name != "HealthyGamerGG"
      AND file.name != "How to make change and learn - Dr K"
      AND file.name != "Let Life Be - The Practice to Transform your Life"
      AND file.name >= "M" AND file.name <= "Z"
SORT file.name ASC
LIMIT 20
```


> [!example] NAV
> ◀️ [[YouTube Video Clips 📽️]] ~ [[NEXT]] ▶️ 

```meta-bind-button
label: Next ➡️
icon: ""
hidden: true
class: ""
tooltip: ""
id: "1"
style: primary
actions:
  - type: open
    link: "[[YouTube Video Clips 📽️ 2]]"

```

```meta-bind-button
label: Previous ⬅️
icon: ""
hidden: true
class: ""
tooltip: ""
id: "2"
style: primary
actions:
  - type: open
    link: "[[YouTube Video Clips 📽️]]"

```

`BUTTON[2]` `BUTTON[1]`
