# Data and service quality

## How it can affect your decision process.

At Vianova, we truly believe that data can help user take better decision. In this context, the more the data is accurate, the better will be the decision. We have decided to give more visibility on the quality of the data we can access, per provider and be totally transparent to our clients so they can consider potential limitations while using our product features.

In order to measure data source quality, we adopted the well know SLO/SLI methodology.

We have defined 7 Indicators as of today, that could express simply and comprehensively the exact objectives that could affect a service quality and we are constantly measuring them with SLI's.

## SLI

### Telemetry score

The number of individual GPS coordinates, collected for a trip, in average. This metric could have a big impact on the way we understand a trip and the route taken within a city. For more informations you can refer to our dedicated article.

### Trip distance score

Having the full distance of trip means better intermediate sampling but also global quality. It can vary from crow flies to detailed path.

### Incident score

Accessing the data is not always easy. The number of incident is a good indicator of past issues and possible downtime of the provider API's.

### Provider reactivity

How fast are the operators to accept feed requests coming from our customers.

### API Uptime

Uptime percentage of the operators API

### Data freshness

This indicator will help us to know how fresh is the data sent by the operators API. 

### Vehicles on prow

We find the feeds that have lost devices.

## SLI Scores 


|    | Operator         | Feed Type   | Driver version   | Telemetry   | Trip distance   | Quality incidents   | Operator reactivity   | Uptime     | Data freshness   | Vehicles on prow   |
|----|------------------|-------------|------------------|-------------|-----------------|---------------------|-----------------------|------------|------------------|--------------------|
| 16 | Atom             | mds         | 1.1              | ⭐          | ⭐⭐⭐⭐⭐      | ⭐⭐⭐⭐            | ⭐⭐⭐                | 0          | 0                | 0                  |
| 24 | Awto             | gbfs        | 1                | 0           | 0               | ⭐                  | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 43 | Beam             | mds         | 0.3.0            | ⭐⭐⭐⭐⭐  | ⭐⭐⭐⭐⭐      | 0                   | ⭐⭐⭐⭐⭐            | ⭐⭐⭐⭐⭐ | 0                | 0                  |
| 11 | Billy            | gbfs        | 1                | 0           | 0               | ⭐⭐                | ⭐⭐⭐⭐⭐            | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 42 | Bird             | mds         | 1.0              | ⭐⭐⭐⭐    | ⭐⭐⭐⭐⭐      | ⭐⭐                | ⭐                    | ⭐⭐⭐⭐   | 0                | ⭐                 |
|  1 | Bird             | gbfs        | 2                | 0           | 0               | ⭐⭐⭐              | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 30 | Bit Mobility     | mds         | 1.0              | No data     | No data         | 0                   | No data               | ⭐⭐⭐     | 0                | 0                  |
|  4 | BoltEU           | mds         | 1.0              | ⭐⭐⭐⭐    | ⭐⭐⭐⭐⭐      | ⭐⭐                | ⭐⭐                  | ⭐⭐⭐⭐⭐ | ⭐⭐⭐           | 0                  |
| 44 | BoltEU           | gbfs        | 2                | 0           | 0               | ⭐⭐                | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
|  2 | COOLTRA          | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐⭐          | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 13 | Check            | gbfs        | 1                | 0           | 0               | ⭐                  | 0                     | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 52 | City Bike        | gbfs        | 2                | 0           | 0               | ⭐⭐                | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 27 | Dott             | mds         | 0.4.0            | ⭐⭐⭐⭐    | ⭐⭐⭐⭐⭐      | ⭐                  | ⭐                    | ⭐⭐⭐⭐⭐ | ⭐               | ⭐                 |
| 32 | Felyx            | gbfs        | 1                | 0           | 0               | 0                   | ⭐⭐                  | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
|  8 | GoSharing        | mds         | 1.2.0            | ⭐          | ⭐⭐⭐⭐⭐      | 0                   | No data               | ⭐⭐⭐⭐⭐ | 0                | 0                  |
| 15 | Goteborg         | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐            | No data               | 0          | ⭐               | 0                  |
| 23 | HELBIZ           | mds         | 1.0              | ⭐⭐⭐⭐⭐  | ⭐⭐⭐⭐⭐      | ⭐                  | 0                     | ⭐⭐⭐⭐⭐ | ⭐⭐             | ⭐⭐⭐             |
| 47 | Inurba           | gbfs        | 2                | 0           | 0               | ⭐⭐⭐              | 0                     | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 17 | LeasysGO!        | mds         | 1.1              | No data     | No data         | ⭐⭐⭐⭐⭐          | No data               | ⭐⭐⭐⭐⭐ | 0                | ⭐⭐⭐⭐⭐         |
| 29 | Lime             | mds         | 0.3.2            | ⭐⭐⭐⭐⭐  | ⭐⭐⭐⭐⭐      | ⭐⭐                | 0                     | ⭐⭐⭐⭐⭐ | 0                | 0                  |
| 21 | Lime             | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐⭐          | No data               | 0          | ⭐               | ⭐⭐⭐⭐⭐         |
|  5 | Link             | gbfs        | 2                | 0           | 0               | ⭐⭐                | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 51 | Mimoto           | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐            | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 31 | Mobility Go      | gbfs        | 2                | 0           | 0               | ⭐⭐⭐⭐            | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 18 | Pick_e_bike      | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐            | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 45 | Pony             | mds         | 1.0              | ⭐          | ⭐⭐⭐⭐⭐      | ⭐⭐                | 0                     | ⭐⭐⭐⭐⭐ | 0                | 0                  |
| 26 | Pony             | gbfs        | 1                | 0           | 0               | ⭐⭐                | 0                     | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 48 | Poppy            | gbfs        | 1                | 0           | 0               | ⭐                  | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 37 | Publibike        | gbfs        | 1                | 0           | 0               | ⭐⭐⭐              | ⭐                    | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 50 | Renault          | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐⭐          | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 33 | RideMovi         | mds         | 1.0              | ⭐⭐⭐⭐    | ⭐              | ⭐⭐                | ⭐⭐                  | ⭐⭐⭐     | ⭐⭐             | 0                  |
|  6 | Ryde             | mds         | 1.0              | ⭐          | ⭐⭐⭐⭐⭐      | ⭐⭐⭐⭐⭐          | ⭐⭐⭐                | ⭐⭐⭐⭐⭐ | 0                | 0                  |
| 20 | SHARE-NOW        | mds         | 1.1              | ⭐⭐⭐⭐⭐  | No data         | ⭐                  | No data               | ⭐⭐⭐⭐⭐ | 0                | 0                  |
| 35 | Seven Group      | mds         | 1.0              | No data     | No data         | ⭐⭐⭐              | ⭐⭐                  | ⭐⭐⭐⭐   | 0                | ⭐⭐⭐             |
| 19 | Spin             | mds         | 0.4.0            | No data     | No data         | ⭐⭐⭐⭐            | No data               | ⭐⭐⭐⭐⭐ | 0                | ⭐⭐⭐⭐           |
| 28 | Spin             | gbfs        | 2                | 0           | 0               | ⭐                  | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 22 | Superpedestrian  | mds         | 1.0              | ⭐⭐⭐      | ⭐⭐⭐⭐⭐      | 0                   | 0                     | ⭐⭐       | 0                | 0                  |
|  3 | Superpedestrian  | gbfs        | 1                | 0           | 0               | 0                   | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 41 | Tier             | mds         | 1.0              | ⭐⭐⭐⭐    | ⭐⭐⭐⭐⭐      | ⭐⭐⭐⭐⭐          | ⭐                    | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 14 | Tier             | gbfs        | 2                | 0           | 0               | ⭐⭐⭐              | 0                     | ⭐⭐⭐⭐   | ⭐               | ⭐⭐⭐⭐⭐         |
| 40 | Voi              | mds         | 0.4.0            | ⭐          | ⭐              | ⭐⭐⭐⭐⭐          | ⭐                    | ⭐⭐⭐⭐⭐ | ⭐⭐⭐           | 0                  |
|  7 | Voi              | gbfs        | 1                | 0           | 0               | ⭐⭐⭐⭐⭐          | No data               | ⭐⭐⭐     | ⭐               | ⭐⭐⭐⭐⭐         |
| 34 | WIND             | mds         | 0.4.1            | No data     | No data         | ⭐⭐⭐⭐            | No data               | ⭐⭐⭐⭐⭐ | 0                | ⭐⭐⭐⭐⭐         |
| 10 | Wheels           | gbfs        | 2                | 0           | 0               | 0                   | No data               | ⭐⭐⭐⭐⭐ | ⭐               | ⭐⭐⭐⭐⭐         |
| 49 | Zeus             | mds         | 1.0              | ⭐⭐⭐⭐    | ⭐⭐⭐⭐⭐      | ⭐⭐⭐              | No data               | ⭐⭐⭐⭐   | 0                | 0                  |
| 46 | ZigZag           | gbfs        | 1                | 0           | 0               | 0                   | No data               | ⭐⭐⭐⭐   | ⭐               | 0                  |
| 25 | Zipp             | mds         | 0.3.2            | ⭐⭐⭐⭐⭐  | ⭐⭐⭐⭐⭐      | ⭐⭐⭐⭐⭐          | No data               | ⭐⭐⭐⭐⭐ | 0                | 0                  |
|  0 | Zisch            | mds         | 1.0              | No data     | No data         | ⭐⭐⭐              | ⭐                    | ⭐⭐⭐⭐   | 0                | ⭐⭐⭐⭐           |
| 36 | Zvipp            | gbfs        | 1                | 0           | 0               | ⭐⭐⭐              | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 38 | Zwings           | gbfs        | 1                | 0           | 0               | 0                   | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 39 | cargoroo         | gbfs        | 1                | 0           | 0               | 0                   | ⭐                    | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
| 12 | highspeedservice | mds         | 0.3.0            | No data     | No data         | ⭐⭐⭐⭐⭐          | No data               | ⭐⭐⭐⭐⭐ | 0                | ⭐⭐⭐⭐⭐         |
|  9 | nextbike         | gbfs        | 1                | 0           | 0               | ⭐⭐                | No data               | ⭐⭐⭐⭐⭐ | ⭐               | 0                  |
## SLI measure

