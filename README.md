## Mohammad Jeneidi

Honors CS and Math minor at Florida State University (3.88 GPA, class of 2028). I build LLM and agent systems, then build the evaluation harness that proves they actually work.

**Right now:** AI/ML Engineer Intern at Access to Arabia, building an Azure OpenAI RAG pipeline behind a FastAPI backend with RBAC and per-document permissions. Also a Research Assistant at FSU implementing differentially private GNN methods in PyTorch Geometric, contributing to the [PyGIP](https://pypi.org/project/pygip/) library.

**Looking for:** an AI/ML or applied-LLM internship for Summer 2027.

### Selected projects

Every one of these ships a real measurement, not a demo video.

| Project | What it does | Measured result |
| --- | --- | --- |
| **[lodestone](https://github.com/Jeneidi/lodestone)** | Hybrid BM25 + dense + reranking retrieval engine built from first principles, with the evaluation lab to prove it | 96.3% top-5 retrieval on a 300-document SQuAD corpus |
| **[chunklab](https://github.com/Jeneidi/chunklab)** · [live](https://chunklab.mjeneidi.com) | RAG chunking benchmark: 8 strategies scored on 800 SQuAD questions with BM25 retrieval | best strategy 93.1% recall@10 against 87.3% for the worst |
| **[toolproof](https://github.com/Jeneidi/toolproof)** · [live](https://toolproof.mjeneidi.com) | Deterministic LLM tool-calling reliability harness, zero LLM judges, BYOK live mode | 40 adversarial cases, 23 tool schemas, 7 failure categories |
| **[mcp-sentinel](https://github.com/Jeneidi/mcp-sentinel)** | Stdlib-only Python scanner that audits MCP server configs for 14 threat classes including tool poisoning and rug pulls | 0.867 precision and 1.000 recall over 60 labeled cases |
| **[driftwatch](https://github.com/Jeneidi/driftwatch)** · [live](https://driftwatch.mjeneidi.com) | Replays a classifier over 6,587 time-ordered sessions and detects data and concept drift entirely client-side | PSI, KS, chi-square, Jensen-Shannon and Page-Hinkley, no server |
| **[sidetrack](https://github.com/Jeneidi/sidetrack)** | Diffs what a coding agent actually changed against what you asked for, and flags out-of-scope edits before you accept | 1.000 precision and recall on a 41-scenario benchmark |

Also worth a look: [trueodds](https://github.com/Jeneidi/trueodds) ([live](https://trueodds.mjeneidi.com)) probability calibration lab with temperature scaling and isotonic regression, [equipoise](https://github.com/Jeneidi/equipoise) ([live](https://equipoise.mjeneidi.com)) fairness audit with 6 group-fairness criteria and an EEOC four-fifths check, [promptarmor](https://github.com/Jeneidi/promptarmor) ([live](https://jeneidi.github.io/promptarmor/)) prompt-injection resistance tester over a 206-attack corpus, [fetchladder](https://github.com/Jeneidi/fetchladder) zero-dependency failure detection for web-reading agents, and [modelroute](https://github.com/Jeneidi/modelroute) ([live](https://jeneidi.github.io/modelroute/)) LLM cost router.

### Experience

- **AI/ML Engineer Intern**, Access to Arabia (May 2026 to present). Azure OpenAI RAG pipeline, FastAPI backend, RBAC, document permissions, input validation, secure API key handling.
- **Research Assistant**, Florida State University (January 2026 to present). Differentially private GNN methods in PyTorch and PyTorch Geometric, privacy-utility tradeoff evaluation, contributor to PyGIP.
- **Software Engineer Intern**, Layouti Design (May to August 2025). Internal systems, debugging and testing.

1st in division and 3rd overall out of 130+ teams at the FSU ACM Spring 2026 Programming Contest. Dean's List, Spring 2026.

### Stack

`Python` `C++` `PyTorch` `PyTorch Geometric` `FastAPI` `Azure OpenAI` `scikit-learn` `NumPy` `Pandas` `SQL` `Git`

RAG and hybrid search, embeddings and rerankers, LLM evaluation, prompt and context engineering, agent tooling, MLOps monitoring, differential privacy.

### Elsewhere

[mjeneidi.com](https://mjeneidi.com) · [LinkedIn](https://www.linkedin.com/in/mohammad-jeneidi) · [Substack](https://mohammadjeneidi.substack.com)
