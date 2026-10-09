# Capabilities — v0.1.0

What HollyEarth can do today, by world. Every line was checked on real data in the v0.1.0 baseline; nothing is listed because it appears in a plan. The full matrix — with real data, limitations and next steps for each feature — is in [docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md).

Statuses: `SHOWCASE_READY` · `WORKING` · `BETA` · `PROTOTYPE` · `DEMO` · `RESEARCH` · `FUTURE` (defined in [docs/FEATURE_STATUS.md](docs/FEATURE_STATUS.md#status-vocabulary)).

## Core

| Capability | Status | Notes |
|---|---|---|
| Canonical graph with provenance | `WORKING` | Holds politics and sport records (25,127 entities). The two are not yet linked to each other, and the social register is kept in its own model |
| Provenance on every record | `WORKING` | Source, snapshot and import path |
| Claims with status | `WORKING` | "Verified" and "corroborated" in the data come from automated checks, not from a person |
| Quotation evidence in cases | `WORKING` | Every case claim carries the quotation it rests on |
| Typed money | `WORKING` | Planned, contract value, ceiling, awarded, monthly fee and unit rate kept apart, never summed across types; no payment records |
| Spatial representation | `WORKING` | Official district geometry, address-register points, 3D city |
| Entity resolution across sources | `BETA` | By stable identifiers; review queues open; one known wrong resolution being corrected |
| Russian, Latvian, English | `WORKING` | New surfaces fully; older screens partly |

## City — Riga Twin

| Capability | Status |
|---|---|
| 3D Riga with district boundaries | `WORKING` |
| Council decisions, sport plots and social-service buildings as layers | `WORKING` (decision card `BETA`) |
| Council panel, district news | `BETA` |
| Research mode, AQAL overlay, case on the map | `PROTOTYPE` |
| Wellbeing scores | `DEMO` |

## Politics

| Capability | Status |
|---|---|
| Council records: sessions, agenda, decisions, votes, deputies, parties, committees | `WORKING` |
| Network · Deputies · Parties & Power | `WORKING` |
| Political OS · Live Sessions · Decisions · City Budget · Evidence Ledger | `BETA` |
| AI Analyzer | `PROTOTYPE` |
| District Impact · Smart City Lenses | `DEMO` |
| Integral City | `RESEARCH` |
| Political Workspace (8 views, internal) | `PROTOTYPE` |

## Sport — HollySport

| Capability | Status |
|---|---|
| Sport records from federation registers, result books and event archives; no stored results of minors | `WORKING` |
| Club and event passports | `SHOWCASE_READY` |
| Sport City (real layer), athlete and venue passports, archive, map, graph | `WORKING` |
| Club → investigation case | `WORKING` |
| Rankings computed from archived bouts (not a federation ranking) | `BETA` |
| Event OS (create event), creator, partnerships, outreach, accounts | `PROTOTYPE` |
| Season, missions, XP, district levels, fan predictions | `DEMO` |
| Market, wallet, leagues, club tokens, ticketing; public money in sport | `FUTURE` |

## Social — Social Intelligence

| Capability | Status |
|---|---|
| Social stage and service dossiers | `SHOWCASE_READY` |
| Register catalogue, map, filters, organisation dossiers, delegation agreements | `WORKING` |
| Money and planning views | `BETA` |
| Provider → investigation case | `WORKING` (1 of 256) |
| Need, outcomes, people served, actual payments | `RESEARCH` — unknown, shown as unknown |

## Investigation

| Capability | Status |
|---|---|
| Case gallery and the evidence path ("where does this amount come from") | `SHOWCASE_READY` |
| Case workspace (desktop), claims and quotations, case graph, typed money, open questions, roadmap, deterministic analysis | `WORKING` |
| Case workspace (phone), model reasoning, research runs, Holly in a case | `BETA` |
| Human verification, promotion to the main graph, recorded source conflicts | `FUTURE` |

## Intelligence and experience

| Capability | Status |
|---|---|
| Story playback in three languages, assembled from case records | `WORKING` |
| Chapter-to-claim traceability in stories | `BETA` |
| Monitoring of official sources behind cases (manual runs) | `BETA` |
| Scheduled monitoring | `FUTURE` |
| Holly: deterministic helpers | `WORKING` |
| Holly: investigation assistant, optional model reasoning, voice | `BETA` |
| Global Holly assistant, autonomous agents | `FUTURE` |
| Holly Eye planetary view — **third-party integration** (God's Eye View by Bilawal Sidhu) | `BETA` |

## Not described as working

- A single unified reality graph across all domains — direction, not today's state.
- Recorded payment executions in cases or Social — none exist; planned, contracted and awarded amounts are not payments.
- Human verification of claims — none yet.
- A global Holly assistant or autonomous agents.
- A public hosted instance — HollyEarth runs as a private installation.
- Action or governance features — `FUTURE`.
