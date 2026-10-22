<div align="center">

# HOLLYEARTH

### A LIVING UNIVERSE

**ONE SYSTEM. MANY WORLDS.**

**A world to explore, understand — and one day help change.**



From a sports club in Bolderāja to city decisions, from one place's story to planetary perspectives. Explore the connections between the world we live in and the worlds we can imagine.

`v0.1.0` · pilot / research & development project · documentation and media only · not open source

**English** · [Русский](docs/README_RU.md) · [Latviešu](docs/README_LV.md) · **[Visual Atlas →](docs/GALLERY.md)**

</div>

<a href="media/screenshots/02-riga-twin.png"><img src="media/screenshots/02-riga-twin.png" alt="HollyEarth — Riga Twin" width="100%"></a>

<sub>Real screenshot, v0.1.0. The Riga Twin: district, sport and social layers on a photorealistic 3D model of Riga. The "Wellbeing" pins are labelled DEMO.</sub>

---

## A Living Universe

![HollyEarth — THE UNIVERSE](media/infographics/overview.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

**The world is bigger than a dashboard.** What if you could move from a street in Riga to the story behind a local sports club, from an official decision to its source, or from a documented city case to a view of the planet?

**HollyEarth is A Living Universe:** a growing family of places, knowledge, investigations and immersive experiences. Start with Riga. Follow evidence, explore stories, enter new worlds. Our ambition reaches **from one neighbourhood to Earth** — and, in time, from understanding reality to taking part in improving it.

**Today:** a private research pilot with working experiences, prototypes, third-party integrations and openly labelled future concepts. It is not yet a publicly hosted, unified platform.

**An integral perspective keeps the human being in the picture.** Every place has more than one side: **I** — lived experience; **We** — relationships and community meaning; **Evidence** — what can be observed and sourced; **Systems** — institutions, infrastructure, rules and resources. This is a guiding perspective, **not a claim that v0.1.0 automatically analyses all four**.

**One place, several worlds:** a Bolderāja sports club can be explored through a map, archival results and public records, while the neighbourhood may one day become a playable story. These are **distinct modules and prototypes today**, not one fully linked end-to-end journey.

**Choose a world to explore:** every world below leads to real screenshots, maturity labels and a deeper gallery.

| World | What it is | Status | Gallery |
|---|---|---|---|
| **City — Riga Twin** | Riga in 3D with district, council, sport and social layers | `WORKING` | [Riga Twin](docs/gallery/RIGA_TWIN.md) |
| **Politics** | Riga City Council: sessions, decisions, deputies, parties, elections, budget, evidence — and an integral research workspace | `BETA` | [Politics](docs/gallery/POLITICS.md) |
| **Sport — HollySport** | Latvian clubs, athletes, events and venues from federations and result books; a game-styled sport city | `WORKING` · game layer `DEMO` | [HollySport](docs/gallery/HOLLYSPORT.md) |
| **Social — Social Intelligence** | Riga's registered social services on an interactive city stage | `SHOWCASE_READY` | [Social](docs/gallery/SOCIAL.md) |
| **Investigation** | Cases built from documents: claims, sources, quotations, typed money, open questions | `WORKING` | [Investigation](docs/gallery/INVESTIGATION.md) |
| **Intelligence** | Deterministic analysis, Holly, monitoring, optional model reasoning | `BETA` | [Holly AI](docs/gallery/HOLLY_AI.md) · [Monitoring](docs/gallery/MONITORING.md) |
| **Experience** | Story in three languages, passports, dossiers; Holly Eye — a third-party 3D globe with live world layers | `WORKING` · Holly Eye `BETA` | [Story](docs/gallery/HOLLY_AI.md#story) · [Holly Eye](docs/gallery/HOLLY_EYE.md) |

<details>
<summary><b>Technical foundation, current scope and limitations · v0.1.0</b></summary>

HollyEarth connects public knowledge, interactive worlds and traceable evidence. It brings together the city, its institutions and organisations, political decisions, public money, social services, sport, documents, sources and evidence — and lets a person explore them on a map, as a graph, as an investigation or as a story.

**Reality → Evidence → Intelligence → Experience → Action** — what registers, councils, federations and archives publish; kept with source, quotation, status and gaps; connected into cases, analysis and open questions; experienced as a 3D city, a sport city, a social map, case workspaces and narrated stories. *Action is `FUTURE`: nothing is written back to the world in v0.1.0.*

> **Vision and today are kept apart.**
> The goal is one connected model of a city. **Today HollyEarth is one product over several connected domain models, not yet one unified reality graph.** Politics and sport records live in one canonical graph but are not yet linked to each other; the social-services register has its own model; each investigation case keeps its own evidence graph; the Riga Twin shows several of these models on one map. See [ARCHITECTURE.md](ARCHITECTURE.md).

</details>


Statuses: `SHOWCASE_READY` · `WORKING` · `BETA` · `PROTOTYPE` · `DEMO` · `RESEARCH` · `FUTURE` — every feature in **[docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md)**. Every screen of the product, labelled: **[HollyEarth Visual Atlas](docs/GALLERY.md)**.

---

## City

![HollyEarth — CITY](media/infographics/city.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### What if your neighbourhood could tell its own story?

You pass a sports ground or a community facility in Riga and wonder: **Who is responsible for this place? Which official records mention it?** The answer is usually scattered across websites, maps and documents.

**Riga Twin turns the city into a starting point for exploration.** Districts, council records, sport locations and registered social-service buildings appear in one 3D experience, with contextual panels and paths toward sources. This isn't only a beautiful model — it helps make a familiar place **legible**.

**Why it matters:** residents can orient themselves, researchers can see unanswered questions, and partners can imagine better ways to present city data. The underlying records are **not yet one unified cross-domain graph**.


<a href="media/storycards/en/city.svg"><img src="media/storycards/en/city.svg" alt="HollyEarth city — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Real Riga Twin data, functions and limitations</b></summary>

**Your city is more than a map.** Explore Riga as a place where locations, institutions and public records acquire context. Open the city first; follow the source when something matters.

**Riga Twin** — the shared 3D map: 58 neighbourhoods, 428 council decisions with an address, 14 city-granted sport plots, 177 social-service buildings, district news, a council panel and doors to every other world. `WORKING`; Research mode and the AQAL overlay `PROTOTYPE`; Wellbeing `DEMO`.

</details>

<table>
<tr>
<td width="33%"><a href="media/gallery/twin/01-default-council.webp"><img src="media/gallery/twin/01-default-council.webp" alt="Twin with council panel"></a><br><sub>Council panel beside the city</sub></td>
<td width="33%"><a href="media/gallery/twin/03-layer-council-decisions.webp"><img src="media/gallery/twin/03-layer-council-decisions.webp" alt="Council decisions layer"></a><br><sub>Council decisions by district</sub></td>
<td width="33%"><a href="media/gallery/twin/17-aqal-overlay.webp"><img src="media/gallery/twin/17-aqal-overlay.webp" alt="AQAL overlay"></a><br><sub>AQAL overlay — `PROTOTYPE`</sub></td>
</tr>
</table>

Not yet: one shared place identity across domains; cases on the map; an answering research mode. → **[Riga Twin gallery](docs/gallery/RIGA_TWIN.md)** · [docs/twin.md](docs/twin.md)

---

## Politics

![HollyEarth — POLITICS](media/infographics/politics.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### Behind every decision are people, documents and consequences

A headline says the council has approved a project. **Who voted? Where is the decision? What does the official record actually say?** Getting beyond the headline can mean searching several disconnected sources.

**Political Holly OS makes the public record navigable:** sessions, officials, votes, documents and relationships. Experimental research lenses offer different views of the same records — not automated judgements about people or parties.

**The value is agency:** instead of accepting somebody else's summary, a person can follow available evidence and see where the public record leaves questions unanswered. These views do not establish real-world outcomes or individual integrity.


<a href="media/storycards/en/politics.svg"><img src="media/storycards/en/politics.svg" alt="HollyEarth politics — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Council coverage, modules and maturity</b></summary>

**A decision has a history.** Move beyond headlines to the official meeting, decision, vote and source record. HollyEarth helps make public institutions legible without treating automated analysis as a political verdict.

**Political Holly OS** — twelve modules over Riga City Council: 175 sessions, 456 decisions, 113 deputies, 7 parties, official 2025 election results, municipal spending and an evidence ledger. Modules range from `WORKING` (Network, Deputies, Parties & Power) through `BETA` to `DEMO` (District Impact, Smart City Lenses) and `RESEARCH` (Integral City).

</details>

<a href="media/gallery/politics/01-political-os.webp"><img src="media/gallery/politics/01-political-os.webp" alt="Political Holly OS" width="100%"></a>

**Integral Political Workspace** — eight research views over the same canonical records, `PROTOTYPE`: Political Archipelago · Focus Orbit · Evidence & Influence Flow · Holarchic Observatory · Integral Lens Field · Living City Torus · Geo / Twin Bridge · Relationship Graph.

<table>
<tr>
<td width="33%"><a href="media/gallery/workspace/01-political-archipelago.webp"><img src="media/gallery/workspace/01-political-archipelago.webp" alt="Political Archipelago"></a><br><sub>Political Archipelago</sub></td>
<td width="33%"><a href="media/gallery/workspace/02b-focus-orbit-selected.webp"><img src="media/gallery/workspace/02b-focus-orbit-selected.webp" alt="Focus Orbit"></a><br><sub>Focus Orbit</sub></td>
<td width="33%"><a href="media/gallery/workspace/03-evidence-influence-flow.webp"><img src="media/gallery/workspace/03-evidence-influence-flow.webp" alt="Evidence and Influence Flow"></a><br><sub>Evidence &amp; Influence Flow</sub></td>
</tr>
<tr>
<td width="33%"><a href="media/gallery/workspace/04-holarchic-observatory.webp"><img src="media/gallery/workspace/04-holarchic-observatory.webp" alt="Holarchic Observatory"></a><br><sub>Holarchic Observatory</sub></td>
<td width="33%"><a href="media/gallery/workspace/05-integral-lens-field.webp"><img src="media/gallery/workspace/05-integral-lens-field.webp" alt="Integral Lens Field"></a><br><sub>Integral Lens Field</sub></td>
<td width="33%"><a href="media/gallery/workspace/06-living-city-torus.webp"><img src="media/gallery/workspace/06-living-city-torus.webp" alt="Living City Torus"></a><br><sub>Living City Torus</sub></td>
</tr>
</table>

Data is real and sourced; several modules have known gaps (budget lines not imported, session data from July 2026), and a labelled demo analysis project appears above most modules. → **[Politics gallery](docs/gallery/POLITICS.md)** · [docs/politics.md](docs/politics.md)

---

## Sport

![HollyEarth — SPORT](media/infographics/sport.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### There is a whole community behind one line in a results book

A young person joins a club. Seasons pass. An official results sheet preserves a result — but the story of the club, its events, venues and sporting community is scattered across archives.

**HollySport makes that world explorable.** Publicly recorded clubs, competitions, locations and results can be approached as profiles, a map and connections — not only rows in a spreadsheet.

**Who benefits:** clubs can present their history, event organisers can demonstrate competitions, and curious people can explore their sporting landscape. The game layer, wallet and economy are still **demos, prototypes or future directions**, not live commercial products.


<a href="media/storycards/en/sport.svg"><img src="media/storycards/en/sport.svg" alt="HollyEarth sport — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Sport data coverage, passports and product maturity</b></summary>

**Behind every result is a community.** Clubs, venues, events and athletes become navigable profiles grounded in publicly available archives. The game-like experience is a `DEMO`; organisers' tools are prototypes.

**HollySport** — **18,143 athletes · 227 events · 1,326 bouts · 8,401 placings · 297 clubs and federations · 133 venues** from federation registers, official result books and public archives; no stored results of minors. Passports `WORKING` / `SHOWCASE_READY`; City Game `DEMO`; Event OS and Creator `PROTOTYPE`; MetaSport economy `FUTURE`.

</details>

<a href="media/screenshots/07-hollysport-city.png"><img src="media/screenshots/07-hollysport-city.png" alt="HollySport City" width="100%"></a>

<table>
<tr>
<td width="33%"><a href="media/screenshots/08-club-passport.png"><img src="media/screenshots/08-club-passport.png" alt="Club passport"></a><br><sub>Club passport</sub></td>
<td width="33%"><a href="media/gallery/sport/12-athlete-passport.webp"><img src="media/gallery/sport/12-athlete-passport.webp" alt="Athlete passport"></a><br><sub>Athlete passport</sub></td>
<td width="33%"><a href="media/gallery/sport/15-event-results.webp"><img src="media/gallery/sport/15-event-results.webp" alt="Event results"></a><br><sub>Event results — adults only</sub></td>
</tr>
<tr>
<td width="33%"><a href="media/gallery/sport/19-sport-graph.webp"><img src="media/gallery/sport/19-sport-graph.webp" alt="Sport graph"></a><br><sub>Sport graph</sub></td>
<td width="33%"><a href="media/screenshots/16-hollysport-missions-demo.png"><img src="media/screenshots/16-hollysport-missions-demo.png" alt="Missions demo"></a><br><sub>Missions — `DEMO`</sub></td>
<td width="33%"><a href="media/gallery/sport/25-wallet-preview.webp"><img src="media/gallery/sport/25-wallet-preview.webp" alt="Wallet preview"></a><br><sub>Wallet — `FUTURE` preview</sub></td>
</tr>
</table>

The game and economy layers show where the platform is going; they are not working commercial services. Event OS is a planning prototype, not an event registration service. → **[HollySport gallery](docs/gallery/HOLLYSPORT.md)** · [docs/sport.md](docs/sport.md)

---

## Social

![HollyEarth — SOCIAL](media/infographics/social.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### Finding help takes more than a list of addresses

Imagine a family trying to locate a relevant social service. A registry may list a provider — but **is the service actually available to this person, at this place, today?** The public record often cannot answer that.

**Social Intelligence brings registered services onto an understandable city stage.** Explore providers, locations and documents; open a dossier; see both the published facts and **the questions the data cannot settle**.

**Honesty is part of the value.** Registered does not mean received, planned capacity is not proof of actual delivery, and unknown payments are not zero. This is a research interface — **not an emergency help service or a live availability checker**.


<a href="media/storycards/en/social.svg"><img src="media/storycards/en/social.svg" alt="HollyEarth social — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Registry snapshot, grounded counts and limitations</b></summary>

**A service on paper is not the same as a service received.** Locate registered providers, inspect their dossiers and see what public records do **not** establish about access, payments or outcomes.

**Social Intelligence** — Riga's social services from the Ministry of Welfare's official register (14 September 2026): **256 services · 106 providers · 177 buildings · 28 delivered at home.** `SHOWCASE_READY`.

</details>

<a href="media/screenshots/10-social-stage.png"><img src="media/screenshots/10-social-stage.png" alt="Social Intelligence" width="100%"></a>

<table>
<tr>
<td width="33%"><a href="media/screenshots/11-social-dossier.png"><img src="media/screenshots/11-social-dossier.png" alt="Service dossier"></a><br><sub>Service dossier — what is not known</sub></td>
<td width="33%"><a href="media/gallery/social/05-holly-sees.webp"><img src="media/gallery/social/05-holly-sees.webp" alt="Holly sees"></a><br><sub>"Holly sees" — register counts, not an assessment</sub></td>
<td width="33%"><a href="media/gallery/social/06-agreements.webp"><img src="media/gallery/social/06-agreements.webp" alt="Delegation agreements"></a><br><sub>Delegation agreements</sub></td>
</tr>
</table>

**Registered ≠ delivered · unknown ≠ zero.** People served, actual payments and quality are unknown for all 256 services and shown as unknown. Providers are not yet linked to the main graph. → **[Social gallery](docs/gallery/SOCIAL.md)** · [docs/social.md](docs/social.md)

---

## Investigation

![HollyEarth — INVESTIGATION](media/infographics/investigation.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### A million euros can mean very different things

One document describes a **planned budget**, another a **contract value**, another an **award**. Add them carelessly, and the result sounds dramatic — but says very little about what happened.

**HollyEarth follows the evidence before it tells the story.** A case collects source documents, exact quotations, attributed claims, typed money and unanswered questions. Explore not just a conclusion, but **why it might be supported — or why it remains uncertain**.

For researchers and journalists, the value is retaining context and resisting false certainty. Automated support is **not human verification**.


<a href="media/storycards/en/investigation.svg"><img src="media/storycards/en/investigation.svg" alt="HollyEarth investigation — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Cases, evidence mechanics and known gaps</b></summary>

**Don't just read a conclusion. Follow its trail.** Each case brings quotations, source documents, the kind of money mentioned and unresolved questions into a navigable research experience.

A case gathers a council decision, a procurement or an organisation with its sources, exact quotations, claims, typed money, open questions and the route the investigation took. 9 cases in v0.1.0.

</details>

<a href="media/screenshots/03-case-overview.png"><img src="media/screenshots/03-case-overview.png" alt="Case overview" width="100%"></a>

<table>
<tr>
<td width="25%"><a href="media/gallery/investigation/01-case-gallery.webp"><img src="media/gallery/investigation/01-case-gallery.webp" alt="Case gallery"></a><br><sub>Case gallery</sub></td>
<td width="25%"><a href="media/screenshots/04-evidence.png"><img src="media/screenshots/04-evidence.png" alt="Evidence path"></a><br><sub>Where an amount comes from</sub></td>
<td width="25%"><a href="media/screenshots/05-roadmap.png"><img src="media/screenshots/05-roadmap.png" alt="Roadmap"></a><br><sub>Course of the investigation</sub></td>
<td width="25%"><a href="media/gallery/investigation/06-kbs-explore.webp"><img src="media/gallery/investigation/06-kbs-explore.webp" alt="Sport club case"></a><br><sub>A sport club's case</sub></td>
</tr>
</table>

**Claim ≠ verified fact.** All 111 case claims are asserted, each with its source and quotation; "confirmed" means directly supported by a quotation; none has been checked by a person. **Planned ≠ paid:** money is typed and never summed across types; cases and Social hold no payment records. → **[Investigation gallery](docs/gallery/INVESTIGATION.md)** · [docs/cases.md](docs/cases.md)

---

## Intelligence

![HollyEarth — INTELLIGENCE](media/infographics/intelligence.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### An AI answer can sound confident. Can you check it?

For questions about public money, institutions and people, a fluent answer without evidence is a risk, not a feature.

**Holly assists research rather than claiming omniscience.** Existing case workflows draw on stored records and deterministic analysis; optional model reasoning may suggest hypotheses, which remain hypotheses. Source monitoring exists, but is still initiated manually.

**The aim:** give people better questions, traceable foundations and explicit uncertainty. A universal, fully autonomous Holly agent **does not exist in v0.1.0**.


<a href="media/storycards/en/intelligence.svg"><img src="media/storycards/en/intelligence.svg" alt="HollyEarth intelligence — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 What Holly actually does in v0.1.0</b></summary>

**AI should help you ask, not pretend to know.** HollyEarth combines traceable records, deterministic analysis and optional model-assisted hypotheses. The assistant is case-scoped in v0.1.0, not a universal autonomous agent.

HollyEarth works without a language model. Holly is deterministic helpers plus a case-scoped assistant; model reasoning is optional and always labelled as hypothesis. Monitoring watches the official sources behind cases — run by hand, no automatic scheduler yet. A global assistant and autonomous agents are not part of v0.1.0.

</details>

<table>
<tr>
<td width="50%"><a href="media/gallery/holly/01-analysis-model-hypotheses.webp"><img src="media/gallery/holly/01-analysis-model-hypotheses.webp" alt="Analysis and model reasoning"></a><br><sub>Deterministic analysis beside <b>model-generated</b> hypotheses — `BETA`</sub></td>
<td width="50%"><a href="media/screenshots/18-monitoring.png"><img src="media/screenshots/18-monitoring.png" alt="Monitoring"></a><br><sub>Monitoring: 18 watches, 26 runs — `BETA`</sub></td>
</tr>
</table>

→ **[Holly AI gallery](docs/gallery/HOLLY_AI.md)** · **[Monitoring / Observatory gallery](docs/gallery/MONITORING.md)** · [docs/holly-ai.md](docs/holly-ai.md) · [docs/monitoring.md](docs/monitoring.md)

---

## Experience

![HollyEarth — EXPERIENCE](media/infographics/experience.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### Information becomes easier to understand when you can experience it

Not everyone wants to read an evidence table. Some people want a story told in chapters; others want a place they can see.

**Story** presents cases as a sequence of chapters in Russian, Latvian and English. The Riga Twin adds a spatial viewpoint. **Holly Eye** changes scale to the planet through an explicitly credited **third-party integration**, including satellites, flight activity and other world data layers.

These are different ways to engage with information, connected through navigation — **not yet one seamless reality model**.


<a href="media/storycards/en/experience.svg"><img src="media/storycards/en/experience.svg" alt="HollyEarth experience — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Stories, voice, Holly Eye and integration limits</b></summary>

**Information becomes meaningful when you can experience it.** Move between a city, a documented case and a multilingual story. Holly Eye adds a planetary perspective as a clearly attributed **third-party integration**.

</details>

<table>
<tr>
<td width="33%"><a href="media/screenshots/06-story.png"><img src="media/screenshots/06-story.png" alt="Story"></a><br><sub><b>Story</b> — a case told as chapters in RU / LV / EN, assembled from its records. `WORKING`</sub></td>
<td width="33%"><a href="media/gallery/holly/04-story-versions.webp"><img src="media/gallery/holly/04-story-versions.webp" alt="Story versions and voices"></a><br><sub><b>Versions and voices</b> — local, hosted (with confirmation) or browser voice. `BETA`</sub></td>
<td width="33%"><a href="media/gallery/holly-eye/01-planet-europe-3d.webp"><img src="media/gallery/holly-eye/01-planet-europe-3d.webp" alt="Holly Eye globe"></a><br><sub><b>World — Holly Eye</b> — a 3D globe with live public data layers. A <b>third-party integration</b> (God's Eye View by Bilawal Sidhu), not HollyEarth technology. `BETA`</sub></td>
</tr>
<tr>
<td width="33%"><a href="media/gallery/holly-eye/40-satellites.webp"><img src="media/gallery/holly-eye/40-satellites.webp" alt="Holly Eye satellites"></a><br><sub>Holly Eye — 830 satellites from CelesTrak</sub></td>
<td width="33%"><a href="media/gallery/holly-eye/03-riga-3d-old-town.webp"><img src="media/gallery/holly-eye/03-riga-3d-old-town.webp" alt="Holly Eye Riga in 3D"></a><br><sub>Holly Eye — Riga in 3D</sub></td>
<td width="33%"><a href="media/gallery/holly-eye/21-live-flights.webp"><img src="media/gallery/holly-eye/21-live-flights.webp" alt="Holly Eye live flights"></a><br><sub>Holly Eye — live flights</sub></td>
</tr>
<tr>
<td width="33%"><a href="media/gallery/holly-eye/24-ais-vessels-channel.webp"><img src="media/gallery/holly-eye/24-ais-vessels-channel.webp" alt="Holly Eye AIS vessels"></a><br><sub>Holly Eye — live AIS vessels</sub></td>
<td width="33%"><a href="media/gallery/holly-eye/53-active-fires-osm-close.webp"><img src="media/gallery/holly-eye/53-active-fires-osm-close.webp" alt="Holly Eye NASA FIRMS fires"></a><br><sub>Holly Eye — NASA FIRMS active fires</sub></td>
<td width="33%"></td>
</tr>
</table>

Not every story chapter is linked to individual claims yet. → [Story](docs/gallery/HOLLY_AI.md#story) · [Holly Eye gallery](docs/gallery/HOLLY_EYE.md) · [Holly Eye media provenance](media/HOLLY_EYE_PROVENANCE.md) · [docs/story.md](docs/story.md)

---

## HollyWorlds — Unreal Engine explorations

![HollyWorlds — Unreal Engine](media/infographics/worlds.svg)

*Concept infographic — not an Unreal Engine capture.*

### What if you could drive through the world you're exploring?

Imagine Bolderāja not only as a dot on the map but as the setting for a future mission: a character moves through streets, explores places and begins a story.

Two separate **Unreal Engine experiments** point in that direction. **Planetary Sandbox** explores large-scale geography with a playable character and vehicles. **AGLS / Bolderāja** is a local map intended for missions and scenarios.

For now, these are **standalone prototypes**. Completed Bolderāja missions and a working connection to HollyEarth Core are **not claimed**.


<a href="media/storycards/en/unreal.svg"><img src="media/storycards/en/unreal.svg" alt="HollyEarth unreal — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🎮 Confirmed prototype scope and next steps</b></summary>

**Play the world, not just view it.** HollyWorlds is a separate experimental track beyond the v0.1.0 web platform. One Unreal Engine prototype explores a traversable planetary environment with a playable character, driving and shooting mechanics (reported by the creators). A second prototype, **AGLS / Bolderāja**, focuses on a local map intended for missions and narrative scenarios. These are **standalone prototypes**: missions in Bolderāja and integration with HollyEarth Core are not presented as completed features.

</details>

---

## Research

![HollyEarth — RESEARCH](media/infographics/research.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### Understanding a city takes more than one point of view

A sports club is a personal journey for one person, a community for another, a collection of results and documents for a researcher, and part of the city's infrastructure for an institution.

This inspires our **integral perspective**: **I — lived experience; We — shared meaning; It — observable evidence; Systems — organisations, places and processes**. The idea is to avoid mistaking a single metric for the whole of reality.

**HEIO and HEIM are research directions** exploring how these perspectives might relate. They are not complete working ontologies or tools for scoring people, neighbourhoods or political beliefs.


<a href="media/storycards/en/research.svg"><img src="media/storycards/en/research.svg" alt="HollyEarth research — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Implemented foundations and HEIO / HEIM research</b></summary>

**Big ideas deserve precise labels.** The implemented foundations are provenance, epistemic status, graph records and spatial views. HEIO, HEIM and integral perspectives are active **research directions**, not fully delivered technologies.

Implemented in v0.1.0: an epistemic model (no unconditional "fact"), provenance on every record, a canonical graph and spatial representation. HEIO and HEIM are internal research documents — **concept architecture, not implemented features**. Integral / AQAL, Spiral Dynamics and Integral City are research influences, never used to rate people, parties or districts.

</details>

<table>
<tr>
<td width="50%"><a href="media/concepts/09-heio-concept-architecture.png"><img src="media/concepts/09-heio-concept-architecture.png" alt="HEIO concept illustration"></a><br><sub><b>Concept illustration.</b> HEIO — HollyEarth Integral Ontology (v0.1). `RESEARCH`</sub></td>
<td width="50%"><a href="media/concepts/10-heim-context-system.png"><img src="media/concepts/10-heim-context-system.png" alt="HEIM concept illustration"></a><br><sub><b>Concept illustration.</b> HEIM — HollyEarth Integrative Metatheory &amp; Context System (v0.2). `RESEARCH`</sub></td>
</tr>
</table>

→ **[Research & Concept Art gallery](docs/gallery/RESEARCH_CONCEPTS.md)** — including nine concept illustrations from the project's design history, each marked as concept / illustrative / not live product data · [docs/research.md](docs/research.md)

---

## Future

![HollyEarth — FUTURE](media/infographics/future.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### What if understanding a place could lead to taking part?

Today there are ways to explore public records and prototypes of new experiences. In the future, the ambition is more participatory: people proposing improvements, collaborating on local projects and examining real outcomes.

That takes both technology and a **sustainable economic model**. We intend to combine a proprietary intelligence core with selectively open-source tools and independent community projects — so openness can grow alongside the ability to pay for the work.

Participation workflows, wallets and economic mechanisms remain **future directions**, not services available today.


<a href="media/storycards/en/future.svg"><img src="media/storycards/en/future.svg" alt="HollyEarth future — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🗺️ Roadmap by maturity: working / in development / research / future</b></summary>

**Open collaboration. Sustainable intelligence.** The intended business model combines a proprietary intelligence core with selectively open-source community tools and independent projects. This repository is **documentation-only**, and no proprietary code is being released.

</details>

| Exists today | In development | Research | Future |
|---|---|---|---|
| Riga Twin · Cases, evidence, roadmap, Story · HollySport data and passports · Social Intelligence · Politics data and workspace · Monitoring (manual) · RU / LV / EN · Holly Eye door (third-party) | Shared identity across domains · Social in the main graph · money semantics (planned → contracted → awarded → paid) · scheduled monitoring · human review · claim-linked story chapters · hosted pilot · Event OS, Creator and partnerships (prototypes) | HEIO · HEIM · Integral / AQAL · Spiral Dynamics (context only) · Integral City | Governed action and appeals · HollyWorlds · MetaSport economy · public hosted instance · more cities |

HollySport's game layer remains `DEMO` until it is built on real mechanics. → [ROADMAP.md](ROADMAP.md)

---

## Current Capabilities

![HollyEarth — CAPABILITIES](media/infographics/capabilities.svg)

*Original concept infographic — a visual metaphor, not a product screenshot.*

### A compelling vision needs evidence of what is real

It is easy to describe the future of a complex product. We choose to mark **what actually works**, what is experimental, what is merely illustrated and what is still a research direction.

The overview below is not a dry scorecard: it helps a prospective partner or researcher understand **what can be demonstrated now and what could be built together**.


<a href="media/storycards/en/capabilities.svg"><img src="media/storycards/en/capabilities.svg" alt="HollyEarth capabilities — illustrated story" width="100%"></a>

*Concept story illustration — a human question, three steps and a benefit. Not a product screenshot.*

<details>
<summary><b>🔎 Reading the capability matrix</b></summary>

**You can see both the promise and the proof.** The detailed matrix below separates working experiences from beta, demo, research and future directions. A concept is not presented as a finished feature.

</details>

| Area | Showcase-ready | Working | Beta / prototype | Demo / research / future |
|---|---|---|---|---|
| Core | — | Provenance · typed money · claims with status · spatial layers · RU / LV / EN | Cross-domain links (partial) | One unified reality graph (`FUTURE`) |
| City | — | 3D Twin · decision, sport and social layers | Research mode · AQAL (`PROTOTYPE`) | Wellbeing scores (`DEMO`) |
| Politics | — | Network · Deputies · Parties & Power | Political OS · Sessions · Decisions · Budget · Evidence Ledger · Workspace | District Impact · Smart City Lenses (`DEMO`) · Integral City (`RESEARCH`) |
| Sport | Club passport · Event passport | Sport City · archive · passports · map · graph | Rankings · Event OS · Creator · Partnerships | Game layer (`DEMO`) · economy (`FUTURE`) |
| Social | Stage · service dossier | Catalogue · map · organisation dossier · agreements | Money · Planning | Need, outcomes, payments (`RESEARCH`) |
| Investigation | Case gallery · evidence path | Case workspace · roadmap · analysis · Story | Holly · research runs · voice · monitoring | Human verification workflow (`FUTURE`) |

Full matrix: **[docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md)** · [CAPABILITIES.md](CAPABILITIES.md) · [MODULES.md](MODULES.md)

## Architecture / Data Principles

**Every record has provenance** · **claim ≠ verified fact** ("verified" in the data never means a person checked it unless it says so) · **no record ≠ no reality** · **unknown ≠ zero** · **planned ≠ paid** · **registered ≠ delivered** · **model output ≠ evidence** · **no stored competition results of minors** · **demo data is labelled DEMO**. → [ARCHITECTURE.md](ARCHITECTURE.md) · [DATA_PRINCIPLES.md](DATA_PRINCIPLES.md) · [DATA_SOURCES.md](DATA_SOURCES.md)

All published images with captions, statuses and attributions: [media/README.md](media/README.md).

---

## Authors / Lab Da Riga

**HollyEarth** is created by **Stanislav Petrovsky** and **Irina Petrovskaya**, Riga, Latvia.

Copyright © 2026 Lab Da Riga. All rights reserved.

This repository contains documentation and media only. It is **not open source** and contains no source code — see [LICENSE.md](LICENSE.md) and [NOTICE.md](NOTICE.md). Third-party maps, data and components remain under their owners' terms.

## Contact / Follow the Project

**Our promise:** show what is built, label what is experimental, and invite partners to help shape what comes next.


- **Follow** — watch this repository and the [HollyEarth organisation](https://github.com/HollyEarth) for releases and documentation updates.
- **Videos** — founder videos (why we built HollyEarth, what it does today, where it goes next) are in production.
- **Contact** — official contact channels will be published by HollyEarth / Lab Da Riga. Security or personal-data concerns: see [SECURITY.md](SECURITY.md).

Release history: [CHANGELOG.md](CHANGELOG.md).
