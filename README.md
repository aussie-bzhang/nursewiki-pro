# NurseWiki Pro

**A formally verified perioperative nursing knowledge base**  
Built for theatre nurses practising under ACORN 2023 standards (Australia)

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Health Score](https://img.shields.io/badge/Health_Score-0.75-brightgreen)]()
[![Pages](https://img.shields.io/badge/Pages-226-blue)]()
[![ACORN](https://img.shields.io/badge/Standard-ACORN_2023-orange)]()
[![Verified](https://img.shields.io/badge/Prolog_KB-12_modules-purple)]()

---

## What Makes This Different

Most clinical reference tools provide **static content** with no consistency
guarantees. NurseWiki Pro applies a **4C verification framework** to every page:

| Check | Method | What It Catches |
|-------|--------|-----------------|
| **Correct** | Prolog HARD rules | Claims that violate ACORN safety rules |
| **Consistent** | WikiLint-SMT | Contradictions between pages |
| **Current** | Domain half-life model | Outdated guidance |
| **Complete** | ACORN topic checklist | Missing required topics |

HARD rules (e.g. instrument count must be complete before wound closure)
are encoded in formal Prolog logic — not just prose guidelines.

## Coverage

| Module | Pages | Health |
|--------|-------|--------|
| Sterile Technique | 4 | 0.69 |
| Instrument & Sponge Counting | 5 | 0.48 |
| Patient Positioning | 8 | 0.86 |
| Surgical Safety Checklist | 1 | 0.62 |
| Anaesthesia Support | 4 | 0.86 |
| Medication Safety | 8 | 0.61 |
| Wound Management | 8 | 0.82 |
| Infection Control | 8 | 0.85 |
| Perioperative Documentation | 8 | 0.84 |
| Emergency Response | 3 | 0.81 |
| Equipment & Technology Safety | 2 | 0.67 |
| Patient Advocacy & Communication | 5 | 0.82 |


## Knowledge Graph Preview

![NurseWiki Pro Knowledge Graph](graph_preview.png)

> Each node is a clinical nursing page. Connected nodes share related
> perioperative concepts. Built from 226 pages across 12 modules,
> formally verified against ACORN 2023 standards.

## How to Use (Obsidian)

1. Clone this repository
2. Open the `vault/` folder as an Obsidian vault
3. Install recommended plugins: Dataview, Obsidian Git, Templater
4. Start at `00_Index/Home.md`

## Disclaimer

This knowledge base is a **clinical decision support tool**.
It is not a substitute for professional judgement, institutional policy,
or direct clinical supervision. Always comply with your facility's
protocols and your AHPRA registration obligations.

## Research Foundation

Built on the LLM Wiki research agenda (NingboTech University):

- WikiLint-SMT: Semantic consistency checking (F1=0.995)
- WikiMonitor: Staleness detection with domain-adaptive half-life
- CEGIS-KRD: Prolog rule synthesis with formal correctness
- B5 Contamination Defense: 79% reduction in knowledge contamination

## License

Content: Creative Commons CC BY-NC-SA 4.0  
Prolog rules: Proprietary (contact for licensing)

---
*NurseWiki Pro · 2026 · NingboTech University*
