# Holly Eye / World — gallery

[← Visual Atlas](../GALLERY.md) · Feature status: [Holly Eye / World](../FEATURE_STATUS.md#holly-eye--world) · Overview: [holly-eye.md](../holly-eye.md) · **Media provenance: [HOLLY_EYE_PROVENANCE.md](../../media/HOLLY_EYE_PROVENANCE.md)**

> **Holly Eye is a third-party integration, not HollyEarth Core.**
> The application is **God's Eye View** by **Bilawal Sidhu** ([github.com/bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view), code under MIT). HollyEarth / Lab Da Riga runs it as a separate application at a pinned version, with integration patches, the HollyEarth interface skin and the **World** door — with a way back to the Riga Twin. The 3D globe, layers, scenes and voice commands below are features of that application.

46 real screenshots, captured on 9 October 2026 from the running application. Each public copy keeps the frame unchanged — including the application's own map credits and the providers' notices — and adds an information band below it: status, the integration credit, the layer-data source and the map credit. Click an image to open it full size.

**Map and imagery.** Holly Eye draws the world on four map stacks — Google photorealistic 3D, Bing aerial, Bing labels and OpenStreetMap — streamed through Cesium ion. Most screens use Google Photorealistic 3D Tiles and Google globe imagery (credits: Google, Airbus, Data SIO, NOAA, U.S. Navy, NGA, GEBCO, Landsat / Copernicus, as shown in each frame); screens marked *OSM* use OpenStreetMap (© OpenStreetMap contributors, ODbL) on Re:Earth terrain (CC BY 4.0). These images are shared as part of a non-commercial presentation; the terms that apply to each one are in the [media provenance](../../media/HOLLY_EYE_PROVENANCE.md). The MIT licence of the application covers its code, not the map imagery or data.

**Status vocabulary** — `WORKING` live data on screen · `BETA` works with limits · `PROTOTYPE` exists but not usable as a product feature in this build. The integration as a whole is `BETA`.

**Contents** — [Planetary view](#planetary-view) · [World layers](#world-layers) · [Space & satellites](#space--satellites) · [Environmental data](#environmental-data) · [Scenes](#scenes) · [Voice interface](#voice-interface) · [HollyEarth ↔ Holly Eye](#hollyearth--holly-eye)

---

## Planetary view

### The globe — `BETA`

<a href="../../media/gallery/holly-eye/01-planet-europe-3d.webp"><img src="../../media/gallery/holly-eye/01-planet-europe-3d.webp" alt="Holly Eye globe" width="100%"></a>

A 3D globe inside the Holly Eye scope, with the HollyEarth / Holly Eye header, the left rail (data layers, scenes), the right rail (display, CCTV, context) and the dock (Ask Holly, location, visual presets).

<a href="../../media/gallery/holly-eye/02-planet-europe-osm.webp"><img src="../../media/gallery/holly-eye/02-planet-europe-osm.webp" alt="Holly Eye globe on OpenStreetMap" width="100%"></a>

The same globe on the OpenStreetMap stack.

### Riga in 3D — `BETA`

<a href="../../media/gallery/holly-eye/03-riga-3d-old-town.webp"><img src="../../media/gallery/holly-eye/03-riga-3d-old-town.webp" alt="Riga in 3D" width="100%"></a>

Riga as photorealistic 3D tiles: the Old Town, the Daugava and its bridges. Holly Eye opens over Austin by default; this view was opened on Riga through the application's own share link (camera position in the URL).

<a href="../../media/gallery/holly-eye/05-riga-osm.webp"><img src="../../media/gallery/holly-eye/05-riga-osm.webp" alt="Riga on OpenStreetMap" width="100%"></a>

Riga on the OpenStreetMap stack.

### First view, display, styles and search — `BETA`

<a href="../../media/gallery/holly-eye/06-first-view-chooser.webp"><img src="../../media/gallery/holly-eye/06-first-view-chooser.webp" alt="Choose your first view" width="100%"></a>

**Choose your first view** — live contacts, space missions, environmental, or explore manually: "Every layer here comes from a public source, named and checkable. What the archive does not hold, it leaves empty."

<table>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/07-display-panel.webp"><img src="../../media/gallery/holly-eye/07-display-panel.webp" alt="Display panel"></a><br><sub><b>Display</b> — HUD, detection, 3D models, scope, celestial, clean UI, bloom, sharpen.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/08-visual-presets.webp"><img src="../../media/gallery/holly-eye/08-visual-presets.webp" alt="Visual presets"></a><br><sub><b>Visual presets</b> — styles and the map source (Google 3D · Bing aerial · Bing labels · OSM).</sub></td>
</tr>
</table>

<table>
<tr>
<td width="33%"><a href="../../media/gallery/holly-eye/09-style-nvg.webp"><img src="../../media/gallery/holly-eye/09-style-nvg.webp" alt="NVG style"></a><br><sub>NVG</sub></td>
<td width="33%"><a href="../../media/gallery/holly-eye/10-style-flir.webp"><img src="../../media/gallery/holly-eye/10-style-flir.webp" alt="FLIR style"></a><br><sub>FLIR</sub></td>
<td width="33%"><a href="../../media/gallery/holly-eye/14-style-crt.webp"><img src="../../media/gallery/holly-eye/14-style-crt.webp" alt="CRT style"></a><br><sub>CRT (on the default start view)</sub></td>
</tr>
<tr>
<td width="33%"><a href="../../media/gallery/holly-eye/11-style-anime.webp"><img src="../../media/gallery/holly-eye/11-style-anime.webp" alt="Anime style"></a><br><sub>Anime</sub></td>
<td width="33%"><a href="../../media/gallery/holly-eye/12-style-noir.webp"><img src="../../media/gallery/holly-eye/12-style-noir.webp" alt="Noir style"></a><br><sub>Noir</sub></td>
<td width="33%"><a href="../../media/gallery/holly-eye/13-style-snow.webp"><img src="../../media/gallery/holly-eye/13-style-snow.webp" alt="Snow style"></a><br><sub>Snow</sub></td>
</tr>
</table>

<table>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/15-location-search.webp"><img src="../../media/gallery/holly-eye/15-location-search.webp" alt="Location search"></a><br><sub><b>Location</b> — place search and quick jumps.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/16-data-attribution.webp"><img src="../../media/gallery/holly-eye/16-data-attribution.webp" alt="Data attribution"></a><br><sub><b>Data attribution</b> — every data provider named in the application, with licence notes. `WORKING`</sub></td>
</tr>
</table>

---

## World layers

<a href="../../media/gallery/holly-eye/20-data-layers-panel.webp"><img src="../../media/gallery/holly-eye/20-data-layers-panel.webp" alt="Data layers panel" width="100%"></a>

Fourteen public data layers, each switched on separately and each naming its source and when it last updated. Counts are what the layers showed when the screenshots were taken (9 October 2026).

| Layer | Source | Seen on screen | Status |
|---|---|---|---|
| Live flights | OpenSky Network | 13.8K aircraft | `WORKING` |
| Military flights | adsb.lol | 164 aircraft | `WORKING` |
| Earthquakes (24 h) | USGS | 33 events | `WORKING` |
| Satellites | CelesTrak | 830 objects (stations, navigation, geostationary, visual) | `WORKING` |
| Space missions (30 days) | Launch Library 2 | 25 missions | `WORKING` |
| Street traffic | OpenStreetMap roads | simulated — no live traffic feed configured | `PROTOTYPE` |
| CCTV | public traffic-camera feeds | 800 cameras loading; the view could not be captured (the page stops rendering under the camera load) — no screenshot | `BETA` |
| Radio | Radio Browser | 750 stations | `WORKING` |
| Bikeshare | GBFS operator feeds (US cities only) | feeds still loading when captured — no screenshot | `BETA` |
| Live AIS vessels | AISStream | 12.0K vessels | `WORKING` |
| Mapped installations | OpenStreetMap | source temporarily unavailable when captured — no screenshot | `BETA` |
| Datacenters | dataset bundled with the application | 4.4K sites | `WORKING` |
| Dams | USACE | 716 dams | `WORKING` |
| FIRMS active fires | NASA FIRMS | 164.2K detections | `WORKING` |

<table>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/21-live-flights.webp"><img src="../../media/gallery/holly-eye/21-live-flights.webp" alt="Live flights"></a><br><sub><b>Live flights</b> over the Baltic — OpenSky Network.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/21b-live-flights-osm.webp"><img src="../../media/gallery/holly-eye/21b-live-flights-osm.webp" alt="Live flights on OSM"></a><br><sub>Live flights on the OpenStreetMap stack.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/23-military-flights.webp"><img src="../../media/gallery/holly-eye/23-military-flights.webp" alt="Military flights"></a><br><sub><b>Military flights</b> — adsb.lol.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/32-context-contacts.webp"><img src="../../media/gallery/holly-eye/32-context-contacts.webp" alt="Contacts"></a><br><sub><b>Context · Contacts</b> — an airliner near Riga with callsign, flight level and speed from public ADS-B data. `BETA`</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/24-ais-vessels-channel.webp"><img src="../../media/gallery/holly-eye/24-ais-vessels-channel.webp" alt="AIS vessels in the English Channel"></a><br><sub><b>Live AIS vessels</b> in the English Channel, with names, type and speed — AISStream.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/24b-ais-vessels-osm.webp"><img src="../../media/gallery/holly-eye/24b-ais-vessels-osm.webp" alt="AIS vessels on OSM"></a><br><sub>The same vessel traffic on the OpenStreetMap stack.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/27-radio.webp"><img src="../../media/gallery/holly-eye/27-radio.webp" alt="Radio"></a><br><sub><b>Radio</b> — 750 stations by genre, Radio Browser.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/30-datacenters.webp"><img src="../../media/gallery/holly-eye/30-datacenters.webp" alt="Datacenters"></a><br><sub><b>Datacenters</b> — 4.4K sites.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/31-dams.webp"><img src="../../media/gallery/holly-eye/31-dams.webp" alt="Dams"></a><br><sub><b>Dams</b> — USACE National Inventory of Dams.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/25-street-traffic-simulated.webp"><img src="../../media/gallery/holly-eye/25-street-traffic-simulated.webp" alt="Street traffic simulated"></a><br><sub><b>Street traffic</b> — `PROTOTYPE`: simulated on OpenStreetMap roads over Riga; the application says so ("SIMULATED — add TomTom key for live").</sub></td>
</tr>
</table>

---

## Space & satellites

<a href="../../media/gallery/holly-eye/40-satellites.webp"><img src="../../media/gallery/holly-eye/40-satellites.webp" alt="Satellites" width="100%"></a>

**Satellites** — 830 objects from CelesTrak orbital elements, grouped as stations, navigation, geostationary and visual, with an orbit traced around the Earth. `WORKING`

<table>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/41-satellites-globe.webp"><img src="../../media/gallery/holly-eye/41-satellites-globe.webp" alt="Satellites around the globe"></a><br><sub>Satellites around the globe.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/42-satellites-close.webp"><img src="../../media/gallery/holly-eye/42-satellites-close.webp" alt="Satellites closer"></a><br><sub>A closer orbital view.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/43-satellites-osm.webp"><img src="../../media/gallery/holly-eye/43-satellites-osm.webp" alt="Satellites on OSM"></a><br><sub>Satellites on the OpenStreetMap stack.</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/47-scene-orbital-watch.webp"><img src="../../media/gallery/holly-eye/47-scene-orbital-watch.webp" alt="Orbital Watch scene"></a><br><sub><b>Orbital Watch</b> scene — labelled satellites and stations in night-vision style.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/44-space-missions.webp"><img src="../../media/gallery/holly-eye/44-space-missions.webp" alt="Space missions"></a><br><sub><b>Space missions (30 days)</b> — launches and spacecraft, Launch Library 2 (The Space Devs).</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/46-context-space-missions.webp"><img src="../../media/gallery/holly-eye/46-context-space-missions.webp" alt="Space missions context"></a><br><sub><b>Context · Space missions</b> — the list of launches and orbital assets. `BETA`</sub></td>
</tr>
</table>

<a href="../../media/gallery/holly-eye/45-space-missions-osm.webp"><img src="../../media/gallery/holly-eye/45-space-missions-osm.webp" alt="Space missions on OSM" width="100%"></a>

Space missions on the OpenStreetMap stack.

---

## Environmental data

<table>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/50-earthquakes.webp"><img src="../../media/gallery/holly-eye/50-earthquakes.webp" alt="Earthquakes"></a><br><sub><b>Earthquakes (24 h)</b> with magnitudes — USGS. `WORKING`</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/51-earthquakes-osm.webp"><img src="../../media/gallery/holly-eye/51-earthquakes-osm.webp" alt="Earthquakes on OSM"></a><br><sub>Earthquakes on the OpenStreetMap stack.</sub></td>
</tr>
<tr>
<td width="50%"><a href="../../media/gallery/holly-eye/52-active-fires-osm.webp"><img src="../../media/gallery/holly-eye/52-active-fires-osm.webp" alt="Active fires"></a><br><sub><b>Active fires</b> — NASA FIRMS detections as a heat grid. `WORKING`</sub></td>
<td width="50%"><a href="../../media/gallery/holly-eye/53-active-fires-osm-close.webp"><img src="../../media/gallery/holly-eye/53-active-fires-osm-close.webp" alt="Active fires closer"></a><br><sub>Active fires, closer: individual detections with fire radiative power.</sub></td>
</tr>
</table>

<a href="../../media/gallery/holly-eye/54-scene-thermal-board.webp"><img src="../../media/gallery/holly-eye/54-scene-thermal-board.webp" alt="Thermal Threat Board scene" width="100%"></a>

**Thermal Threat Board** scene — earthquakes and heat in thermal style. `BETA`

---

## Scenes

Scripted camera tours that combine layers and styles — `BETA`.

<a href="../../media/gallery/holly-eye/60-scenes-panel.webp"><img src="../../media/gallery/holly-eye/60-scenes-panel.webp" alt="Scenes panel" width="100%"></a>

<table>
<tr>
<td width="33%"><a href="../../media/gallery/holly-eye/61-scene-global-flights-radar.webp"><img src="../../media/gallery/holly-eye/61-scene-global-flights-radar.webp" alt="Global Flights Radar"></a><br><sub>Global Flights Radar</sub></td>
<td width="33%"><a href="../../media/gallery/holly-eye/62-scene-city-overload.webp"><img src="../../media/gallery/holly-eye/62-scene-city-overload.webp" alt="City Overload"></a><br><sub>City Overload</sub></td>
<td width="33%"><a href="../../media/gallery/holly-eye/63-scene-omniscience-pullback.webp"><img src="../../media/gallery/holly-eye/63-scene-omniscience-pullback.webp" alt="Omniscience Pullback"></a><br><sub>Omniscience Pullback</sub></td>
</tr>
</table>

Orbital Watch and Thermal Threat Board are shown above under Space and Environmental.

---

## Voice interface

<a href="../../media/gallery/holly-eye/70-voice-dock.webp"><img src="../../media/gallery/holly-eye/70-voice-dock.webp" alt="Voice dock" width="100%"></a>

**Ask Holly** — `PROTOTYPE`. The dock (centre bottom) holds push-to-talk ("hold Space to speak · click mic to toggle voice"), a voice tier switch and a running cost meter. Voice commands steer the map — fly to a place, switch layers and styles. In this build no voice provider is configured, so the dock stays in standby; when enabled, voice uses paid speech services and is limited to internal use. Nothing was spoken or sent for these screenshots.

---

## HollyEarth ↔ Holly Eye

<a href="../../media/gallery/holly-eye/80-hollyearth-start-world-door.webp"><img src="../../media/gallery/holly-eye/80-hollyearth-start-world-door.webp" alt="HollyEarth start with the World door" width="100%"></a>

<a href="../../media/gallery/holly-eye/82-holly-eye-after-door.webp"><img src="../../media/gallery/holly-eye/82-holly-eye-after-door.webp" alt="Holly Eye after the door" width="100%"></a>

The **World** card on the HollyEarth start screen (Russian interface, `BETA` · world layers) opens Holly Eye through the World door, which hands over to the separate application — or says plainly that it is not running and how to start it (`WORKING`). Holly Eye opens on its default start view with **← TWIN** to return to the Riga Twin.

The two applications share no data in v0.1.0: Holly Eye holds no HollyEarth graph, case or Riga register data, and the door is navigation, not integration of records.
