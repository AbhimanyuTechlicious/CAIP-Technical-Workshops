<a id="rapid-prototyping"></a>

## 18. ⚡ Rapid Prototyping

<a id="rapid-prototyping-assets"></a>

### 18.1 Rapid Prototyping Assets

Sellers have a spectrum of rapid-prototyping assets to choose from:

1. **Solution Accelerators** — Reusable, tested, and GBB/engineering-recommended code components that can be quickly integrated.
2. **Hands-on Labs** — Step-by-step walkthrough of relevant scenarios for customers to get hands-on experience.
3. **GitHub Repos** — A wide choice of ready-to-use GitHub code repositories to fast-track custom prototype creation.
4. **Sample Prototype – Test Drive** — Learn via an actual test drive how to easily provide simple prompts to arrive at a sample prototype package.
5. **Sample Prototype Package** — Download a sample package pre-created for an example business scenario.
6. **Prototyping using Cora** — After test drive and sample prototype package review, sellers work live with **Cora (AI agent)** to get their custom prototype.

   ![RP-2](Assests-unified/RP-2.png)

**Site:** [https://aka.ms/AmplifyTechWorkshops](https://aka.ms/AmplifyTechWorkshops)

<a id="whiteboarding-experience"></a>

### 18.2 Whiteboarding Experience

**Cloud & AI Platform Whiteboard Experiences for the Sellers**

- A single site for Solution Engineers, GBBs, and Specialists with Microsoft Whiteboard templates for the top CAIP reference architectures across 3 solution plays.
- Customer-facing whiteboards curated from GBBs, Engineering, the Gold Standard Accelerators team, the Azure Architecture site, SEs, and partners.
- During business and technical envisioning, sellers collaborate with customers and partners to design tailored architectures for specific scenarios.
- Sellers can export these architectures and use Whiteboard Copilot or VS Code to create deployable ARM/Bicep templates for rapid pilots/POCs.

  ![WB-63](Assests-unified/WB-63.png)

**Where is it?** [https://aka.ms/CAIPWhiteboards](https://aka.ms/CAIPWhiteboards)

**The four-stage whiteboarding journey:**

| Stage | Owner | Steps |
|---|---|---|
| **Positioning Session** | Account Executive / ATS | The account team works with customer leadership to understand business context and position business and technical envisioning. Outcomes include an envisioning charter and internal alignment. Details are in the CAIP Envisioning Reference guide. |
| **Whiteboard-Enabled Business Envisioning** | Specialist | The Cloud & AI specialist gains commitment from the customer for the workshop and facilitates a ~90-minute session with business and IT stakeholders. Whiteboard templates map current pain points, brainstorm future-state ideas, and prioritize 3–5 high-value business scenarios. Relevant SEs may be included. |
| **Whiteboard-Enabled Assessment** | SE | For each chosen priority scenario, the team conducts in-depth assessments to recommend the best-fit solution. Whiteboards enable data collection & tooling, interviews/workshops, gap analysis, and solution options. Outcomes include an Assessment Report & Recommendations and Business Case updates. |
| **Co-Design Technical Solution Architecture & Phased Plan** | SE | SEs leverage info from business envisioning and assessments for technical requirements & gap analysis, co-design solution architecture, and develop a phased implementation plan. Outcomes include the future-state architecture diagram (via updated whiteboards), an implementation roadmap, solution design documentation, an action plan/overview, and exec buy-off. Sellers can export whiteboards and upload them into VS Code for Bicep/ARM templates for rapid pilots/POCs — outcome includes "project go ahead" from the customer. |

**Now available for Sellers: Technical Envisioning Whiteboard OLT** — see [5.2](#caip-site-overview) above ([aka.ms/DREAMwhiteboards](https://aka.ms/DREAMwhiteboards)).

**Whiteboard templates referenced in the deck:**
- *Whiteboard Template for Microsoft IQ Solution Accelerator: Business-to-AI Solution Design* — an icebreaker space, business-envisioning canvas, technical-envisioning workshop canvas, icon palette, and reference/future-state architecture panels, all pre-built for the Microsoft IQ accelerator conversation.
- *Whiteboard Template: Designing AI-Powered Solutions with Fabric IQ, Foundry IQ & Work IQ* — an "Agentic Graphs" whiteboard walking through current-state architecture, technical-envisioning discovery, the agentic 3IQ story, and the future-state proposed architecture.



<a id="hands-on-labs-walkthrough"></a>

### 18.3 🧪 Hands-On Labs Walkthrough

**Building intelligent solutions with Microsoft IQ — Fabric IQ · Foundry IQ · Work IQ**

- **3 hands-on labs**, **90 minutes each**
- **Self-paced & instructor-led**
- Delivered via **MCAPS Academy**

  ![WB-62](Assests-unified/mcaps1.png)

#### 18.3.1 Program Overview — Three Labs, One Intelligence Journey

Progress from data to agents to action — each lab builds on the last:

| Lab | Focus | Description |
|---|---|---|
| **Lab One — Fabric IQ** | Turn raw enterprise data into trusted, business-aware insights | A governed, end-to-end intelligence layer. |
| **Lab Two — Foundry IQ** | Ground agents in enterprise knowledge and governance | Evolve from insight to intelligence to action. |
| **Lab Three — Work IQ** | Orchestrate multi-agent automation across Microsoft 365 | Turn work context into coordinated action. |

> **Fabric IQ → Foundry IQ → Work IQ**
> *trusted data → grounded agents → coordinated action*

#### 18.3.2 🚀 Master Launch Sequence (all labs)

1. Select the lab link.
2. Log in with your Entra ID.
3. Select the lab launch link.
4. Refresh if the Start button is missing.
5. Select "Start" or "Continue".
6. Select "Start" by the MCAPS Academy logo.
7. Wait a few minutes while it launches.
8. **Begin** — add your lab username and begin building your lab.

> Facilitator tip: the goal is not to perfect every click. The goal is to help participants connect each step to a real business problem.

#### 18.3.3 📊 Lab One · Fabric IQ — An End-to-End Intelligence Layer

**Duration:** 90 minutes\
**Direct link:** [Microsoft Fabric IQ Hands-on Lab](https://aka.ms/fabriciqlab)\
**Raw code blueprints:** [Fabric IQ GitHub Repository](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/FabricIQ/Lab/Lab%20Building%20Fabric%20IQ)

Fabric IQ serves as an **end-to-end intelligence layer** within Microsoft Fabric, transforming raw enterprise data into trusted, business-aware insights. By the end you'll have a fully integrated environment combining data engineering, real-time analytics, and semantic modeling.

**You'll be able to:**
- Establish a governed data foundation in **OneLake**.
- Ingest batch, historical & streaming data — **Lakehouse + Eventhouse**.
- Define entities & relationships via a **Fabric IQ ontology**.
- Apply real-time signals to enrich business context.
- Enable natural-language interaction via **Fabric Data Agents**.

> **Eva, Data Engineer · Zava:** *"Before developing Fabric IQ capabilities, I need a governed workspace where data, analytics, and AI artifacts are stored securely — the foundation to connect Zava's data, manage access, and support the intelligence layer we'll build next."*

**Exercises:**
1. Create a workspace for Fabric IQ
2. Generate ontology data
3. Create ontology
4. Create a data agent with ontology
5. Create operation agent

**Recap — what you did & achieved:**
- Created a governed Fabric workspace
- Generated & modeled ontology data
- Built a data agent on the ontology
- Added an operation agent

*Achievement:* Fabric IQ acts as an end-to-end intelligence layer, transforming fragmented enterprise data into trusted, business-aware insights through a unified platform.

Related preview: *Three-minute preview video about IQ Labs with AI Virtual Proctor.*

#### 18.3.4 📚 Lab Two · Foundry IQ — From Insight to Intelligence to Action

**Duration:** 90 minutes\
**Direct link:** [Microsoft Foundry IQ Hands-on Lab](https://aka.ms/foundryiqlab)\
**Raw code blueprints:** [Foundry IQ GitHub Repository](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/FoundryIQ/Lab/Lab%20Building%20Foundry%20IQ)

Foundry IQ enables a single, end-to-end intelligence layer that turns enterprise signals into trusted, business-aware AI actions. Using the **Zava Retail** scenario, you'll see a business evolve from fragmented understanding into a **Frontier Organization** — human-led and AI-operated.

**You'll be able to:**
- Establish a shared business language for AI.
- Ground agent reasoning in enterprise knowledge & governance.
- Enable safe, collaborative, multi-agent execution.
- Shift from **insight → intelligence → action**.

> **Miguel, AI Engineer / Data Scientist:** *"Before designing agents that can reason and act, the foundation must be secure, governed, and scalable. I'll provision the Foundry environment, configure the Agent Service, and deploy the foundational models agents use — ensuring every agent is observable, auditable, and secure."*

**Exercises:**
1. Build the Foundry IQ intelligence foundation
2. Provision the AI Foundry foundation
3. Integrate enterprise knowledge via Foundry IQ
4. Build intelligent agents
5. Enable multi-agent orchestration & validation
6. Structure observability, evaluation & guardrails

**Recap — what you did & achieved:**
- Provisioned the AI Foundry foundation
- Integrated enterprise knowledge via Foundry IQ
- Built intelligent agents
- Enabled multi-agent orchestration & guardrails

*Achievement:* A comprehensive journey from foundational setup to advanced AI orchestration and governance — building, integrating, and managing enterprise intelligence with Fabric and Foundry IQ, with business alignment and responsible AI practices.

Related preview: *Three-minute preview video about IQ Labs with AI Virtual Proctor.*

#### 18.3.5 ⚙️ Lab Three · Work IQ — Intelligent Automation Across Microsoft 365

**Duration:** 90 minutes\
**Direct link:** [Building Intelligent Solutions with Microsoft Work IQ — Hands-on Lab](https://aka.ms/workiqlab)\
**Raw code blueprints:** [Work IQ GitHub Repository](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/WorkIQ/Lab/Lab%20Building%20Work%20IQ)

Build and orchestrate intelligent automation for a retail business with **Work IQ and Fabric**. Using the **Zava Retail** scenario, you'll design a multi-agent workflow, publish it as an app, and simulate a team member going on sick leave — then validate the automation across email, calendar, and documents.

This lab shows how Work IQ helps turn operational disruptions into coordinated actions within Microsoft 365. Zava, which runs both retail stores and e-commerce operations, faces common challenges like delayed responses, manual coordination, limited visibility, slow approvals, and disconnected workflows. With Work IQ, these challenges are addressed by unifying context, automating coordination, and streamlining approvals and execution.

**You'll see how AI agents:**
- **Detect risks** using Fabric IQ data.
- **Recommend actions** using Foundry IQ intelligence.
- **Execute workflows** using Work IQ automation.
- **Learn policies** for future prevention.

> **Ashley, Store Manager · Zava:** *"When a key team member is unavailable, the challenge isn't only knowing that work needs to be reassigned. The system also needs to understand responsibilities, dependencies, approvals, and service-level impact before taking action."*

In the scenario, Ashley uses Work IQ to handle an unexpected absence: the system analyzes impact, recommends actions, and drives execution across Microsoft 365 — reducing manual effort and improving operational efficiency.

**Exercises:**
1. Build the Work IQ foundation
2. Build intelligent agents
3. Build workflow for multi-agent orchestration
4. Execute the end-to-end Retail IQ scenario

**Recap — what you did & achieved:**
- Built the Work IQ foundation & agents
- Orchestrated a multi-agent workflow
- Published the workflow as an app
- Executed the end-to-end sick-leave scenario

*Achievement:* An end-to-end multi-agent workflow combining Fabric data, Foundry IQ knowledge, and Microsoft 365 actions (Outlook, Teams, OneDrive) via Work IQ — detecting stockout risk, assessing impact, scheduling coverage, notifying stakeholders, and capturing a reusable SOP, all through one conversational interface.

> **Microsoft IQ: trusted data → grounded agents → coordinated action.**

<a id="solution-accelerators"></a>

### 18.4 🏗️ Solution Accelerators

#### 18.4.1 Microsoft IQ Accelerator — Intro

**Scenario:** Zava, a global consumer goods company, manages a complex network of distribution centers, stores, and suppliers to maintain on-shelf availability and protect revenue amid changing demand. When a supplier disruption occurs, **Ruza**, a Supply Chain Manager, must quickly understand what is at risk, evaluate feasible sourcing options, and determine how to respond before downstream impact spreads across the business.

Using a **unified intelligence ecosystem**, Ruza moves from early disruption signals to impact assessment and coordinated action, bringing together business data, supplier constraints, and execution workflows in one shared context. This ensures customers and sales are not affected, and revenues are not disrupted.

#### 18.4.2 User Journey

**Ruza Antunovic, Supply Chain Manager** manages supply continuity and needs early disruption signals to keep operations running and prevent downstream delays:

1. **Detect disruption** — Receives a supplier email indicating a potential supply disruption.
2. **Review impact** — Opens the Agent in Teams to confirm the disruption and assess what's at risk.
3. **Validate demand and inventory** — Reviews customer demand and inventory levels across distribution centers.
4. **Assess supplier feasibility** — Evaluates alternative suppliers, contract terms, and lead times to determine feasible production ramp options.
5. **Evaluate sourcing options** — Evaluates feasible supplier options based on demand, inventory, and constraints.
6. **Coordinate and execute** — Confirms the recommended approach with stakeholders and proceeds with updated sourcing and replenishment decisions.

Ruza quickly assesses impact and updates sourcing and replenishment plans that protect availability and meet demand.

#### 18.4.3 Architecture

The accelerator architecture connects three platforms:

- **Microsoft Fabric** — Supply Chain Dashboard + Fabric Data Agent, drawing on a Fabric Lakehouse and **Fabric IQ** ontology, fed by Inventory Data, Product Data, Demand Forecast, and Supplier Data — all unified via **OneLake**.
- **Microsoft 365 Copilot** — Copilot Studio hosts the Supply Chain Agent and Agent Flows, which connect to **Work IQ** (Chats, Meetings, Emails, Documents, and more), including a **Supplier Disruption Event** trigger.
- **Microsoft Foundry** — Agent Orchestration via the Agent Framework hosts a Supplier Terms Agent, backed by **Foundry IQ**, Azure OpenAI, and Agent Service — drawing on Supplier Terms stored in Azure Storage.

#### 18.4.4 Key Features

| Feature | Description | Powered By |
|---|---|---|
| **Role-aware signal detection** | Work IQ monitors role-aware signals across emails, chats, meetings, and operational activity to detect early signs of disruption, surfacing what matters to the right people at the right time. | Work IQ |
| **Enable early data readiness** | Fabric IQ unifies inventory, product, demand forecast, and supplier data in OneLake using a shared semantic model and ontology to surface early disruption signals from governed data. | Fabric IQ |
| **Assess impact consistently** | Fabric IQ enables consistent impact assessment across suppliers, products, and distribution centers, so teams can understand what's at risk before decisions are made. | Fabric IQ |
| **Reason through feasible options** | Foundry IQ retrieves and reasons over supplier contracts, SLAs, lead times, policies, and historical performance to evaluate feasible sourcing and replanning paths. | Foundry IQ |
| **Execute decisions in workflow** | A supply-chain agent, orchestrated through Copilot Studio, coordinates sub-agents, people, and workflows across Microsoft 365 to validate disruptions, align stakeholders, and act. | Work IQ |

#### 18.4.5 GitHub Repository

**Solution overview:** *"The Microsoft IQ Solution Accelerator is an AI-powered enterprise intelligence accelerator that enables faster, more informed decisions by unifying enterprise data, business knowledge, and execution workflows into a shared context. It connects unified data, semantic models and ontologies in Fabric IQ, enterprise knowledge and retrieval in Foundry IQ, and work context in Work IQ to identify signals, assess impact, and recommend disruption mitigation, supporting human decision-making and coordinated responses."*

**Key use cases and customization:**
- **Supply Chain Use Case** — During supplier disruptions, teams assess risk and inventory, evaluate sourcing options, and coordinate actions to protect product availability and continuity of supply.
- **Reusability and Customization** — The architecture can be adapted for other business scenarios (see the "How to customize" guidance in the repo README).

This is a ready-to-deploy solution accelerator built on **Microsoft 365 Copilot, Microsoft Foundry, and Microsoft Fabric**, combining Work IQ, Foundry IQ, and Fabric IQ to support end-to-end disruption detection, analysis, and response.

Access the GitHub repository to deploy this solution accelerator: **GitHub Repo** *(hyperlink embedded in the source slide — locate via the [Microsoft IQ solution accelerator GitHub](https://github.com/microsoft/microsoft-iq-solution-accelerator) org, or through the [CAIP Technical Workshops site](https://aka.ms/AmplifyTechWorkshops) → Rapid Prototyping Assets → Solution Accelerator(s); confirm the exact repo URL before sharing externally).* The repo README includes sections for **Solution Overview**, **Quick Deploy**, **Business Scenario**, and **Supporting Documentation**.

<a id="github-repos-quick-access"></a>

### 18.5 🗂️ GitHub Repos — Quick Access

Quick access links for Fabric IQ, Foundry IQ, Work IQ, and the integrated Microsoft IQ GitHub repos:

| Repo | Focus | Link |
|---|---|---|
| **Fabric IQ** | Business data, semantic models, and ontology (`FabricIQ / Lab Building Fabric IQ`) | [Open repo](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/FabricIQ/Lab/Lab%20Building%20Fabric%20IQ) |
| **Foundry IQ** | Grounded reasoning, knowledge, and agents (`FoundryIQ / Lab Building Foundry IQ`) | [Open repo](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/FoundryIQ/Lab/Lab%20Building%20Foundry%20IQ) |
| **Work IQ** | Work context and collaboration workflows (`WorkIQ / Lab Building Work IQ`) | [Open repo](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/WorkIQ/Lab/Lab%20Building%20Work%20IQ) |
| **Microsoft IQ (combined)** | Fabric IQ, Foundry IQ, and Work IQ together (`FabricIQ-FoundryIQ-WorkIQ / Lab`) | [Open repo](https://github.com/TechExperiences/Microsoft-Fabric-and-Foundry-IQ-v2/tree/FabricIQ-FoundryIQ-WorkIQ/Lab) |

Use these links for hands-on lab access and workshop navigation — they map directly to the **Git hub Repos** section of the CAIP site's **Amplify Your Intelligence → Rapid Prototyping Assets** menu.

---