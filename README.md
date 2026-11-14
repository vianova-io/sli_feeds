# Data quality of mobility operators

Cities and customers use this page to see how good the data of each mobility operator is. Vianova checks the data every day and shows the result for each operator and feed type, so that you can decide how much you can trust it.

**Last updated:** 2026-11-14 (UTC)

To search, filter and sort the table, open the [interactive page](https://vianova-io.github.io/sli_feeds/).

## How to read this table

Each row gives the typical values of one operator for one feed type (MDS or GBFS). Incidents (90 days) and Reactivity show the median, so that one extreme feed does not set the level. The other indicators show the average. The colour is calculated from the value that is shown, so the colour and the number always agree.

- 🟢 **Good**: the value is at the best level of the indicator.
- 🟠 **Fair**: the value is between Good and Poor.
- 🔴 **Poor**: the value is below the level that we expect.
- **n/a**: the indicator does not apply to this feed type. Telemetry, Trip distance and Freshness do not apply to GBFS feeds.
- **–**: we have no measurement for this indicator. A dash is not a bad score.
- **Range**: a range in brackets after the value, for example "(40–200 h)", shows the lowest and the highest value of the operator. The page shows a range only when enough measurements exist and they are not all the same. Incidents (90 days) never show a range.

The levels and the time window of each indicator are in the sections below the table.

## Operators

| Operator | Type | Telemetry | Trip distance | Incidents (90 days) | Reactivity | Uptime | Freshness |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Atom | MDS | 🟢 12 /min | 🟢 1.25 | 🟢 0 | – | 🟢 99.0 % | – |
| Beam | MDS | 🟢 18 /min (14–24 /min) | 🟢 1.10 (0.81–1.27) | 🟢 0 | – | 🟢 100.0 % | – |
| Bird | MDS | 🟢 8 /min (6–13 /min) | 🟢 1.26 (1.18–1.36) | 🟠 2 | 🟠 89 h (2–741 h) | 🔴 95.3 % (88.0–100.0 %) | 🔴 88 s (11–131 s) |
| Bolt | MDS | 🟢 9 /min (1–15 /min) | 🟢 1.24 (1.19–1.29) | 🟢 0 | 🟢 36 h (1–8657 h) | 🟢 100.0 % | 🟠 26 s (3–98 s) |
| cargoroo | GBFS | n/a | n/a | 🟢 0 | – | 🟢 100.0 % | n/a |
| Check | GBFS | n/a | n/a | 🟢 0 | – | 🔴 52.0 % | n/a |
| Cooltra | MDS | 🔴 1 /min | 🟢 1.54 | 🟠 2 | 🟢 36 h | 🟢 100.0 % | 🟠 36 s |
| Donkey | MDS | 🔴 1 /min | – | 🔴 242 | – | 🟢 100.0 % | – |
| Dott | MDS | 🟢 6 /min (4–14 /min) | 🟢 1.36 (1.24–1.94) | 🟢 0 | 🟢 6 h (1–974 h) | 🟠 97.1 % (73.0–100.0 %) | – |
| Edog | MDS | 🔴 1 /min | 🟢 1.19 | 🔴 10 | 🟢 1 h | 🟠 98.0 % | – |
| Hopp | MDS | 🔴 1 /min | 🟢 1.16 (1.12–1.23) | 🟠 2 | 🟠 88 h | 🟢 100.0 % | – |
| Hopp | GBFS | n/a | n/a | 🔴 41 | – | 🟢 100.0 % | n/a |
| Lime | MDS | 🟠 4 /min (3–8 /min) | 🟢 1.17 (1.09–1.26) | 🟢 0 | 🔴 295 h (1–14443 h) | 🟢 99.8 % (96.0–100.0 %) | – |
| moby | GBFS | n/a | n/a | 🟢 0 | – | 🟢 100.0 % | n/a |
| nextbike | GBFS | n/a | n/a | 🔴 116 | – | 🟢 99.9 % (99.0–100.0 %) | n/a |
| Pick_e_bike | GBFS | n/a | n/a | 🟢 0 | – | 🟢 100.0 % | n/a |
| Pikyrent | GBFS | n/a | n/a | 🔴 26 | – | 🔴 77.0 % | n/a |
| Pony | MDS | 🔴 1 /min | 🟢 1.32 | 🟠 2 | 🔴 750 h | 🔴 75.0 % | – |
| Poppy | GBFS | n/a | n/a | 🔴 8 | – | 🔴 95.0 % | n/a |
| Publibike | GBFS | n/a | n/a | 🔴 52 | 🔴 429 h | 🟢 100.0 % | n/a |
| RideMovi | MDS | 🟠 4 /min (4–5 /min) | 🔴 0.00 | 🟢 0 | – | 🟢 99.3 % (98.0–100.0 %) | 🟠 45 s (25–77 s) |
| Ryde | MDS | 🔴 2 /min (2–5 /min) | 🟢 1.31 (1.27–1.34) | 🟠 2 | 🟢 50 h (13–275 h) | 🟢 99.8 % (99.0–100.0 %) | 🟠 31 s (10–84 s) |
| Velospot | GBFS | n/a | n/a | 🔴 36 | – | 🟢 100.0 % | n/a |
| Voi | MDS | 🔴 1 /min (1–2 /min) | 🟢 1.30 (1.00–1.39) | 🟢 0 | 🟠 95 h (1–1775 h) | 🟢 99.8 % (96.0–100.0 %) | 🟠 21 s (12–29 s) |
| Yego | MDS | 🟠 3 /min | 🟢 1.54 | 🔴 4 | 🟢 27 h | 🔴 75.0 % | – |
| Zeus | MDS | 🟢 5 /min | – | 🔴 171 | 🔴 480 h | 🟢 100.0 % | 🔴 137 s |
| Zisch | MDS | – | – | 🟢 0 | – | 🟢 99.0 % | 🔴 119 s |

## No recent data

We do not score the operators in this list. We have no recent measurement for Telemetry, Trip distance and Freshness, so a score would not describe their data.

- Neuron (MDS)

## The indicators

### Telemetry

**What it measures:** How often the operator sends the position of a vehicle during a trip.

**Why it matters:** More positions show the real route of each trip. Few positions only show where a trip started and ended.

**Levels:**

- 🟢 Good: 5 or more updates per minute
- 🟠 Fair: 3 to 5
- 🔴 Poor: fewer than 3

**Time window:** last 2 days

**Operator value:** the average of the feeds of the operator.

**Applies to:** MDS feeds. GBFS feeds show n/a.

### Trip distance

**What it measures:** The trip distance that the operator reports, divided by the straight-line distance from start to end.

**Why it matters:** A ratio near 1 means that the operator reports a straight line, not the distance along the streets.

**Levels:**

- 🟢 Good: 1.1 or more (distance along the streets)
- 🔴 Poor: below 1.1 (straight line)

**Time window:** last 3 days, up to 1,000 trips

**Operator value:** the average of the feeds of the operator.

**Applies to:** MDS feeds. GBFS feeds show n/a.

### Incidents (90 days)

**What it measures:** The number of data incidents (API down, login error, missing or invalid data) that started in the last 90 days, for a typical feed of the operator.

**Why it matters:** Each incident means that data can be missing or wrong for some period.

**Levels:**

- 🟢 Good: no incident
- 🟠 Fair: 1 or 2 incidents
- 🔴 Poor: 3 or more incidents

**Time window:** last 90 days

**Operator value:** the median of the feeds of the operator.

**Applies to:** MDS and GBFS feeds.

### Reactivity

**What it measures:** The time that the operator takes to accept or reject a data request from a city, for a typical feed of the operator.

**Why it matters:** A slow answer delays the moment when a city can see the data.

**Levels:**

- 🟢 Good: 72 hours or less
- 🟠 Fair: 72 hours to 7 days
- 🔴 Poor: more than 7 days

**Time window:** all data requests since the first one

**Operator value:** the median of the feeds of the operator.

**Applies to:** MDS and GBFS feeds.

### Uptime

**What it measures:** The share of minutes when we could read the operator API without an error.

**Why it matters:** Each minute of downtime is a gap in the data.

**Levels:**

- 🟢 Good: 99 % or more
- 🟠 Fair: 97 % to 99 %
- 🔴 Poor: below 97 %

**Time window:** since March 2022, or since the first data if later

**Operator value:** the average of the feeds of the operator.

**Applies to:** MDS and GBFS feeds.

### Freshness

**What it measures:** The average delay between the newest event in the operator data and the time of our call.

**Why it matters:** A long delay means that the map does not show the vehicles in real time.

**Levels:**

- 🟢 Good: less than 15 seconds
- 🟠 Fair: 15 to 60 seconds
- 🔴 Poor: 60 seconds or more

**Time window:** last 7 days

**Operator value:** the average of the feeds of the operator.

**Applies to:** MDS feeds. GBFS feeds show n/a.
