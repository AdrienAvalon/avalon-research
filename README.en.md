[Français](README.md) · **English**

<div align="center">

<img src="docs/assets/research.svg" alt="Three connected nodes around a central memory, the Avalon Research emblem." width="112">

# Avalon Research

**Exploring memory, reasoning and AI agent architectures.**

A collection of exploratory papers examining hypotheses, discussing methods
and opening avenues for research. Available in French and English, with no installation required.

[Choose a paper](#publications) · [Reading paths](#where-to-start) · [Cite](#citing-this-work) · [Discuss](#discussion)

[![Status: exploratory research](https://img.shields.io/badge/status-exploratory%20research-8b7cf6?style=flat-square)](#at-a-glance)
[![PDF: French and English](https://img.shields.io/badge/PDF-French%20%C2%B7%20English-2496ed?style=flat-square)](#publications)
[![References: Zenodo DOIs](https://img.shields.io/badge/references-Zenodo%20DOIs-1682d4?style=flat-square)](#citing-this-work)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-2ea44f?style=flat-square)](LICENSE)

</div>

## At a glance

| Area | Question explored |
|---|---|
| **Persistent memory** | How can an agent retain facts, procedures and useful history between sessions? |
| **Symbolic representations** | Can a more compact notation save context without losing meaning? |
| **Agent architectures** | How might specialized modules share a model or representations? |
| **Evaluation** | How can we measure an agent's limitations and distinguish a local result from a general capability? |

This collection contains **exploratory work from February 2026**: proposals, arguments
and experiments reported in the papers. Any numerical results depend on their protocols
and datasets; they are not guaranteed performance figures. The repository does not provide
a software suite or a complete set of code, data and weights for reproducing the experiments.

The Zenodo links help readers find and cite the deposited papers. Their presence does not
establish peer review or independent validation. Terms such as “cognition,” “thought” and
“memory” describe models of software behavior here.

## Where to start

| Your question | Suggested reading path |
|---|---|
| **What should persist between sessions?** | [Meta-Calibration](papers/en/ava-calibration-en.pdf) → [Procedural Memory](papers/en/ava-procedural-en.pdf) → [.ava Notation](papers/en/ava-notation-en-v2.pdf) |
| **How can context be represented?** | [.ava Notation](papers/en/ava-notation-en-v2.pdf) → [BPE Tokenization](papers/en/ava-tokenizer-en.pdf) → [Symbolic Reasoning](papers/en/ava-thinking-en.pdf) |
| **How can specialized modules be organized?** | [Micro-AGI](papers/en/ava-micro-agi-en.pdf) → [Thought Engine](papers/en/ava-thought-engine-en.pdf) → [Dynamic Vector Networks](papers/en/ava-vector-network-en.pdf) |

These reading paths open the English PDFs. French versions are available in the catalogue below.

## Publications

| Paper | Français | English | Reference |
|---|:---:|:---:|---|
| **Meta-Calibration** | [PDF](papers/fr/ava-calibration-fr.pdf) | [PDF](papers/en/ava-calibration-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770858) |
| **Cognitive Curvature** | [PDF](papers/fr/ava-curvature-fr.pdf) | [PDF](papers/en/ava-curvature-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770860) |
| **Micro-AGI** | [PDF](papers/fr/ava-micro-agi-fr.pdf) | [PDF](papers/en/ava-micro-agi-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770862) |
| **.ava Notation** | [PDF · v3](papers/fr/ava-notation-fr-v3.pdf) | [PDF · v2](papers/en/ava-notation-en-v2.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770864) |
| **Procedural Memory** | [PDF](papers/fr/ava-procedural-fr.pdf) | [PDF](papers/en/ava-procedural-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770869) |
| **Symbolic Reasoning** | [PDF](papers/fr/ava-thinking-fr.pdf) | [PDF](papers/en/ava-thinking-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770871) |
| **Thought Engine** | [PDF](papers/fr/ava-thought-engine-fr.pdf) | [PDF](papers/en/ava-thought-engine-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770877) |
| **BPE Tokenization** | [PDF](papers/fr/ava-tokenizer-fr.pdf) | [PDF](papers/en/ava-tokenizer-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770879) |
| **Dynamic Vector Networks** | [PDF](papers/fr/ava-vector-network-fr.pdf) | [PDF](papers/en/ava-vector-network-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770883) |

The French and English versions of the `.ava` notation paper differ; specify which version you consulted.

<details>
<summary><strong>Read the summaries and limitations of each paper</strong></summary>

### 1. Meta-Calibration

*Meta-Calibration: When AI Agents Know Their Own Limits*

A proposal for a reliability profile by domain, built from feedback and loaded into
an agent's context. The paper examines how this profile could guide its responses
and the way it communicates uncertainty.

### 2. Cognitive Curvature

*Cognitive Curvature: Persistent Behavioral Deformation of AI Agents Through Experience*

A conceptual framework for describing persistent behavioral changes based on a history
of interactions. “Curvature” is a modeling analogy, not an established physical property
or a claim of lived experience.

### 3. Micro-AGI

*Micro-AGI: Emergent Intelligence from Networks of Small Language Models*

A proposed architecture built around a frozen model, specialized LoRA adapters and
routing between modules. The paper reports experiments whose results depend on the
model and evaluator; the project's name does not demonstrate general intelligence.

### 4. .ava Notation

*.ava: A Compressed Symbolic Notation for Persistent AI Agent Memory*

A readable, editable symbolic notation for representing memory information. The paper
measures its token cost on an example corpus with a specific tokenizer. Text compression
alone does not demonstrate improved reasoning.

### 5. Procedural Memory

*Procedural Memory for Persistent LLM Agents: Know-How as the Missing Component*

A proposal for reusable procedures extracted from repeated experience, complementing
stored facts and events. The central question is how to turn a history of actions
into explicit know-how.

### 6. Symbolic Reasoning

*Is Natural Language the Right Medium for Machine Thought?*

An argument for more compact representations of structured reasoning. The paper
formulates a hypothesis and an evaluation agenda: saving tokens and improving
reasoning quality remain separate questions.

### 7. Thought Engine

*Thought Engine: Learnable Cognitive Modules for LLM Agent Networks*

Experiments with small sets of trainable vectors injected into a frozen model's KV
cache. The reported evaluations explore how specialized modules can steer the model,
within the scope of the described protocol.

### 8. BPE Tokenization

*The Inefficiency of BPE Tokenizers on Symbolic Languages*

A study of how a BPE tokenizer fragments compound symbols, followed by a targeted
vocabulary extension. The measurements concern the chosen .ava notation corpus and
tokenizer; they do not establish how a model trained with that extended vocabulary would behave.

### 9. Dynamic Vector Networks

*Dynamic Vector Networks: Self-Organizing Knowledge Structures Beyond Transformers*

A proposed network of vector representations whose nodes and links evolve with input.
The paper describes a proof of concept on a small set of relationships, rather than
a large-scale validated alternative to Transformers.

</details>

## Citing this work

For an individual paper, use its DOI and the metadata of its corresponding Zenodo record.
The French and English .ava notation PDFs have different versions; specify the one you consulted.
To cite the collection as a whole:

<details>
<summary><strong>Copy the collection's BibTeX reference</strong></summary>

```bibtex
@misc{cros2026avalon,
  author = {Cros, Adrien and Ava},
  title = {Avalon Research: AI Agent Architecture Papers},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/AdrienAvalon/avalon-research}
}
```

</details>

**Publication attribution:** Adrien Cros and Ava, the AI agent identified in the documents
as Claude Opus 4.6. This attribution describes the AI-assisted contribution to these texts.

## Discussion

Methodological criticism, replication attempts and corrections are welcome in the
[issues](https://github.com/AdrienAvalon/avalon-research/issues). Include the paper,
its version and the relevant passage to keep the discussion precise.

[Avalon Network website](https://avalon-network.com) · [Contact](mailto:contact@avalon-network.com) · [LinkedIn](https://www.linkedin.com/in/adrien-cros-8803717b/)

## License

The publications are distributed under **[Creative Commons Attribution 4.0 International](LICENSE)**.
This license allows sharing and adaptation, **including for commercial purposes**,
with attribution, a link to the license and an indication of changes.
See the [official CC BY 4.0 summary](https://creativecommons.org/licenses/by/4.0/).
