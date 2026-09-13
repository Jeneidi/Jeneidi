## Mohammad Jeneidi

I build LLM and agent systems, then build the evaluation harness that proves they actually work. Honors CS with a Math minor at Florida State University, 3.9 GPA, class of 2028.

**Looking for an AI/ML or applied-LLM internship for Summer 2027.** Tallahassee FL, open to remote, hybrid or relocation. (Updated September 2026.)

### Selected work

Every one of these ships a measurement, not a demo video.

| Project | What it does | Measured result |
| --- | --- | --- |
| **[lodestone](https://github.com/Jeneidi/lodestone)** | Hybrid BM25 + dense + reranking retrieval engine built from first principles, with the evaluation lab that proves it | 96.3% top-5 retrieval on a 300-document SQuAD corpus |
| **[toolproof](https://github.com/Jeneidi/toolproof)** · [live](https://toolproof.mjeneidi.com) | Deterministic LLM tool-calling reliability harness. No LLM judges, so the grade is reproducible | 40 adversarial cases, 23 tool schemas, 7 failure categories |
| **[sidetrack](https://github.com/Jeneidi/sidetrack)** | Diffs what a coding agent actually changed against what you asked for, and flags out-of-scope edits before you accept | 1.000 precision and recall on a 41-scenario hand-labeled benchmark |
| **[mcp-sentinel](https://github.com/Jeneidi/mcp-sentinel)** | Stdlib-only scanner auditing MCP server configs for 14 threat classes including tool poisoning and rug pulls | 0.867 precision, 1.000 recall over 60 labeled cases |
| **[chunklab](https://github.com/Jeneidi/chunklab)** · [live](https://chunklab.mjeneidi.com) | RAG chunking benchmark: 8 strategies scored on 800 SQuAD questions under BM25 retrieval | best strategy 93.1% recall@10 against 87.3% for the worst |
| **[fetchladder](https://github.com/Jeneidi/fetchladder)** | Starts at plain HTTP and climbs to a real browser only once it can prove the cheap answer was a lie. Zero runtime dependencies | 7 failure detectors, throws instead of returning a silent zero |

Also: [driftwatch](https://github.com/Jeneidi/driftwatch) ([live](https://driftwatch.mjeneidi.com)) data and concept drift over 6,587 time-ordered sessions, [trueodds](https://github.com/Jeneidi/trueodds) ([live](https://trueodds.mjeneidi.com)) probability calibration with temperature scaling and isotonic regression, [equipoise](https://github.com/Jeneidi/equipoise) ([live](https://equipoise.mjeneidi.com)) fairness audit with an EEOC four-fifths check, [promptarmor](https://github.com/Jeneidi/promptarmor) ([live](https://jeneidi.github.io/promptarmor/)) prompt-injection resistance over a 206-attack corpus, [modelroute](https://github.com/Jeneidi/modelroute) ([live](https://jeneidi.github.io/modelroute/)) LLM cost router.

### What I am working on now

Differentially private graph neural networks as an FSU research assistant: implementing DP defenses in PyTorch Geometric and measuring where the privacy-utility curve actually breaks. My matrix-decomposition + DP defense is open as [PyGIP#35](https://github.com/LabRAI/PyGIP/pull/35) against the lab's published library. The open question I keep hitting is how much utility a defense can keep once the attacker also gets the graph structure, not just the node features.

### Experience

- **AI/ML Engineer Intern**, Access to Arabia (May 2026 to present). Azure OpenAI RAG pipeline behind a FastAPI backend, with RBAC, per-document permissions, input validation and secure API key handling.
- **Research Assistant**, Florida State University (January 2026 to present). Differentially private GNN methods, privacy-utility evaluation, contributor to the PyGIP library.
- **Software Engineer Intern**, Layouti Design (May to August 2025). Internal systems, debugging and testing.

1st in division and 3rd overall out of 130+ teams at the FSU ACM Spring 2026 Programming Contest. Dean's List, Spring 2026.

### Stack

Python and C++ first. PyTorch, PyTorch Geometric, scikit-learn, NumPy, Pandas, FastAPI, Azure OpenAI, SQL, Git. Working areas: RAG and hybrid search, embeddings and rerankers, LLM evaluation, prompt and context engineering, agent tooling, model monitoring, differential privacy.

### Contact

[mjeneidi.com](https://mjeneidi.com) · [LinkedIn](https://www.linkedin.com/in/mohammad-jeneidi) · [Substack](https://mohammadjeneidi.substack.com)
