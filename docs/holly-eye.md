# World — Holly Eye

The **World** door in HollyEarth opens **Holly Eye**, a planetary 3D view with live public data layers.

> **Holly Eye is a third-party integration, not HollyEarth's own technology.**
> It is the open-source application **God's Eye View** by **Bilawal Sidhu** (stated licence: MIT), run as a separate application at a pinned version with HollyEarth integration patches and interface skin, and connected to HollyEarth by a door and a way back to the Riga Twin.

Screens: **[Holly Eye gallery](gallery/HOLLY_EYE.md)**.

## Status

| Part | Status | Notes |
|---|---|---|
| World door in HollyEarth | `WORKING` | Opens Holly Eye, or says plainly that it is not running and how to start it |
| Planetary view — 3D globe and 3D cities | `BETA` | Photorealistic 3D tiles or OpenStreetMap on a 3D globe; first-view chooser, display options, eight visual styles, location search, data-attribution list |
| World layers | `WORKING` (14 layers) | Live flights, military flights, earthquakes, satellites, space missions, CCTV (`BETA`), radio, bikeshare, live AIS vessels, mapped installations, datacenters, dams, NASA FIRMS active fires; street traffic is simulated without a live feed (`PROTOTYPE`) |
| Space & satellites | `WORKING` | Satellites from CelesTrak orbital elements, space missions from Launch Library 2 |
| Scenes | `BETA` | Scripted camera tours combining layers and styles |
| Context | `BETA` | Nearest contacts and space missions around the camera |
| Voice commands ("Ask Holly") | `PROTOTYPE` | Push-to-talk map commands with a cost meter; no voice provider configured in this build; when enabled, internal use only and paid speech services |
| HollyEarth data inside Holly Eye | `FUTURE` | Holly Eye holds no Riga, graph or case data |

## Limits

- English only; opens over Austin by default (other places through search or a share link).
- Depends on third-party map tiles, data feeds and keys; each layer degrades on its own without them.
- Map and imagery credits are shown in the application and kept in every published screenshot; third-party data and imagery terms apply — see [DATA_SOURCES.md](../DATA_SOURCES.md) and [NOTICE.md](../NOTICE.md).
