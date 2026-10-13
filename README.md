# KL in Numbers / KL Dalam Angka

Prototype of a public, no-login data site for Kuala Lumpur, built for the Federal Territories fellowship.

It covers housing, homelessness, city services, floods, getting around, environment, the DBKL budget and population, citywide and for each of KL's 11 parliamentary seats. It's available in English and Bahasa Malaysia.

**All figures are mock data for illustration, except Homelessness.** Homelessness uses real JKM WPKL rescue-operation records from January 2023 to September 2026, reduced to totals before they enter this repo. The figures match the 14 October 2026 briefing, *Pembentangan Analisis Operasi Gelandangan*. No names, ID numbers or individual records are published.

Live: https://aaronagai.com/kl-in-numbers/

## Sources

- Homelessness: JKM WPKL "Profil Operasi dan Orang Papa yang Diselamatkan", January 2023 to September 2026, aggregated (people matched across operations by IC, passport or UNHCR number, then by name and birth year; a person registered twice on one day counts as one pick-up).
- Seat boundaries: DOSM electoral boundaries ([dosm-malaysia/data-open](https://github.com/dosm-malaysia/data-open)), simplified.
- Icons: [Reicon](https://reicon.dev) (MIT).
- Colours follow [bencho.dev](https://bencho.dev). The homelessness heatmap is an original implementation inspired by bencho's Heat map block.

The site is a single `index.html` with no build step.
