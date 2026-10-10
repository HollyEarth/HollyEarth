# Changelog

## Holly Eye gallery — 2026-10-09

- **[Holly Eye gallery](docs/gallery/HOLLY_EYE.md)** — 46 new screenshots of the third-party Holly Eye integration (God's Eye View by Bilawal Sidhu, MIT): the 3D globe and Riga in 3D, eight visual styles, 14 world layers (flights, military flights, satellites, space missions, earthquakes, NASA FIRMS active fires, AIS vessels, radio, datacenters, dams, simulated street traffic and more), scenes, context, the voice dock and the door from HollyEarth.
- Each copy keeps the frame unchanged — including the application's own map credits and the provider's notices — and adds an information band below it with status, layer data source and map / imagery credit.
- [Media provenance](media/HOLLY_EYE_PROVENANCE.md) for every image — application by Bilawal Sidhu, integration and interface by HollyEarth / Lab Da Riga, map imagery and data by their providers — with the terms that apply. The images are shared as part of a non-commercial presentation (owners' determination); the MIT licence of the application covers its code, not the map imagery or data.
- Visual Atlas, README, [docs/holly-eye.md](docs/holly-eye.md) and the media index updated.

## Visual atlas — 2026-10-09

- **[HollyEarth Visual Atlas](docs/GALLERY.md)** — 15 sections and nine galleries: [Riga Twin](docs/gallery/RIGA_TWIN.md), [Politics and the Integral Political Workspace](docs/gallery/POLITICS.md) (all eight research views), [HollySport](docs/gallery/HOLLYSPORT.md), [Social](docs/gallery/SOCIAL.md), [Investigation](docs/gallery/INVESTIGATION.md), [Monitoring / Observatory](docs/gallery/MONITORING.md), [Holly AI / Story](docs/gallery/HOLLY_AI.md), [Holly Eye](docs/gallery/HOLLY_EYE.md), [Research & Concept Art](docs/gallery/RESEARCH_CONCEPTS.md).
- 131 published images: 120 real product screenshots (WORKING to FUTURE, each labelled), 2 research concept illustrations and 9 concept illustrations marked as concept / fictional example data / earlier design exploration.
- README rebuilt around City, Politics, Sport, Social, Investigation, Intelligence, Experience, Research and Future, with 34 images.
- 3D-city screenshots (Riga Twin, HollySport City) published after the owners confirmed the rights to the GeoRiga data.
- Public copies: personal data blurred in two frames; one product label corrected (a mistaken VERIFIED badge); demo screens marked; the ecosystem concept's wrong language flags replaced with RU · LV · EN. [media/README.md](media/README.md) lists every change.

## Documentation update — 2026-10-09

No product release; the public documentation was rebuilt from an internal product audit of v0.1.0.

### Added
- README restructured around **ONE SYSTEM. MANY WORLDS.**, with every world (City, Politics, Sport, Social, Investigation, Intelligence, Experience) showing what works and what does not yet.
- [docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md) — status, real data, limitations and next step for every significant feature.
- New pages: [Politics](docs/politics.md), [Monitoring](docs/monitoring.md), [Holly AI](docs/holly-ai.md), [Holly Eye](docs/holly-eye.md), [Research](docs/research.md).
- Russian and Latvian summaries: [docs/README_RU.md](docs/README_RU.md), [docs/README_LV.md](docs/README_LV.md).
- 15 real product screenshots and a media index: [media/README.md](media/README.md). Two research concept illustrations (HEIO, HEIM). Screenshots of the 3D city follow once the reuse terms of the Riga 3D city model are confirmed.

### Corrected
- **The social-services register is not part of the canonical graph.** Earlier v0.1.0 documents described politics, sport and social records as one graph. In v0.1.0 politics and sport share the canonical graph (as two sub-graphs not yet linked to each other) and the social register keeps its own model.
- **The 177 social-service buildings are not among the 565 canonical places.** They are drawn on the same map but belong to a separate model.
- **"Verified" is not human verification.** Verified and corroborated statuses in v0.1.0 come from automated checks; no claim has been checked by a person.
- **Money.** Investigation cases and Social hold no recorded payment executions; the Politics City Budget module reads a separate municipal spending dataset whose payment semantics are still being established.
- **"One City · One Graph"** is presented as the vision, not as a description of v0.1.0.
- Twin documentation: the council-decision card currently shows a VERIFIED badge that does not mean verification.

## v0.1.0 — Public Baseline (2026-10)

The first integrated baseline of HollyEarth: one evidence core, three lenses, one city.

### Core
- Canonical, evidence-aware graph holding politics and sport records, each with provenance; the social-services register is kept in its own model *(corrected 2026-10-09 — earlier text said all three domains were in one graph)*.
- Claims with explicit status (asserted, corroborated, verified, partially supported) and source quotations.
- Typed money: planned, contract, awarded, ceiling and rate kept apart and never summed across types.
- Spatial representation: official district geometry, address-register points, 3D city.
- Interface in Russian, Latvian and English.

### Investigations
- Investigation cases with established facts, open questions, typed money, analysis and monitoring.
- Evidence and provenance inspector ("where did this come from").
- Investigation roadmap — the route a real investigation took.
- Story — a case narrated in three languages, assembled from its own records.
- Source monitoring (beta).

### City
- 3D Riga Twin with district, sport, social and council layers, including council decisions on the map.
- Illustrative district scores clearly labelled DEMO.

### Politics
- Riga City Council as a graph: meetings, agenda, decisions, votes, deputies, factions, committees.
- The political lens counts only the council's own records.

### Sport — HollySport
- Sport records from Latvian federation registers, official result books and public archives.
- Club, athlete, event and venue passports with shareable links.
- HollySport City over the Twin; club → investigation case.
- No stored competition results of minors.
- Season / missions / XP preview, labelled DEMO.

### Social — Social Intelligence
- Riga's register of social service providers as an interactive city stage.
- Service and provider dossiers; commissioner and agreements, money and planning views.
- Explicit distinction between registered services and services actually received.

### World
- Planetary view through the third-party Holly Eye integration (God's Eye View).
