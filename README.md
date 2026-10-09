<div align="center">

# HOLLYEARTH

### ONE SYSTEM. MANY WORLDS.

**City · Politics · Sport · Social · Investigation · Intelligence · Experience**

Real places, public records, sources, evidence and open questions — explored as one system, starting with Riga, Latvia.

`v0.1.0` · documentation and media only · not open source

**English** · [Русский](docs/README_RU.md) · [Latviešu](docs/README_LV.md)

</div>

![HollyEarth start screen](media/screenshots/01-start.png)

<sub>Real screenshot, v0.1.0. The start screen: five areas, each labelled with its maturity and where its data comes from.</sub>

---

## What is HollyEarth?

HollyEarth is an AI-native platform for spatial, civic and investigative intelligence. It brings together the city, its institutions and organisations, political decisions, public money, social services, sport, documents, sources and evidence — and lets a person explore them on a map, as a graph, as an investigation or as a story.

Its direction is a single chain:

**Reality → Evidence → Intelligence → Experience → Action**

| | |
|---|---|
| **Reality** | What registers, councils, federations and archives actually publish |
| **Evidence** | Those records kept with their source, quotation, status and gaps |
| **Intelligence** | Cases, analysis and open questions that connect records and say what is known, what is only claimed and what is missing |
| **Experience** | A 3D city, a sport city, a map of social services, case workspaces and narrated stories in Russian, Latvian and English |
| **Action** | `FUTURE` — nothing is written back to the world in v0.1.0 |

> **Vision and today are kept apart.**
> The goal is one connected model of a city — one place, one organisation, one decision seen from every angle.
> **Today HollyEarth is one product over several connected domain models, not yet one unified reality graph.** Politics and sport records live in one canonical graph but are not yet linked to each other; the social-services register has its own model; each investigation case keeps its own evidence graph; the Riga Twin shows several of these models on one map. The links between them are real but partial. See [ARCHITECTURE.md](ARCHITECTURE.md).

Everything below separates what works today from what is demo, research or future. The detailed, per-feature view is in **[docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md)**.

---

## Explore the Worlds

