### Carlos André Ferreira — AI Engineer

I build LLM agents and the verification around them: evaluation, security and observability, so they hold up in production.
Senior Engineer at **Critical Software** (safety-critical software) · PhD candidate in Web Science & Technology (UTAD / Universidade Aberta) · ~8 years in industry · Viseu, Portugal

#### What I work on

- **Agentic systems** — LangGraph, Pydantic AI, MCP servers and tool design
- **Retrieval & memory** — PostgreSQL/pgvector, Neo4j, Graphiti (temporal knowledge graphs)
- **Local inference & fine-tuning** — vLLM, llama.cpp, Ollama, Unsloth, PEFT/LoRA, bitsandbytes quantization
- **Evaluation** — pre-registered benchmarks, pass@1 with confidence intervals, harness-vs-model comparisons, energy per run
- **LLM security** — prompt-injection defenses (OWASP LLM01), credential confinement, least-privilege tool exposure
- **Engineering** — Python, FastAPI, OpenTelemetry, pytest, GitHub Actions · ISTQB CTFL v4

#### Featured

**[viriato-bench](https://github.com/CarlosAndreFerreira/viriato-bench)** — How much agentic coding moves from a frontier API to a local 27B model on a mini-PC (AMD Strix Halo)?
Same harness, code-verified correctness: Claude 9/9 vs local Qwen 0/9 on the spec-driven tasks (Fisher p = 0.00002); in lighter harnesses the local model reaches 9/12 clean passes. Energy measured per run.

**[moodle-obsidian-mcp](https://github.com/CarlosAndreFerreira/moodle-obsidian-mcp)** — MCP server for Moodle, built for untrusted content.
Read-only by default, hidden-text stripping before content reaches the model, user confirmation via MCP elicitation for every write, token never sent off the configured host, SSO login through a signed one-time passport. 32 tools, CI on Linux/macOS/Windows.

#### Research

- *Agentic AI for Root Cause Analysis in Cybersecurity Incident Response* (CIRA-MAS) — full paper, **CENTERIS 2026**

#### Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-carlos--andre--ferreira--ai.netlify.app-000000?style=flat-square&logo=netlify)](https://carlos-andre-ferreira-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-carlos--andré--ferreira-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/carlos-andr%C3%A9-ferreira-8367a912a/)
