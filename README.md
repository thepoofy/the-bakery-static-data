## Collection of datasets used by [The Bakery](https://bread.report)

### Mapping of Weapon to YouTube Reviews

See `item_reviews.json`
Data is still compiled by hand.

Data collections and deduplication is done in this google spreadsheet:
https://docs.google.com/spreadsheets/d/1Cl6P1Ak2GVrAmjZvhcrOiikR1dXqBvzeo1Mh4mYMAG8/edit#gid=0


### Mapping of Weapon Archetypes to PvP damage

See `weapon_damage_by_type.json`.
Data is still compiled by hand.

Base weapon damage is collected from the `Massive Breakdown` spreadsheet:
https://docs.google.com/spreadsheets/d/1_6zsM7kzvg0aUT8YtM_-Wg_5K1gKDOlrwfVzutEjq-s/edit#gid=388764678

Weapon perk effects are collected from `The Destiny Data Compendium` spreadsheet:
https://docs.google.com/spreadsheets/d/1WaxvbLx7UoSZaBqdFr1u32F2uWVLo-CJunJB4nlGUE4/edit#gid=1662574278


### Mapping of Weapon Range

See `weapon_range_by_type_v2.json`

Weapon range calculator based upon base data and formulas from this spreadsheet:
https://docs.google.com/spreadsheets/d/1SR7cVCxkZdKA0GvSVbKcWn17KEv71bKXLXA_jt3fOIU/edit#gid=0

Perk effects are compiled by hand from `The Destiny Data Compendium` spreadsheet:
https://docs.google.com/spreadsheets/d/1WaxvbLx7UoSZaBqdFr1u32F2uWVLo-CJunJB4nlGUE4/edit#gid=1662574278


### Bootstrap.json

Not for external use.
The value in this file is incremented when source data in this repository has been updated and verified to work with [The Bakery](https://bread.report).


### Deprecated

`sandbox_perk_info.json`, `perk_details.json`: Used to provide descriptions of perks.  Weapon perk info is now being provided by [Clarity](https://d2clarity.com).

`weapon_reviews.json`:  Replaced by `item_reviews.json`.

`weapon_range_by_type.json`: Did not support perks with multiple tiers of effects and was retired.

