# The graph

HollyEarth keeps its records in a **canonical graph** with provenance, beside a separate social register and one evidence graph per investigation case. This page describes what the graph holds in v0.1.0 and where it is going.

## What the canonical graph holds — `WORKING`

- **Entities** — people, organisations, places, meetings, agenda items, decisions, documents, events, bouts, competition categories, sport disciplines.
- **Relationships** — membership, positions held, recipients named in decisions, where something is located or affects, who competed where, which club trains where.
- **Claims** — statements about entities, each with a status.
- **Evidence** — the record a claim rests on.
- **Provenance** — the source, the snapshot of that source, and how the record was imported.

In v0.1.0: **25,127 entities · 26,293 relationships · 11,115 claims · 18,377 evidence records · 25,380 external identifiers · 565 places**.

## Domains inside it

| Domain | In the canonical graph | Notes |
|---|---|---|
| Politics | 3,892 entities | Council sessions, agenda, decisions, documents, deputies, parties, committees, places of decisions |
| Sport | 21,235 entities | Athletes, clubs, federations, events, bouts, categories, venues |
| Social | 0 | The social-services register (256 services, 106 providers, 177 buildings) has its own model |

A record belongs to a domain because of **where it came from**, not because of its type — a deputy and an athlete are both people.

**Politics and sport are not yet linked to each other**: no relationship and no place connects the two sub-graphs in v0.1.0. Cross-domain connections exist today through investigation cases (club → case, social provider → case, decision → case) and through navigation, not through shared identity.

## Status is part of the data

Claims are *asserted* (11,057) or *corroborated* by an automated institutional cross-check (58). 2,439 relationships carry a *verified* status that comes from an official source's own structure (meeting → agenda item → decision). **None of these statuses means a person has checked the record.** See [evidence-and-provenance.md](evidence-and-provenance.md).

## Identity

Records are joined only through stable source identifiers, never by a similar name; possible matches become questions for a human reviewer. Open questions in v0.1.0 include 1,284 sport person candidates and 450 organisation-name candidates. One known error — a registration number shared by many municipal bodies attached to a single organisation — is being corrected; it shows why an organisational hierarchy (legal entity → institution → department → service provider → unit) is part of the direction.

## Direction

One connected graph of the city — shared organisations, people and places across politics, sport, social and cases; contracts and agreements as records; reviewed case findings promoted into the core. See [ARCHITECTURE.md](../ARCHITECTURE.md) and [ROADMAP.md](../ROADMAP.md).

Status of each part: [FEATURE_STATUS.md](FEATURE_STATUS.md#core).
