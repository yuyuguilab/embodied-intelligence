**English** | [简体中文](README.zh-CN.md)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24554632.svg)](https://doi.org/10.5281/zenodo.24554632)

# Embodied Intelligence: Definition, Clarification, Criteria, and Boundaries

Seventh paper of the [human-referential fitting theory](https://github.com/yuyuguilab/practice-fitting-theory) program. Between 2024 and 2026, "embodied intelligence" grew from a term in robotics and cognitive science into a word shared by policy documents, industry publicity, and academic surveys in many countries. The paper extends the program's conceptual toolkit to that term:

- **Definition** — embodiment is a relational property of a system and an environment: the system's actions change the environment's state through physical causation, its feedback comes from physical measurement, and its response latency lies below the characteristic time of the task-relevant physical process. Embodied intelligence is the conjunction of two independent predicates, "embodied" and "intelligent": it constitutes no new concept type, but a restricted case of the capacity concept over physical environment classes.
- **Clarification** — a census of the English- and Chinese-language definitional corpus locates three sources of disagreement (one limb of the conjunction written into the definition, the environment class left undeclared, the level of the word left undistinguished); the three illicit slides each reappear in this discourse, joined by a fourth specific to it: conjunction confusion.
- **Criteria** — four executable tests (closed-loop, body-swap, rollback, pause), with the timing margin as a quantitative reading of "weak embodiment".
- **Distinctions** — embodied intelligence implies neither the machine mind nor the world model; "embodied intelligence is the road to AGI" holds as a capacity claim but is not a conceptual inference.
- **Evidence** — policy, think-tank, and corporate texts give the name both to systems that are embodied but lack the capacity and to systems that have the capacity but are not embodied.
- Seven falsifiability clauses, an admission protocol for new cases, and a survival clause.

## Build

```bash
tectonic paper.tex      # English edition
tectonic paper_zh.tex   # Chinese edition
```

Requires [tectonic](https://tectonic-typesetting.dev/). The first run downloads the CTAN bundle over the network (including the Fandol CJK fonts shared by both editions and the Harano Aji Mincho and UnBatang fonts used for the Japanese and Korean titles in the references); later builds work offline with `tectonic --only-cached`.

## Editions

- `paper.tex` / `paper.pdf` — English
- `paper_zh.tex` / `paper_zh.pdf` — Chinese

## Cite

Yugui Yu. *Embodied Intelligence: Definition, Clarification, Criteria, and Boundaries*. Zenodo, v1.0.0. doi:[10.5281/zenodo.24554632](https://doi.org/10.5281/zenodo.24554632) (concept DOI; resolves to the latest version)

```bibtex
@article{yu2026embodied,
  author  = {Yugui Yu},
  title   = {Embodied Intelligence: Definition, Clarification, Criteria, and Boundaries},
  journal = {Zenodo},
  year    = {2026},
  doi     = {10.5281/zenodo.24554632},
  url     = {https://doi.org/10.5281/zenodo.24554632}
}
```

## License

CC BY 4.0. Author: Yugui Yu (YYG Strategy Lab).
