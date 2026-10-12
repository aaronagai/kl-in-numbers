# KL in Numbers / KL Dalam Angka

Prototype of a public, no-login data site for Kuala Lumpur, built for the Federal Territories fellowship.

It covers housing, homelessness, city services, floods, getting around, environment, the DBKL budget and population, citywide and for each of KL's 11 parliamentary seats. It's available in English and Bahasa Malaysia.

**All figures are mock data for illustration, except Homelessness.** Homelessness uses real JKM WPKL rescue-operation records for 2023–2025, reduced to totals before they enter this repo. No names, ID numbers or individual records are published.

Live: https://aaronagai.com/kl-in-numbers/

## Sources

- Homelessness: JKM WPKL "Profil Operasi dan Orang Papa yang Diselamatkan", 2023–2025, aggregated (people matched across operations by ID number, then name and birth year).
- Seat boundaries: DOSM electoral boundaries ([dosm-malaysia/data-open](https://github.com/dosm-malaysia/data-open)), simplified.
- Icons: [Reicon](https://reicon.dev) (MIT).
- Colours follow [bencho.dev](https://bencho.dev). The homelessness heatmap is an original implementation inspired by bencho's Heat map block.

The site is a single `index.html` with no build step.
