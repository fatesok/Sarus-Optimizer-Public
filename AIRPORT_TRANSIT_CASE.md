# Airport Transit Hub Planning Case

This public case page explains the airport-transit hub planning scenario at a high level. It is intended for public communication only and does not expose source code, private algorithms, raw data, or internal calibration details.

![Airport transit hub capacity concept](assets/airport-transit-hub-concept.svg)

## Planning question

Which regional transit candidate or portfolio best serves expanded airport demand while satisfying station, road, curb, parking, connector, and service-level constraints?

## Why this case matters

Major airport expansion can create ground-access pressure long before the terminal itself reaches theoretical capacity. Sarus-Optimizer frames the problem as a connected demand, access, and hub-capacity question.

The case connects:

- regional demand allocation
- airport passenger movement by hour
- O-D and connecting passenger separation
- candidate rail, HSR, bus, LRT, and local-transit systems
- hub-level mode allocation
- station and terminal-connector capacity
- road, curb, parking, and ride-hail constraints
- cost and service-level tradeoffs

## What Sarus-Optimizer evaluates

Public-safe evaluation categories:

- candidate regional transit systems
- HSR or non-HSR access alternatives
- station-centered catchment areas
- demand captured by each candidate
- demand not captured by candidate systems
- peak-hour hub demand
- bus, LRT, rail, concourse, vertical-circulation, and connector requirements
- road, parking, curb, taxi, and ride-hail constraints
- unmet demand, if any
- sensitivity to demand, mode share, capacity, peak spreading, and cost assumptions

## Example comparison frame

| Dimension | Public comparison question |
|---|---|
| Regional access | Which corridors capture the strongest demand? |
| Hub demand | How much demand remains for the airport public-transport hub? |
| Capacity | Which station or access components become binding? |
| Service level | Are queueing, crowding, and connector assumptions acceptable? |
| Road/parking | How much demand must shift away from private vehicles? |
| Sensitivity | Which assumptions change the recommendation most? |

## Public outputs planned

The public version of this case can include:

- scenario overview
- candidate-system summary
- demand-capture summary
- hub-service requirement summary
- capacity-constraint summary
- sensitivity summary
- selected visuals or static outputs

## What remains private

The public case page does not publish:

- source code
- private optimization logic
- implementation details
- raw datasets
- internal tasks
- unreviewed model outputs
- exact private calibration assumptions

## Status

This case is in specification and private development. Public benchmark summaries should be published only after the assumptions and outputs have been reviewed.
