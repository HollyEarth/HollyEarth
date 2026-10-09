# Riga Twin — gallery

[← Visual Atlas](../GALLERY.md) · Feature status: [City — Riga Twin](../FEATURE_STATUS.md#city--riga-twin) · Overview: [twin.md](../twin.md)

A photorealistic 3D model of Riga used as the shared map of HollyEarth: district boundaries, council decisions, sport plots, social-service buildings, district news, the council panel and doors to the other worlds. Status: `WORKING`; Research mode and the AQAL overlay are `PROTOTYPE`, Wellbeing pins are `DEMO`. Real screenshots of v0.1.0, mostly Russian interface. Click an image to open it full size.

**Map and 3D sources** (attributions are shown inside the product): GeoRiga photorealistic 3D model of Riga and LOD2 buildings, Latvian Geospatial Information Agency (LGIA) reality model, ArcGIS platform ("Powered by Esri"), OpenStreetMap contributors (CC BY-SA), mesh generated with Agisoft Metashape, neighbourhood boundaries from data.gov.lv, building points from the State Address Register (VZD).

**Today the Twin composes several data models on one map** — council decisions and sport plots from the canonical graph, social buildings from the social register, districts from an open-data snapshot — rather than one shared place graph.

---

## The city

<a href="../../media/screenshots/02-riga-twin.png"><img src="../../media/screenshots/02-riga-twin.png" alt="Riga Twin — layers" width="100%"></a>

District, sport and social layers on 3D Riga (English interface, partly Russian). The "Wellbeing" pins are labelled `DEMO` — illustrative, not measurements.

<a href="../../media/gallery/twin/01-default-council.webp"><img src="../../media/gallery/twin/01-default-council.webp" alt="Riga Twin — default view with the council panel" width="100%"></a>

The default view: the left rail (council decisions 428, sessions 175, district news, investment plan), map layers, the right panel open on the council network (322 nodes, 607 links, 7 factions), and the dock to the other worlds.

## Layers

<table>
<tr>
<td width="50%"><a href="../../media/gallery/twin/02-layer-sport-plots.webp"><img src="../../media/gallery/twin/02-layer-sport-plots.webp" alt="Sport plots layer"></a><br><sub><b>Clubs and arenas</b> — 14 territories the city granted to sport institutions. `WORKING`</sub></td>
<td width="50%"><a href="../../media/gallery/twin/03-layer-council-decisions.webp"><img src="../../media/gallery/twin/03-layer-council-decisions.webp" alt="Council decisions layer"></a><br><sub><b>Council decisions</b> — 428 acts with an address, grouped by district with published sums. `BETA`</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/twin/04-layer-social-buildings.webp"><img src="../../media/gallery/twin/04-layer-social-buildings.webp" alt="Social buildings layer"></a><br><sub><b>Social services</b> — 177 buildings from the official register, numbered by services per building. `WORKING`</sub></td>
<td width="50%"><a href="../../media/gallery/twin/05-layer-district-news.webp"><img src="../../media/gallery/twin/05-layer-district-news.webp" alt="District news layer"></a><br><sub><b>District news</b> — headline markers with links, no article text. `BETA`: national headlines sometimes appear as district news.</sub></td>
</tr>
</table>

## Council decisions on the map

<table>
<tr>
<td width="50%"><a href="../../media/gallery/twin/06-decisions-by-district.webp"><img src="../../media/gallery/twin/06-decisions-by-district.webp" alt="Decisions by district"></a><br><sub>District cards: how many decisions, how many with a published sum.</sub></td>
<td width="50%"><a href="../../media/gallery/twin/07-decision-pin.webp"><img src="../../media/gallery/twin/07-decision-pin.webp" alt="Decision pin"></a><br><sub>A district opened: the decisions placed in it.</sub></td>
</tr>
</table>

<a href="../../media/gallery/twin/08-decision-card.webp"><img src="../../media/gallery/twin/08-decision-card.webp" alt="Decision card" width="100%"></a>

**Decision card** — title, address, published amount, date, district and a source sentence (riga.lv register, amount taken from the attached act). **Public copy with one corrected label:** the product shows a "VERIFIED" badge on this card by mistake; the record is imported, not verified, so this copy marks it "UNVERIFIED*" and says so on the image.

## Council panel

<table>
<tr>
<td width="50%"><a href="../../media/gallery/twin/09-council-money.webp"><img src="../../media/gallery/twin/09-council-money.webp" alt="Council money"></a><br><sub><b>Money</b> — 42 decisions with published sums.</sub></td>
<td width="50%"><a href="../../media/gallery/twin/10-council-people.webp"><img src="../../media/gallery/twin/10-council-people.webp" alt="Council people"></a><br><sub><b>People</b> — 113 deputies with party.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/twin/11-council-committees.webp"><img src="../../media/gallery/twin/11-council-committees.webp" alt="Council committees"></a><br><sub><b>Committees</b> — 13 committees with meeting counts.</sub></td>
<td width="50%"><a href="../../media/gallery/twin/12-council-cases.webp"><img src="../../media/gallery/twin/12-council-cases.webp" alt="Council cases"></a><br><sub><b>Cases</b> — the 9 investigation cases, filterable.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/twin/13-faction-dossier.webp"><img src="../../media/gallery/twin/13-faction-dossier.webp" alt="Faction dossier"></a><br><sub><b>Faction dossier</b> — mandates and a chain of links; seat totals here (54) differ from the election results (60). `BETA`</sub></td>
<td width="50%"><a href="../../media/gallery/twin/14-case-over-twin.webp"><img src="../../media/gallery/twin/14-case-over-twin.webp" alt="Case over the Twin"></a><br><sub><b>Case from the Twin</b> — the case workspace opens over the city. Cases do not yet land on the map. `PROTOTYPE`</sub></td>
</tr>
</table>

## Objects, news and lenses

<table>
<tr>
<td width="50%"><a href="../../media/gallery/twin/15-sport-plot-selected.webp"><img src="../../media/gallery/twin/15-sport-plot-selected.webp" alt="Sport plot selected"></a><br><sub>A sport plot selected: the map flies to it and highlights the territory. No passport link yet.</sub></td>
<td width="50%"><a href="../../media/gallery/twin/16-news-intelligence.webp"><img src="../../media/gallery/twin/16-news-intelligence.webp" alt="News intelligence"></a><br><sub>News intelligence for a district, with "open source" per headline.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/twin/17-aqal-overlay.webp"><img src="../../media/gallery/twin/17-aqal-overlay.webp" alt="AQAL overlay"></a><br><sub><b>AQAL overlay</b> — `PROTOTYPE` research lens: live rows (air quality, weather, LOD2, open datasets), demo rows and offline rows, each labelled.</sub></td>
<td width="50%"><a href="../../media/gallery/twin/18-research-mode.webp"><img src="../../media/gallery/twin/18-research-mode.webp" alt="Research mode"></a><br><sub><b>Research mode</b> — `PROTOTYPE`: a question bar and example prompts; it cannot answer questions in v0.1.0.</sub></td>
</tr>
</table>
