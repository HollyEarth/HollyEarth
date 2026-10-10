# Feature status — HollyEarth v0.1.0

The state of every significant HollyEarth feature in v0.1.0, as established by an internal product audit of the v0.1.0 baseline (October 2026). A feature is listed as working only if it was seen working on real data. Nothing is listed because it appears in a plan.

Numbers are counts of records in v0.1.0 and will change with the next import. "Next step" is a direction, not a commitment — see [ROADMAP.md](../ROADMAP.md).

## Status vocabulary

| Status | Meaning |
|---|---|
| `SHOWCASE_READY` | Works on real data and is polished and honest enough to show to strangers without apologising for breakage |
| `WORKING` | Works on real data; may have stated limitations |
| `BETA` | Works, with known defects or gaps, or depends on optional services |
| `PROTOTYPE` | The interface or mechanism exists, but it is not in real use or cannot yet do its job |
| `DEMO` | Invented or illustrative content, labelled DEMO in the interface |
| `RESEARCH` | A concept, method or framework being explored; not a product capability |
| `FUTURE` | Planned or previewed; no working implementation |

A status never means "verified by a person". In v0.1.0 no claim has yet been checked by a person.

## Contents

[Core](#core) · [City — Riga Twin](#city--riga-twin) · [Politics](#politics) · [Political Workspace](#political-workspace) · [HollySport](#hollysport) · [Social Intelligence](#social-intelligence) · [Investigation](#investigation) · [Monitoring](#monitoring) · [Story and voice](#story-and-voice) · [Holly AI](#holly-ai) · [Holly Eye / World](#holly-eye--world) · [Research](#research) · [Platform and internal tools](#platform-and-internal-tools)

---

## Core

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Canonical graph | Core | `WORKING` | 25,127 entities · 26,293 relationships · 11,115 claims · 18,377 evidence records · 25,380 external identifiers | One schema with provenance for politics and sport records; one graph engine draws it | Politics (3,892 entities) and sport (21,235) form two sub-graphs with no relationship between them; the social register is not in it; there is no contract or agreement entity type | Shared organisation identity; social providers and buildings in the graph; a contract type |
| Provenance | Core | `WORKING` | 50 sources · 5,015 source snapshots | Source → snapshot → import path kept with records and shown in the interface | Cases and Social keep their own claim and quotation records beside the canonical ones | One evidence vocabulary across stores |
| Claim and relationship status | Core | `WORKING` | Canonical claims: 11,057 asserted, 58 corroborated · relationships: 2,439 marked verified | Status is stored and shown | "Verified" relationships are structural links taken from official source metadata, and "corroborated" claims come from an automated cross-check — neither is a human verification | Human review workflow; clearer labels |
| Entity resolution | Core | `BETA` | 1 merge · 4 pending matches · 1,284 sport person candidates · 450 organisation-name candidates | People and organisations are joined only by stable source identifiers, never by name alone | Review queues are not yet worked through; one shared municipal registration number is attached to the wrong organisation and pulls unrelated municipal bodies together — being corrected | Registration-number-first resolution with an institution-level guard; human review |
| Typed money | Core | `WORKING` | 84 case money records: contract value 43 · planned 15 · monthly fee 9 · awarded 8 · unit rate 6 · contract ceiling 3 | Each amount keeps its type, source and quotation; types are never summed together | There is no payment type and no recorded payment execution; some rows are stored twice; only fees are linked to a claim | A money model from planned to contracted, awarded, invoiced and paid |
| Spatial representation | Core | `WORKING` | 565 canonical places · 58 neighbourhoods · 177 social-service buildings (separate model) | Points only from the address register or the source; no guessed points | The 177 social buildings and the district boundaries are not canonical places; many canonical places are not yet used by any relationship | Shared place identity across domains |
| Languages | Core | `WORKING` | Russian · Latvian · English | New surfaces fully translated; source data stays in its original language | Older screens mix languages; some internal codes are visible | Finish localisation |
| Cross-domain navigation | Core | `WORKING` | — | One top bar; doors between City, Politics, Sport, Social, cases and World | Most doors open another module's default view; the selected record is lost on the way | Entity-level links in both directions |

## City — Riga Twin

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| 3D Riga scene | Twin | `WORKING` | Photogrammetric city mesh, LOD2 buildings | Photorealistic Riga with scene switching | Needs a graphics card; without one the base map stays black | — |
| District boundaries | Twin | `WORKING` | 58 neighbourhoods (official open data) | On by default, with source line | Kept as a snapshot, not as canonical places | Canonical district places |
| Council decisions on the map | Twin | `BETA` | 428 decisions that name an address | District cards and a decision card with published amount, date and source | The decision card shows a "VERIFIED" badge that does not mean human verification; no link from a decision to its case | Correct the badge; link decisions to cases |
| Sport plots | Twin | `WORKING` | 14 city-granted territories | Pins fly to the plot | No card and no link to a club passport | Link to passports |
| Social-service buildings | Twin | `WORKING` | 177 buildings | Place card with address, method and linked services | The Twin's own Social panel still says "no data"; opening the catalogue loses the selected building | Keep the selection; one place identity |
| District news | Twin | `BETA` | 4 markers from public-broadcaster headlines | Headlines and links only | National headlines appear as district news | Better geographic filtering |
| Council panel | Twin | `BETA` | 322 nodes · 607 links; 113 people; 13 committees; 42 decisions with sums; 9 cases | Factions, people, committees, money and cases beside the map | Seat totals differ between views; decision analysis in this panel needs a language model and is being changed to run only on an explicit request | Deterministic default view |
| Wellbeing lens | Twin | `DEMO` | Invented scores | Labelled DEMO on every pin | Not a measurement | Replace with a real source or remove |
| AQAL overlay | Twin | `PROTOTYPE` | Air quality, weather, LOD2 and open-dataset rows are live; others demo or offline | Opens as an overlay with row-level status | Mixes live, demo and offline rows; contradicts other layers in places | Treat as a research lens |
| Research mode | Twin | `PROTOTYPE` | — | Question bar and example prompts | Cannot answer questions in v0.1.0 | Connect to the graph |
| Case on the map | Twin | `PROTOTYPE` | — | A case can be opened from the Twin | The case does not yet land on the city; most case entities have no place | Case places on the Twin |
| Events · investment plan · aid organisations layers | Twin | `FUTURE` | — | Shown honestly as "no data" | — | Import sources |

## Politics

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Council records | Politics | `WORKING` | 175 sessions · 456 agenda items · 456 decisions · 5,402 ballots · 62,772 votes · 113 deputies · 7 parties · 13 committees | Imported from the council's publications and voting protocols, each with its source | Status "imported, unverified"; no human review | Review workflow |
| Political OS | Politics | `BETA` | Network of 322 nodes and 607 links; 7 parties, 113 deputies; 456 decisions, 175 sessions | Network, balance of power, council faces, decision chains | The city-money card does not finish loading; the council pulse keeps reconnecting; its seat total differs from Parties & Power | Fix empty states; one seat source |
| Network | Politics | `WORKING` | 884 records · 1,351 links | Integrated graph with filters and layouts | Graph sizes differ between Political OS, Network and the Workspace without explanation | Explain the scopes |
| Live Sessions | Politics | `BETA` | 175 sessions, latest July 2026 | Session list and links to recordings | Data is about three months old; the latest session has no agenda, speakers or transcript yet | Refresh and process sessions |
| Decisions | Politics | `BETA` | 400 decisions · 33% coverage · amounts as published in the decisions | Decision → impact chain with review status | Act type shows "undefined"; the outcome step has no data; the procurement source is offline | Fill act types and outcomes |
| AI Analyzer | Politics | `PROTOTYPE` | 175 sessions as basis; public-broadcaster headlines | Deterministic daily view | The AI brief is not connected in v0.1.0, though the screen suggests it is temporarily unavailable | Connect or relabel |
| City Budget | Politics | `BETA` | A separate open dataset of Riga municipal spending (data.gov.lv, Q2 2026) | Spending by paying body and by expense article | Budget lines are not imported (the screen shows an error text); decision → budget links are not computed; how the dataset's rows relate to individual payments is still being reviewed | Import budget lines; establish payment semantics |
| Deputies | Politics | `WORKING` | 113 dossiers; 351 attributed remarks awaiting review | Dossiers with status "imported, unverified" | Portrait rights not yet reviewed; individual roll-call votes are not published in the dossier | Rights review |
| Integral City | Politics | `RESEARCH` | — | — | No data in v0.1.0 (the screen keeps loading). Value-profile ideas must never rate parties or people | Keep as research |
| Parties & Power | Politics | `WORKING` | Official results of the 7 June 2025 election; 60 seats; turnout 52.3% | Votes, percentages and seats per list | — | — |
| District Impact | Politics | `DEMO` | Public-broadcaster headlines per district | — | Wellbeing scores and smart-city signals are demo texts, labelled | Real district indicators |
| Smart City Lenses | Politics | `DEMO` | — | Quadrant analysis of an illustrative project | The whole module analyses a demo air-sensor project, which also appears as a banner above most Politics modules | Label more strongly or remove |
| Evidence Ledger | Politics | `BETA` | 193 evidence objects · 175 sessions · public-broadcaster headlines | Source-backed ledger with a party lens | The source monitor is not built; general national news is listed among council evidence | Filter evidence |

## Political Workspace

Internal research tool (separate page), `PROTOTYPE`. It shows up to 793 of the 3,892 canonical politics records (bulk types capped), with evidence filters (verified, supported, contested, unverified) and an evidence inspector. Interface mostly in English.

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Political Archipelago | Workspace | `PROTOTYPE` | Parties and institutions with evidence coverage | Communities as islands, verified relations as bridges | Spatial metaphor; internal only | — |
| Focus Orbit | Workspace | `PROTOTYPE` | Connected records of a selected entity | Recentring on any record | Generic view until something is selected | — |
| Evidence & Influence Flow | Workspace | `PROTOTYPE` | Six stages from evidence to outcome | Data gaps shown in place (procurement, contracts not ingested) | Title overlaps a stage label | Ingest procurement and contracts |
| Holarchic Observatory | Workspace | `RESEARCH` | Records by scale | Follow a record up and down scales | A research lens | — |
| Integral Lens Field | Workspace | `RESEARCH` | Counts per quadrant | One record seen in four quadrants | The quadrant mapping is a research lens, not a finding | — |
| Living City Torus | Workspace | `PROTOTYPE` | Stage counts | Observe → interpret → decide → act → outcome loop | Every stage shows the per-type cap; "learn" and "value" have no data | Real stage data |
| Geo / Twin Bridge | Workspace | `PROTOTYPE` | Geocoded politics records | Records placed on the ground | 620 records have no place yet; abstract grid, no base map | Place extraction |
| Relationship Graph | Workspace | `WORKING` | 884 records · 1,351 links | Same graph as Politics → Network | Its reading guide shows the wrong legend | Fix legend |

## HollySport

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Sport data import | Sport | `WORKING` | Athletics results and calendar, WAKO official results books, King of Kings event archive, the register of recognised federations, a research dataset of combat-sport clubs | Each record keeps its source | Several sources are international; Latvia-wide data is shown under "Riga" in places | Clear geographic scope |
| Minors policy | Sport | `WORKING` | No junior or cadet categories stored | Results of anyone possibly under 18 are not stored; the rule is explained on the event passport | People without birth information are not treated as minors; federation award titles are shown and are being reviewed against the policy | Tighten the review |
| Sport City (real layer) | Sport | `WORKING` | 198 clubs and schools · 30 on the map · 18,143 athletes · 7 cases · 66 venues in Riga | Real counts, map, archive events, search | The demo game layer dominates the first screen; two club counts are easy to misread | Lead with real data |
| Game layer — season, missions, XP, district levels | Sport | `DEMO` | Invented | Labelled DEMO; "nobody has earned points" | No progression mechanics | Build on real mechanics |
| Clubs | Sport | `WORKING` | 297 = 198 clubs and schools + 99 federations | Cards, list and map views | 198 is Latvia-wide; plot counts differ between screens | Scope labels |
| Athletes | Sport | `WORKING` | 18,143 | Search and lists | Includes unresolved duplicates (1,284 identity questions); only one athlete is linked to a club | Human review |
| Events | Sport | `WORKING` | 227 events · 1,326 bouts · 8,401 placings | Event lists and maps | Some events exist twice, so their bouts are counted twice | De-duplicate |
| Club passport | Sport | `SHOWCASE_READY` | Club, places, federations, family price, coaches named by the club, public context | Eight sections; price shown as "a price, not income"; door into the club's case | Athletes and events are not linked to clubs; an overdue source check is shown as "next check" | Club ↔ athlete links |
| Athlete passport | Sport | `WORKING` | Bouts and placings as printed by the source | Opponent, event and method as published | The club is unknown for almost every athlete | Representation data |
| Event passport | Sport | `SHOWCASE_READY` | e.g. WAKO Senior World Championships 2025: 136 categories, 1,897 starts, 1,609 athletes | Results by category; "no venue recorded" said plainly | No links from events to clubs | Club links |
| Venue passport | Sport | `WORKING` | 133 venues, 106 with an address-register point | District, point and events held there | Owner, operator and capacity are "not recorded" | — |
| Business passport | Sport | `PROTOTYPE` | 89 organisations | Opens a record | The organisations come from the council register and are not sport businesses | Real business data |
| Archive overview | Sport | `BETA` | — | Entry to the archive | Headline speaks of Riga for Latvia-wide data; English interface | Scope and translation |
| Rankings | Sport | `BETA` | Computed from 1,326 archived bouts | Labelled "not a federation ranking" | Name duplicates appear | De-duplicate |
| Sport graph | Sport | `WORKING` | 18,759 entities · 21,425 relationships | Graph of clubs, athletes, events, venues, disciplines and federations | — | — |
| Sport map | Sport | `WORKING` | 30 clubs with coordinates | Points only where the address register confirms them | Address-only venues are listed, not drawn | — |
| Event OS (create event) | Sport | `PROTOTYPE` | Real clubs, venues and athletes to pick from | Nine-step planning wizard | A draft lives only in the browser; it is not an event registration or publishing service | — |
| Creator, partnerships, outreach, projects, review | Sport | `PROTOTYPE` | Test accounts only; 3 draft campaigns; 0 media | Sign-in and review mechanics exist | No real use | Pilot with real organisers |
| Fan predictions | Sport | `DEMO` | Invented leaderboard | "Demo points, not money" | Contracts not deployed | — |
| Market · Wallet · Leagues · Club tokens · Ticketing | Sport | `FUTURE` | — | Preview sheets that say so | "No accounts, payments or contracts" | — |
| Club → case | Sport | `WORKING` | 7 clubs with cases | Passport opens the case and its story | No link back from the case to the passport | Two-way links |
| Public money in sport | Sport | `FUTURE` | No records | Passports say "no record does not mean no money" | — | Connect public support data |

## Social Intelligence

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Register import | Social | `WORKING` | Ministry of Welfare register, snapshot 2026-09-14: 2,082 rows → 256 services in Riga; 3,110 facts | Every fact has a quotation and a locator in the source | One register snapshot | Scheduled refresh |
| Social stage | Social | `SHOWCASE_READY` | 256 services · 106 providers · 177 buildings · 28 at home | City as interface, service-type column, metrics, filters | Dossiers and filters are not linkable by URL | Shareable links |
| Map | Social | `WORKING` | 177 buildings with address-register points | Clustered points, legend "at home — no point" | "Confirmed place of delivery" means register plus address register, not confirmed delivery; one building lies outside the city boundary | Clarify wording |
| Filters and search | Social | `WORKING` | 19 service types · 17 target groups · 35 neighbourhoods · delivery mode | Type, for whom, where and how | Filtering without a category highlights points but gives no list | Result list |
| Service dossier | Social | `SHOWCASE_READY` | Register record, planned capacity, place, documents, money, unknowns | "What is not known" for every service | A note that the address is a legal address is printed even under a confirmed delivery address | Conditional note |
| Organisation dossier | Social | `WORKING` | Services, buildings, register conflicts | Organisation view of the register | Register-only; not linked to the main graph or to politics | Canonical organisations |
| Delegation agreements | Social | `WORKING` | 49 documents: 3 matched through a case document, 13 name-match candidates, 33 unresolved | Match strength shown for each | Most agreements are not yet tied to a provider | Resolve matches |
| Money | Social | `BETA` | One programme: a 2026 limit set by agreement, three conditional future-year plans, three maximum per-client rates | Plan, limit and rate shown by type; "actual payments not established" | The section headline adds the firm limit to the conditional plans; no payment records | Separate the bases; payment data |
| Planning | Social | `BETA` | Register-derived distribution | A planning view labelled "not a fact" | Not a measure of need | — |
| "Holly sees" | Social | `WORKING` | Three register counters | Deterministic counts with "not an assessment" note | — | — |
| Service → case | Social | `WORKING` | 1 of 256 services | Door into the related case | — | More cases |
| Dossier → Twin | Social | `FUTURE` | — | — | No way back from a dossier to the Twin | Two-way links |
| Provider monitoring | Social | `FUTURE` | — | Shown as a plan | Not watched | — |
| Need, outcomes, people served, actual payments | Social | `RESEARCH` | Unknown for all 256 services | Shown as unknown, never as zero | No source yet | Find sources |

## Investigation

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Case gallery | Cases | `SHOWCASE_READY` | 9 cases: 7 sport, 2 council decisions | Filters, three actions per case, shareable links | — | More domains |
| Case workspace (desktop) | Cases | `WORKING` | e.g. Rīgas nami: 38 objects · 34 claims · 14 sources · 153 open questions | Explore, Analyze, Roadmap and Story modes; established / unknown / money / analysis / monitoring | "Confirmed" means "directly supported by a quotation"; in one case two different contract figures appear on the same screen; a console warning on every case | Clearer labels; one money summary |
| Case workspace (phone) | Cases | `BETA` | — | No horizontal scrolling | Graph controls cover the case card | Mobile layout |
| Claims with quotations | Cases | `WORKING` | 111 claims, all with source and quotation; 106 directly supported, 4 partially, 1 not | Deterministic quotation check; every case relationship traces to a claim | All 111 are asserted; none checked by a person | Human review |
| Model-extracted claims | Cases | `BETA` | 8 of 111 claims, 12 of 104 entities, 7 of 84 money records | Kept only if the quotation is found word for word in the source | Not yet marked as model-extracted in the interface | Mark and filter them |
| Sources | Cases | `WORKING` | 55 sources with content hash and stored copy | Official, procurement, political-finance and self-reported classes | 29 sources were read but nothing was extracted from them | — |
| Case graph | Cases | `WORKING` | 104 case entities, 97 relationships | Graph with layouts and legend (archive record / case candidate / supported / partly supported) | A separate graph per case: 24 of 104 entities resolved to the main graph (2 incorrectly); 12 orphans | Resolution and promotion to the main graph |
| Evidence path | Cases | `SHOWCASE_READY` | — | "Where does this amount come from": source read → quotation → type of amount | — | — |
| Typed money in cases | Cases | `WORKING` | 84 records of 6 types | Never summed across types; "a type of statement, not a fact of payment" | No payment records; some rows stored twice; one case's overview ignores its fees | One money summary per case |
| Open questions and gaps | Cases | `WORKING` | 324 tasks; 16 evidence gaps | "A gap in the sources, not a zero" | Tasks have no owner field | — |
| Roadmap | Cases | `WORKING` | Built from research runs, tasks and gaps | The route the investigation took, including unfinished branches | — | — |
| Analysis (deterministic) | Cases | `WORKING` | 14 stored analyses (6 deterministic) | Patterns, questions, hypotheses, next steps — none marked as fact | Stored analyses can be older than the case; the product says so | Refresh |
| Open model reasoning | Cases | `BETA` | 8 model analyses (3 completed) | Labelled as hypotheses | Model text appears in English inside other languages; internal codes visible | Localise |
| Research runs and deepening | Cases | `BETA` | 84 runs, 127 acquisition attempts | Register research is deterministic; discovery is model-assisted with a per-session budget | Requires a language model and a database write | Clear cost labels |
| Holly in a case | Cases | `BETA` | 1 saved conversation | Answers from the saved analysis first; actions validated against case records | Needs a model for open questions | — |
| Source conflicts | Cases | `FUTURE` | 0 recorded | A place for conflicts exists | Disagreements are not yet recorded | Record conflicts |
| Human verification and promotion to the main graph | Cases | `FUTURE` | 0 promoted, 0 human-verified | — | — | Reviewer workflow |

## Monitoring

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Watches | Monitoring | `BETA` | 18 watches in 3 of 9 cases, on two official sources (company officers; procurement results) | Proposed from the case's organisations and money counterparties | Six cases have none | Wider coverage |
| Runs and snapshots | Monitoring | `BETA` | 26 runs and 26 snapshots (September 2026) | Each run stores the full snapshot, request and outcome | All runs were started by hand; procurement snapshots keep the newest 40 records only | Mark windowed snapshots |
| Change detection | Monitoring | `BETA` | 0 changes recorded | Compares records by identity, not position; keeps "no change", "source did not answer" and "parser changed" apart | Has not yet fired on a real change | — |
| Monitoring page | Monitoring | `BETA` | 18 rows | One table across cases | Overdue checks still show as "active"; no watch or run detail | Show due dates |
| Scheduler | Monitoring | `FUTURE` | — | "Weekly" is stored | No automatic scheduler exists | Scheduled checks |

## Story and voice

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Story playback | Story | `WORKING` | 12 saved versions | ≈1, 3 and 9 minute tellings; RU / LV / EN; chapters directed over the case graph | All saved versions are currently marked out of date | Rebuild versions |
| Case-based assembly | Story | `WORKING` | 11 of 12 versions without model wording | Structure comes from the case's records | — | — |
| Chapter-to-claim traceability | Story | `BETA` | 3 of 12 saved versions link chapters to claims | Chapters can carry claim references | 9 of 12 saved versions have no chapter-level claim links; some were planned from model hypotheses | Ground every chapter or refuse it |
| Model-assisted wording | Story | `BETA` | 1 version | Wording checked against the deterministic plan | — | — |
| Browser voice | Story | `BETA` | — | Free | The browser-voice path also asks the server for a cached hosted voice | Separate the paths |
| Local voice model | Story | `PROTOTYPE` | — | Runs on a local machine | Needs a separate local worker | — |
| Hosted voice | Story | `BETA` | Cached audio | Paid, used only after confirmation | — | Server-side consent |

## Holly AI

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Deterministic helpers | Holly | `WORKING` | — | "Holly sees", case analysis, story assembly, quotation checks — no model | — | — |
| Investigation assistant | Holly | `BETA` | — | Case-scoped chat bound to the case's records | Needs a model for open questions | — |
| Model boundary | Holly | `WORKING` | — | Model output is labelled as hypothesis or prediction; models cannot write to the main graph or mark anything verified | Voice and Holly Eye services are outside this boundary | One AI gateway with budgets |
| Decision analysis on the Twin | Holly | `BETA` | — | Hypotheses about a decision from its canonical record | Starts when a decision is selected; being changed to run only on explicit request, with caching and limits | Explicit action |
| Global Holly assistant | Holly | `FUTURE` | — | — | Not connected in v0.1.0; buttons that open it lead to an unavailable state | Connect or hide |
| Autonomous agents | Holly | `FUTURE` | — | — | Holly is not an agent in v0.1.0 | — |

## Holly Eye / World

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| World door | World | `WORKING` | — | Opens Holly Eye or says plainly that it is not running | — | — |
| Holly Eye planetary view | World | `BETA` | Third-party 3D map tiles and 14 public data layers (flights, military flights, earthquakes, satellites, space missions, CCTV, radio, bikeshare, AIS vessels, installations, datacenters, dams, active fires, simulated street traffic) | 3D globe and 3D cities, layer menus, scenes, context, eight visual styles, data-attribution list — see the [Holly Eye gallery](gallery/HOLLY_EYE.md) | **Third-party application (God's Eye View by Bilawal Sidhu), not HollyEarth technology**; English only; opens over Austin by default; depends on third-party keys; street traffic is simulated | — |
| Holly Eye voice commands | World | `PROTOTYPE` | — | Push-to-talk map commands | Internal setting only; paid speech services | — |
| HollyEarth data inside Holly Eye | World | `FUTURE` | None | — | Holly Eye holds no Riga or graph data | — |

## Research

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| HEIO — HollyEarth Integral Ontology (v0.1) | Research | `RESEARCH` | — | Internal research document | Not implemented as a system; some principles (provenance, no unconditional fact) match v0.1.0 | — |
| HEIM — HollyEarth Integrative Metatheory & Context System (v0.2) | Research | `RESEARCH` | — | Internal research document | Not implemented in v0.1.0 | — |
| Integral / AQAL lenses | Research | `RESEARCH` | — | Used as research lenses in the Workspace and Twin overlay | Not findings; never used to rate people | — |
| Spiral Dynamics | Research | `RESEARCH` | — | Considered only for context, never for people | No data in v0.1.0 | — |
| Integral City | Research | `RESEARCH` | — | Design influence | The Politics module is empty in v0.1.0 | — |

## Platform and internal tools

| Feature | Module | Status | Real data | What works | Limitations | Next step |
|---|---|---|---|---|---|---|
| Hosted public instance | Platform | `FUTURE` | — | — | HollyEarth runs as a private installation | Hosted pilot |
| Production hardening | Platform | `FUTURE` | — | — | Authentication, rate limits and AI cost controls are needed before any public deployment | In development |
| Accounts | Platform | `PROTOTYPE` | Test accounts only (Sport) | Sign-in for organisers and reviewers | No accounts in the shared shell | — |
| Project Observatory | Internal | `PROTOTYPE` | Snapshot of August 2026 | Project control plane | Frozen; not a current status | — |
| Legacy demo modules (personal cockpit, impact, perspective) | Internal | `DEMO` | Demo data | Kept out of navigation | — | Retire |
