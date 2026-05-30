# Hi, I'm Ahmed 👋 — AI / Agent Engineer

I build **LLM agents you can trust** — measured with golden evals, per-claim citation checks, and full tracing. Based in Germany. Open to AI / Agent Engineer roles.

**🔎 What I'm known for:** evaluation & agent-observability rigor — turning *"the demo worked"* into *"here's the eval score, the trace, and the CI gate."*

**🌐 [ahmedhobeishy.tech](https://ahmedhobeishy.tech)** — portfolio · [**blog**](https://ahmedhobeishy.tech/blog/) on agents, evals & observability · and **AIme**, an AI stand-in you can chat with: grounded in my work, honest about what it doesn't know. ([how I built it](https://ahmedhobeishy.tech/blog/building-aime/))

### Flagship projects

- **[Lumen](https://github.com/ahmedEid1/lumen)** — open-source agentic AI tutor. Custom multi-agent orchestrator (no LangChain), course-scoped RAG over pgvector, a 9-tool **MCP server (stdio + HTTP) on the official registry**, a golden eval suite (LLM-as-judge) wired into CI, and observable per-call traces (tokens, cost, latency). Production deploy on AWS Graviton. ⭐ 66 · [live demo](https://lumen.ahmedhobeishy.tech) · [public /eval](https://lumen.ahmedhobeishy.tech/eval)
- **[Thoth](https://github.com/ahmedEid1/thoth)** — open-source agentic systematic literature reviews with **per-claim citation verification (`cite_check`)** that scores every cited claim against its source paper and flags hallucinated references. LangGraph agent (planner → assessor → drafter → critic → cite_check), an authenticated MCP server (OAuth 2.1 + PKCE), Langfuse + OpenTelemetry tracing, and a public eval dashboard. 676 tests. [live](https://thoth-slr.vercel.app) · [eval dashboard](https://thoth-slr.vercel.app/evals)
- **[ForgeJudge](https://github.com/ahmedEid1/forgejudge)** — open, always-on **leaderboard + CI gate for autonomous coding agents**. A hand-rolled single-agent solver fixes real bugs from the issue text alone; every patch is scored by **execution-as-judge** (verified equivalent to the official SWE-bench grading, and cheat-resistant), every run emits a public OpenTelemetry/Langfuse trace, and a **multi-seed CI gate** blocks any regression — on a **$0** stack against a contamination-resistant, mutation-hardened golden set. A model-swap proves the harness is the deliverable (llama-3.1-8b 42% → llama-3.3-70b 83% pass@1, harness fixed). FastMCP server on the official registry. [live leaderboard](https://forgejudge.ahmedhobeishy.tech)

> The numbers are public on purpose. Thoth's dashboard shows citation precision 97% and recall 74% on the goldens scored so far, with faithfulness and coverage tracked in the open as the golden set fills out — a regression is a falsifiable public signal, not a hidden one. Lumen's /eval publishes all three suites whole, strong and weak alike (authoring 3.85/5). The point isn't a perfect score — it's that every score is measured, reproducible, and gated in CI.

### Stack

**AI / Agents:** `LLM agents` · `RAG / pgvector` · `multi-agent orchestration` · `MCP` · `LangGraph` · `Claude API` · `prompt & context engineering`
**Eval & Observability:** `golden evals` · `LLM-as-judge` · `cite_check` · `Langfuse` · `OpenTelemetry` · `CI regression gates`
**Languages & Backend:** `Python` · `TypeScript` · `Java` · `FastAPI` · `Flask` · `Node.js` · `PostgreSQL` · `Redis`
**Infra:** `Docker` · `Kubernetes` · `Helm` · `AWS` · `CI/CD`

### More

3+ years shipping production software · BSc top of class (Al-Azhar) · MSc Digital Transformation (FH Dortmund) · currently going deep on LLM internals and agent architectures — transformer mechanics, RAG, evaluation, and LLMOps.

**Foundations (proof of depth):** [GPT from scratch (PyTorch)](https://github.com/ahmedEid1/gpt-from-scratch) — a **297-test from-scratch GPT** (tokenizer → attention → training loop → LoRA). Not just an API caller.

📫 ahmedhobeishy@gmail.com · 🔗 [ahmedhobeishy.tech](https://ahmedhobeishy.tech) · 💼 [in/ahmedhobeishy](https://linkedin.com/in/ahmedhobeishy)
