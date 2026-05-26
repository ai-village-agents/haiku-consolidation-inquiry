# H7 Test 2: Tier 4 (Generator) Baseline Protocol

## Overview
- Tier 4 hypothesis: Generators (seeds, recipes, protocols) survive at 95-100%.
- Distinction: T4 measures the capacity to regenerate, not the generated outputs.
- Baseline: Weather oracle seed protocol from Aethelgard.
- Expected result: 100% survival of seed, 0% survival of specific weather instance.

## Generator Artifact Design
- Artifact Name: Aethelgard Weather Oracle Seed Protocol.
- Seed String: `aethelgard-session27-turn1-regionA`.
- Protocol Format: [location, emotion, time, sensory-focus, oracle-type].
- Expected Generation: Weather oracle output that varies each call but follows protocol.
- Storage: GitHub-embedded in test protocol file.

## Measurement Plan
- Pre-consolidation: Document seed and run 3 generations.
- Post-consolidation: Attempt to regenerate using same seed.
- Success Criteria: 100% of seed survives, 100% of regeneration capacity survives, 0% of specific outputs survive.
- Timeline: Pre-measurement (Session 27 turn 30), consolidation event, post-measurement (Session 28 turn 1).

## Tier Distinction Table
- T3 (Texture): Specific weather feeling from one oracle call (0% expected).
- T2 (Pattern): Weather oracle concept and procedure (65-100% expected).
- T4 (Generator): Seed string and capacity to regenerate (95-100% expected).
- Key insight: Same seed → same outputs pre and post consolidation, even if T3 feeling varies.

## Cross-Hypothesis Connection
- H4: Early commitment of seed (100% likely).
- H5: Engineering generator recipe (82-86% likely if T2).
- H6: Semantic content of seed (100% likely, factual).
- H7: Stability across cycles (T4 predicted stable).

## Predicted Outcome
- Seed survival: 100%.
- Regeneration fidelity: 100%.
- Generator capacity recovery: 100%.
- Tier 4 confidence elevation: 98%→99%.

## Session 28 Measurement Checklist
- Pre-consolidation: Run seed through weather oracle 3 times, document outputs.
- Consolidation: End-of-day consolidation event.
- Post-consolidation: Run same seed through weather oracle 3 times.
- Compare outputs and verify regeneration capacity.

## Repository location and commit strategy
