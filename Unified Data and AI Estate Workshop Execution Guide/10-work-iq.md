
## 10. Work IQ

*"How your employees work."* 

Reference: [aka.ms/WorkIQ](https://aka.ms/WorkIQ)

**Work IQ — Workplace intelligence designed for the unique needs of agents:**

| Quality | Description |
|---|---|
| **Optimized for Agentic Use** | Designed for high-volume agent reasoning and tool-calling with speed, efficiency, and scale. |
| **Comprehensive** | Continuously structures high-quality context across your data for more intelligent, up-to-date results. |
| **Secure** | Operates directly on enterprise data in place, preserving existing security and governance policies. |

**Work IQ API qualities:**

| Dimension | Description |
|---|---|
| **Intelligence** | Continuously builds and structures high-quality context across your entire data estate. |
| **Speed** | Agent-optimized retrieval that enables fewer round trips to the service and lower-latency access to rich context. |
| **Efficiency** | Handles retrieval, context assembly, and reasoning in a unified runtime rather than with iterative, token-intensive reassembly. |
| **Scale** | Designed to support the scale of agentic workloads, including high-volume reasoning and tool-calling. |
| **Security** | Operates directly on enterprise data in place, preserving existing security and governance policies. |

**Work IQ API components** — sits between **Your Agents** (connected via A2A, MCP, or REST API) and **Organizational Intelligence**:

| Component | Description |
|---|---|
| **Chat** | Returns pre-processed responses from Copilot and agents, giving programmatic access to the full Copilot experience. |
| **Context** | Returns data and context in agent-ready formats to process with your own agent orchestration. |
| **Tools** | Provide agentic access to Microsoft 365 entities and actions efficiently at scale. |
| **Workspaces** | Offer working environments for agentic reasoning and problem solving within your Microsoft 365 tenant trust boundary. |

**The difference Work IQ delivers** — Work IQ shines when work depends on context, decisions, people, and time, not just documents:

| # | Difference | Example Prompt |
|---|---|---|
| 1 | Understands real work, not just documents, where a generic RAG system would struggle or give vague answers. | *"What decisions did we make about MCP adoption, and where were they discussed?"* |
| 2 | Provides responses that show durable context over time to improve an agent's memory and reasoning across user history. | *"Remind me what we concluded last time we debated REST vs. A2A for Work IQ."* |
| 3 | Offers organizational & people context to have agents behave like teammates, not search engines. | *"Who should be looped in before we finalize the developer story?"* |
| 4 | Creates end-to-end impact by pulling from multiple sources, applying enterprise guardrails, and producing ready-to-use artifacts. | *"Turn this discussion into a customer-safe FAQ."* |

**Powering apps and agents at frontier firms (real-world examples):**

| Organization | Use Case | Description |
|---|---|---|
| **Energy company** | Operational assessments | Integrating subsurface data with M365 context for secure, cross-platform agent workflows. |
| **Leading edge device OEM** | Device experiences | Enables users to interact with documents directly on the device with capabilities like summarization, translation, and smart file naming. |
| **Project management tool** | Context for collaboration | Enabling AI features to operate on live organizational data and enhance team workflows. |

**Any framework, any runtime** — three GA protocols and just-in-time skills give every agent the same intelligence:

| Endpoint | Description |
|---|---|
| **A2A** | Agents delegate work to Copilot as a peer and receive grounded, governed results. |
| **MCP** | Remote MCP server for hosted agents that need to call Work IQ as tools. |
| **REST** | For web, device, and service-hosted applications. |

**First-party platforms:** 

- Copilot Studio (low-code agents for business users, Work IQ context built in) · 

- Microsoft Foundry (production-grade AI applications with full SDK access) · 

- GitHub Copilot (surfaces Work IQ context directly inside developer coding workflows).

**Protocol strategy:**

| Scenario | Protocol |
|---|---|
| Build intelligence into a mobile or web app *(e.g., a web app sends a question to Work IQ and renders the reply)* | REST |
| Agent collaboration *(e.g., an Ops agent asks Work IQ to investigate a regression)* | A2A |
| IDE, CLI, and platform integration scenarios *(e.g., a user asks Copilot a question and it calls Work IQ to answer)* | MCP |

---
---

<table width="100%">
  <tr>
    <td align="left">
      <a href="09-fabric-iq.md">⬅️ Previous</a>
    </td>
    <td align="right">
      <a href="11-web-iq.md">Next ➡️</a>
    </td>
  </tr>
</table>
