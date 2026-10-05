# Capabilities — v0.1.0

Every capability below was checked against real data in the v0.1.0 baseline. Nothing is listed as working because it appears in a plan.

| Status | Meaning |
|---|---|
| **WORKING** | Works on real data |
| **SHOWCASE READY** | Works on real data and is polished enough to demonstrate |
| **BETA** | Works, with known limits |
| **PROTOTYPE** | Interface or mechanism exists; not in real use yet |
| **RESEARCH** | Being explored; not a product capability |

## Core

| Capability | Status | Notes |
|---|---|---|
| Canonical graph (entities and relationships across domains) | WORKING | Politics, sport and social records in one graph |
| Provenance on every record | WORKING | Source, snapshot and import path kept with each record |
| Claims with status (asserted / corroborated / verified) | WORKING | Status is shown to the reader, never hidden |
| Evidence with source quotations | WORKING | Each claim in a case carries the quotation it rests on |
| Typed money | WORKING | Planned, contract value, awarded, ceiling and rate are kept apart and never summed across types |
| Spatial representation | WORKING | District geometry, State Address Register points, 3D city scene |
| Interface in Russian, Latvian, English | WORKING | New surfaces fully; some older screens partially |

## Investigation

| Capability | Status | Notes |
|---|---|---|
| Case gallery and shareable case links | SHOWCASE READY | |
| Case workspace: established / unknown / money / analysis / monitoring | SHOWCASE READY | Desktop; phone layout is BETA |
| Evidence and provenance inspector | WORKING | "Where did this sum come from", "how did this record get into the case" |
| Investigation roadmap | WORKING | The branches a real investigation run created, and the questions not asked yet |
| Saved analytic reasoning (hypotheses labelled as hypotheses) | WORKING | |
| New research runs (model-assisted) | BETA | |
| Story — narrated case, ≈1 / 3 / 9 minutes, RU / LV / EN | SHOWCASE READY | Assembled from the case's records; voice narration is optional |
| Story voice narration | BETA | |
| Asking Holly inside a case | BETA | Answers from the case's saved analysis first |
| Source monitoring | BETA | Watches the official sources behind cases; runs on request, not yet on a schedule |

## Politics

| Capability | Status |
|---|---|
| Riga City Council records: meetings, agenda, decisions, votes, deputies, factions, committees | WORKING |
| Council network in the Twin | WORKING |
| Council decisions on the city map | WORKING |
| Council overview screen (older generation) | BETA |
| Political research workbench | PROTOTYPE (internal) |

## Sport — HollySport

| Capability | Status |
|---|---|
| Sport data from federation registers, result books and public archives | WORKING |
| Club, athlete, event and venue passports | WORKING (club and event passports SHOWCASE READY) |
| HollySport City — real clubs, venues and events over the Twin | WORKING |
| Club → investigation case | WORKING |
| Sport directory, sport map and sport graph | BETA |
| Ranking computed from the bouts the archive holds (labelled as not a federation ranking) | BETA |
| Event planning wizard | PROTOTYPE |
| Organiser / reviewer accounts, event projects, review queue | PROTOTYPE |
| Creator workspace, partnerships, outreach | PROTOTYPE |
| Season, missions, XP, district levels | PROTOTYPE (DEMO) |
| Fan predictions | PROTOTYPE (DEMO) |
| Market, wallet, leagues, club tokens, ticketing | RESEARCH |

## Social — Social Intelligence

| Capability | Status |
|---|---|
| Register of social service providers for Riga | WORKING |
| Social Intelligence stage (city as interface, filters, "Holly sees" register counts) | SHOWCASE READY |
| Service and provider dossiers | SHOWCASE READY |
| Commissioner and agreements, money, planning views | WORKING |
| Provider → investigation case | WORKING (where a case exists) |
| Phone layout | WORKING |
| Need, outcome and actual-payment data | RESEARCH |

## City and world

| Capability | Status | Notes |
|---|---|---|
| 3D Riga Twin | WORKING | |
| District wellbeing scores | PROTOTYPE (DEMO) | Illustrative numbers, labelled DEMO in the interface |
| Planetary view via Holly Eye | BETA | **Third-party integration** of the open-source God's Eye View project; not HollyEarth's own technology |

## Not described as working

- A general-purpose Holly assistant outside cases — not available in v0.1.0.
- A public hosted instance — HollyEarth runs as a private installation.
- Need / outcome / actual-payment intelligence for social services — the data does not exist in the system yet.
