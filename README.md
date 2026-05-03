# alias8818

I build **agentic research infrastructure**: local-control-plane systems, queue safety, worker orchestration, evidence capture, and AI-generated research artifact pipelines.

## Featured work

### Enoch: Agentic Research Control Plane

Enoch is an open-source control plane for running bounded AI research workflows end to end. It coordinates idea intake, queue state, pause/maintenance controls, worker preflight, single-lane safety, evidence synchronization, dashboard visibility, alerting, and publication-style artifact packaging.

- Launch site: <https://alias8818.github.io/>
- System repo: <https://github.com/alias8818/enoch-agentic-research-system>
- Research corpus: <https://github.com/alias8818/enoch-ai-research-corpus>
- Documentation website: <https://solo-09d10f60.mintlify.app/>

### AI-generated research corpus

The companion corpus contains **120 AI-generated research artifacts** packaged with provenance metadata, claim ledgers, evidence bundles, manifests, and quality reports.

Important framing: these papers are released as AI-generated artifacts. I am not claiming human authorship of the paper prose, research claims, or generated results. The work I am highlighting is the system design, control-plane implementation, evidence workflow, and public packaging around those outputs.

## What I care about

- Agent orchestration and durable workflow state
- Local AI infrastructure and worker safety
- Evidence-grounded automation
- Human-visible provenance for generated artifacts
- Queue/dispatch systems that fail loudly instead of hanging silently
- Practical tooling for AI-assisted research loops

## Stack and systems

- Python, FastAPI, SQLite-backed control state
- LangGraph-era control-plane boundaries
- GitHub Actions, branch protections, release packaging
- Local worker orchestration and wake-gated execution
- Codex-assisted development and oh-my-codex/OMX operations

## Current public repos

- [`enoch-agentic-research-system`](https://github.com/alias8818/enoch-agentic-research-system) — control-plane code, deployment docs, dashboard, alerting, and paper workflow
- [`enoch-ai-research-corpus`](https://github.com/alias8818/enoch-ai-research-corpus) — generated research artifacts with provenance/evidence metadata
- [Enoch Docs](https://solo-09d10f60.mintlify.app/) — hosted operator and reviewer documentation for the system, corpus, deployment path, and release boundaries ([source](https://github.com/alias8818/enoch-docs))
