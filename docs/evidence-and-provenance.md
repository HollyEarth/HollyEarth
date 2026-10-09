# Evidence and provenance

Every figure HollyEarth shows should be traceable. Two questions are always answerable:

1. **Where did this come from?** — the source, the snapshot of that source, and the import path.
2. **How sure are we?** — the record's status.

## In a case
- Each claim carries the **quotation** from the document it was extracted from and a link to the source.
- Selecting an object shows **why it is in the case**, **how the case found it**, and, for money, **where each sum came from** — the document read, the type of sum and its period.
- The case keeps the **route of discovery** separate from the relationships themselves: how the archive learned something is not the same as what it proves.

## Statuses a reader sees
| Status | Meaning |
|---|---|
| Imported, unverified | Faithfully what an official source published; not independently checked |
| Asserted | A statement extracted from a document |
| Directly supported (shown as "confirmed" in cases) | The quotation supports the whole statement — it does not mean the fact was checked independently |
| Partially supported | The quotation supports part of the statement |
| Corroborated | An automated cross-check against an independent institutional source could have failed and did not |
| Verified (relationships) | A structural link taken from an official source's own metadata, for example meeting → agenda item → decision |
| Checked by a person | **None in v0.1.0** — a human review workflow is in development |
| Unknown / no record | The archive does not hold this — which is not the same as "none" |

## Monitoring
For the official sources behind a case (for example company officers and procurement results), HollyEarth stores snapshots and compares them, distinguishing **"no change"** from **"the source did not answer"**. Status: `BETA` — checks run on request, not yet on a schedule. See [monitoring.md](monitoring.md).

See also [DATA_PRINCIPLES.md](../DATA_PRINCIPLES.md).
