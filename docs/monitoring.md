# Monitoring

Monitoring watches the official sources behind investigation cases and records whether they changed. Status: `BETA`.

![Monitoring](../media/screenshots/18-monitoring.png)

<sub>Real screenshot, v0.1.0 (Russian interface). All watches across cases: case, domain, what is watched, source, state and last result.</sub>

## What exists

| | v0.1.0 |
|---|---|
| Watches | 18, in 3 of 9 cases |
| Sources | Two official open-data sources: company officers (Register of Enterprises) and procurement results (Electronic Procurement System) |
| Runs | 26, all completed, started by hand in September 2026 |
| Snapshots | 26 — each run stores the full set of records it read, the request and the outcome |
| Recorded changes | 0 |

## How a change is decided

- Records are matched **by identity, not by position**, so a re-sorted export is "no change".
- The same record with different fields is **changed** (old value → new value), never "removed and added".
- "Removed" means the export no longer contains the record — not that something happened in the world.
- Every change carries the window in which it was observed, never an invented event date.
- "Source did not answer", "parser changed", "blocked" and "rate-limited" are kept apart from "no change".
- A monitoring run never writes into the graph; deciding what a change means is left to the evidence workflow.

## Limits in v0.1.0

- **Checks are run by hand.** "Weekly" is stored as a cadence, but there is **no automatic scheduler**; every watch is now overdue.
- **No change has ever been recorded**, so change detection has not yet been exercised on a real change.
- The monitoring page shows overdue watches as "active" and has no per-watch or per-run detail.
- Procurement snapshots keep the newest 40 records, and this window is not yet flagged in the interface.

## Next

Scheduled checks, due dates and overdue state on screen, run detail, and wider coverage across cases. See [ROADMAP.md](../ROADMAP.md).

Details: [FEATURE_STATUS.md](FEATURE_STATUS.md#monitoring).
