<a id="deep-dive-work-iq"></a>

## 11. ⚙️ Deep Dive: Work IQ

*"How your employees work."* 

Reference: [aka.ms/WorkIQ](https://aka.ms/WorkIQ)

### 11.1 What It Is

**Work IQ** is workplace intelligence designed for the unique needs of agents:

- **Optimized for Agentic Use** — Designed for high-volume agent reasoning and tool-calling with speed, efficiency, and scale.
- **Comprehensive** — Continuously structures high-quality context across your data for more intelligent, up-to-date results.
- **Secure** — Operates directly on enterprise data in place, preserving existing security and governance policies.

### 11.2 The Work IQ API

Workplace intelligence designed for the unique needs of agents:

| Dimension | Description |
|---|---|
| **Intelligence** | Continuously builds and structures high-quality context across your entire data estate. |
| **Speed** | Agent-optimized retrieval that enables fewer round trips to the service and lower latency access to rich context. |
| **Efficiency** | Handles retrieval, context assembly, and reasoning in a unified runtime rather than with iterative, token-intensive reassembly. |
| **Scale** | Designed to support the scale of agentic workloads, including high-volume reasoning and tool-calling. |
| **Security** | Operates directly on enterprise data in place, preserving existing security and governance policies. |

**Reported benchmarks** *(internal Microsoft data / testing)*:
- **600+ TB** average data footprint of Work IQ within Fortune 500 orgs *(Internal Microsoft data, May 2026)*
- **2x output** per second of run time using Work IQ APIs vs. traditional APIs *(Internal testing across 20 scenarios using a leading coding harness, May 2026)*
- **80% fewer tokens** used by coding harnesses when using Work IQ APIs instead of traditional APIs *(Internal testing across 20 scenarios using a leading coding harness, May 2026)*
- **10x year-over-year growth** in requests to Microsoft 365 driven by agents *(Internal Microsoft data, April 2025 – April 2026)*

### 11.3 Work IQ API Components

The Work IQ API sits between **Your Agents** (connected via A2A, MCP, or REST) and **Organizational Intelligence**, exposing four building blocks:

| Component | Description |
|---|---|
| **Chat** | Returns pre-processed responses from Copilot and agents, giving programmatic access to the full Copilot experience. |
| **Context** | Returns data and context in agent-ready formats to process with your own agent orchestration. |
| **Tools** | Provide agentic access to Microsoft 365 entities and actions efficiently at scale. |
| **Workspaces** | Offer working environments for agentic reasoning and problem solving within your Microsoft 365 tenant trust boundary. |

### 11.4 The Difference Work IQ Delivers

Work IQ shines when work depends on **context, decisions, people, and time** — not just documents:

1. **Understand real work, not just documents** — where a generic RAG system would struggle or give vague answers. *Example prompt: "What decisions did we make about MCP adoption, and where were they discussed?"*
2. **Durable context over time** — improves an agent's memory and reasoning across user history. *Example prompt: "Remind me what we concluded last time we debated REST vs A2A for Work IQ."*
3. **Organizational & people context** — agents behave like teammates, not search engines. *Example prompt: "Who should be looped in before we finalize the developer story?"*
4. **End-to-end impact** — pulling from multiple sources, applying enterprise guardrails, and producing ready-to-use artifacts. *Example prompt: "Turn this discussion into a customer-safe FAQ."*

### 11.5 Real-World Examples — Powering Apps and Agents at Frontier Firms

| Organization | Use Case | Description |
|---|---|---|
| **Energy company** | Operational assessments | Integrating subsurface data with M365 context for secure, cross-platform agent workflows. |
| **Leading edge device OEM** | Device experiences | Enables users to interact with documents directly on the device with capabilities like summarization, translation, and smart file naming. |
| **Project management tool** | Context for collaboration | Enabling AI features to operate on live organizational data and enhance team workflows. |

### 11.6 Any Framework, Any Runtime

Three GA protocols and just-in-time skills give every agent the same intelligence — on the surface that fits its runtime:

| Endpoint | Description |
|---|---|
| **A2A** | Agents delegate work to Copilot as a peer and receive grounded, governed results. |
| **MCP** | Remote MCP server for hosted agents that need to call Work IQ as tools. |
| **REST** | For web, device, and service-hosted applications. |

**First-party platforms:**
- **Copilot Studio** — Low-code agents for business users with Work IQ context built in.
- **Microsoft Foundry** — Production-grade AI applications with full SDK access.
- **GitHub Copilot** — Surface Work IQ context directly inside developer coding workflows.

**Protocol strategy:**

| Scenario | Protocol |
|---|---|
| Build intelligence into a mobile or web app *(e.g., a web app sends a question to Work IQ and renders the reply)* | REST |
| Agent collaboration *(e.g., an Ops agent asks Work IQ to investigate a regression)* | A2A |
| IDE, CLI, and platform integration scenarios *(e.g., a user asks Copilot a question and it calls Work IQ to answer)* | MCP |

---