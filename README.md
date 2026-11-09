# Reza Rahimi, Ph.D.

**AI/ML Engineering Manager · Architect · Builder**

I design and build **trustworthy AI systems that can be evaluated, governed, and operated in production**. My public work spans agentic platforms and interoperability, LLM safety and evaluation, reproducible research, enterprise compliance automation, and practical ML infrastructure.

🔭 Current focus: making LLM applications and AI agents more **reliable, observable, secure, and efficient** — from context and tool use to deployment and risk control.
💞️ Open to collaborating on public work in **AI/ML · agentic systems · LLM safety · evaluation · MLOps / AgentOps · responsible automation**.

📫 [GitHub](https://github.com/rrahimi-uci) · Pronouns: He/Him

---

## 🚀 Selected Public Projects

These repositories represent three connected themes: building usable AI infrastructure, studying how to make agentic systems safer and more dependable, and turning complex enterprise policies into auditable automation.

### 📖 [Building an Enterprise General Intelligence Platform](https://github.com/rrahimi-uci/building-enterprise-general-intelligence)
A practical guide to building enterprise AI agents that are **secure, governed, auditable, and dependable in production**. The book treats an agentic application as a distributed system and covers architecture, knowledge and context, identity and control, evaluation, release, and real-world operations, with executable examples, a 28-checkpoint offline mortgage case study (`C01`–`C28`, deterministic teaching doubles that never decide credit), and a reproducible publication workflow.
`enterprise AI architecture` · `agent governance` · `security` · `auditability` · `agent operations` · `technical leadership`

### 🧭 [CALIBER Suite](https://github.com/rrahimi-uci/caliber-suite) · [Project site](https://rrahimi-uci.github.io/caliber-suite/)
An MLflow-integrated control plane for **trusted agentic workflows**: governed prompts, tools, skills, MCP servers, workflows, knowledge bases, evaluations, calibration, observability, deployment, and the Aria copilot. A new **Workspace layer** adds multi-project/tenant authorization scoping, a pluggable source-control provider contract with a GitHub adapter, a PR-like Change Request review/promotion lifecycle, and release-governance state machines with break-glass policy. It requires MLflow 3.15+ and ships with 22 cookbook labs and a published documentation site. The **`0.1.0a1` alpha is published** as a GitHub [pre-release](https://github.com/rrahimi-uci/caliber-suite/releases/tag/caliber-v0.1.0a1) (wheel-verified; not on PyPI), proven by a real Playwright journey from a flagged trace through diagnosis, a measured candidate, Apply, and rollback. Work on `main` now targets a **Beta** that is not yet released: a supported reference profile (PostgreSQL, CSRF, two-person approval) whose support claims are tied to scenario tests, with unsupported surfaces kept explicitly preview.
`AI agent platform` · `MLflow` · `AgentOps` · `LLMOps` · `MCP` · `RAG` · `governance` · `multi-tenancy` · `evaluation` · `observability` · `prompt engineering`

### ⚙️ [Guarded Agentic Compaction](https://github.com/rrahimi-uci/guarded-agentic-compaction) · [Project site](https://rrahimi-uci.github.io/guarded-agentic-compaction/)
**Traces establish recurrence, not admissibility.** A trace-to-program compiler that turns repeated read-only agent prefixes into deterministic **guarded programs** — the program an engineer would have written, found automatically — and refuses whenever the evidence cannot license one. Typed value provenance, effect and position barriers, a bounded 23-operator DSL, runtime verification, and a finite-sample selective-risk gate whose default output is retirement. Across three live-provider GitHub workflow families it matches the baseline on **90/90 exact outcomes** (versus 89/90), while reducing provider requests by **66.6%**; against adapted offline Agent Workflow Memory on 1,344 fresh records, five of six workflow-and-model cells meet a preregistered five-point noninferiority margin at **36.9–79.1% lower estimated cost**. A public **BIRD** text-to-SQL study compiled a schema-first opening on 26 of 31 databases (about 45% fewer requests, no detected accuracy loss). The November evidence extends a cross-repository, time-forward study to the model's final answer: 3 misses in 760 one-per-author pull-request groups across four repositories, then seven more repositories at 400 groups each — five admitted and two retired by the gate — with compiled, unchanged, and hand-written arms meeting 3,510, 3,507, and 3,504 of 3,560 contracts. It reports its negatives plainly: NESTFUL, API-Bank, and BFCL are refused for thin calibration support, AppWorld's program is rarely eligible, and a learned dispatch gate shows no demonstrated benefit — the result, not a failure. The published [artifact shelf](https://rrahimi-uci.github.io/guarded-agentic-compaction/artifacts.html) documents the evidence and its limits.
`LLM agents` · `agent optimization` · `program synthesis` · `compiler` · `text-to-SQL` · `provenance` · `tool use` · `trace analysis` · `selective risk control` · `reproducible research`

### 📚 [Policy-to-Knowledge](https://github.com/rrahimi-uci/policy-to-knowledge) · [Project site](https://rrahimi-uci.github.io/policy-to-knowledge/)
Enterprise **compliance automation** — turn compliance documents into queryable knowledge graphs via a 15-agent pipeline (11 extraction + 4 comparison), with executable-readiness gating, independent grounding verification, a coverage-checked dependency-DAG generator, and an interactive graph explorer.
`knowledge graphs` · `compliance automation` · `RegTech` · `multi-agent AI` · `grounding verification` · `JanusGraph` · `FastAPI` · `LLM`

### 🛡️ [Safety Guard Dynamics](https://github.com/rrahimi-uci/safety-guard-dynamics) · [Project site](https://rrahimi-uci.github.io/safety-guard-dynamics/) · [v0.0.1 release](https://github.com/rrahimi-uci/safety-guard-dynamics/releases/tag/guard-v0.0.1)
**Safety benchmark gains do not guarantee safety transfer.** A paired, same-checkpoint study of how compact prompt-safety **guards** specialize, transfer, and compose — LoRA-SFT vs. base-anchored KL-SFT across four instruction checkpoints, a dual-labeled mortgage benchmark, and an analysis-preregistered panel of released vendor guards. The v0.0.1 [research hub](https://rrahimi-uci.github.io/safety-guard-dynamics/) brings together the published HTML report and the [unified report PDF](https://github.com/rrahimi-uci/safety-guard-dynamics/blob/main/papers/unified-report/unified_report.pdf). The release records explicit study state, evidence tiers, verification paths, and redistribution decisions; 28 of 32 generated inputs verify in the standard environment, with the remaining four requiring the pinned analysis environment.
`LLM safety` · `AI safety` · `guardrails` · `jailbreak detection` · `prompt injection` · `content moderation` · `LoRA / SFT` · `small language models` · `reproducible research`

### ⚖️ [Policy Logic Forge](https://github.com/rrahimi-uci/policy-logic-forge) · [Project site](https://rrahimi-uci.github.io/policy-logic-forge/)
A focused research spinoff that compiles compliance policy text into typed, source-grounded **executable decision logic** — DMN/BPMN/CMMN/SBVR plus a LinkML business information model. Its thirteen-agent CLI pipeline independently re-derives each rule's evidence from the raw corpus rather than trusting the citation the rule carries, then partitions the survivors into dependency DAGs with a checked coverage guarantee. **RegDelta** diffs two versions of a policy and propagates the impact, now layering an optional LLM-assisted semantic comparison over its deterministic diff — scoring unmatched rules for equivalence and routing contradictions to human review rather than auto-resolving them; six properties of the type lattice, bounded prover, and dependency partition are discharged by exhaustive enumeration rather than by example.
`compliance automation` · `business rules` · `decision automation` · `DMN / BPMN` · `knowledge graphs` · `LinkML` · `grounding` · `dependency DAGs` · `differential execution` · `RegTech` · `semantic comparison`

### 🤝 [A2A Protocol Reference](https://github.com/rrahimi-uci/a2a-poc) · [Project site](https://rrahimi-uci.github.io/a2a-poc/)
A clean reference implementation of the **Agent-to-Agent (A2A) protocol** — specialized AI agents that discover each other and collaborate over JSON-RPC 2.0. Python · FastAPI · Pydantic, with 147 tests at 93% coverage and a worked cookbook.
`A2A protocol` · `multi-agent systems` · `agent interoperability` · `agent communication` · `JSON-RPC` · `FastAPI` · `Pydantic` · `LLM agents`

### 🏠 [Tabular AutoML Template](https://github.com/rrahimi-uci/buyer-stage-prediction)
Domain-agnostic, single-node, `docker compose`-portable **tabular AutoML pipeline** (Dagster + FLAML + MLflow + FastAPI) with drift monitoring, an online feature store, a Streamlit dashboard, and one-command start/stop. The real-estate **buyer-stage** classifier ships as the worked example — all domain knowledge lives in YAML, never in framework code.
`AutoML` · `MLflow` · `Dagster` · `FLAML` · `drift detection` · `tabular ML` · `feature store` · `real estate ML`

### 💸 [RL for Anti-Money-Laundering](https://github.com/rrahimi-uci/rl-anti-money-laundry) · [Project site](https://rrahimi-uci.github.io/rl-anti-money-laundry/)
**Reinforcement learning** (PPO/A2C/DQN) that dynamically tunes AML risk-scoring weights per case — Gymnasium env, FastAPI backend, React training dashboard.
`reinforcement learning` · `anti-money laundering` · `RegTech` · `PPO` · `Gymnasium` · `risk scoring` · `FastAPI` · `React`

### 🎓 [Guru.AI — Interviewer GPT](https://github.com/rrahimi-uci/interviewer-gpt) · [Project site](https://rrahimi-uci.github.io/interviewer-gpt/)
AI-powered **mock-interview assistant** for ML engineering, leadership/behavioural, and coding interviews. Gradio 6 · LangChain 1.x · OpenAI · Whisper.
`interview prep` · `LangChain` · `GPT` · `OpenAI` · `Whisper` · `speech-to-text` · `generative AI` · `Gradio`

### 🧠 [Agentic Context Engineering (ACE)](https://github.com/rrahimi-uci/agentic-context-engineering) · [Project site](https://rrahimi-uci.github.io/agentic-context-engineering/)
Faithful **ICLR 2026** implementation — evolving, self-improving context playbooks for LLM agents via a Generator → Reflector → Curator loop with incremental delta updates. OpenAI Agents SDK support, 163 tests, and an 11-recipe cookbook.
`context engineering` · `self-improving agents` · `in-context learning` · `agent memory` · `LLM agents` · `prompt optimization` · `RAG` · `OpenAI Agents SDK`

---

## 🛠️ Focus Areas

**Agentic AI** · **LLM safety & guardrails** · **prompt-injection / jailbreak detection** · **LLM & agent evaluation** · **program synthesis & selective risk control** · **MLflow / LLMOps / MLOps** · **RAG** · **reinforcement learning (RLHF/GRPO/PPO)** · **fine-tuning (SFT/LoRA)** · **knowledge graphs** · **multi-agent systems**

Python · PyTorch · Transformers · TRL · MLflow · FastAPI · LangChain · React

---

<sub>⭐ If any of these are useful, a star helps others find them too.</sub>
