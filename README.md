# Pedro Henrique Gago de Oliveira

**AI Engineer · Agents, RAG & MCP on production SaaS**

I build the AI layer of a multi-tenant SaaS: the MCP server agents use to reach product data, retrieval over company knowledge, LangGraph pipelines that run with no human in the loop, the context each agent turn receives, and the evals and tracing that make it safe to ship.

Before AI, I spent years building full stack products end to end — funnels, dashboards, multi-role platforms — so I care as much about the product flow as about the model.

🔗 [LinkedIn](https://www.linkedin.com/in/pedrogagodev/) · [Email](mailto:pedrogagodev@gmail.com)

---

## What I work on

### Franchise Frameworks — Full Stack & AI Engineer
- **MCP server** (Fastify) giving LLM agents access to CRM data and the knowledge base through the product API, so every agent runs with the user's permissions and only sees its own tenant
- **Retrieval** over internal docs and decision records, exposed to agents as a single search tool
- **Unattended LangGraph pipeline** turning sales-call transcripts into schema-validated CRM fields, on idempotent background jobs with retries, LangSmith tracing, and Sentry monitoring
- **In-app AI assistant** (in progress): SSE streaming with AG-UI, tool calls over live data, long-term memory, server-side context assembly within a token budget
- **Eval harness** (in progress): replayed scenarios, LLM judge plus deterministic tool-call checks, regressions block the release

### Borderless Coding — Full Stack Lead Engineer
- Brought **AI coding agents** (Claude Code, Codex, Cursor) into the team's workflow, with shared skills, hooks, and project instructions
- Set up a **multi-agent dev loop**: an orchestrator routes tasks to implementer agents, a separate reviewer agent checks each diff, every agent isolated in its own git worktree
- Built internal platforms and **operational dashboards** with full audit logging, enabling traceability and safe rollback
- Replaced manual processes with **automation workflows** across core operations (Next.js, Cloudflare)

---

## Other projects

### DxGen — AI documentation agent
A developer-experience product that keeps documentation up to date without anyone writing it. I built the full stack, including the agent that:
- Reads the repository to understand the project's context
- Generates and updates READMEs, architecture diagrams, and code summaries
- Reviews pull requests and writes mini-docs flagging potential issues

### Guimaps — tourism platform
A platform connecting licensed guides, local partners, and travelers. As Full Stack Engineer I built the guide dashboard, the partner dashboard (venues, bars, event spaces), and the flow where travelers build custom itineraries from tours and partner experiences — three user roles, one coherent workflow.

---

## Stack
**LLM & agents:** LangGraph · LangChain · MCP · RAG · hybrid search · context engineering · memory · multi-agent orchestration · LLM-as-judge evals · AG-UI · Claude & OpenAI APIs  
**Developer tools:** Claude Code · Codex · Cursor · agent skills · hooks  
**Backend & frontend:** TypeScript · Python · Node.js · Fastify · FastAPI · React · Next.js · PostgreSQL · PostGIS · Redis · RabbitMQ · Inngest  
**Cloud & ops:** AWS · Kubernetes · Docker · Cloudflare · Vercel · GitHub Actions · Sentry · LangSmith · PostHog
