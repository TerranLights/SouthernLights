# Reference: Shared Tepenia-Universe Lore

Southern Lights is set in Tepenia, the same universe as the game *Inner Tepenia*, a planned "Cryptograph Helix" novel series, and a planned "Outer Tepenia" game trilogy. This doc is a pointer, plus a pull-out of the facts most likely to matter for the show, not a copy of the source material. Treat the source repos as canon; update this doc if it drifts.

**Two source repos now, not one — check dates, since content is actively migrating between them:**

- **https://github.com/TerranLights/TepenianUniverseTimeline** (local clone: `Doll-Fi/media/Reference/TepenianUniverseTimeline`) — the **official cross-media canon/timeline repo**, shared across every property in the universe, not specific to the game. As of 2026-07-11, universe-level history/timeline content is being migrated *out* of InnerTepeniaGDD and *into* this repo — e.g. `InnerTepeniaGDD/Worldspace/World_History_Reference.md` is now just a pointer stub; the real content lives at `TepenianUniverseTimeline/Reference/World_History_Reference.md`. **Check here first for anything timeline/history-related.** Structure: four eras — First Interwar Period (2083–2564, no dedicated project yet), **Second Interwar Period (2564–2812, this show's basis)**, Solar Colonization (4th millennium, basis for the Cryptograph Helix novels), Post-Solar eras (basis for the Outer Tepenia game trilogy).
- **https://github.com/TerranLights/InnerTepeniaGDD** (~600MB, ~2,270 files — too large to copy in) — still the primary source for game-specific material: characters, factions, district/city Megasheets, story content not yet migrated to the universe-timeline repo.

**Scope:** everything in that repo is fair game for Southern Lights **except** the video-game-mechanics material, which doesn't apply to a TV show:
- `Game-Mechanics/` (character creation, AP/combat system, perks, cyberware, stats)
- `Storyline/Minmax-Builds/` (pure stat-build theorycrafting)
- `Dev-Road-Map/` (game production planning/phasing)
- `Press-Outreach/` (game marketing)
- `Reference/perks-full-list.txt`, `Reference/traits-full-list.txt`

Everything else — history, geography, characters, factions, religions, story material, reference art/maps — is in scope. Below is a topic index into the parts most likely to matter, organized by subject rather than by folder. Pull specific files/facts into Southern Lights' own docs as they actually get used; this stays a map, not a mirror.

## Southern Lights' own working docs (pulled-out material, not just pointers)

**Storyline:**
- [`Storyline/Timeline.md`](../Storyline/Timeline.md) — the show's adopted macro-structure (a beat sheet you synthesized from Save the Cat/Bell/Truby/Campbell), dated across the full 2564–2812 span, plus every other dated event found across the source
- [`Storyline/The-Falkland-Treaty.md`](../Storyline/The-Falkland-Treaty.md) — the opening event: real-world treaty precedents, the Maggie Aarden coerced-signature thread, the Great Corruption mystery
- [`Storyline/The-Amundsen-Tower.md`](../Storyline/The-Amundsen-Tower.md) — the Tower's engineering, construction era, and destruction; Kendra Heinrich's last stand
- [`Storyline/Writers-Room-Hooks.md`](../Storyline/Writers-Room-Hooks.md) — the strongest dramatic material pulled together across the whole survey, ranked by usability
- [`Storyline/Weapons-and-Tools-Philosophy.md`](../Storyline/Weapons-and-Tools-Philosophy.md) — written directly for the show by the source project (2026-07-11): tools in civilian identity vs. their game-era weaponized form, and confirmation that **the final season depicts the Long Night War on-screen**

