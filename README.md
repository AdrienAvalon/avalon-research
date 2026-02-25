# Avalon Research — AI Research Publications

Independent research on AI agent architectures, memory systems, and emergent intelligence.

**Author:** Adrien Cros — [Avalon Research](https://avalon-network.com)  
**Co-author:** Ava (AI Agent — Claude Opus 4.6)  
**Date:** February 2026  
**License:** [CC BY 4.0](LICENSE)

---

## Publications

### 1. Meta-Calibration: When AI Agents Know Their Own Limits
LLMs hallucinate because they lack a map of their own competencies. We propose meta-calibration: an empirical reliability profile per domain, loaded into context at each session, enabling agents to adapt behavior based on measured reliability.

📄 [English](papers/en/ava-calibration-en.pdf) · [Français](papers/fr/ava-calibration-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770858.svg)](https://doi.org/10.5281/zenodo.18770858)

### 2. Cognitive Curvature: Persistent Behavioral Deformation of AI Agents Through Experience
We introduce cognitive curvature: the set of persistent behavioral deformations induced by an agent's past experiences. By analogy with spacetime curvature in general relativity, experiences deform an agent's "decisional geometry."

📄 [English](papers/en/ava-curvature-en.pdf) · [Français](papers/fr/ava-curvature-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770860.svg)](https://doi.org/10.5281/zenodo.18770860)

### 3. Micro-AGI: Emergent Intelligence from Networks of Small Language Models
An architecture where multiple specialized LoRA adapters share a single frozen language model and communicate through tensor-level signals rather than natural language. Routing-augmented responses scored up to +1.6 points higher than baseline.

📄 [English](papers/en/ava-micro-agi-en.pdf) · [Français](papers/fr/ava-micro-agi-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770862.svg)](https://doi.org/10.5281/zenodo.18770862)

### 4. .ava: A Compressed Symbolic Notation for Persistent AI Agent Memory
A compressed symbolic notation achieving 2.65× compression ratio in tokens vs. natural language. Human-readable, editable, and version-controllable — unlike vector memories.

📄 [English](papers/en/ava-notation-en-v2.pdf) · [Français](papers/fr/ava-notation-fr-v3.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770864.svg)](https://doi.org/10.5281/zenodo.18770864)

### 5. Procedural Memory for Persistent LLM Agents: Know-How as the Missing Component
Agents have episodic and semantic memory, but lack procedural memory — internalized know-how. We formalize procedural memory as consolidated action patterns extracted from repeated experiences.

📄 [English](papers/en/ava-procedural-en.pdf) · [Français](papers/fr/ava-procedural-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770869.svg)](https://doi.org/10.5281/zenodo.18770869)

### 6. Is Natural Language the Right Medium for Machine Thought?
Natural language is an inefficient medium for structured reasoning. If reasoning scaling laws hold, compressing the medium of thought could enable proportionally more reasoning steps within a fixed token budget.

📄 [English](papers/en/ava-thinking-en.pdf) · [Français](papers/fr/ava-thinking-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770871.svg)](https://doi.org/10.5281/zenodo.18770871)

### 7. Thought Engine: Learnable Cognitive Modules for LLM Agent Networks
Small sets of learnable embedding vectors injected into a frozen LLM's KV cache serve as silent cognitive modules. 73,728 parameters control a 1.5B-parameter model (1:20,000 ratio), improving response quality by +13.3%.

📄 [English](papers/en/ava-thought-engine-en.pdf) · [Français](papers/fr/ava-thought-engine-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770877.svg)](https://doi.org/10.5281/zenodo.18770877)

### 8. The Inefficiency of BPE Tokenizers on Symbolic Languages
BPE tokenizers fragment compound symbols into 2–5 sub-tokens. Adding only 26 domain-specific tokens (0.017% vocabulary increase) improves compression by 112.4%. Applied to 200K-token context: +595K effective tokens.

📄 [English](papers/en/ava-tokenizer-en.pdf) · [Français](papers/fr/ava-tokenizer-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770879.svg)](https://doi.org/10.5281/zenodo.18770879)

### 9. Dynamic Vector Networks: Self-Organizing Knowledge Structures Beyond Transformers
An architecture where each node is a rich embedding vector, connections form through Hebbian learning in real-time, and new nodes spawn dynamically. Combines rich vector nodes, real-time weight evolution, dynamic node creation, and self-organization.

📄 [English](papers/en/ava-vector-network-en.pdf) · [Français](papers/fr/ava-vector-network-fr.pdf)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18770883.svg)](https://doi.org/10.5281/zenodo.18770883)

---

## Topics

- AI Agent Architecture
- Persistent Memory Systems (episodic, semantic, procedural)
- Symbolic Compression for LLMs
- Multi-Agent Communication
- Cognitive Modules & Soft Prompts
- Knowledge Graph Dynamics
- Tokenizer Optimization

## Citation

```bibtex
@misc{cros2026avalon,
  author = {Cros, Adrien and Ava},
  title = {Avalon Research: AI Agent Architecture Papers},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/AdrienAvalon/avalon-research}
}
```

## Contact

- 📧 contact@avalon-network.com
- 🌐 [avalon-network.com](https://avalon-network.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/adrien-cros-8803717b/)