### Telemetry score

#### Classification

For all feeds, we compute the number of trips updates we have per minute.

`CEIL(AVG(DIV0(ST_NPOINTS(trip_trajectory), trip_duration / 60.0)))`

We count the number of points we have for one full trip.
We divide it by the trip duration (in minutes).
We compute the average of this indicator for all trips a feed sent
=> We have an average number of trip updates per minute a feed gives.

Warning : The GBFS feeds only have start and end points information, they will always have 0 for this indicator.

Based on the number of trip updates per minute, we can attribute a score to the feed, as you can see on the table below :

#### Scoring
- 0 Only start/end trip
- 1 telemetry per minute < 1
- 2 telemetry per minute < 2
- 3 telemetry per minute < 3
- 4 telemetry per minute >= 6
- 5 Full telemetry of the trip

#### Timeline
Computed on the last 2 days of data

### Trip distance score

#### Classification

This indicator will help us know how precise is the trip distance given by a feed. We base the assumption on : if a trip distance is ~= to the crow fly distance between the start point and end point, it means that the trip distance computed by the feed used a crow fly measurement, instead of computing the real distance based on the streets.

We make a ratio between the crow fly distance computed by us and the trip distance given by the feed. If this ratio is close to 1, it means that the trip distance has been computed using a crow-fly distance.