**Worldspace:**
- [`Worldspace/Characters.md`](../Worldspace/Characters.md) — full-span robots, war-era figures, pre-Treaty founding-myth Dolls, human dynasties
- [`Worldspace/Factions-and-Religions.md`](../Worldspace/Factions-and-Religions.md) — the six robot religions, city-origin factions, post-war refugee factions
- [`Worldspace/Locations.md`](../Worldspace/Locations.md) — the Falkland Treaty's internal structure, all ~35 Federation cities and their fates, Concordia's 13 districts, Upper Earth & orbital infrastructure
- [`Worldspace/Robot-Biology-and-Culture.md`](../Worldspace/Robot-Biology-and-Culture.md) — how an ageless robot cast actually works: lifespan, death, the iris emotion-tell, siligel/coolant/smoking culture
- [`Worldspace/Core-Systems.md`](../Worldspace/Core-Systems.md) — the grid/currency/city-logistics systems tying the war's ending together, plus the Enneagram character framework and the unmarked-discovery design principle
- [`Worldspace/Environments-Concordia-Districts.md`](../Worldspace/Environments-Concordia-Districts.md) — deep environment/daily-life/culture reference for all 13 Concordia districts, for scene and set planning
- [`Worldspace/Environments-Federation-Cities.md`](../Worldspace/Environments-Federation-Cities.md) — the same, for all ~35 Federation cities across five subnets (Concordia's own subnet is covered by the districts doc above)

**Notable:** the source GDD already names this exact project — `Worldspace/Locations-and-Levels/Outside-World/Orbital-Infrastructure/README.md` describes "a planned TV series spanning the entire Second Interwar Period," alongside a planned novel series and the game itself, all three meant to share lore rather than duplicate it.

### History & world logic
- **`TepenianUniverseTimeline/Reference/World_History_Reference.md`** — full timeline of confirmed world history (moved here 2026-07-11; see pulled-out table below)
- **`TepenianUniverseTimeline/Timeline Eras/2 The Second Interwar Period/Timeline.md`** — the authoritative version of the beat sheet [`Storyline/Timeline.md`](../Storyline/Timeline.md) is built from; re-check this before treating our own Timeline.md as fully current
- `General-Overview-Notes/broad_overview_summary.md` — one-paragraph setting summary
- `Worldspace/Design_Principles.md`, `Worldspace/City_Logistics.md`, `Worldspace/National_Economy_and_Currency.md`, `Worldspace/Energy_Grid_Failure_Rationale.md`, `Worldspace/Enneagram_Dynamics.md`
- `Theoretical-Calculations/` — hard-science justification for Tepenian infrastructure (Amundsen Tower/space elevator design, orbital infrastructure, Von Braun wheel mass budgets)
- `Reference/Materials/Treaties/`, `to-be-integrated/treaties/` — Falkland Treaty draft and real-world treaty research behind it
- `Reference/Real-World/` — the real Antarctic station data and climate data the setting is built on

### Characters
- `Worldspace/Characters/` — `Dolls/`, `Major_NPCs/`, `Minor_non-Doll_NPCs/`, `District-Quest-NPCs/`, `Upper-Earth_Defectors/`, plus `Character_Concept_Bank.md`, `Character_Connection_Map.md`, `Enneagram_Character_Index.md`

### Factions & religion
- `Worldspace/Factions/` — faction concepts, district-origin factions, Eyes of Gold, district conflicts
- `Worldspace/Factions/Robot_Religions/` — The Eyes of Gold, Sylvester James Gates Adinkras, Polydimensional Animism, Ice-Cold Buddhism, Cymatics Reverence, God-mind Universe Simulation
- `Worldspace/Robot_Biology_and_Culture/Robot_Physiology_and_Cultural_Practices.md`

### Locations
- `Worldspace/Locations-and-Levels/Concordia-City/` — district layout, districts, Second Interwar cultural sheet
- `Worldspace/Locations-and-Levels/Outside-World/` — `Tepenian-Federation/`, `Upper-Earth/`, `Orbital-Infrastructure/`
- `Reference/Images/Maps/` — Antarctic highway/flight/Arcanet maps, North America map with tentative post-war labels

### Story material
- `Storyline/DLC_Overview.md`, `Storyline/DLC_01_Echoes_of_Amundsen.md`, `Storyline/DLC_PSB_Framework.md` (Planetary Split Brain)
- `Storyline/Main-Story/` — main quest hooks, act progression, ending possibilities
- `Storyline/Endings/`, `Storyline/Side-Content/`
- `to-be-integrated/` — raw brainstorming not yet folded into canon; check `miscellaneous/` and skip `x-possible-trash/` unless nothing else covers the topic

### Reference art
- `Reference/Images/Concept-Art/`, `Reference/Images/Flags/`, `Reference/Images/Logos_and_Symbols/`

## Shared-universe timeline (confirmed as of the source GDD)

| Date | Event |
|---|---|
| 2083-09-26 | Global nuclear war reshapes the world; same year, first sentient robot created at U.R.U.K. off Hawaii |
| 2318-04-27 | Jeju-do court ruling grants robots full legal personhood (Gyeong-ja Yun case) |
| ~2563–2564 | The War of Upper Earth — first anti-robot war |
| 2564-06-21 | Falkland Treaty signed at Stanley, Falkland Islands. Ends the War of Upper Earth; exiles robots (and human allies who elect to go with them) to Antarctica; establishes the **Federation of Tepenia** |
| ~2630–2640 | Amundsen Tower (space elevator at the South Pole) completed |
| 2812 | The Long Night War — second anti-robot war, fought in/around Tepenia itself. Destroys Amundsen Tower, cripples the continental power grid, likely causes the Planetary Split Brain, forces evacuation of much of the population off-world |

**Present day (game's "now"):** roughly a generation-plus after the Long Night War. Upper Earth has written Tepenia off as no longer a threat. The off-world evacuees who fled via Amundsen Tower before its destruction are alive and have built out into orbit and toward Mars — Concordia has no idea what's become of them.

## Geography that may matter

Every real Antarctic research station became a Tepenian city. Confirmed mappings:

| Real station | Tepenian city | Notes |
|---|---|---|
| Concordia Station (Dome C) | Concordia | Last major surviving city; inland (~1,100 km from coast), altitude 3,233m |
| Jang Bogo Station | Janbogo | Ross Sea coast; damaged in the Long Night War, source of refugees; off-map/referenced only in the game |
| Palmer Station | Palmer City | Cultural/entertainment hub, neutral ground ("Las Vegas/Atlantic City/New Orleans/St. Petersburg in one") |
| Belgrano Station II | Belgrano | Coastal |
| McMurdo Station | Fort McMurdo | Coastal; military connotation |
| Neumayer Station III | Neumayer | Coastal |
| All others | TBN | Same real-station-to-city naming pattern applies |

Most coastal cities were hit hard in the Long Night War; Concordia survived on inland position and self-sufficiency.

## Open items in the source GDD to watch

The source lore is under active development — some things flagged TBD there (Sinian Federation detail, Unified Korea's present-day status, the Falkland Treaty's full text/signatories, The Vigil faction) may firm up or change over time. Re-check `World_History_Reference.md` before locking any Southern Lights beat to a TBD item.

## Southern Lights' own place in this timeline

Decided — see [`Storyline/Timeline.md`](../Storyline/Timeline.md) for the full picture: the show *is* the Second Interwar Period, start to finish (2564 landing through the 2812 war), robot-anchored ensemble cast, final season depicts the war on-screen.
