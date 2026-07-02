# Guadalupe Higuera

**Software Engineer — GenAI Platform & Agentic AI**

I build production LLM systems: agent platforms, RAG pipelines, and the orchestration, evaluation, and observability infrastructure that keeps them reliable at scale.

At Wells Fargo I helped build a production agentic-AI platform from inception — now serving **10,000+ users across 6 business use cases** spanning policy, finance, and investments — including the agent-configuration and orchestration APIs behind a self-serve system that lets non-technical users create, modify, and deploy their own agents without engineering involvement.

---

### What I work on

- **Agentic AI** — agent configuration, orchestration, and tool/function-calling; self-serve platforms for non-technical users; human-in-the-loop controls and guardrails
- **RAG & retrieval** — vector search, chunking strategy, contradiction/consistency detection, LLM-as-judge evaluation
- **LLM infrastructure** — orchestration (Semantic Kernel, Bedrock Agents), QLoRA fine-tuning, LLMOps, observability, self-healing deployments
- **Cloud** — AWS (Bedrock, Lambda, DynamoDB, API Gateway, S3, IAM), Terraform, CI/CD

---

### Featured projects

**iRacing AI Race Strategist** — [repo](https://github.com/LupeHiguera/iRacing_Ai_PitCrewChief) · [demo](https://www.youtube.com/watch?v=15d633gyyfY)
Fine-tuned Llama 3.1 8B (QLoRA) on 9,269 synthetic examples. Built a 12-metric weighted evaluation harness plus LLM-as-judge blind A/B comparison; eval scores improved **29.7 → 78.5** and hallucinations dropped from **48/55 cases to 0/55**. Event-driven LLM orchestration with priority-based dispatch, per-event cooldowns, and state-machine transitions — replacing naive per-tick inference.

**Titanic Historical RAG — Contradiction Detection** — [repo](https://github.com/LupeHiguera/Titanic_RAG) · [live](https://titanic.higuera.io/)
RAG system over 3,300+ pages of testimony (**40K chunks across 68 witnesses**) that surfaces contradictions *between* witnesses instead of collapsing them. Pairwise LLM-as-judge comparison with structured JSON output, 0–1 confidence scoring, and pluggable caching to cut inference cost.

**AWS Bedrock Agentic Shopping Assistant** — [repo](https://github.com/LupeHiguera/Natural_Language_Shopping_Agent) · [live](https://shop.higuera.io/)
Autonomous shopping agent with custom action groups for natural-language search and tool-calling. Full infrastructure provisioned with Terraform: DynamoDB, Lambda, API Gateway, S3, IAM.

---

### Stack

**Languages** Python · C# / ASP.NET Core · TypeScript / React · SQL
**GenAI/LLM** LLM orchestration · RAG · QLoRA · Vector DBs (Pinecone, ChromaDB) · Hugging Face · LLM evaluation & LLM-as-judge · MCP
**Cloud & infra** AWS Bedrock · Lambda · DynamoDB · API Gateway · S3 · IAM · Terraform · OpenShift · CI/CD · LLMOps
**Testing & monitoring** Playwright · Splunk · LLM observability

---

### Currently

- M.S. in Computer Science @ Arizona State University
- Going deeper on agent evaluation, MCP tooling, and LLMOps

📫 [LinkedIn](www.linkedin.com/in/guadalupe-higuera) · [Personal site](https://higuera.io/) · Guadalupe.Higuera@protonmail.com
