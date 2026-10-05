# Architecture (overview)

A high-level view of how HollyEarth is organised. Implementation details are not published.

```
  Sources (registers, council publications, federations, archives, address register)
        │  imported with source, snapshot and import path
        ▼
  ┌──────────────────────── Canonical graph ────────────────────────┐
  │ entities · relationships · claims · evidence · places            │
  │ every record: provenance + status                                │
  └───────────────┬──────────────────────────────┬───────────────────┘
                  │ lenses (by provenance)        │
        ┌─────────┼──────────┐                    │
     Politics   Sport     Social                  │
        └─────────┬──────────┘                    │
                  ▼                               ▼
  ┌──────── Investigation layer ────────┐   ┌── Spatial layer ──┐
  │ cases · claims as found · evidence  │   │ districts, points │
  │ typed money · roadmap · monitoring  │   │ 3D city scene     │
  │ story (assembled from records)      │   └───────────────────┘
  └──────────────────┬──────────────────┘
                     ▼
        Experience: Start · Riga Twin · Cases · Story
                    HollySport City & passports · Social stage
```

## Key ideas

- **One graph, many lenses.** Domains do not have separate databases. A lens selects records by where they came from, so a sport archive and a council register can sit in one graph without being confused for each other.
- **The case layer is separate from the canonical layer.** An investigation records what it found, with status and quotations, without silently rewriting the canonical graph.
- **Stories are assembled, not invented.** The structure of a narrated case comes from the case's records; a model may only help with wording, and the story stays valid without it.
- **Space is evidence too.** Points come from an address register or the source itself; areas from official district geometry.
- **Paid and external services are opt-in.** Voice synthesis and model calls are explicit, gated actions.

## Third-party components

HollyEarth integrates third-party components and services, for example a 3D mapping platform for the Twin, OpenStreetMap data, and the open-source **God's Eye View** application (by Bilawal Sidhu) for the planetary **Holly Eye** view. These remain under their own licenses and terms; see [NOTICE.md](NOTICE.md) and [DATA_SOURCES.md](DATA_SOURCES.md).
