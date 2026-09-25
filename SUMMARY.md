# Pre Draft v6.11

## What was wrong in v6.10
Protecting only ESPN `active_53` cut stars who are currently on ESPN IR (Myles Garrett, Micah Parsons, Laremy Tunsil, etc.).

## Rules now
1. Repair stale JSON `rating` from attribute average (**2236** players; Chig 65→83)
2. Treat IR as normal roster (per earlier request)
3. Each team keeps **top 54 by rating**; rest → FA

## Cut audit
- Accidental active-53 cuts (OVR ≥ team cutoff): **36**
- Active-53 below cutoff (correct cuts): **192**
- Unmatched names / no card: **1**
