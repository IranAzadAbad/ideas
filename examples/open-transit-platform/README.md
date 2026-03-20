# Open Real-Time Transit Platform for Iranian Cities

> This is an example idea to show good structure. See [CONTRIBUTING.md](../../CONTRIBUTING.md) for submission guidelines.

---

## Author

**Name**: [Sample Author]
**Background**: Urban planner and software engineer, worked with Tehran's municipality on infrastructure projects for 4 years. Now based in Amsterdam. Frustrated every visit home by the lack of reliable transit information for a city of 10 million.
**Contact**: example@email.com

---

## Abstract

An open-source platform that aggregates real-time location data from Tehran's buses, metro, and BRT lines into a single unified feed -- accessible via a public API and a simple mobile app. Lets citizens plan trips, reduces wait time uncertainty, and gives municipalities data they currently don't have.

Problem: Tehran operates one of the region's largest transit networks (metro, BRT, regular buses) but has no unified real-time tracking. Commuters wait without information. Planners make decisions without data. The city's transit potential is undermined by poor information. Problem solved: A lightweight data layer on top of existing infrastructure -- no new vehicles, no new routes, just visibility.

---

## Why It's Interesting

**Why now**:
- GPS-enabled phones are ubiquitous among drivers and can act as low-cost tracking devices
- Tehran's metro authority has begun digitizing operations -- data exists but isn't public
- Civic tech movements in Iran are growing; developers want to build useful local tools
- Similar open transit projects (OpenStreetMap, TransitApp, Moovit) have demonstrated the model globally

**Why Iran**:
- Tehran is among the most congested cities in the world -- even marginal transit improvements have large impact
- No unified transit app exists; commuters rely on word of mouth and guesswork
- Farsi-first design is essential and often missing from international transit tools
- Municipal governments respond well to demonstrated pilots -- proof of concept in Tehran opens doors to Isfahan, Mashhad, Shiraz
- Open data from this platform could enable secondary innovation: research, journalism, urban planning tools

**Expected impact**:
- Year 1: Real-time tracking live for 3-5 metro lines and 10+ BRT routes. 10,000+ active users in Tehran.
- Year 2: Full metro coverage, 50+ bus routes, open API with 5+ third-party apps built on it.
- Year 3: Expansion to 2 additional cities. Platform adopted or endorsed by at least one municipal transit authority.

---

## Approach

### Key Steps

1. **Data & Partnership (Months 1-3)**: Secure the data
   - Identify which transit authorities have GPS data and in what format
   - Negotiate open data agreements with Tehran Metro, BRT authority, and bus operators
   - Where data doesn't exist: prototype crowdsourced tracking via driver apps (similar to how Moovit started)
   - Engage municipality's smart city office -- they have political motivation to show innovation

2. **Core Platform (Months 3-6)**: Build the data layer
   - Ingest and normalize real-time vehicle location feeds (GTFS-RT standard)
   - Build public API: any developer can query live transit positions
   - Basic web map showing live vehicle locations
   - Farsi-first interface throughout

3. **Commuter App (Months 6-9)**: User-facing product
   - Trip planner: enter origin/destination, get route with live ETAs
   - Line status alerts (delays, disruptions)
   - Offline fallback for scheduled times when live data unavailable
   - Android-first (higher market share in Iran), PWA for web

4. **Open Ecosystem (Months 9-18)**: Enable others to build
   - Publish open API documentation
   - Outreach to developer communities (Iranian dev Telegram groups, universities)
   - Partner with navigation apps to embed transit data
   - Publish anonymized ridership data for researchers and urban planners

### Timeline

Data partnerships + first API: 6 months. Public app launch: 9 months. Multi-city expansion: 18-24 months.

### Methods & Technology

- **Standard**: GTFS and GTFS-RT (global transit data standards) -- ensures compatibility with existing tools
- **Stack**: Python data ingestion pipeline, PostgreSQL + PostGIS for spatial data, REST API, React Native mobile app
- **Crowdsourcing fallback**: Driver-side lightweight app to report position where official feeds don't exist
- **Open source**: All code on GitHub. MIT license. Invites global transit tech community to contribute.
- **Hosting**: Cloud-based with Iranian CDN fallback for reliability within Iran

### Go-to-Market

- **Phase 1**: Launch with a vocal commuter community -- Tehran has active urban planning and civic tech groups on Telegram and Twitter/X
- **Phase 2**: Developer outreach -- open API with good docs invites third-party apps (accessibility tools, delivery routing, research)
- **Phase 3**: Municipal engagement -- bring usage data and commuter feedback to city officials as evidence for formal adoption

---

## Help Needed

- **Backend engineer(s)**: 1-2 people, 6+ months. Experience with geospatial data, real-time data pipelines, and API design.
- **Mobile developer**: 1 person for Android/PWA app. Farsi language support and RTL layout experience strongly preferred.
- **Urban data specialist**: 1 person familiar with GTFS standards and transit data formats to lead data partnerships.
- **Iran-based liaison**: 1 person in Tehran to navigate municipal relationships, attend meetings, coordinate with transit authorities.
- **UX designer**: 1 person (part-time) for Farsi-first interface design and usability testing with real commuters.
- **Funding**: $50-80K for 12 months (salaries, cloud infrastructure, travel for municipal meetings, user research).
- **Partnerships**: Data access agreements with Tehran Metro, BRT, and bus operators -- critical path item. Municipal smart city office endorsement helps unlock these.

---

## Supporting Material

- GTFS standard documentation: [developers.google.com/transit](https://developers.google.com/transit)
- Case study: how Moovit crowdsourced transit data in early markets: [Link]
- Tehran Metro network map: [Link to public map for reference]
- Similar open civic tech projects in the region: [Link]

---

## Notes

- **Critical dependency**: Data access from transit authorities. If they won't share GPS feeds, crowdsourced approach is slower but viable -- Moovit proved this model.
- **Government as partner**: Open data and civic tech are now welcomed, not feared. Transit authorities have every incentive to be seen as modern and responsive -- use that. Come with a working demo, not just a proposal.
- **Sustainability**: Open-source core stays free. Revenue options: premium API tiers for commercial users (delivery companies, logistics), white-label app for municipalities, or sponsorship from civic foundations.
- **RTL and Farsi**: Non-negotiable from day one. Retrofitting RTL support is painful -- build it in at the start.
