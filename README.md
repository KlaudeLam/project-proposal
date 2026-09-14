# Project Proposal

## Project title

**Yumma!** — a NYC halal food map for Muslim diners

## What and why?

Finding reliable halal food is harder than it should be. A restaurant tagged "halal" online might be officially certified, might just avoid pork, or might be wrong entirely — Google Maps and Yelp weren't built to capture that distinction. Muslims in NYC currently piece this together from scattered sources: word-of-mouth, outdated blog posts, and directories like Zabihah or HMS that are useful but siloed and not tailored to quick, everyday decision-making.

Yumma solves this by giving users a single, trustworthy map of halal food in NYC — with a clear indicator of how certain each listing's halal status actually is, so people can decide for themselves how much to trust it.

## For whom?

Muslims living in or visiting NYC who keep halal — especially students, since we have direct access to campus Muslim Student Associations for early testing, feedback, and seed data validation. This is a real, reachable user base we can talk to throughout the semester, not a hypothetical one.

## How?

- **Map view**: See halal restaurants, groceries, and butchers near you or in any NYC neighborhood.
- **Trust indicator**: Each listing shows its certification basis (e.g., HMS/IFANCA-certified, Muslim-owned, self-declared) so users know how confident to be.
- **Listing details**: Cuisine, certification source, alcohol-served flag, hours, and halal-specific reviews.
- **Search and filter**: By certification type, cuisine, distance, or open now.
- **Save spots**: Bookmark places for later.

The goal: open the app anywhere in NYC and get a fast, trustworthy answer to "where can I eat here?"

## Scope

### Short-term (within semester)

- **NYC only.** A dense, well-documented city means the map will feel genuinely useful, not sparse.
- **Team-curated data, not crowd-sourced.** Real sources exist to build from — Zabihah (346+ NYC listings) and HMS USA (114+ certified NYC listings) — but neither offers a public API or bulk export, so the team will manually research and hand-enter a seed database (~50–100 listings), cross-referencing certification status. This sidesteps the much harder problem of building and moderating an open submission pipeline.
- **Fixed trust categories**, not an open-ended reputation system, keeps the verification feature buildable in one semester.


### Long-term

- **More cities**: Expand beyond NYC to other major US cities with large Muslim populations (Chicago, Dallas, LA), then internationally.
- **Crowd-sourced submissions**: Open listings to user submissions with moderation, instead of team-curated data.
- **User features**: Trip planning, personalized recommendations, prayer time/qibla integration.
- **Business tools**: Self-serve portal for owners to claim/verify their own listing.

All expansions build on the same core data model from the NYC MVP — growth is additive, not a redesign.

This leaves a solid core (map, search/filter, verified data) achievable well before semester end, with clear stretch goals (user submissions, more boroughs, richer reviews) if time allows.