Warning : The GBFS feeds will always have 0 for this indicator.

#### Scoring
- 0 : GBFS
- 1: Ratio < 1.1
- 5: Ratio > 1.1

#### Timeline
Computed on the last 3 days of data

### Incidents score

#### Classification

The data pipeline is complex consist in 4 distincts steps. At each steps incidents can occurs.

##### Extract
At the extraction step, any of this HTTP issue will be consider as an incident

- provider_system_down (timeout)
- provider_system_status (HTTP 500)
- provider_system_auth (HTTP 401)

##### Load / Transform / Serve
During those step, various problems can occurs, please find an non exhaustive list of issues.

- provider_data_valid(specs) 
- provider_data_complete (missing field)
- provider_data_accuracy (invalid field) 
- provider_data_integrity (wrong relation)
- provider_kpi_availiblity (not accessible)
In order to simplify, we will detect when there is a low number of trips VS the number of devices that we can detect.
We will count 1 drop as an incident, even if the drop continues over time.

#### Scoring
- 0 less than 1 over the last day
- 1 less than 1 over the last 3 days
- 2 less than 1 over the last week
- 3 less than 1 over the last month
- 4 less than 1 over the last 3 month
- 5 less than 0 over the last 6 month

#### Timeline
Computed on the last 6 month of data

### Provider reactivity

#### Classification

TODO

#### Scoring

TODO

#### Timeline
Computed since the first feed request that happened

### API Uptime

#### Classification

We will compute the uptime of the different feeds.

We  keeps track of all ingestion errors that happened on the feeds. One ingestion error matches to 1 feed not being able to be reached (or some other errors) for 1 minute.

Based on this data, we can compute average uptime of the feeds (since 03/2022, when we started keeping ingestion errors)

#### Scoring

uptime is a percentage between 0 and 1

- 0 : uptime < 0.96
- 1 : uptime < 0.97
- 2 : uptime < 0.98
- 3 : uptime < 0.99
- 4 : uptime < 1
- 5 : uptime = 1

#### Timeline
If the feed ingestion started before 03/2022, computed since 03/2022 else computed since the oldest feed ingestion date

### Data freshness

#### Classification

This indicator will help us to know how fresh is the data sent by the providers API. We will compare the most recent events in the API response to the time we actually asked for the data. If the average difference (in seconds) is high, it means the data is not fresh enough. It will have impact on showing devices in real time.

For GBFS feeds, we only have one update per minute, so the score will always be 1

For MDS, we take the most recent event in the API response compared to the call execution time.

#### Scoring

avgdiff = Average difference in seconds

- 5 : avgdiff < 5
- 4 : avgdiff < 10
- 3 : avgdiff < 15
- 2 : avgdiff < 30
- 1 : avgdiff < 60 or feed = GBFS
- 0 : avgdiff < 60*5 (5 min)

#### Timeline
Computed on the last week of data for MDS
### Vehicles on prow

#### Classification

We will find the feeds where we lost devices.

We define a “lost device” as a device that has not given any update for more than 7 days in a row across the whole history fleet.

Basically, if a vehicle is lost or is in PROW, it's a bad rate for this indicator.

A Public Right Of Way (PROW) is a way, which the public have a right to pass and re-pass providing that the public stay on the route and do not cause a nuisance or obstruction. The purpose of Public Rights Of Way is to protect the rights of the public to use these accesses and also to prevent their obstruction.

#### Scoring

vehicle_state_on_prow

- 0 : vehicle_state_on_prow = False
- 5 : vehicle_state_on_prow = True

#### Timeline
Computed on the last 3 month of data
