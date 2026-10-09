# Riga Twin

The **City** in HollyEarth is a 3D twin of Riga: a photogrammetric city scene with layers from the other worlds. Status: `WORKING`.

![Riga Twin](../media/screenshots/02-riga-twin.png)

<sub>Real screenshot, v0.1.0. Interface partly in Russian; the "Wellbeing" pins are labelled DEMO. More screens: [Riga Twin gallery](gallery/RIGA_TWIN.md).</sub>

## Layers

| Layer | Status | What it shows |
|---|---|---|
| District boundaries | `WORKING` | 58 neighbourhoods (apkaimes) from official open data |
| Council decisions | `BETA` | 428 decisions that name an address; district cards and a decision card with published amount, date and source |
| Clubs and arenas | `WORKING` | 14 territories granted by the city to sport institutions |
| Social services | `WORKING` | 177 buildings where registered services are delivered, with a place card; home services have no point |
| District news | `BETA` | Headlines and links (no article text); national headlines sometimes appear as district news |
| Events · investment plan · aid organisations | `FUTURE` | Shown as "no data" |
| Wellbeing | `DEMO` | Illustrative district scores, labelled DEMO on every pin |

## Panels and modes

- **Council panel** (`BETA`) — network, people, committees, decisions with published sums, and cases. Seat totals differ between views. Decision analysis in this panel uses a language model and is being changed to run only on an explicit request.
- **AQAL overlay** (`PROTOTYPE`) — a mix of live rows (air quality, weather, LOD2 buildings, open datasets), demo rows and offline rows; a research lens, not a live analysis.
- **Research mode** (`PROTOTYPE`) — a question bar that cannot answer questions in v0.1.0.
- **Doors** — to Politics, Sport, Social, the cases and the World (Holly Eye).

## What the Twin is today

The Twin is the place where council decisions and social buildings meet the territory, and the hub from which the other worlds open. **It composes several data models on one map rather than showing one shared place graph**: council decisions and sport plots come from the canonical graph, social buildings from the social register, and district boundaries from an open-data snapshot. Sport and Social keep their own maps; a club pin does not open its passport; cases do not yet land on the city; opening the social catalogue from a building loses the selection.

## Known issues

- The council-decision card shows a **VERIFIED** badge for imported, unverified records; it does not mean anyone verified the decision. Being corrected.
- The Twin's Sport and Social side panels say "no data" for layers the map shows with data.
- Without a graphics card the base map stays black.

## Holly Eye

From the Twin, a door leads to the planetary **Holly Eye** view and back. Holly Eye is a **third-party integration** of the open-source God's Eye View application; it is not HollyEarth's own technology. See [holly-eye.md](holly-eye.md).

Details per feature: [FEATURE_STATUS.md](FEATURE_STATUS.md#city--riga-twin).
