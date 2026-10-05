# The graph

HollyEarth keeps the city's records in **one canonical graph**.

- **Entities** — people, organisations, places, meetings, decisions, documents, events, bouts, competition categories.
- **Relationships** — membership, positions held, recipients named in decisions, where something is located, who competed where.
- **Claims** — statements about entities, each with a status.
- **Evidence** — the quotation or record a claim rests on.
- **Provenance** — the source, the snapshot of that source, and how the record was imported.

## Lenses, not silos

Politics, sport and social services are not separate databases. They are **lenses** over the same graph. A lens selects records by **provenance** — by which source put them there and on whose authority — not by entity type, because a deputy and an athlete are both people. The political lens, for example, counts only records written from the council's own sources.

## Status is part of the data

Records keep their epistemic state: imported and unverified, asserted, corroborated, verified, partially supported. The interface shows it. See [evidence-and-provenance.md](evidence-and-provenance.md).

## Scale in v0.1.0

The v0.1.0 graph holds tens of thousands of entities and relationships across Riga council records, Latvian sport records and the social-services register, plus several thousand source snapshots. Exact figures change with every import and are shown in the product next to the source and date they come from.

Status: **WORKING**.
