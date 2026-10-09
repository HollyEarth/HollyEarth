# Architecture (overview)

A high-level view of how HollyEarth v0.1.0 is actually organised, followed by where it is meant to go. Implementation details and source code are not published.

## Today — v0.1.0

```
  Sources: council publications and voting protocols · election results · company and procurement
           registers · the social-service provider register · address register · federations,
           result books and sport archives · open city data · documents read inside cases
        │  imported with source, snapshot and import path
        ▼
  ┌──────────────────────── Shared provenance base ─────────────────────────┐
  │ sources · source snapshots                                              │
  └──────┬─────────────────────────────┬──────────────────────┬─────────────┘
         ▼                             ▼                      ▼
  ┌──── Canonical graph ────┐   ┌── Social register ──┐  ┌──── Case layer ─────────────┐
  │ politics sub-graph      │   │ providers, services │  │ one evidence graph per case │
  │ sport sub-graph         │   │ buildings, facts,   │  │ claims + quotations, typed  │
  │ (not yet linked to each │   │ agreements, money   │  │ money, gaps, tasks, runs,   │
  │ other) · places         │   │ (own model)         │  │ analyses, stories, watches  │
  └───────────┬─────────────┘   └─────────┬───────────┘  └──────┬──────────────────────┘
              │                           │     anchored to one canonical record per case
              └──────────────┬────────────┴─────────────────────┘
                             ▼
  Experience: Start · Riga Twin (several models on one map) · Politics · HollySport City and
              passports · Social stage · Case workspace · Story · Monitoring · Holly
              · World door → Holly Eye (separate third-party application)
```

### What this means

- **One schema and one provenance base, several domain models.** Politics and sport records live in one canonical graph (25,127 entities, 26,293 relationships, 11,115 claims, 18,377 evidence records, 565 places), but as two sub-graphs with no relationship between them yet. The social-services register (256 services, 106 providers, 177 buildings, 3,110 facts) has its own model and is not part of the canonical graph; its 177 buildings are not among the 565 canonical places.
- **Cases are evidence graphs of their own.** Each case is anchored to one canonical record (a council decision or a club) and keeps its own entities, claims with quotations, money and open questions. 24 of the 104 case entities are resolved to canonical records today; the rest are candidates. Case claims are not yet promoted into the canonical graph.
- **The Twin composes several models.** Council decisions and sport plots come from the canonical graph, social buildings from the social register, district boundaries from an open-data snapshot, and the Wellbeing pins are demo values.
- **Cross-domain links are doors, not shared identity.** Club → case, social provider → case (one), decision → case through the Twin, and navigation between modules. Shared identity for organisations and places across domains is in development.
- **Status is part of the data.** Claims are asserted, corroborated or (for structural relationships) verified — automatically, never by a person so far. See [DATA_PRINCIPLES.md](DATA_PRINCIPLES.md).
- **AI sits around the core, not inside it.** Everything above works without a language model. Optional model calls (case chat, reasoning, model-assisted extraction, story wording, decision analysis) are labelled, and models cannot write into the canonical graph or set a verified status. Model-proposed case claims are kept only if their quotation is found word for word in the source. See [docs/holly-ai.md](docs/holly-ai.md).
- **Runtime.** HollyEarth runs as a private installation on a relational database with a spatial extension. There is no public hosted instance; production hardening (authentication, rate limits, AI cost controls) is in development.

## Direction — where the architecture is going

These are goals, not features of v0.1.0:

- **Shared identity** — one organisation, person or place recognised across politics, sport, social and cases, with an organisational hierarchy (legal entity → institution → department → service provider → unit), so that one registration number shared by many municipal bodies is not mistaken for one organisation.
- **Social in the graph** — providers, services and buildings as canonical entities and places.
- **Contracts and money semantics** — agreements and contracts as first-class records; money modelled from planned to committed, contracted, awarded, invoiced and paid.
- **Case → core** — reviewed case findings promoted into the canonical graph, with a human verification workflow.
- **Shared places** — one place identity for the Twin, Sport City, the Social stage and cases.
- **One AI gateway** — every model and voice provider behind one boundary with budgets and logging.

The long-term picture — one connected, evidence-aware model of a city — is described in [VISION.md](VISION.md). Research concepts (HEIO, HEIM) are in [docs/research.md](docs/research.md).

## Third-party components

HollyEarth integrates third-party components and services, for example a 3D mapping platform for the Twin, OpenStreetMap data, optional model and voice providers, and the open-source **God's Eye View** application (by Bilawal Sidhu) for the planetary **Holly Eye** view. These remain under their own licences and terms; see [NOTICE.md](NOTICE.md) and [DATA_SOURCES.md](DATA_SOURCES.md).
