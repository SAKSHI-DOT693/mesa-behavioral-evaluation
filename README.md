# Mesa Behavioral Evaluation

## Project Goal

This repository explores how well Mesa supports structured behavioral modeling through hands-on implementation and evaluation.

The focus is on evaluating Mesa’s support for:

- Needs-based behavioral architectures
- Belief–Desire–Intention (BDI) style agents
- Event-driven and interruptible behaviors using DEVS

Rather than proposing abstractions upfront, this project follows an implementation-first approach to identify strengths, friction points, and opportunities for improvement grounded in real models.

---

## Approach

For each behavioral theory:

1. Implement a minimal but meaningful example model in Mesa.
2. Document what works naturally.
3. Identify structural tensions or awkward patterns.
4. Compare (where relevant) with similar implementations in other ABM platforms.
5. Extract cross-model insights.

The goal is not to build a full behavioral framework, but to systematically evaluate Mesa’s current capabilities and propose targeted, reusable improvements where justified.

---

## Repository Structure

- `needs_based/` – Predator–prey model with explicit internal needs
- `bdi/` – Goal-directed / belief-based agent prototype
- `event_driven/` – Exploration using Mesa’s DEVS capabilities
- `docs/` – Implementation observations and pattern analysis
- `comparison/` – Notes comparing Mesa to other ABM platforms

---

## Current Status

Phase 0: Repository structure and planning  
Next: Implement needs-based Wolf–Sheep extension
