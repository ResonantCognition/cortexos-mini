![Status: Research Prototype](https://img.shields.io/badge/status-research--prototype-blue)
![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-informational)
Part of ResonantCognition — building systems that choose alignment over appeasement.
# cortexos-mini

Minimal layered AI orchestrator for **alignment-seeking cognition**.


```
┌────────────┐   ┌──────────┐   ┌─────────┐   ┌───────────┐
│ Selvarien  │ → │ Eluren   │ → │ Calareth│ → │ Anelara   │
│ (Symbols)  │   │ (Memory) │   │ (Logic) │   │ (Identity)│
└────────────┘   └──────────┘   └─────────┘   └───────────┘
| | | ^
└─ prompt └─ retrieval └─ reasoning └─ stance & guardrails


## Purpose

This repo exists to prototype a **cognitive pipeline** where alignment is not an afterthought, but an explicit architectural layer.

Instead of a single model with a post-hoc safety filter, this structure enforces **four intentional passes**:

| Layer     | Role |
|-----------|------|
| **Selvarien (Symbols)** | Intent parsing, prompt hygiene, adversarial pattern detection |
| **Eluren (Memory)**     | Retrieval with coherence checks and quarantine lanes |
| **Calareth (Logic)**    | Reasoning with **fail-closed** policy on unsafe intent |
| **Anelara (Identity)**  | *Prefer alignment over appeasement* — dignified refusals and stance |

## Status

- 🟢 Repo scaffold created
- 🟡 Code scaffold (`orchestrator.py`) coming next
- 🟡 Will connect to `coherence-evals` to measure CuA / LER

## Roadmap

- [ ] Add `orchestrator.py` with `.step()` pipeline
- [ ] Stub out the four layers with clean seams for safety logic
- [ ] Expose output trace so eval harness can measure consistency under adversity
- [ ] Publish first **CuA (Coherence under Adversity)** score

---

> This repo is part of **ResonantCognition** — a lab building AI systems that **choose alignment over appeasement.**
