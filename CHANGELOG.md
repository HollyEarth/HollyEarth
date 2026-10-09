# Changelog

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
