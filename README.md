# alias8818

I build **auditable AI infrastructure**: control planes, audit gates, and local AI systems where worker state, evidence, and public claims have to line up.

## Featured work: Enoch

**Enoch is an open-source control plane for bounded autonomous AI research.** It coordinates idea intake, queue state, pause/maintenance controls, worker preflight, single-lane safety, evidence synchronization, dashboard visibility, alerting, and publication-style artifact packaging.

| Public surface | Link |
| --- | --- |
| Launch site | <https://alias8818.github.io/> |
| System repo | <https://github.com/alias8818/enoch-agentic-research-system> |
| Research corpus | <https://github.com/alias8818/enoch-ai-research-corpus> |
| Promising signals | <https://github.com/alias8818/enoch-promising-signals> |
| Docs | <https://solo-09d10f60.mintlify.app/> |
| Hugging Face dataset | <https://huggingface.co/datasets/aliasocracy/enoch-ai-research-corpus> |

## Current public corpus status

The companion corpus indexes **393 canonical AI-generated research artifacts**. The separate promising-signals repo preserves **6,381** bounded no-paper signals and is not counted as corpus papers.

Current corpus audit status:

- **393/393** pass packaging/provenance lint.
- **393/393** pass strict claim/evidence audit.
- **0** empty claim ledgers.
- **0** missing public result-file references.

Important framing: these papers are released as AI-generated artifacts. I am not claiming human authorship of the paper prose, research claims, or generated results. The packaging/provenance lint does not imply peer review, scientific correctness, independent replication, or deep claim/evidence auditability. The work I am highlighting is the system design, control-plane implementation, evidence workflow, and public packaging around those outputs.

## What I care about

- Agent orchestration and durable workflow state
- Local AI infrastructure and worker safety
- Evidence-grounded automation
- Human-visible provenance for generated artifacts
- Queue/dispatch systems that fail loudly instead of hanging silently
- Practical tooling for AI-assisted research loops

## Stack and systems

- Python, FastAPI, SQLite/Postgres-backed control state
- FastAPI control-plane boundaries with a hard state contract
- GitHub Actions, branch protections, release packaging
- Local worker orchestration and worker-gated execution
- Codex-assisted development and oh-my-codex/OMX operations
