# Data sources

Sources actually used by HollyEarth v0.1.0. **Reuse and licence terms have not yet been reviewed for public use.** Until each source is reviewed, its status is `REVIEW REQUIRED`. No permission is implied by this list.

Columns: **source** | **used for** | **provenance in HollyEarth** | **reuse / licence status**

## Riga municipality and Latvian public bodies

| Source | Used for | Provenance | Reuse / licence status |
|---|---|---|---|
| Riga City Council — agenda and decision publications (riga.lv) | Meetings, agenda items, decisions, decision documents | Imported per publication snapshot; every record links to its source | REVIEW REQUIRED |
| Riga City Council — voting protocols (pkip.riga.lv) | Ballots and individual votes | Parsed from published protocols | REVIEW REQUIRED |
| Riga City Council — deputies and factions (riga.lv) and Central Election Commission results | Deputies, factions, electoral lists | Imported, status "imported, unverified" | REVIEW REQUIRED |
| Riga City Council — session video recordings | Live Sessions module (links to recordings) | Linked per session | REVIEW REQUIRED |
| data.gov.lv — Riga municipality spending dataset | Politics "City Budget" module | Read from the open dataset; the meaning of its records with respect to individual payments is still being established | REVIEW REQUIRED |
| Riga municipality — list of delegation and cooperation agreements | Social-services agreements and counterparties | Imported; provider matching labelled by strength | REVIEW REQUIRED |
| Riga City Council — territories granted to education, culture and sport institutions | Sport plots shown on the Twin | Imported area geometry | REVIEW REQUIRED |
| data.gov.lv — Riga neighbourhood (apkaime) boundaries | District geometry on all maps | Official shapefile | REVIEW REQUIRED |
| Ministry of Welfare (Labklājības ministrija) — register of social service providers | Social services, providers, delivery addresses, target groups, planned capacity | Register snapshot with date shown on screen | REVIEW REQUIRED |
| State Land Service (VZD) — State Address Register | Building points for addresses (social services, sport venues) | Point taken only when exactly one register building matches | REVIEW REQUIRED |
| Register of Enterprises (Uzņēmumu reģistrs) | Organisations, registration numbers, officers (in cases and monitoring) | Read per case; monitored in snapshots | REVIEW REQUIRED |
| Electronic Procurement System (EIS) | Procurement results (in cases and monitoring) | Read per case; monitored in snapshots | REVIEW REQUIRED |
| Other official public sources read inside cases (e.g. Latvijas Vēstnesis, KNAB, VID) | Evidence in individual investigations | Each claim keeps its source and quotation | REVIEW REQUIRED |

## Sport

| Source | Used for | Provenance | Reuse / licence status |
|---|---|---|---|
| Latvian Athletics Association — calendar and results (athletics.lv) | Athletics events, results, clubs, venues | Imported per page; results of possible minors excluded | REVIEW REQUIRED |
| WAKO — official results books (wako.sport) | Kickboxing championship placings | Parsed from official result documents; senior and veteran classes only | REVIEW REQUIRED |
| King of Kings — the promotion's own event archive (kokfights.com) | Kickboxing events, bouts, results as printed | Imported per event page | REVIEW REQUIRED |
| Latvian Sports Federations Council (LSFP) — register of recognised federations | Sport federations | Imported register | REVIEW REQUIRED |
| HollySport research dataset of Latvian combat-sport clubs | Clubs, training places, programmes, family prices | Compiled by the project from public sources (club and federation websites, registers); each record names its sources | REVIEW REQUIRED |
| Club and organisation websites (cited in cases) | Evidence in club investigations | Each claim keeps its source and quotation | REVIEW REQUIRED |

## Maps, 3D and media

| Source | Used for | Provenance | Reuse / licence status |
|---|---|---|---|
| OpenStreetMap | Basemap data in the Twin | Attribution displayed in the map | REVIEW REQUIRED |
| ArcGIS / Esri platform and basemaps | 3D scene engine and basemaps for the Twin | Attribution displayed in the map | REVIEW REQUIRED |
| GeoRiga — Riga photorealistic 3D model and LOD2 buildings; Latvian Geospatial Information Agency (LGIA) reality model | 3D Riga in the Twin and HollySport City | Loaded from the publishers' hosted scene services | REVIEW REQUIRED — screenshots showing the 3D model are not published until reuse terms are confirmed |
| Riga news headlines (public broadcaster RSS) | District news markers (headlines and links only, no article text) | Linked, not stored | REVIEW REQUIRED |
| Open-Meteo | Weather and air-quality widget | Live request | REVIEW REQUIRED |
| Portraits from public institutional pages and Wikimedia Commons | Faces of public figures and athletes where available | Each image keeps its origin and licence note | REVIEW REQUIRED (per image) |

## Third-party components and integrations

| Component | Used for | Provenance | Reuse / licence status |
|---|---|---|---|
| God's Eye View (Bilawal Sidhu), used as **Holly Eye** | Planetary view, run as a separate application | Third-party open-source project, integrated, not owned by HollyEarth | REVIEW REQUIRED (project states MIT; attribution and data terms to be reviewed) |
| Datasets and 3D tiles used by God's Eye View (e.g. Cesium ion, Google map tiles) | Inside the Holly Eye application only | Third-party | REVIEW REQUIRED |
| Google Vertex AI (Gemini models) | Optional wording of stories and research assistance | Called only on explicit action; outputs labelled | REVIEW REQUIRED |
| ElevenLabs | Optional voice narration of stories | Generated only after explicit confirmation | REVIEW REQUIRED |
| Qwen3-TTS (local model) | Optional local voice narration | Third-party model | REVIEW REQUIRED |
| Open-source software libraries | Application framework, graph rendering, mapping | Third-party packages | REVIEW REQUIRED (to be listed in NOTICE before any binary or media release that includes them) |
