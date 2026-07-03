# Toronto Stadium Planning Case

This public case page explains the Toronto stadium planning scenario at a high level. It is intended for public communication only and does not expose source code, private algorithms, raw data, or internal calibration details.

![Stadium location and capacity concept](assets/stadium-location-capacity-concept.svg)

## Planning question

Where should a larger multi-purpose stadium serving the Greater Toronto Area be located, and what capacity is feasible when demand, access, transport constraints, cost, revenue, and long-term value are considered together?

## Why this case matters

Stadium planning is often discussed as a design or land question first. Sarus-Optimizer treats it as a connected planning problem:

- demand is spatial
- access differs by mode
- capacity is limited by transport feasibility
- events have different demand patterns
- cost and revenue change with size and location
- the best answer should remain understandable under sensitivity testing

## What Sarus-Optimizer evaluates

The Toronto stadium scenario is designed to compare location-capacity alternatives using the same planning logic.

Public-safe evaluation categories:

- candidate location
- capacity range
- walking access
- micromobility access
- local transit access
- regional transit access
- car and parking access
- event demand potential
- revenue and cost components
- life-cycle ROI or value range
- sensitivity to major assumptions
- constraint status and unmet demand, if any

## Example comparison frame

A public benchmark summary can compare an optimized alternative with a known benchmark site.

| Dimension | Public comparison question |
|---|---|
| Location | Which site better serves the regional catchment? |
| Capacity | Which capacity range is feasible under access constraints? |
| Transport | Which transport modes become binding? |
| Demand | Which event and fan segments can realistically reach the site? |
| Financials | How do revenue, cost, and life-cycle value change? |
| Sensitivity | Which assumptions matter most? |

## Public outputs planned

The public version of this case can include:

- a plain-language case narrative
- selected maps or concept visuals
- candidate-site comparison summary
- transport-access summary
- capacity-feasibility summary
- sensitivity summary
- reviewed benchmark summary

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

This case is in active private development. Public benchmark summaries should be published only after the assumptions and outputs have been reviewed.
