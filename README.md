# Reza Rahimi

**AI/ML Engineering Manager · Architect and Builder**

Building and scaling **trustworthy, production-grade AI/ML products** — AI/ML, Agentic AI, LLMs, LLM safety & guardrails, evaluation systems, and scalable ML infrastructure (MLOps / AgentOps).

🔭 Currently: how to **build, evaluate, calibrate, scale, and safely deploy** LLM applications and AI agents efficiently.
💞️ Open to collaborating on open-source in **AI/ML, LLMs · Generative AI · agentic workflows · AI evaluation · AgenticOps**.

📫 [GitHub](https://github.com/rrahimi-uci) · Pronouns: He/Him

---

## 🚀 Featured Projects

### 🧭 [CALIBER Suite](https://github.com/rrahimi-uci/caliber-suite) · [documentation](https://rrahimi-uci.github.io/caliber-suite/)
An MLflow-integrated control plane for **trusted agentic workflows**: governed prompts, tools, skills, MCP servers, workflows, knowledge bases, evaluations, calibration, observability, deployment, and the Aria copilot. The current release tracks MLflow 3.15 and PostgreSQL 17, with a layered architecture, 16 UI cookbooks, and a published documentation site.
`AI agent platform` · `MLflow` · `AgentOps` · `LLMOps` · `MCP` · `RAG` · `governance` · `evaluation` · `observability` · `prompt engineering`

### 🛡️ [Safety Guard Dynamics](https://github.com/rrahimi-uci/safety-guard-dynamics) · [research hub](https://rrahimi-uci.github.io/safety-guard-dynamics/) · [v0.0.1 release](https://github.com/rrahimi-uci/safety-guard-dynamics/releases/tag/guard-v0.0.1)
**Safety benchmark gains do not guarantee safety transfer.** A paired, same-checkpoint study of how compact prompt-safety **guards** specialize, transfer, and compose — LoRA-SFT vs. base-anchored KL-SFT across four instruction checkpoints, a dual-labeled mortgage benchmark, and an analysis-preregistered panel of released vendor guards. The v0.0.1 [research hub](https://rrahimi-uci.github.io/safety-guard-dynamics/) brings together the published HTML report and the [unified report PDF](https://github.com/rrahimi-uci/safety-guard-dynamics/blob/main/papers/unified-report/unified_report.pdf). The release records explicit study state, evidence tiers, verification paths, and redistribution decisions; 28 of 32 generated inputs verify in the standard environment, with the remaining four requiring the pinned analysis environment.
`LLM safety` · `AI safety` · `guardrails` · `jailbreak detection` · `prompt injection` · `content moderation` · `LoRA / SFT` · `small language models` · `reproducible research`

### ⚙️ [Guarded Agentic Compaction](https://github.com/rrahimi-uci/guarded-agentic-compaction) · [research site](https://rrahimi-uci.github.io/guarded-agentic-compaction/)
**Traces establish recurrence, not admissibility.** A trace-to-program compiler that turns repeated read-only agent prefixes into deterministic **guarded programs** — and refuses whenever the evidence cannot license one. Typed value provenance, effect and position barriers, a bounded 23-operator DSL, runtime verification, and a finite-sample selective-risk gate whose default output is retirement. Across three live-provider GitHub workflow families it matches the baseline on **90/90 exact outcomes** (versus 89/90), while reducing provider requests by **66.6%**; on NESTFUL and API-Bank every recurrent family retires — which is the result, not a failure. The newly published [artifact shelf](https://rrahimi-uci.github.io/guarded-agentic-compaction/artifacts.html) documents the evidence and its limits.
`LLM agents` · `agent optimization` · `program synthesis` · `compiler` · `provenance` · `tool use` · `trace analysis` · `selective risk control` · `reproducible research`

### 🧠 [Agentic Context Engineering (ACE)](https://github.com/rrahimi-uci/agentic-context-engineering) · [docs](https://rrahimi-uci.github.io/agentic-context-engineering/)
Faithful **ICLR 2026** implementation — evolving, self-improving context playbooks for LLM agents via a Generator → Reflector → Curator loop with incremental delta updates. OpenAI Agents SDK support, 163 tests, and an 11-recipe cookbook.
`context engineering` · `self-improving agents` · `in-context learning` · `agent memory` · `LLM agents` · `prompt optimization` · `RAG` · `OpenAI Agents SDK`

### 🤝 [A2A Protocol Reference](https://github.com/rrahimi-uci/a2a-poc) · [project site](https://rrahimi-uci.github.io/a2a-poc/)
A clean reference implementation of the **Agent-to-Agent (A2A) protocol** — specialized AI agents that discover each other and collaborate over JSON-RPC 2.0. Python · FastAPI · Pydantic, with 147 tests at 93% coverage and a worked cookbook.
`A2A protocol` · `multi-agent systems` · `agent interoperability` · `agent communication` · `JSON-RPC` · `FastAPI` · `Pydantic` · `LLM agents`

### 📚 [Policy-to-Knowledge](https://github.com/rrahimi-uci/policy-to-knowledge) · [docs](https://rrahimi-uci.github.io/policy-to-knowledge/)
Enterprise **compliance automation** — turn compliance documents into queryable knowledge graphs via a multi-agent AI pipeline, with an interactive graph explorer.
`knowledge graphs` · `compliance automation` · `RegTech` · `multi-agent AI` · `JanusGraph` · `FastAPI` · `LLM`

### ⚖️ [Policy Logic Forge](https://github.com/rrahimi-uci/policy-logic-forge) · [project site](https://rrahimi-uci.github.io/policy-logic-forge/)
A focused research spinoff that compiles compliance policy text into typed, source-grounded **executable decision logic** — DMN/BPMN/CMMN/SBVR plus a LinkML business information model. Its thirteen-agent CLI pipeline independently re-derives each rule's evidence from the raw corpus rather than trusting the citation the rule carries, then partitions the survivors into dependency DAGs with a checked coverage guarantee. **RegDelta** diffs two versions of a policy and propagates the impact; six properties of the type lattice, bounded prover, and dependency partition are discharged by exhaustive enumeration rather than by example.
`compliance automation` · `business rules` · `decision automation` · `DMN / BPMN` · `knowledge graphs` · `LinkML` · `grounding` · `dependency DAGs` · `differential execution` · `RegTech`

### 💸 [RL for Anti-Money-Laundering](https://github.com/rrahimi-uci/rl-anti-money-laundry) · [project site](https://rrahimi-uci.github.io/rl-anti-money-laundry/)
**Reinforcement learning** (PPO/A2C/DQN) that dynamically tunes AML risk-scoring weights per case — Gymnasium env, FastAPI backend, React training dashboard.
`reinforcement learning` · `anti-money laundering` · `RegTech` · `PPO` · `Gymnasium` · `risk scoring` · `FastAPI` · `React`

### 🏠 [Tabular AutoML Template](https://github.com/rrahimi-uci/buyer-stage-prediction)
Domain-agnostic, single-node, `docker compose`-portable **tabular AutoML pipeline** (Dagster + FLAML + MLflow + FastAPI) with drift monitoring, an online feature store, a Streamlit dashboard, and one-command start/stop. The real-estate **buyer-stage** classifier ships as the worked example — all domain knowledge lives in YAML, never in framework code.
`AutoML` · `MLflow` · `Dagster` · `FLAML` · `drift detection` · `tabular ML` · `feature store` · `real estate ML`

### 🎓 [Guru.AI — Interviewer GPT](https://github.com/rrahimi-uci/interviewer-gpt) · [project site](https://rrahimi-uci.github.io/interviewer-gpt/)
AI-powered **mock-interview assistant** for ML engineering, leadership/behavioural, and coding interviews. Gradio 6 · LangChain 1.x · OpenAI · Whisper.
`interview prep` · `LangChain` · `GPT` · `OpenAI` · `Whisper` · `speech-to-text` · `generative AI` · `Gradio`

---

## 🛠️ Focus Areas

**Agentic AI** · **LLM safety & guardrails** · **prompt-injection / jailbreak detection** · **LLM & agent evaluation** · **program synthesis & selective risk control** · **MLflow / LLMOps / MLOps** · **RAG** · **reinforcement learning (RLHF/GRPO/PPO)** · **fine-tuning (SFT/LoRA)** · **knowledge graphs** · **multi-agent systems**

Python · PyTorch · Transformers · TRL · MLflow · FastAPI · LangChain · React

---

<sub>⭐ If any of these are useful, a star helps others find them too.</sub>
