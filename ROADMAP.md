# Public Roadmap

This roadmap is intentionally public-safe. It communicates direction and progress without exposing source code, implementation tricks, private task lists, or unresolved internal issues.

## Current position

Sarus-Optimizer is in private development. The public launch should begin with documentation and selected benchmark summaries before any code release.

## Phase 1 - Public foundation

**Goal:** Make the project understandable without opening the codebase.

Public outputs:

- vision statement
- public roadmap
- milestone overview
- use-case descriptions
- benchmark-summary format
- publishing rules for what stays private

Status: **in progress**

## Phase 2 - Toronto stadium planning scenario

**Goal:** Demonstrate Sarus-Optimizer on a stadium location and capacity planning problem.

Public story:

- evaluate stadium location and capacity together
- compare an optimized site against a known benchmark site
- summarize access by walking, micromobility, local transit, regional transit, and car
- explain how accessibility, demand, cost, revenue, and ROI interact
- publish reviewed benchmark summaries and selected figures when ready

Public-safe outputs:

- problem statement
- scenario assumptions at a summary level
- benchmark-summary tables
- selected charts or maps
- explanation of constraints and tradeoffs

Private by default:

- source code
- exact implementation details
- internal model task lists
- raw or proprietary datasets
- unreviewed calibration details

Status: **active private development**

## Phase 3 - Airport-transit hub planning scenario

**Goal:** Extend Sarus-Optimizer to a regional airport public-transport access and station-capacity problem.

Public story:

- evaluate candidate regional transit systems serving a major airport
- estimate demand allocation across a broad regional catchment
- compare high-speed rail, conventional transit, and non-HSR hub-access alternatives
- size airport public-transport station capacity under peak-hour and service-level constraints
- report road, parking, curb, station, and connector constraints clearly

Public-safe outputs:

- scenario overview
- candidate-system descriptions
- demand-allocation summary
- hub-capacity summary
- service-level and constraint summaries
- sensitivity summaries

Status: **planned / specification stage**

## Phase 4 - Benchmark and validation package

**Goal:** Build trust through evidence while keeping the implementation private.

Public outputs:

- benchmark methodology
- reviewed benchmark summaries
- comparison tables
- sensitivity summaries
- reproducibility notes
- known limitations and assumptions

Benchmark summaries should distinguish between:

- example results
- planning assumptions
- calibrated inputs
- sensitivity results
- final claims that are ready for public use

Status: **planned**

## Phase 5 - Controlled public demos

**Goal:** Show the system in action without releasing source code.

Possible public outputs:

- screenshots of reports
- short video walkthroughs
- static example outputs
- no-code demo interface
- selected downloadable result tables
- public FAQ

Status: **future**

## Phase 6 - External review and partnerships

**Goal:** Collect feedback from planners, infrastructure analysts, agencies, researchers, and potential users.

Possible public outputs:

- request-for-feedback page
- contact form
- public issue/discussion page for non-code feedback
- selected reviewer notes
- case-study invitations

Status: **future**

## Release rule

A public release should happen in layers:

1. publish the story
2. publish the assumptions at a safe summary level
3. publish reviewed benchmark summaries
4. publish selected visuals
5. publish controlled demos
6. consider code release only if there is a separate strategic reason