| World | What it is | Status | Details |
|---|---|---|---|
| **City — Riga Twin** | Riga in 3D with district, council, sport and social layers | `WORKING` | [Riga Twin](#riga-twin) |
| **Politics** | Riga City Council: sessions, decisions, deputies, parties, elections, budget, evidence | `BETA` | [Politics](#politics--intelligence-workspace) |
| **Sport — HollySport** | Latvian clubs, athletes, events and venues from federations and result books; a game-styled sport city | `WORKING` · game layer `DEMO` | [HollySport](#hollysport) |
| **Social — Social Intelligence** | Riga's registered social services on an interactive city stage | `SHOWCASE_READY` | [Social Intelligence](#social-intelligence) |
| **Investigation** | Cases built from documents: claims, sources, quotations, typed money, open questions | `WORKING` | [Investigation](#investigation--evidence) |
| **Intelligence** | Deterministic analysis, Holly, monitoring of sources, optional model reasoning | `BETA` | [Holly AI, Story, Monitoring](#holly-ai--story--monitoring) |
| **Experience** | Story in three languages, passports, dossiers, the planetary Holly Eye door | `WORKING` | [Story](#story) · [Holly Eye](#holly-eye--world) |

Status vocabulary: `SHOWCASE_READY` · `WORKING` · `BETA` · `PROTOTYPE` · `DEMO` · `RESEARCH` · `FUTURE` — defined in [docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md).

---

## Riga Twin

A photorealistic 3D model of Riga that works as a shared map for the other worlds.

> Screenshots of the 3D city will be added once the reuse terms of the Riga 3D city model are confirmed.

**Works today**
- 3D Riga with 58 neighbourhood (apkaime) boundaries from official open data.
- Council decisions that name an address — 428 of them — on the map, each opening a card with its published amount and source.
- Sport plots granted by the city (14 territories) and 177 buildings where registered social services are delivered.
- District news markers (headlines and links only), a council panel (factions, people, committees, money, cases), and doors to Politics, Sport, Social and the cases.

**Not ready yet**
- The Twin is a viewer over several data models, not yet one shared place identity: sport and social places open their own maps rather than the same record on the Twin.
- Events, the investment plan and aid organisations are shown as "no data". The district "Wellbeing" scores are `DEMO`.
- The Research mode ("ask the city") is a `PROTOTYPE` that cannot answer questions in v0.1.0.
- Cases do not yet appear on the map; a club pin does not open its passport.

→ [docs/twin.md](docs/twin.md)

---

## Politics / Intelligence Workspace

Riga City Council as data: 175 council sessions, 456 decisions, 113 deputies and 7 parties from the council's own publications and the Central Election Commission — each record with its source and an "imported, unverified" status where nobody has checked it.

![Politics — Parties & Power](media/screenshots/17-politics-parties-and-power.png)

<sub>Real screenshot, v0.1.0 (Russian interface). Parties & Power: official results of the 7 June 2025 council election and the 60 council seats. The band at the top is a labelled demo analysis project (an illustrative air-sensor scenario), not a real Riga project.</sub>

**Political Holly OS — 12 modules**

| Module | Status | What it shows |
|---|---|---|
| Political OS | `BETA` | Network of deputies, decisions and money; balance of power; council pulse. Some panels do not finish loading; seat totals differ between views |
| Network | `WORKING` | Integrated politics graph (884 records, 1,351 links) |
| Live Sessions | `BETA` | 175 sessions with recordings; data last updated July 2026 |
| Decisions | `BETA` | 400 decisions with coverage and review state; the outcome step has no data yet |
| AI Analyzer | `PROTOTYPE` | Deterministic daily view; the AI brief is not connected in v0.1.0 |
| City Budget | `BETA` | A separate open dataset of municipal spending; budget lines and decision → budget links are not imported yet |
| Deputies | `WORKING` | 113 deputy dossiers, marked "imported, unverified" |
| Integral City | `RESEARCH` | Value-profile research lens; no data in v0.1.0 and not used to rate people |
| Parties & Power | `WORKING` | 2025 election results and seats |
| District Impact | `DEMO` | Illustrative district scores and signals, labelled demo |
| Smart City Lenses | `DEMO` | An illustrative demo project analysed through quadrant lenses |
| Evidence Ledger | `BETA` | 193 evidence objects and 175 sessions; the source monitor is not built yet |

**Political Workspace — 8 views** · `PROTOTYPE`, internal research tool

Political Archipelago · Focus Orbit · Evidence & Influence Flow · Holarchic Observatory · Integral Lens Field · Living City Torus · Geo / Twin Bridge · Relationship Graph.
It shows up to 793 of the 3,892 canonical politics records, keeps data gaps visible in place (for example, procurement and contracts are not ingested; 620 records have no place yet), and treats the integral and holarchic views as research lenses.

→ [docs/politics.md](docs/politics.md)

---

## HollySport

Latvian sport from official sources: **18,143 athletes · 227 events · 1,326 bouts · 8,401 placings · 297 clubs and federations · 133 venues** — from federation registers, official result books and public event archives. Competition results of anyone who may have been under 18 are not stored.

<table>
<tr>
<td width="50%"><img src="media/screenshots/08-club-passport.png" alt="Club passport"><br><sub>Club passport: sport, place, source, and a door into the club's public case.</sub></td>
<td width="50%"><img src="media/screenshots/12-club-family-price.png" alt="What a family pays"><br><sub>Club passport: what a family pays — a price, not income.</sub></td>
</tr>
<tr>
<td width="50%"><img src="media/screenshots/09-event-passport.png" alt="Event passport"><br><sub>Event passport from official results books — "no venue recorded" is said plainly.</sub></td>
<td width="50%"><img src="media/screenshots/15-create-event-preview.png" alt="Create event preview"><br><sub>Event planning wizard (<b>PROTOTYPE</b>, Russian interface): a draft stays in the browser; this is not an event registration service.</sub></td>
</tr>
</table>

| `WORKING` | `DEMO` | `PROTOTYPE` / preview | `FUTURE` |
|---|---|---|---|
| Sport City (real layer) · Clubs · Athletes · Events · Venues · Club / Athlete / Event / Venue passports · Archive · Map · Graph · Rankings computed from archived bouts (`BETA`, not a federation ranking) | Season · Missions · XP · District levels · Fan predictions | Event OS (create event) · Creator · Partnerships · Outreach · Organiser and reviewer accounts | MetaSport economy · Market · Wallet · Leagues · Club tokens · Ticketing |

Known limits: some athletes and events exist twice and wait for human review; only one athlete is linked to a club; "198 clubs" covers Latvia, not only Riga; there are no public-money records for sport yet.

→ [docs/sport.md](docs/sport.md)

---

## Social Intelligence

Riga's social services from the official **register of social service providers** of the Ministry of Welfare (snapshot of 14 September 2026):

**256 services · 106 providers · 177 buildings · 28 services delivered at home**

<table>
<tr>
<td width="50%"><img src="media/screenshots/10-social-stage.png" alt="Social Intelligence stage"><br><sub>The Social Intelligence stage: the city as the interface, from the official register.</sub></td>
<td width="50%"><img src="media/screenshots/11-social-dossier.png" alt="Service dossier"><br><sub>Service dossier: 2,400 clients planned at registration — actual payments and people served are unknown.</sub></td>
</tr>
</table>

**Works today** — Catalogue · Map · Filters (type, for whom, where, how) · Search · Service dossier · Organisation dossier · Delegation agreements (49 documents, with match strength shown) · Money (plans, limits and maximum rates where an agreement exists) · Planning view (labelled "not a fact").

**Registered ≠ Delivered.** The register says what is registered, where and for whom. It does not say how many people were actually served, what was actually paid, or how good the service was — HollyEarth shows those as unknown for all 256 services. Home-delivered services have no point on the map.

**Not ready yet** — providers are not yet linked to the main graph or to politics; money exists for one programme; one provider links to an investigation case; there are no recorded payment executions; there is no need or outcome data.

→ [docs/social.md](docs/social.md)

---

## Investigation / Evidence

A case gathers a council decision, a procurement or an organisation together with its sources, quotations, claims, money, open questions and the route the investigation took. **9 cases** today (7 about sport clubs, 2 about council decisions — one of them on delegating social work).

<table>
<tr>
<td width="50%"><img src="media/screenshots/03-case-overview.png" alt="Case overview"><br><sub>A council decision as a case: what is established, what is unknown, and money by type — never added together.</sub></td>
<td width="50%"><img src="media/screenshots/04-evidence.png" alt="Evidence path"><br><sub>"Where does this amount come from?" — the source read, the quotation, and the kind of amount: planned, not paid.</sub></td>
</tr>
<tr>
<td width="50%"><img src="media/screenshots/05-roadmap.png" alt="Investigation roadmap"><br><sub>The course of an investigation — including where the research did not finish.</sub></td>
<td width="50%"><img src="media/screenshots/13-club-public-context.png" alt="Club public context"><br><sub>A sport club's public context: claims, sources, monitoring and the door into its case.</sub></td>
</tr>
</table>

**Works today** — Cases · Claims · Sources · Evidence quotations · Case graph · Typed money · Open questions · Roadmap · Analysis · Story · Monitoring · Holly.

**Claim ≠ Verified Fact.** All 111 case claims are *asserted*: each carries the exact quotation and source it rests on, and an automatic check says whether the quotation supports it directly (106), partially (4) or not (1). **None has been checked by a person yet.** Where the interface says "confirmed", it means "directly supported by a quotation".

**Money is typed.** Planned amounts, contract values, contract ceilings, awarded amounts, monthly fees and unit rates are kept apart and never summed across types. In cases and in Social there are no recorded payment executions; a missing payment record is not a missing payment.

→ [docs/cases.md](docs/cases.md) · [docs/evidence-and-provenance.md](docs/evidence-and-provenance.md)

---

## Holly AI / Story / Monitoring

### Holly AI

HollyEarth works without a language model. Navigation, maps, graphs, cases, evidence, deterministic analysis, Story, Sport, Social and the Twin all run without one.

- **Deterministic first** — "Holly sees" counters, case analysis, story assembly and quotation checks are rule-based.
- **Investigation assistant** — Holly inside a case answers from the saved analysis first and uses a model only when needed. `BETA`
- **Optional model reasoning** — hypotheses and new ideas, always labelled as hypotheses, never stored as facts. `BETA`
- **Model-assisted research** — a model may propose a case claim only if its quotation is found word for word in the source. `BETA`
- **Voice** — browser voice, a local voice model, or a paid hosted voice used only after confirmation. `BETA`

A model can never write into the canonical graph or mark anything verified. A global Holly assistant across the whole product is **not available** in v0.1.0, and Holly is not an autonomous agent. → [docs/holly-ai.md](docs/holly-ai.md)

### Story

![Story](media/screenshots/06-story.png)

<sub>Real screenshot, v0.1.0. A case told as a story — chapter 1 of 7, assembled from the case's own records. Narrated voice off.</sub>

Short, brief or detailed tellings in Russian, Latvian and English, saved as versions; a version says when the case has changed since it was made. Story is assembled from case records, not written by a model. **Not every chapter is linked to individual claims yet** — completing that traceability is in development. `WORKING` → [docs/story.md](docs/story.md)

### Monitoring

![Monitoring](media/screenshots/18-monitoring.png)

<sub>Real screenshot, v0.1.0 (Russian interface). What the cases watch: 18 watches on official registers.</sub>

18 watches on two official sources (company officers and procurement results), 26 runs and 26 stored snapshots, and change detection that compares records by identity and keeps "no change" apart from "the source did not answer". **Checks are run by hand today; there is no automatic scheduler**, and no change has been recorded yet. `BETA` → [docs/monitoring.md](docs/monitoring.md)

---

## Holly Eye / World

The **World** door opens **Holly Eye**, a planetary 3D view. Holly Eye is the open-source application **God's Eye View by Bilawal Sidhu**, integrated into HollyEarth as a separate application with a way back to the Riga Twin. **It is a third-party integration, not HollyEarth's own technology.** It is English-only, opens outside Riga, and depends on third-party map services and keys. `BETA` (integration) → [docs/holly-eye.md](docs/holly-eye.md)

---

## Research Foundations

Implemented in v0.1.0: an epistemic model (no unconditional "fact"), provenance on every record, a canonical graph and spatial representation. Research influences — AQAL / Integral theory, Spiral Dynamics, Integral City and others — are design lenses, not scientific claims, and are **never used to rate people, parties or districts**.

<table>
<tr>
<td width="50%"><img src="media/concepts/09-heio-concept-architecture.png" alt="HEIO concept illustration"><br><sub><b>Concept illustration, not a product screenshot.</b> HEIO — HollyEarth Integral Ontology (v0.1): an internal research document on a shared ontology for the city. <code>RESEARCH</code> · not implemented as a system.</sub></td>
<td width="50%"><img src="media/concepts/10-heim-context-system.png" alt="HEIM concept illustration"><br><sub><b>Concept illustration, not a product screenshot.</b> HEIM — HollyEarth Integrative Metatheory &amp; Context System (v0.2): an internal research document on how to ask complex questions. <code>RESEARCH</code> · not implemented in v0.1.0.</sub></td>
</tr>
</table>

→ [docs/research.md](docs/research.md)

---

## Current Capabilities

| Area | Showcase-ready | Working | Beta / prototype | Demo / research / future |
|---|---|---|---|---|
| Core | — | Provenance · typed money · claims with status · spatial layers · RU / LV / EN | Cross-domain links (partial) | One unified reality graph (`FUTURE`) |
| City | — | 3D Twin · decision, sport and social layers | Research mode (`PROTOTYPE`) | Wellbeing scores (`DEMO`) |
| Politics | — | Network · Deputies · Parties & Power | Political OS · Sessions · Decisions · Budget · Evidence Ledger · Workspace | District Impact · Smart City Lenses (`DEMO`) · Integral City (`RESEARCH`) |
| Sport | Club passport · Event passport | Sport City · archive · passports · map · graph | Rankings · Event OS · Creator · Partnerships | Game layer (`DEMO`) · economy (`FUTURE`) |
| Social | Stage · service dossier | Catalogue · map · organisation dossier · agreements | Money · Planning | Need, outcomes, payments (`RESEARCH`) |
| Investigation | Case gallery · evidence path | Case workspace · roadmap · analysis · Story | Holly · research runs · voice · monitoring | Human verification workflow (`FUTURE`) |

Full matrix with real data, limitations and next steps: **[docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md)** · summary: [CAPABILITIES.md](CAPABILITIES.md) · modules: [MODULES.md](MODULES.md).

---

## What's Next

| Exists today | In development | Research | Future |
|---|---|---|---|
| Riga Twin · Cases, evidence, roadmap, Story · HollySport data and passports · Social Intelligence · Politics data · Monitoring (manual) · RU / LV / EN · Holly Eye door (third-party) | Shared identity across domains · Social in the main graph · money semantics (planned → contracted → awarded → paid) · scheduled monitoring · human review · claim-linked story chapters · hosted pilot · Event OS, Creator and partnerships (prototypes) | HEIO · HEIM · Integral / AQAL · Spiral Dynamics (context only) · Integral City | Governed action and appeals · HollyWorlds · MetaSport economy · public hosted instance · more cities |

HollySport's game layer remains `DEMO` until it is built on real mechanics. → [ROADMAP.md](ROADMAP.md)

---

## Architecture / Data Principles

- **Every record has provenance** — source, snapshot and import path.
- **Claim ≠ verified fact** — "verified" in the data never means a person checked it unless it says so.
- **No record ≠ no reality** · **unknown ≠ zero**.
- **Planned ≠ paid** — money types are never added together.
- **Registered ≠ delivered.**
- **Model output ≠ evidence.**
- **No stored competition results of minors.**
- **Demo data is labelled DEMO.**

→ [ARCHITECTURE.md](ARCHITECTURE.md) · [DATA_PRINCIPLES.md](DATA_PRINCIPLES.md) · [DATA_SOURCES.md](DATA_SOURCES.md)

---

## Screenshots / Product Gallery

<table>
<tr>
<td width="33%"><img src="media/screenshots/01-start.png" alt="Start"><br><sub>Start</sub></td>
<td width="33%"><img src="media/screenshots/17-politics-parties-and-power.png" alt="Parties and Power"><br><sub>Politics — Parties &amp; Power</sub></td>
<td width="33%"><img src="media/screenshots/10-social-stage.png" alt="Social stage"><br><sub>Social Intelligence stage</sub></td>
</tr>
<tr>
<td width="33%"><img src="media/screenshots/11-social-dossier.png" alt="Service dossier"><br><sub>Service dossier</sub></td>
<td width="33%"><img src="media/screenshots/03-case-overview.png" alt="Case overview"><br><sub>Case overview</sub></td>
<td width="33%"><img src="media/screenshots/04-evidence.png" alt="Evidence path"><br><sub>Evidence path</sub></td>
</tr>
<tr>
<td width="33%"><img src="media/screenshots/05-roadmap.png" alt="Roadmap"><br><sub>Investigation roadmap</sub></td>
<td width="33%"><img src="media/screenshots/06-story.png" alt="Story"><br><sub>Story</sub></td>
<td width="33%"><img src="media/screenshots/18-monitoring.png" alt="Monitoring"><br><sub>Monitoring</sub></td>
</tr>
<tr>
<td width="33%"><img src="media/screenshots/08-club-passport.png" alt="Club passport"><br><sub>Club passport</sub></td>
<td width="33%"><img src="media/screenshots/12-club-family-price.png" alt="What a family pays"><br><sub>What a family pays</sub></td>
<td width="33%"><img src="media/screenshots/13-club-public-context.png" alt="Club public context"><br><sub>Club public context</sub></td>
</tr>
<tr>
<td width="33%"><img src="media/screenshots/09-event-passport.png" alt="Event passport"><br><sub>Event passport</sub></td>
<td width="33%"><img src="media/screenshots/14-venue-passport.png" alt="Venue passport"><br><sub>Venue passport (Russian interface)</sub></td>
<td width="33%"><img src="media/screenshots/15-create-event-preview.png" alt="Event OS preview"><br><sub>Event OS — <b>PROTOTYPE</b></sub></td>
</tr>
</table>

All published images, with captions, status, capture notes and attribution: [media/README.md](media/README.md). Every screenshot is an unedited capture of the real v0.1.0 product; concept illustrations are always labelled as such. Screenshots of the 3D city (Riga Twin, HollySport City) will follow once the reuse terms of the Riga 3D city model are confirmed.

---

## Authors / Lab Da Riga

**HollyEarth** is created by **Stanislav Petrovsky** and **Irina Petrovskaya**, Riga, Latvia.

Copyright © 2026 Lab Da Riga. All rights reserved.

This repository contains documentation and media only. It is **not open source** and contains no source code — see [LICENSE.md](LICENSE.md) and [NOTICE.md](NOTICE.md). Third-party maps, data and components remain under their owners' terms.

## Contact / Follow the Project

- **Follow** — watch this repository and the [HollyEarth organisation](https://github.com/HollyEarth) for releases and documentation updates.
- **Videos** — founder videos (why we built HollyEarth, what it does today, where it goes next) are in production.
- **Contact** — official contact channels will be published by HollyEarth / Lab Da Riga. Security or personal-data concerns: see [SECURITY.md](SECURITY.md).

Release history: [CHANGELOG.md](CHANGELOG.md).
