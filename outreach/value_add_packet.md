# Professor Outreach Value-Add Packet

## Bottom Line

This repository is currently a **research proposal and execution scaffold**, not a completed result. Use it to show Professor Goldstein that you understand the research area and can contribute a concrete, reproducible artifact.

## Target Professor

- **Professor:** Tom Goldstein
- **University:** University of Maryland
- **Program:** Computer Science
- **Research area from CSV:** ML + optimization, adversarial robustness, LLMs, data
- **Representative paper from CSV:** Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks; 2018; NeurIPS
- **Scholar link:** https://scholar.google.com/scholar?q=Poison+Frogs%21+Targeted+Clean-Label+Poisoning+Attacks+on+Neural+Networks

## Proposed Value Add

Build **an adaptive red-team and repair harness for robustness, safety, privacy, or fairness failures** focused on **optimization**.

### What You Can Contribute

- Create a repeatable stress-test suite tailored to the lab's model/task domain.
- Mine minimal counterexamples instead of reporting only average benchmark scores.
- Evaluate whether proposed repairs generalize beyond the discovered failures.

## Concrete Starter Project

Implement a counterexample-mining loop with static benchmarks, adaptive perturbations, and a repair-vs-regression report.

## 30/60/90-Day Plan

### First 30 Days

- Re-read 3-5 recent lab papers and write a one-page problem framing memo.
- Build the first dataset or evaluation slice with documented source provenance.
- Reproduce one credible baseline and record exact commands.
- Create a failure bank with at least 20 concrete examples.

### Days 31-60

- Add the proposed method or evaluation contribution.
- Run ablations that isolate the contribution from data scale and model-size effects.
- Add robustness, temporal, domain-shift, or subgroup tests where relevant.
- Write interim results as a short lab-note style report.

### Days 61-90

- Expand the benchmark to 50-100 examples or the equivalent for the domain.
- Run statistical checks, seed variance checks, and cost/runtime analysis.
- Convert results into a paper-style technical report.
- Package the repo so another student can reproduce the main table.

## Deliverables To Offer The Professor

- A red-team prompt/data suite with severity labels.
- Attack or stress-test success metrics.
- Before/after repair table with regression checks.
- A failure taxonomy suitable for a short workshop-style report.

## Skills This Demonstrates

model evaluation, adversarial testing, safety analysis, fairness/OOD metrics, careful reporting of limitations.

## Honest Outreach Framing

Do **not** claim this is finished. The honest claim is:

> I prepared a concrete research scaffold aligned with your work and would like to turn it into a reproducible contribution if it matches your lab's current priorities.

## Sharing Note

This GitHub repository is public. Before emailing, verify the professor's current work, personalize the email, and be ready to explain exactly what is implemented versus planned.
