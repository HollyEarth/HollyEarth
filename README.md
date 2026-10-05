# HollyEarth

**Reality → Evidence → Intelligence → Experience**

HollyEarth is an evidence-aware spatial intelligence platform connecting real-world data, provenance, investigations and interactive city experiences in one evolving graph.

Created in Riga, Latvia, by Stanislav Petrovsky and Irina Petrovskaya.
Current release: **v0.1.0 — Public Baseline** (documentation and media only; see [LICENSE](LICENSE.md)).

**Languages**

- English — canonical documentation
- Latvian — public summary planned
- Russian — public summary planned

---

## What HollyEarth is

Cities publish an enormous amount of information — council decisions, contracts, registers of services, sport results, addresses — but it lives in separate places, in different formats, and rarely says how sure anyone is about any of it.

HollyEarth brings those records into **one graph**. Every record keeps its source. Every claim keeps its status. A question about public money becomes an **investigation case** that shows what is established, what is only asserted, what is still unknown and what to check next. A case can then **tell itself** as a narrated story, and the whole city can be explored **spatially** — as a 3D twin of Riga, a sport city, or a map of the social system.

The first city is **Riga**. The first three domain lenses are **Politics**, **Sport** and **Social services**.

## What works today

Verified in v0.1.0 against real data:

- **One canonical graph** holding council records, sport records and the social-services register side by side, each with provenance.
- **Investigation cases** — evidence, typed money, open questions, the route the investigation took, and monitoring of the sources behind it.
- **Story** — a case narrated chapter by chapter in Russian, Latvian and English, assembled from the case's own records.
- **3D Riga Twin** — the city as a navigable 3D scene with district, sport and social layers.
- **HollySport** — clubs, athletes, events and venues from official and public sources, with shareable passports.
- **Social Intelligence** — Riga's registered social services on an interactive city stage, with agreements, money and planning views.
- **Three interface languages** — Russian, Latvian and English across the new surfaces.

HollyEarth currently runs as a private installation. There is no public hosted instance yet.

## One graph — multiple lenses

```
                 ┌──────────────── Experience ─────────────────┐
                 │  Riga Twin · Sport City · Social stage       │
                 │  Cases · Story · Passports                   │
                 ├──────────────── Lenses ─────────────────────┤
                 │   Politics      Sport        Social          │
                 ├──────────────── Core ───────────────────────┤
                 │  canonical graph · entities & relationships  │
                 │  claims · evidence · provenance · cases      │
                 │  typed money · roadmap · story · monitoring  │
                 │  spatial representation                      │
                 └──────────────────────────────────────────────┘
```

A deputy and a boxer are both people in the same graph. What separates them is **where each record came from and on whose authority** — the lens decides what belongs to a domain, not a separate database.

## Core capabilities

| Capability | Status |
|---|---|
| Canonical graph with provenance on every record | WORKING |
| Claims and evidence with source quotations | WORKING |
| Typed money (planned / contract / awarded / rate) | WORKING |
| Investigation cases | SHOWCASE READY |
| Investigation roadmap | WORKING |
| Story (RU / LV / EN) | SHOWCASE READY |
| Source monitoring | BETA |
| Spatial representation (3D Twin, district geometry, address register) | WORKING |

Full list: [CAPABILITIES.md](CAPABILITIES.md).

## Politics

Riga City Council as a graph: meetings, agenda items, decisions, votes, deputies, factions and committees, plus the organisations named in decisions and the money those decisions publish. Council decisions that name an address appear on the city map. Politics is also the domain of the first full investigation cases. [More →](docs/cases.md)

## Sport

HollySport turns Latvian sport records into a navigable city: clubs, athletes, events and venues from federation registers, official result books and public archives, each with a shareable **passport**. A club passport is a window into a case about that club. A season / missions / XP layer exists as a clearly labelled **demo preview** — it is not a working game. [More →](docs/sport.md)

## Social

Riga's registered social services — who provides them, for whom, where, and under which agreements — on an interactive city stage. It shows exactly what the register says and is explicit about what it cannot say: a registered service is not the same as a service actually received. [More →](docs/social.md)

## Data honesty principles

- Every record has provenance.
- Asserted is not verified.
- The absence of a record is not the absence of reality.
- Different kinds of money are never added together.
- A registered service is not a service actually received.
- Model output is never automatically fact.
- HollySport does not publish stored competition results of minors.
- Demo data is always labelled DEMO.

These are central to the project: [DATA_PRINCIPLES.md](DATA_PRINCIPLES.md).

## Screenshots and demos

Screenshots and short demo videos are being prepared under a publication review (real people, addresses and sensitive services are checked before anything is published). See [media/SCREENSHOT_PLAN.md](media/SCREENSHOT_PLAN.md) and [media/VIDEO_PLAN.md](media/VIDEO_PLAN.md).

## Current maturity

| Status | Meaning |
|---|---|
| WORKING | Works on real data |
| SHOWCASE READY | Works on real data and is polished enough to demonstrate |
| BETA | Works, with known limits |
| PROTOTYPE | Interface or mechanism exists; not in real use yet |
| RESEARCH | Being explored; not a product capability |

HollyEarth v0.1.0 is an early baseline: a strong evidence core and three lenses, running privately. It is not yet a hosted product.

## Roadmap

Direction, not promises: [ROADMAP.md](ROADMAP.md).

## Authors and rights

Created by **Stanislav Petrovsky** and **Irina Petrovskaya**, Riga, Latvia, 2026.
Copyright © 2026 Lab Da Riga. All rights reserved.

This repository contains public documentation and media related to HollyEarth. It is **not** open source; publication does not grant a license to HollyEarth proprietary source code, software implementation, product design, documentation, or HollyEarth-owned media unless explicitly stated otherwise. Third-party materials remain under their owners' terms. See [LICENSE.md](LICENSE.md), [NOTICE.md](NOTICE.md) and [AUTHORS.md](AUTHORS.md).
