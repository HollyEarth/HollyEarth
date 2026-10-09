# Social — Social Intelligence

Social Intelligence is the social-services world: Riga's registered social system as a place you can explore.

**256 services · 106 providers · 177 buildings · 28 services delivered at home** — from the Ministry of Welfare **register of social service providers**, snapshot of 14 September 2026 (2,082 register rows, of which 256 are services delivered in Riga). 3,110 register facts, each with its quotation and locator in the source.

<table>
<tr>
<td width="50%"><img src="../media/screenshots/10-social-stage.png" alt="Social stage"><br><sub>The Social Intelligence stage.</sub></td>
<td width="50%"><img src="../media/screenshots/11-social-dossier.png" alt="Service dossier"><br><sub>Service dossier with "what is not known".</sub></td>
</tr>
</table>

## What works

| Feature | Status |
|---|---|
| **Stage** — Riga as the interface: choose a type of service and the city shows where it is | `SHOWCASE_READY` |
| **Map** — buildings confirmed by the State Address Register; home services have no point, and the legend says so | `WORKING` |
| **Filters and search** — 19 service types, 17 target groups, 35 neighbourhoods, delivery mode | `WORKING` |
| **Service dossier** — register record, planned capacity, place, documents, money and "what is not known" | `SHOWCASE_READY` |
| **Organisation dossier** — the provider's services and buildings, with register conflicts flagged | `WORKING` |
| **Delegation agreements** — 49 municipal documents, matched to providers with the strength of each match shown (3 through a case document, 13 name-match candidates, 33 unresolved) | `WORKING` |
| **Money** — plans, agreement limits and maximum per-client rates, each with its type; rates are never summed | `BETA` |
| **Planning** — how registered services are distributed, labelled **not a fact** | `BETA` |
| **"Holly sees"** — three counts the register itself computes, with the reminder that they say nothing about need | `WORKING` |
| Russian, Latvian and English; a dedicated phone layout | `WORKING` |

## Registered ≠ delivered

The register tells HollyEarth what is registered. It does not tell how many people actually received a service, whether it is running today, what was actually paid, or how good it was — HollyEarth shows those as **unknown** for all 256 services, never as zero. The catalogue does not decide whether a person is entitled to a service. An empty district on the map is a fact about the register, not about the people who live there.

## Money

Money exists for one programme: a 2026 limit set by an agreement, three conditional plans for later years ("informative, depends on the budget") and three maximum per-client monthly rates. **None of these is money paid; there are no payment records in Social.** Known issue: the Money section headline adds the firm 2026 limit to the conditional plans.

## How Social connects to the rest

- **Not yet in the main graph.** The 106 providers and 177 buildings are kept in the social register's own model; they are not canonical organisations or places, and are drawn on the Twin from that model.
- **One investigation case.** One service links to a case about a council decision to delegate social work (1 of 256).
- **Twin.** The Twin draws the 177 buildings; a dossier does not yet lead back to the Twin, and opening the catalogue from the Twin loses the selected building.

## Known limits

- "Confirmed place of delivery" means the register lists the address and the address register confirms the building — not that delivery is confirmed.
- One building with a remote service point lies outside the city boundary; one service has a known address outside Riga that is not geocoded.
- Dossiers print a "legal address, not the place of service" note even under a confirmed delivery address.

Need, outcomes, people served and actual payments: `RESEARCH`. Details per feature: [FEATURE_STATUS.md](FEATURE_STATUS.md#social-intelligence).
