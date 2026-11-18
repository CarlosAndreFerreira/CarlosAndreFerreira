### Carlos André Ferreira — AI Engineer

I build LLM agents and the verification around them: evaluation, security and observability, so they hold up in production.
Senior Engineer at **Critical Software** (safety-critical software) · PhD researcher in Web Science & Technology (UTAD / Universidade Aberta) · ~8 years in industry · Viseu, Portugal

#### What I work on

- **Agentic systems** — LangGraph, Pydantic AI, MCP servers and tool design
- **Retrieval & memory** — PostgreSQL/pgvector, Neo4j, Graphiti (temporal knowledge graphs)
- **Local inference & fine-tuning** — vLLM, llama.cpp, Ollama, Unsloth, PEFT/LoRA, bitsandbytes quantization
- **Evaluation** — pre-registered benchmarks, pass@1 with confidence intervals, harness-vs-model comparisons, energy per run
- **LLM security** — prompt-injection defenses (OWASP LLM01), credential confinement, least-privilege tool exposure
- **Engineering** — Python, FastAPI, OpenTelemetry, pytest, GitHub Actions · ISTQB CTFL v4

#### Featured

**[ai-quality-pack](https://github.com/CarlosAndreFerreira/ai-quality-pack)** — A quality layer for AI coding agents: a completion gate that runs the project's own checks, and a verdict that comes from commands that ran, not from the agent's report.
Reproduction tests recorded before the change, counterexamples run on the base commit, an independent evaluator, a guard on the files that check the agent, and a hash-chained run log. Standard-library Python, for Claude Code, Codex and OpenCode. Measurements are published with their limits, negative results included: on hard SWE-bench issues an LLM evaluator did not separate wrong patches from correct ones on two models (agreement near zero), and the central claim, fewer false "done", is not measured yet.

**[viriato-bench](https://github.com/CarlosAndreFerreira/viriato-bench)** — How much agentic coding moves from a frontier API to a local 27B model on a mini-PC (AMD Strix Halo)?
Same harness, code-verified correctness: Claude 9/9 vs local Qwen 0/9 on the spec-driven tasks (Fisher p = 0.00002); in lighter harnesses the local model reaches 9/12 clean passes. Energy measured per run.

**[moodle-obsidian-mcp](https://github.com/CarlosAndreFerreira/moodle-obsidian-mcp)** — MCP server for Moodle, built for untrusted content.
Read-only by default, hidden-text stripping before content reaches the model, user confirmation via MCP elicitation for every write, token never sent off the configured host, SSO login through a signed one-time passport. 32 tools, CI on Linux/macOS/Windows. Published on [PyPI](https://pypi.org/project/moodle-obsidian-mcp/) and indexed as a reference prompt-injection defense on [XERJ Corpus Hub](https://hub.xerj.org/contributors/CarlosAndreFerreira).

#### Research

- **[Agentic AI for Root Cause Analysis in Cybersecurity Incident Response: A Multi-Agent Architecture Based on LLMs and Knowledge Graphs](https://frontend.scms.scika.org/uploads/scms/u1508-ed29-pub1873-zScyv_Pb4ghHvQfp4Si0eiNZOA-lJQoi.pdf)** — full paper, CENTERIS 2026, with Henrique São Mamede.
  CIRA-MAS: four LangGraph agents (ingestion, knowledge, causal reasoning, response) over LightRAG graph retrieval on a CVE → ATT&CK → IoC schema, producing auditable incident reports with a causal chain for SOC analysts. Architecture and falsifiable evaluation agenda; empirical validation is next.

#### Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-carlos--andre--ferreira--ai.netlify.app-000000?style=flat-square&logo=netlify)](https://carlos-andre-ferreira-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-carlos--andre--ferreira-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/carlos-andr%C3%A9-ferreira-8367a912a/)
[![XERJ Corpus Hub](https://img.shields.io/badge/XERJ_Corpus_Hub-Contributor-181717?style=flat-square)](https://hub.xerj.org/contributors/CarlosAndreFerreira)
