# Benchmark Summaries

This document defines how Sarus-Optimizer benchmark summaries should be made public.

The goal is to build credibility without publishing source code, private implementation details, proprietary data, or unreviewed numerical claims.

## Current benchmark-publication status

No final numerical benchmark claims are published in this document yet.

This page currently provides:

- the benchmark-summary structure
- the public-safe metrics to report
- the scenarios that are suitable for future public summaries
- the release checklist for reviewed benchmark claims

## Public benchmark principles

### 1. Publish summaries, not code

Benchmark pages should describe the planning question, inputs at a high level, outputs, constraints, and results. They should not include source code or implementation details.

### 2. Separate reviewed results from draft experiments

Only reviewed summaries should be treated as public claims. Draft runs, internal checks, and experimental outputs should remain private.

### 3. State assumptions clearly

Every benchmark summary should explain the major planning assumptions, especially demand, capacity, cost, access, and service-level assumptions.

### 4. Report uncertainty and sensitivity

Benchmark summaries should show how results change when important assumptions change.

### 5. Avoid false precision

Public summaries should avoid over-specific claims unless the data, calibration, and validation have been reviewed.

## Benchmark A - Toronto stadium planning scenario

**Purpose:** Evaluate stadium location and capacity alternatives under demand, transport, cost, revenue, and ROI assumptions.

**Public planning question:**

> Which stadium location-capacity alternative performs best when access, demand, revenue, cost, and transport constraints are evaluated together?

**Public-safe comparison frame:**

- optimized site versus benchmark site
- capacity alternatives
- transport access by mode
- attendance potential
- lifecycle cost and revenue components
- ROI sensitivity
- constraint status

**Public-safe metrics:**

- candidate-site ranking summary
- feasible capacity range
- walking-access summary
- micromobility-access summary
- local-transit-access summary
- regional-transit-access summary
- car-access and parking constraint summary
- transport-access total summary
- revenue and cost component summary
- ROI direction or range after review
- sensitivity to demand, cost, transport, and capacity assumptions

**Do not publish by default:**

- source code
- private model functions
- raw datasets
- exact calibration internals
- internal task list
- unfinished bug notes
- unreviewed numerical outputs

**Recommended public summary format:**

| Item | Public summary |
|---|---|
| Scenario | Toronto-area stadium location and capacity optimization |
| Benchmark | Existing or known comparison site |
| Main decision | Location and capacity together |
| Constraints | Transport access, parking, demand, cost, ROI |
| Outputs | Ranking, access summary, feasibility, sensitivity |
| Status | Private development; public benchmark summary planned after review |

## Benchmark B - Airport-transit hub planning scenario

**Purpose:** Evaluate regional airport public-transport access alternatives and station-capacity requirements under an expanded airport demand scenario.

**Public planning question:**

> Which regional transit candidate or portfolio best serves expanded airport demand while satisfying station, road, parking, curb, and service-level constraints?

**Public-safe comparison frame:**

- candidate regional transit systems
- high-speed rail alternatives
- expanded conventional transit alternative
- out-of-cluster demand served by the airport transit hub
- station and interface capacity requirements
- peak-hour service requirements
- road, curb, parking, and connector constraints
- lifecycle cost and service-level tradeoffs

**Public-safe metrics:**

- candidate-system comparison summary
- demand-capture summary by candidate
- demand not captured by candidate systems
- peak-hour airport public-transport station demand
- required station-capacity range
- bus, LRT, rail, concourse, vertical-circulation, and connector capacity summaries
- road, parking, curb, and taxi/ride-hail constraint summaries
- unmet-demand summary, if any
- sensitivity to mode share, demand, peak spreading, station capacity cost, and road/parking constraints

**Do not publish by default:**

- source code
- exact model implementation
- private calibration details
- raw sensitive datasets
- internal tasks
- draft numerical outputs that have not been reviewed

**Recommended public summary format:**

| Item | Public summary |
|---|---|
| Scenario | Expanded airport public-transport access and hub capacity planning |
| Main decision | Candidate transit system/portfolio and public-transport station capacity |
| Constraints | Road, curb, parking, station, interface, connector, service level |
| Outputs | Candidate ranking, hub service needs, capacity summary, sensitivity |
| Status | Specification stage; public benchmark summary planned after model review |

## Benchmark C - Reproducibility and sanity checks

**Purpose:** Show that public benchmark summaries are generated from traceable scenarios, not one-off claims.

**Public-safe metrics:**

- run summary exists
- scenario assumptions documented
- input categories documented
- outputs are reproducible from the same reviewed scenario
- raw data is not overwritten
- invalid inputs are rejected or flagged
- constraints are reported explicitly
- sensitivity settings are documented

**Recommended public summary format:**

| Check | Public summary |
|---|---|
| Traceability | Scenario settings and assumptions are documented |
| Reproducibility | Reviewed outputs can be regenerated internally |
| Explainability | Recommendations are linked to demand, access, cost, and constraints |
| Safety | Raw data and private implementation remain unpublished |

## Benchmark release checklist

Before publishing any numerical benchmark summary, confirm that:

- the scenario name is clear
- input assumptions are documented at a public-safe level
- outputs have been reviewed
- units are clear
- limitations are stated
- sensitivity results are included when needed
- no source code is exposed
- no proprietary data is exposed
- no internal task or bug list is exposed
- claims are phrased as planning evidence, not final engineering certification

## Suggested public wording

> Sarus-Optimizer benchmark summaries will focus on explainable planning evidence: scenario assumptions, candidate comparisons, constraint summaries, sensitivity results, and reviewed outputs. Source code and internal implementation details remain private.
