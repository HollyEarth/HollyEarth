# Investigation cases

A **case** is a council decision, a procurement or an organisation gathered together with its sources, quotations, claims, money, what is still unknown and what to check next. **9 cases** in v0.1.0: 7 about sport clubs and 2 about council decisions (one on a municipal company, one on delegating social work).

<table>
<tr>
<td width="50%"><img src="../media/screenshots/03-case-overview.png" alt="Case overview"><br><sub>Case overview.</sub></td>
<td width="50%"><img src="../media/screenshots/04-evidence.png" alt="Evidence path"><br><sub>Where an amount comes from.</sub></td>
</tr>
</table>

## What a case shows
- **What is established** — claims with the quotation they rest on, and how many are directly or partially supported by it.
- **What is unknown** — open research questions and evidence gaps ("a gap in the sources, not a zero").
- **Money** — every sum with its type (planned, contract value, contract ceiling, awarded, monthly fee, unit rate) and the rule that different types are not added together.
- **Analysis** — patterns, questions, hypotheses and next steps, none marked as fact.
- **Monitoring** — which official sources the case watches and whether they changed. See [monitoring.md](monitoring.md).

## Four ways to read a case
- **Explore** — the case as a network; select any object to see why it is here and where it came from.
- **Analyze** — the reasoning: hypotheses, what would confirm or refute them, and questions to Holly.
- **Roadmap** — the route the investigation actually took: which run opened which branch, which questions remain, and where research did not finish.
- **Story** — the case told as chapters. See [story.md](story.md).

## The numbers (v0.1.0)

| | |
|---|---|
| Claims | 111 — all *asserted*; each with source and quotation; 106 directly supported by its quotation, 4 partially, 1 not |
| Human-verified claims | **0** |
| Sources | 55, each with a content hash and stored copy |
| Case entities / relationships | 104 / 97 — every relationship traces to a claim |
| Money records | 84 of 6 types — **no payment records** |
| Open tasks / evidence gaps | 324 / 16 |
| Example: Rīgas nami (council decision on a municipal company) | 38 objects · 34 claims · 14 sources · 31 directly and 3 partially supported · 153 open questions |

## Claim ≠ verified fact

Claims in cases are extracted from documents and have **not** been checked by a person. "Confirmed" in the interface means "directly supported by a quotation". A case shows what is known, what supports it and what is still missing; it is not a legal assessment.

A model may propose a case claim only if its quotation is found word for word in the source (8 of 111 claims came this way). They are not yet marked as model-extracted in the interface — being added.

## How cases connect

Each case is its own evidence graph, anchored to one canonical record (a club or a council decision). 24 of its 104 entities are resolved to canonical records; the rest are candidates. Doors into cases: club passports (7), one social service, council decisions on the Twin, and the monitoring page. There is no link yet from a case back to a club passport or a social dossier.

## Status
- Case gallery, evidence path — `SHOWCASE_READY`
- Case workspace (desktop), roadmap, deterministic analysis — `WORKING`
- Case workspace on a phone, model reasoning, research runs, Holly in a case, monitoring — `BETA`
- Human verification and promotion into the canonical graph — `FUTURE`

Known limits: in one case two different contract figures appear on one screen; some money rows are stored twice; saved analyses and stories can be older than the case (the product says so). Details: [FEATURE_STATUS.md](FEATURE_STATUS.md#investigation).
