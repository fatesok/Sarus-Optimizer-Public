# Vision

Sarus-Optimizer is a planning-optimization system for complex facilities and infrastructure decisions where location, capacity, demand, transport access, cost, and long-term value interact.

The goal is to help planners, analysts, investors, public agencies, and operators answer questions such as:

- Where should a facility be located?
- How large should it be?
- Which demand groups can realistically reach it?
- Which transport or access constraints become binding?
- How do revenue, cost, service level, and life-cycle value change under different assumptions?
- Which candidate is best, and why?

Sarus-Optimizer is not meant to be a black-box scoring tool. Its purpose is to make optimization results explainable, testable, and useful for planning discussions.

## Core idea

Many facility-planning decisions fail when location, capacity, demand, and access are evaluated separately. Sarus-Optimizer treats them as connected decisions.

A location with strong theoretical demand may fail if transport capacity is weak. A facility with attractive capacity may be oversized if catchment demand is limited. A financially promising option may become fragile when assumptions change. Sarus-Optimizer is designed to expose these tradeoffs clearly.

## Public principles

### 1. Optimize location and capacity together

Sarus-Optimizer evaluates where a facility should be placed and how large it should be as connected decisions, rather than treating capacity as an afterthought.

### 2. Treat access as a constraint, not decoration

Walking, micromobility, public transit, regional transit, roads, parking, station capacity, curb capacity, and transfer interfaces can limit feasible demand. Sarus-Optimizer makes these constraints visible.

### 3. Use spatial and segment-specific demand

Demand is not a single number. It depends on geography, distance, travel friction, event type, passenger type, user segment, and scenario assumptions.

### 4. Explain financial and service outcomes

The system is intended to connect demand and capacity decisions to outputs such as revenue, cost, ROI, service level, queueing/crowding indicators, and unmet demand.

### 5. Support transparent sensitivity testing

A good planning model should show how conclusions change when assumptions change. Sarus-Optimizer is designed to report sensitivity instead of hiding uncertainty.

### 6. Public evidence, private implementation

The project can publish public-facing vision, roadmap, use cases, milestone status, and benchmark summaries while keeping source code, internal algorithms, private task lists, and proprietary data private.

## Initial focus areas

Sarus-Optimizer currently focuses on facility and transport planning scenarios, including:

- stadium location and capacity planning
- candidate-site comparison
- transport-constrained event facility sizing
- airport public-transport hub capacity planning
- regional transit or high-speed rail candidate comparison
- sensitivity and scenario reporting for planning decisions

## Long-term direction

The long-term vision is to turn Sarus-Optimizer into a reusable optimization framework for public-facing planning evidence: clear assumptions, traceable scenarios, reproducible benchmark summaries, and explainable recommendations.
