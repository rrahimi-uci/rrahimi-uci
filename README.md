# Reza Rahimi

**AI/ML Engineering Manager · Architect and Builder**

Building and scaling **trustworthy, production-grade AI/ML products** — AI/ML, Agentic AI, LLMs, LLM safety & guardrails, evaluation systems, and scalable ML infrastructure (MLOps / AgentOps).

🔭 Currently: how to **build, evaluate, calibrate, scale, and safely deploy** LLM applications and AI agents efficiently.
💞️ Open to collaborating on open-source in **AI/ML, LLMs · Generative AI · agentic workflows · AI evaluation · AgenticOps**.

📫 [GitHub](https://github.com/rrahimi-uci) · Pronouns: He/Him

---

## 🚀 Featured Projects

### 🧭 [CALIBER Suite](https://github.com/rrahimi-uci/caliber-suite) · [documentation](https://rrahimi-uci.github.io/caliber-suite/)
An MLflow-integrated control plane for **trusted agentic workflows**: governed prompts, tools, skills, MCP servers, workflows, knowledge bases, evaluations, calibration, observability, deployment, and the Aria copilot. A new **Workspace layer** adds multi-project/tenant authorization scoping, a pluggable source-control provider contract with a GitHub adapter, a PR-like Change Request review/promotion lifecycle, and release-governance state machines with break-glass policy. The current release tracks MLflow 3.15 and PostgreSQL 17 with MCP 2.x, a layered architecture, 16 UI cookbooks, a published documentation site, and CI-gated UI test coverage above 90%.
`AI platform` · `MLflow` · `AgentOps` · `governance` · `multi-tenancy` · `evaluation` · `observability`

### 🛡️ [Safety Guard Dynamics](https://github.com/rrahimi-uci/safety-guard-dynamics) · [research hub](https://rrahimi-uci.github.io/safety-guard-dynamics/) · [v0.0.1 release](https://github.com/rrahimi-uci/safety-guard-dynamics/releases/tag/guard-v0.0.1)
**Safety benchmark gains do not guarantee safety transfer.** A paired, same-checkpoint study of how compact prompt-safety **guards** specialize, transfer, and compose — LoRA-SFT vs. base-anchored KL-SFT across four instruction checkpoints, a dual-labeled mortgage benchmark, and an analysis-preregistered panel of released vendor guards. The v0.0.1 [research hub](https://rrahimi-uci.github.io/safety-guard-dynamics/) brings together the published HTML report and the [unified report PDF](https://github.com/rrahimi-uci/safety-guard-dynamics/blob/main/papers/unified-report/unified_report.pdf). The release records explicit study state, evidence tiers, verification paths, and redistribution decisions; 28 of 32 generated inputs verify in the standard environment, with the remaining four requiring the pinned analysis environment.
`LLM safety` · `guard models` · `LoRA / SFT` · `preregistration` · `benchmark transfer` · `reproducible research` · `research release`

### ⚙️ [Guarded Agentic Compaction](https://github.com/rrahimi-uci/guarded-agentic-compaction) · [research site](https://rrahimi-uci.github.io/guarded-agentic-compaction/)
**Traces establish recurrence, not admissibility.** A trace-to-program compiler that turns repeated read-only agent prefixes into deterministic **guarded programs** — and refuses whenever the evidence cannot license one. Typed value provenance, effect and position barriers, a bounded 23-operator DSL, runtime verification, and a finite-sample selective-risk gate whose default output is retirement. Across three live-provider GitHub workflow families it matches the baseline on **90/90 exact outcomes** (versus 89/90), while reducing provider requests by **66.6%**; on NESTFUL and API-Bank every recurrent family retires — which is the result, not a failure. Now finalized through an ICLR reviewer-response revision and proofreading pass, the published [artifact shelf](https://rrahimi-uci.github.io/guarded-agentic-compaction/artifacts.html) documents the evidence and its limits.
`agent optimization` · `program synthesis` · `provenance` · `selective risk control` · `LLM agents` · `reproducible research`

### 🧠 [Agentic Context Engineering (ACE)](https://github.com/rrahimi-uci/agentic-context-engineering) · [docs](https://rrahimi-uci.github.io/agentic-context-engineering/)
Faithful **ICLR 2026** implementation — evolving, self-improving context playbooks for LLM agents via a Generator → Reflector → Curator loop with incremental delta updates. OpenAI Agents SDK support, 163 tests, and an 11-recipe cookbook.
`context engineering` · `self-improving agents` · `in-context learning` · `agent memory`

### 🤝 [A2A Protocol Reference](https://github.com/rrahimi-uci/a2a-poc) · [project site](https://rrahimi-uci.github.io/a2a-poc/)
A clean reference implementation of the **Agent-to-Agent (A2A) protocol** — specialized AI agents that discover each other and collaborate over JSON-RPC 2.0. Python · FastAPI · Pydantic, with 147 tests at 93% coverage and a worked cookbook.
`multi-agent systems` · `agent interoperability` · `A2A` · `FastAPI`

### 📚 [Policy-to-Knowledge](https://github.com/rrahimi-uci/policy-to-knowledge) · [docs](https://rrahimi-uci.github.io/policy-to-knowledge/)
Enterprise **compliance automation** — turn compliance documents into queryable knowledge graphs via a 15-agent pipeline (11 extraction + 4 comparison), with executable-readiness gating, independent grounding verification, a coverage-checked dependency-DAG generator, and an interactive graph explorer.
`knowledge graphs` · `compliance` · `RegTech` · `multi-agent` · `grounding verification` · `JanusGraph`

### ⚖️ [Policy Logic Forge](https://github.com/rrahimi-uci/policy-logic-forge) · [project site](https://rrahimi-uci.github.io/policy-logic-forge/)
A focused research spinoff that compiles compliance policy text into typed, source-grounded **executable decision logic** — DMN/BPMN/CMMN/SBVR plus a LinkML business information model. Its thirteen-agent CLI pipeline independently re-derives each rule's evidence from the raw corpus rather than trusting the citation the rule carries, then partitions the survivors into dependency DAGs with a checked coverage guarantee. **RegDelta** diffs two versions of a policy and propagates the impact, now layering an optional LLM-assisted semantic comparison over its deterministic diff — scoring unmatched rules for equivalence and routing contradictions to human review rather than auto-resolving them; six properties of the type lattice, bounded prover, and dependency partition are discharged by exhaustive enumeration rather than by example.
`compliance automation` · `executable rules` · `DMN / BPMN` · `grounding` · `dependency DAGs` · `differential execution` · `semantic comparison`

### 💸 [RL for Anti-Money-Laundering](https://github.com/rrahimi-uci/rl-anti-money-laundry) · [project site](https://rrahimi-uci.github.io/rl-anti-money-laundry/)
**Reinforcement learning** (PPO/A2C/DQN) that dynamically tunes AML risk-scoring weights per case — Gymnasium env, FastAPI backend, React training dashboard.
`reinforcement learning` · `AML` · `RegTech` · `PPO` · `risk scoring`

### 🏠 [Tabular AutoML Template](https://github.com/rrahimi-uci/buyer-stage-prediction)
Domain-agnostic, single-node, `docker compose`-portable **tabular AutoML pipeline** (Dagster + FLAML + MLflow + FastAPI) with drift monitoring, an online feature store, a Streamlit dashboard, and one-command start/stop. The real-estate **buyer-stage** classifier ships as the worked example — all domain knowledge lives in YAML, never in framework code.
`AutoML` · `MLflow` · `Dagster` · `drift detection` · `tabular ML`

### 🎓 [Guru.AI — Interviewer GPT](https://github.com/rrahimi-uci/interviewer-gpt) · [project site](https://rrahimi-uci.github.io/interviewer-gpt/)
AI-powered **mock-interview assistant** for ML engineering, leadership/behavioural, and coding interviews. Gradio 6 · LangChain 1.x · OpenAI · Whisper.
`interview prep` · `LangChain` · `speech-to-text` · `generative AI`

---

## 🛠️ Focus Areas

**Agentic AI** · **LLM safety & guardrails** · **prompt-injection / jailbreak detection** · **LLM & agent evaluation** · **program synthesis & selective risk control** · **MLflow / LLMOps / MLOps** · **RAG** · **reinforcement learning (RLHF/GRPO/PPO)** · **fine-tuning (SFT/LoRA)** · **knowledge graphs** · **multi-agent systems**

Python · PyTorch · Transformers · TRL · MLflow · FastAPI · LangChain · React

---

<sub>⭐ If any of these are useful, a star helps others find them too.</sub>
