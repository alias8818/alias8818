# alias8818

I build **auditable AI infrastructure**: control planes, audit gates, and Blackwell (sm_121) kernel debugging for GPU work.

## Currently

**May 2026** — Shipping polish on Enoch: strict claim/evidence audit coverage, representative audit examples on the landing page, and kernel-work-first ordering on the personal site. Open to AI infrastructure roles; I'm the person who reads Xid error codes *and* writes the control plane that notices the worker died. Oklahoma City.

---

## Featured work

### Enoch: Agentic Research Control Plane

Enoch is an open-source control plane for running bounded AI research workflows end to end. It coordinates idea intake, queue state, pause/maintenance controls, worker preflight, single-lane safety, evidence synchronization, dashboard visibility, alerting, and publication-style artifact packaging.

- Launch site: <https://alias8818.github.io/>
- System repo: <https://github.com/alias8818/enoch-agentic-research-system>
- Research corpus: <https://github.com/alias8818/enoch-ai-research-corpus>
- Promising signals: <https://github.com/alias8818/enoch-promising-signals>
- Documentation website: <https://solo-09d10f60.mintlify.app/>

### AI-generated research corpus

The companion corpus indexes **393 canonical AI-generated research artifacts**. The separate promising-signals repo is explicitly not a paper corpus and is not counted as corpus papers. Current status: **393/393 pass packaging/provenance lint** and **393/393 pass strict claim/evidence audit**. I built the strict-audit gate and keep it visible on the project's front page, because the packaging/provenance lint alone would let readers over-trust the corpus.

Important framing: these papers are released as AI-generated artifacts. I am not claiming human authorship of the paper prose, research claims, or generated results. The packaging/provenance lint does not imply peer review, scientific correctness, independent replication, or deep claim/evidence auditability. The work I am highlighting is the system design, control-plane implementation, evidence workflow, and public packaging around those outputs.

## What I care about

- Agent orchestration and durable workflow state
- Local AI infrastructure and worker safety
- Evidence-grounded automation
- Human-visible provenance for generated artifacts
- Queue/dispatch systems that fail loudly instead of hanging silently
- Practical tooling for AI-assisted research loops

## Stack and systems

- Python, FastAPI, SQLite-backed control state
- FastAPI control-plane boundaries with a hard state contract
- GitHub Actions, branch protections, release packaging
- Local worker orchestration and wake-gated execution
- Codex-assisted development and oh-my-codex/OMX operations

## Current public repos

- [`enoch-agentic-research-system`](https://github.com/alias8818/enoch-agentic-research-system) — control-plane code, deployment docs, dashboard, alerting, and paper workflow
- [`enoch-ai-research-corpus`](https://github.com/alias8818/enoch-ai-research-corpus) — generated research artifacts with provenance/evidence metadata plus strict claim/evidence audit status
- [`enoch-promising-signals`](https://github.com/alias8818/enoch-promising-signals) — bounded useful or compute-scale-blocked no-paper signals preserved for larger-compute follow-up
- [Enoch Docs](https://solo-09d10f60.mintlify.app/) — hosted operator and reviewer documentation for the system, corpus, deployment path, and release boundaries ([source](https://github.com/alias8818/enoch-docs))
