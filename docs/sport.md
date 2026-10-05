# Sport — HollySport

HollySport is the sport lens: Latvian sport records turned into a navigable city.

## Real data — WORKING
- Records from **federation registers**, **official result books** and **public event archives** (see [DATA_SOURCES.md](../DATA_SOURCES.md)): clubs, athletes, events, bouts, competition categories, placings, venues.
- Venue points come from the State Address Register when an address matches exactly one building.
- People are joined only through stable source identifiers; possible matches go to human review.
- **No stored competition results of minors** under the current project policy.

## Passports — WORKING
Shareable pages for every club, athlete, event and venue:
- **Club** — training places, sports, federations, the price a family pays (a price, not revenue), coaches named by the club, seasons read from official protocols, and a **public context** window into the investigation about the club. **SHOWCASE READY**.
- **Athlete** — bouts as the source printed them (opponent, event, method), placings from official books; nothing invented about height, weight or club.
- **Event** — results by category, participants, the clubs athletes represented. **SHOWCASE READY**.
- **Venue** — district, address-register point, what was held there; owner, capacity and hire shown as "not recorded" when unknown.

## HollySport City — WORKING (real layer)
A game-styled city view over the Twin with real counts, real clubs and venues on the map, and real past events.

## Preview layers — PROTOTYPE / DEMO
- **Season, missions, XP, district levels** — a labelled DEMO preview; nobody has earned points; there is no progression system.
- **Event planning wizard, organiser accounts, review queue, creator and partnership workspaces** — PROTOTYPE, not in real use.
- **Market, wallet, leagues, club tokens, ticketing** — RESEARCH; shown only as "coming later".

## Other
- Sport directory, sport map and sport graph — **BETA**.
- A ranking computed from the bouts the archive holds, labelled as not a federation ranking — **BETA**.
