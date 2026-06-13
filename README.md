# Relics of Rome

**AppADay #038** | Category: S (Spirituality) | Built: 2026-06-13 | Live: 2026-06-14

## What it does

A pilgrimage map of Rome marking fifty churches, basilicas, and sites that hold relics of the saints, fragments of the True Cross, and other objects of Christian veneration. Tap any pin for the story behind the relic, what it is, and the address of the church that holds it.

## Features

- **50 relic sites across Rome**, from St. Peter’s tomb and the four great relics of the basilica to lesser-known stops like San Giovanni in Oleo and the Tre Fontane abbey.
- **Filter by category**: Apostles, Passion Relics, Marian/Nativity, Saints’ Tombs, and My Places.
- **My Places**: tap “+ Add Place,” then tap anywhere on the map to drop a personal pin (a hotel, a restaurant, a meeting point). Name it, add a note, and it’s saved to your phone’s local storage so it’s there next time you open the app. No account, no API, no network call required.
- **Illuminated-manuscript styling**: Cinzel and Crimson Text typefaces, a parchment, maroon, and gold palette, and reliquary-cross markers throughout.
- Built on Leaflet, with the library inlined directly into the page so the map works even when the page is opened from a sandboxed preview with no outside script access.

## How it’s built

Single self-contained `index.html`. Leaflet 1.9.4 (CSS and JS) is inlined in the page; map tiles come from CARTO’s Voyager basemap over OpenStreetMap data. No build step, no external accounts, no API keys.

## Relic sites included

Major basilicas (St. Peter’s, San Paolo fuori le Mura, Santa Maria Maggiore, San Giovanni in Laterano, Santa Croce in Gerusalemme), apostolic relics and martyrdom sites (San Pietro in Vincoli, Santi Apostoli, the Mamertine Prison, San Pietro in Montorio), Passion relics (Santa Croce’s True Cross fragments, the Column of the Scourging at Santa Prassede, the gridiron fragment at San Lorenzo in Lucina, the Domine Quo Vadis footprint stone), and dozens of saints’ tombs and relics across Trastevere, the Aventine, the Caelian Hill, the Esquiline, and out along the Appian Way, including St. Monica, St. Cecilia, St. Lawrence, St. Agnes, St. Philip Neri, St. Frances of Rome, and St. John Paul II.

## Notes

Descriptions use “traditionally venerated as” and similar language where historical attribution is a matter of long-standing devotion rather than documented certainty, consistent with how these sites are generally described.

## Future Updates

- Might be helpful to add mass times at churches where relics are kept to know Catholics could attend mass and non-Catholics know when not to visit so as to not interrupt services.
-----

*Part of [AppADay](https://augustineiacopelli.github.io/appaday/), a one-app-a-day build challenge.*
