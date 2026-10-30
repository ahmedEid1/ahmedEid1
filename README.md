## Ahmed Hobeishy · AI Engineer for agentic systems

I build production LLM agents and RAG systems that cite their sources, and the evals, tracing and guardrails that prove they work. 4+ years shipping production software, the last two in applied AI and LLM systems. Based in Germany.

### Selected work

**[Ordnung](https://github.com/ahmedEid1/ordnung)**: an AI secretary for paperwork in Germany. Claude extracts quote-grounded facts from each letter; a tested rules engine turns them into deadlines with a cited receipt for every step. 97.0% of 168 held-out deadlines exactly right, 16.1 points above the same model alone, measured against three same-model baselines with bootstrap CIs. An Ask agent answers through read-only MCP tools with a claim-level citation check. [Demo](https://ahmedeid1.github.io/ordnung/)

**[Lumen](https://github.com/ahmedEid1/lumen)**: an open-source AI tutor. One sentence in, a course out (45 to 90 seconds for 10 lessons after the intake), and a course-scoped RAG tutor over pgvector that cites the lessons it retrieves. Custom multi-agent orchestrator (no framework), permission-filtered retrieval in SQL, an MCP server on the official registry, and golden eval suites with every report published, weak scores included. It ran live on AWS in 2026; [walkthrough video and screenshots](https://github.com/ahmedEid1/lumen/tree/main/docs/demo/2026-10-30)

**[ForgeJudge](https://github.com/ahmedEid1/forgejudge)**: a leaderboard and CI gate for coding agents. SWE-bench-style grading on a contamination-resistant set of 18 mutation-tested tasks, with hidden tests and stricter checks than the stock grader; 162 of 162 verdicts reproduced on re-grade. Archived in September 2026. [Leaderboard](https://forgejudge.ahmedhobeishy.tech)

**[Thoth](https://github.com/ahmedEid1/thoth)**: agentic literature reviews. A LangGraph agent plans, screens and drafts, then checks every cited claim before anyone reads the draft; three human-in-the-loop gates and an MCP server with OAuth 2.1.

**Agents on Amazon Bedrock AgentCore**: three AWS agent systems built on Udacity's starter templates, with my own agents, prompts and evals. The largest routes to four specialist agents with parallel RAG over three Knowledge Bases. [Multi-agent RAG](https://github.com/ahmedEid1/multi-agent-ecommerce-rag) · [Runtime agent](https://github.com/ahmedEid1/agentcore-support-agent) · [Support chatbot](https://github.com/ahmedEid1/bedrock-support-chatbot)

### Stack

Python · TypeScript · Claude API · MCP · LangGraph · FastAPI · Next.js · PostgreSQL and pgvector · OpenTelemetry · Langfuse · Amazon Bedrock and AgentCore · Docker · Kubernetes

### Background

M.Sc. Digital Transformation, FH Dortmund · B.Sc. Systems and Computer Engineering, Al-Azhar University · Selected for the Linux Foundation's Open Mainframe Project mentorship

[ahmedhobeishy.tech](https://ahmedhobeishy.tech) · [LinkedIn](https://linkedin.com/in/ahmedhobeishy) · ahmedhobeishy@gmail.com
