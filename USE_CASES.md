# Public Use Cases

Sarus-Optimizer is designed for planning problems where the best answer depends on location, capacity, demand, access constraints, cost, service quality, and uncertainty.

## Use case 1 - Stadium location and capacity planning

**Question:** Where should a new stadium be located, and how large should it be?

**Typical users:** facility planners, sports clubs, stadium operators, municipalities, investors, consultants.

**What Sarus-Optimizer can evaluate:**

- candidate locations
- capacity alternatives
- event demand by geography and event type
- walking, micromobility, local transit, regional transit, and car access
- attendance potential
- revenue and cost components
- ROI and sensitivity
- constraints that limit feasible attendance

**Public-safe output:** a plain-language summary of which location-capacity alternatives perform better and why.

## Use case 2 - Candidate-site comparison

**Question:** How does one candidate site compare with another under the same assumptions?

**Typical users:** planners, analysts, investment reviewers, public agencies.

**What Sarus-Optimizer can evaluate:**

- site ranking
- access differences
- demand catchment differences
- transport bottlenecks
- cost and revenue differences
- feasibility differences
- sensitivity to changed assumptions

**Public-safe output:** comparison tables and charts that explain tradeoffs without exposing implementation details.

## Use case 3 - Transport-constrained facility sizing

**Question:** What facility capacity is actually feasible once transport and access limits are considered?

**Typical users:** public agencies, developers, event operators, transportation planners.

**What Sarus-Optimizer can evaluate:**

- maximum feasible attendance or passenger throughput
- mode-capacity limits
- parking and road constraints
- transit access constraints
- walking or connector constraints
- unmet demand when constraints bind

**Public-safe output:** a constraint summary showing what limits practical capacity.

## Use case 4 - Airport public-transport hub capacity planning

**Question:** What public-transport station and hub capacity is needed for an expanded airport scenario?

**Typical users:** airport authorities, transit agencies, infrastructure sponsors, public agencies, regional planners.

**What Sarus-Optimizer can evaluate:**

- airport passenger demand scenarios
- peak-hour passenger movement
- O-D and connecting passenger separation
- road, parking, curb, and taxi/ride-hail constraints
- bus, LRT, rail, station, concourse, vertical-circulation, and terminal connector capacity
- service-level constraints and unmet demand

**Public-safe output:** station and hub capacity summaries, service requirement summaries, and constraint summaries.

## Use case 5 - Regional transit and HSR candidate comparison

**Question:** Which regional transit or high-speed rail candidate system best supports a major facility?

**Typical users:** regional planners, infrastructure analysts, transit agencies, consultants.

**What Sarus-Optimizer can evaluate:**

- candidate corridors
- station-centered catchment areas
- demand capture by candidate
- demand not captured by candidate systems
- required service frequency
- candidate feasibility
- cost and service-level tradeoffs

**Public-safe output:** candidate-system comparison summaries and selected maps or charts.

## Use case 6 - Sensitivity and scenario reporting

**Question:** Does the recommendation remain strong when assumptions change?

**Typical users:** decision-makers, reviewers, analysts, investors.

**What Sarus-Optimizer can evaluate:**

- demand assumptions
- access assumptions
- transport capacity assumptions
- cost assumptions
- mode-share assumptions
- peak-spreading assumptions
- catchment assumptions
- candidate-portfolio assumptions

**Public-safe output:** sensitivity tables showing which assumptions matter most.

## What Sarus-Optimizer does not replace

Sarus-Optimizer is a planning optimization and scenario-analysis tool. It does not replace:

- final architectural design
- structural engineering
- detailed traffic microsimulation
- legal land assembly work
- certified appraisal
- transit agency operating plans
- formal government approval processes

Its role is to create transparent planning evidence before those later-stage decisions.
