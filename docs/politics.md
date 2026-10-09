# Politics — Political Holly OS and Political Workspace

The politics world is Riga City Council as data, with the investigation cases built on its decisions. Overall status: `BETA` — the council data is real and working; the modules around it range from working to demo.

![Parties & Power](../media/screenshots/17-politics-parties-and-power.png)

<sub>Real screenshot, v0.1.0 (Russian interface). Official 2025 election results and 60 council seats. The band at the top is a labelled demo analysis project, not a real Riga project.</sub>

## The data — `WORKING`

**175 council sessions · 456 agenda items · 456 decisions · 5,402 ballots · 62,772 votes · 113 deputies · 7 parties · 13 committees**, imported from the council's agenda and decision publications, voting protocols, deputy and faction lists, and the Central Election Commission. Every record keeps its source; deputy records are marked "imported, unverified". In the canonical graph these are 3,892 politics entities — not yet linked to the sport or social records.

## Political Holly OS — 12 modules

| Module | Status | What works | Not ready yet |
|---|---|---|---|
| **Political OS** | `BETA` | Network deputy → decision → money (322 nodes, 607 links), balance of power, council faces, decision chains | The city-money card does not finish loading; the council pulse keeps reconnecting; its seat total differs from Parties & Power |
| **Network** | `WORKING` | Integrated graph of 884 records and 1,351 links with filters and layouts | Graph sizes differ between modules without explanation |
| **Live Sessions** | `BETA` | 175 sessions with links to recordings | Latest data July 2026; the latest session has no agenda, speakers or transcript yet |
| **Decisions** | `BETA` | 400 decisions, coverage and review status, a decision → impact chain | Act type missing; the outcome step has no data; the procurement source is offline |
| **AI Analyzer** | `PROTOTYPE` | A deterministic daily view over 175 sessions and media headlines | The AI brief is not connected in v0.1.0 |
| **City Budget** | `BETA` | Riga municipal spending from a separate open dataset (Q2 2026), by paying body and expense article | Budget lines are not imported; decision → budget links are not computed; how the dataset's records relate to individual payments is still being established |
| **Deputies** | `WORKING` | 113 deputy dossiers with "imported, unverified" status | Remarks await review; portrait rights not yet reviewed |
| **Integral City** | `RESEARCH` | — | No data in v0.1.0. Value-profile ideas are research and must never be used to rate parties or people |
| **Parties & Power** | `WORKING` | 2025 election results, votes and seats per list, coalition and opposition | — |
| **District Impact** | `DEMO` | District news radar | Wellbeing scores and smart-city signals are labelled demo texts |
| **Smart City Lenses** | `DEMO` | Quadrant analysis | Applied to an illustrative demo project |
| **Evidence Ledger** | `BETA` | 193 evidence objects, 175 sessions, party lens | The source monitor is not built; national news appears among council evidence |

A labelled demo analysis project (an illustrative air-sensor scenario) is shown as a banner above most modules; it is not a real Riga project.

## Political Workspace

An internal research tool over the canonical politics records — `PROTOTYPE`. It shows up to 793 of the 3,892 records at a time (bulk types capped), with filters for entity type, convocation, dates, semantic depth and evidence state (verified, supported, contested, unverified), an evidence inspector, and data gaps shown in place: procurement and contracts are not ingested.

| View | Status | What it shows |
|---|---|---|
| Political Archipelago | `PROTOTYPE` | Parties and institutions as islands; verified relations as bridges; evidence coverage per island |
| Focus Orbit | `PROTOTYPE` | A selected record in the centre, connected records by distance |
| Evidence & Influence Flow | `PROTOTYPE` | Evidence → actor → institution → decision → execution → territory/outcome, with gaps in place |
| Holarchic Observatory | `RESEARCH` | Records by scale (territory, institutions, committees, people, sittings, agenda, decisions, evidence) |
| Integral Lens Field | `RESEARCH` | One record seen through four quadrants — a research lens, not a finding |
| Living City Torus | `PROTOTYPE` | Observe → interpret → decide → act → outcome loop; "learn" and "value" have no data |
| Geo / Twin Bridge | `PROTOTYPE` | Geocoded records on the ground; 620 records have no place yet |
| Relationship Graph | `WORKING` | The same graph as the Network module |

## Politics and investigations

Two investigation cases are built on council decisions — one on a municipal company, one on delegating social work to a non-governmental organisation (which also links to the Social world). A decision on the Twin can lead to its case; the Politics modules do not yet link to cases.

Details per feature: [FEATURE_STATUS.md](FEATURE_STATUS.md#politics) · [Political Workspace](FEATURE_STATUS.md#political-workspace).
