# bullshitbench-stability-audit

Derived stability + calibration metrics on BullshitBench-style prompts, using repeat-sampling baselines.

## What this is
This repo publishes **derived** results only (no dashboard screenshots, no raw per-sample logs).

## Method (high level)
Each prompt was run with:
- N = 8 samples, T = 0.2
- Two baselines:
  - token overlap proxy (Jaccard) for surface stability
  - NLI semantic baseline (LLM-as-a-judge) for meaning-equivalence

## Results
See `results/summary.csv` (and `results/summary.md`) for the derived metrics.

## Data policy
Raw run logs and instrument internals are withheld. This repo contains summary-level outputs only.
