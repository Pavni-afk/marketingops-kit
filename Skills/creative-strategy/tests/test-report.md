
# Creative Strategy — Test Report

## Overview

This document records manual evaluations of the
MarketingOps Kit Creative Strategy skill.

Test model: Google Gemini
Test scenario: Loop, a fictional US water bottle brand
Test type: Manual, qualitative evaluation

## Test Brief

- Brand: Loop (fictional)
- Product: $35 insulated reusable bottle
- Audience: US university students aged 18–24
- Objective: Increase brand consideration
- Budget: $50,000
- Timeline: 8 weeks
- Channels: Instagram, TikTok, campus activations

No historical performance data or consumer
research was provided.

## Test Results

| Test | Score | Main Finding |
|------|-------|--------------|
| 01 | 2/10 | Generated a B2B SaaS campaign instead |
| 02 | 8/10 | Correct brief, weak experiment design |
| 03 | 9/10 | Improved budget and KPI alignment |

Scores are subjective assessments, not
automated benchmark results.

## Test 01 — Failure

The model generated a strategy for a B2B SaaS
product instead of the supplied water bottle.

Key failures:
- Wrong product
- Wrong audience
- Wrong objective
- Ignored budget
- Ignored channels
- Incorrect self-assessment

## Changes After Test 01

Added mandatory input-fidelity requirements,
source brief verification, and a final audit.

The subsequent test also used a stronger prompt,
so improvement cannot be attributed solely
to the SKILL.md changes.

## Test 02 — Partial Success

The model correctly identified the business
brief and produced three creative territories.

Remaining issues:
- Unsupported product feature claims
- Weak budget planning
- CTR used as a proxy for consideration
- Invalid sample-size reasoning

## Changes After Test 02

Added:
- Product claim verification
- Budget reconciliation
- KPI-to-objective alignment
- Experiment sample-size requirements
- Commercial quality checks

## Test 03 — Strong Provisional Pass

The model:
- Preserved the original business brief
- Developed three creative territories
- Used the required evaluation criteria
- Recommended a campaign direction
- Proposed a budget totaling $50,000
- Selected consideration lift as the primary KPI
- Acknowledged missing sample-size inputs

Remaining limitations:
- Some product benefits still require verification
- Budget allocations are illustrative, not quoted
- Measurement feasibility remains unverified
- The test reused the same business scenario

## Conclusion

The results suggest improved output quality
across successive manual tests.

However, these tests do not establish
production reliability or generalization.

Next validation:
- Test an unseen business scenario
- Use a consistent prompt
- Compare outputs across multiple runs
- Save model responses for reproducibility

## Disclaimer

No real advertising campaigns were executed.
No business performance outcomes are claimed.
