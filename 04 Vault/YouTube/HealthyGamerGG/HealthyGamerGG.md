Channel: [[+ HealthyGamerGG]]

``` dataview
TABLE WITHOUT ID
 file.link as "List from Vault",
 (date(today) - file.cday).day as "Days alive"

FROM "04 Vault/YouTube/HealthyGamerGG" 

WHERE file.name != "+ HealthyGamerGG"
AND
file.name != "HealthyGamerGG"

SORT file.name ASC

LIMIT 90
```

