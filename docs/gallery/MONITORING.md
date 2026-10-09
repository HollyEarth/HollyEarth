# Monitoring / Observatory — gallery

[← Visual Atlas](../GALLERY.md) · Feature status: [Monitoring](../FEATURE_STATUS.md#monitoring) · Overview: [monitoring.md](../monitoring.md)

Real screenshots of v0.1.0 (Russian and English interface). Click an image to open it full size.

---

## Monitoring — `BETA`

Monitoring watches the official sources behind investigation cases: **18 watches** on two open-data sources (company officers from the Register of Enterprises, procurement results from the Electronic Procurement System), **26 runs**, 26 stored snapshots. Change detection compares records by identity and keeps "no change", "the source did not answer" and "parser changed" apart.

> **Checks are run by hand. There is no automatic scheduler yet**, and no change has been recorded so far.

<a href="../../media/screenshots/18-monitoring.png"><img src="../../media/screenshots/18-monitoring.png" alt="Monitoring page" width="100%"></a>

**Watches** — one table across all cases: case, domain, what is watched, source and cadence, state, last result.

<table>
<tr>
<td width="50%"><a href="../../media/gallery/monitoring/01-case-watches-rigas-nami.webp"><img src="../../media/gallery/monitoring/01-case-watches-rigas-nami.webp" alt="Case watches"></a><br><sub><b>Sources and changes inside a case</b> — each watch with source type and records in the snapshot, "Changes 0 — no change since watching began", and "Check now" (manual).</sub></td>
<td width="50%"><a href="../../media/gallery/monitoring/02-case-watches-kbs.webp"><img src="../../media/gallery/monitoring/02-case-watches-kbs.webp" alt="Run history"></a><br><sub><b>Run history</b> — date · source · outcome ("first observation"), for a sport club's two watches.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/monitoring/03-case-watches-social-delegation.webp"><img src="../../media/gallery/monitoring/03-case-watches-social-delegation.webp" alt="Watches social delegation"></a><br><sub>Watches of the social-delegation case — "no changes" kept apart from "first observation".</sub></td>
<td width="50%"><a href="../../media/gallery/monitoring/04-case-findings-gaps.webp"><img src="../../media/gallery/monitoring/04-case-findings-gaps.webp" alt="Findings and gaps"></a><br><sub><b>Findings and gaps</b> — "the case holds 40 of 370 records found; the rest stayed in the register", "no record in the register: final beneficiaries".</sub></td>
</tr>
</table>

---

## Project Observatory — internal

The Observatory is HollyEarth's **internal project control plane** — a registry of work, milestones, architecture contracts and design decisions. **It is a snapshot from August 2026 and several of its statements are out of date** (for example it describes production ingestion and the political graph as not yet implemented, which v0.1.0 has since built). Shown as part of how the project is run, not as current product status. Interface in English.

<table>
<tr>
<td width="50%"><a href="../../media/gallery/monitoring/05-observatory-overview.webp"><img src="../../media/gallery/monitoring/05-observatory-overview.webp" alt="Observatory overview"></a><br><sub><b>Overview</b> — registered work, blocked items, current operating state; marked "stale snapshot".</sub></td>
<td width="50%"><a href="../../media/gallery/monitoring/06-observatory-roadmap.webp"><img src="../../media/gallery/monitoring/06-observatory-roadmap.webp" alt="Observatory roadmap"></a><br><sub><b>Roadmap</b> — gate-driven milestones M0–M6 without invented dates.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/monitoring/07-dependency-graph.webp"><img src="../../media/gallery/monitoring/07-dependency-graph.webp" alt="Dependency graph"></a><br><sub><b>Dependency graph</b> — architecture nodes from schema and identity to the politics API, with an inspector.</sub></td>
<td width="50%"><a href="../../media/gallery/monitoring/08-work-items.webp"><img src="../../media/gallery/monitoring/08-work-items.webp" alt="Work items"></a><br><sub><b>Work items</b> — blocked / open / in progress / review / done.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/monitoring/11-core-observatory.webp"><img src="../../media/gallery/monitoring/11-core-observatory.webp" alt="Core observatory"></a><br><sub><b>Core observatory</b> — canonical core contracts (schema registry, identity, source, provenance, bitemporal time, claims, evidence) with validation state.</sub></td>
<td width="50%"><a href="../../media/gallery/monitoring/12-design-review.webp"><img src="../../media/gallery/monitoring/12-design-review.webp" alt="Design review"></a><br><sub><b>Design review</b> — research and design directions for the control room, awaiting owner review.</sub></td>
</tr>
</table>
