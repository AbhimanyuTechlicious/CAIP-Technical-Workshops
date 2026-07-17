# Build a Unified, Governed Data and AI Estate — Technical Workshop Execution Guide

> **Audience:** Microsoft Solution Engineers, GBBs, other FTEs, and Partners who deliver this workshop.\
> **Workshop Level:** L300 \
> **Primary Theme:** Bring data, applications, and AI together on **one unified, governed foundation** — built on **Microsoft Fabric**, **Microsoft Foundry**, and the Purview/Entra governance stack.[...]
> **Delivery Model:** Instructor-led, self-paced, or modular customer engagement — eight self-contained scenario-modules, deliverable together or individually

---

## 🌟 Executive Summary & Welcome

**The Opportunity:** Organizations struggle to scale AI due to fragmented data, AI, and governance across disconnected systems — slowing adoption and increasing cost, risk, and complexity.

**How we solve it:** Microsoft brings data, AI, context, and governance together on one foundation — eliminating silos and saving cost: unified scale (OneLake + 200+ connectors, 11,000+ models in Fo[...]

**The Microsoft differentiation:** Microsoft is the only platform providing an end-to-end foundation to become Frontier — unify data in Fabric with 200+ connectors, build and scale agents in Foundry[...]

> **The narrative:** Establish a Unified, Trusted Data and AI Foundation for Your Frontier Transformation.
> *Your AI is only as good as your data. Your AI is only as impactful as your context. Your AI is only as scalable as its trust.*

---

## 🗂️ Table of Contents

1. [Overview for the Sellers](01-overview-for-the-sellers.md)
    - 1.1 [Technical Workshop | xMSFT Definition](./01-overview-for-the-sellers.md#technical-workshop-xmsft-definition)
    - 1.2 [Workshop Deep Dive — Example Technical Workshop](01-overview-for-the-sellers.md#example-technical-workshop)
2. [Unify Tech Workshop Overview](02-unify-tech-workshop-overview.md)
    - 2.1 [A Unified, Governed Data and AI Platform — Customer Conversation](02-unify-tech-workshop-overview.md#a-unified-governed-data-and-ai-platform-customer-conversation)
    - 2.2 [Narrative & Business Metrics](02-unify-tech-workshop-overview.md#narrative-business-metrics)
    - 2.3 [Identifying High-Impact Scenarios](02-unify-tech-workshop-overview.md#identifying-high-impact-scenarios)
    - 2.4 [Workshop Purpose](02-unify-tech-workshop-overview.md#workshop-purpose)
    - 2.5 [One Platform, Not a Collection of Experiences](02-unify-tech-workshop-overview.md#one-platform)
    - 2.6 [The Problem This Workshop Addresses](02-unify-tech-workshop-overview.md#the-problem)
    - 2.7 [How to Frame It for Customers](02-unify-tech-workshop-overview.md#how-to-frame-it)
    - 2.8 [The Workshop at a Glance](02-unify-tech-workshop-overview.md#workshop-at-a-glance)
    - 2.9 [Audience & Pre-Work](02-unify-tech-workshop-overview.md#audience-pre-work)
    - 2.10 [Recommended Audience & Expected Outputs](02-unify-tech-workshop-overview.md#recommended-audience-expected-outputs)
    - 2.11 [The Arc — How the Workshop Unfolds](./02-unify-tech-workshop-overview.md#the-arc)
    - 2.12 [Execution Guidance for the Sellers](02-unify-tech-workshop-overview.md#execution-guidance)
    - 2.13 [Delivering the Session — Suggested Workshop Flow](02-unify-tech-workshop-overview.md#suggested-workshop-flow)
    - 2.14 [Token Spend: Questions to Ask](02-unify-tech-workshop-overview.md#token-spend-questions)
    - 2.15 [Optional Modular Deep-Dive Tracks (A–L)](02-unify-tech-workshop-overview.md#modular-deep-dive-tracks)
    - 2.16 [How to Use This Content](02-unify-tech-workshop-overview.md#how-to-use-this-content)
    - 2.17 [Technical Workshop Modules](02-unify-tech-workshop-overview.md#technical-workshop-modules)
    - 2.18 [Personas & Outcomes](02-unify-tech-workshop-overview.md#personas-outcomes)
3. [Technical Workshops Site Content Overview](03-technical-workshops-site-content-overview.md)
    - 3.1 [CAIP Technical Workshop Site](03-technical-workshops-site-content-overview.md#caip-site)
    - 3.2 [Technical Envisioning Whiteboard OLT](03-technical-workshops-site-content-overview.md#technical-envisioning-whiteboard-olt)
4. [Outcome: Unify Data and Knowledge Estate](04-outcome-unify-data-and-knowledge-estate.md)
    - 4.1 [Scenario 01 — Unify your Data Estate for AI](04-outcome-unify-data-and-knowledge-estate.md#scenario-01)
    - 4.2 [Key Discussion Areas](04-outcome-unify-data-and-knowledge-estate.md#key-discussion-areas)
    - 4.3 [What Good Looks Like](04-outcome-unify-data-and-knowledge-estate.md#what-good-looks-like)
5. [Microsoft Fabric](05-microsoft-fabric.md)
    - 5.1 [The Unified Data Platform for AI Transformation](05-microsoft-fabric.md#fabric-platform)
    - 5.2 [OneLake — Bring All Your Data Together](05-microsoft-fabric.md#onelake-bring-together)
    - 5.3 [Ingest Data into OneLake with Data Factory](05-microsoft-fabric.md#data-factory-ingest)
    - 5.4 [Build a Governed Data Mesh with OneLake](05-microsoft-fabric.md#governed-data-mesh)
    - 5.5 [Open Delta & Iceberg — One Copy for All Computes](05-microsoft-fabric.md#one-copy-computes)
    - 5.6 [Data Warehouse & Databases Built on OneLake](05-microsoft-fabric.md#warehouse-databases)
    - 5.7 [Discover, Govern and Protect Data with OneLake](05-microsoft-fabric.md#discover-govern-and-protect-data-with-onelake)
    - 5.8 [End-to-End Platform Capability Coverage](05-microsoft-fabric.md#capability-coverage)
    - 5.9 [Technical Deep Dives](05-microsoft-fabric.md#technical-deep-dives)
6. [Demos](06-demos.md)
    - 6.1 [Build a Unified Governed Data and AI Platform Demos](06-demos.md#caldova-demo)
    - 6.2 [Additional Interactive Demos (CDX Experiences)](06-demos.md#additional-cdx-demos)
7. [Activities](07-activities.md)
    - 7.1 [Rapid Prototyping](07-activities.md#rapid-prototyping-1)
    - 7.2 [Whiteboarding Experience](07-activities.md#whiteboarding-1)
    - 7.3 [Hands-on Labs — Outcome 1](07-activities.md#hands-on-labs-1)
    - 7.4 [Solution Accelerators — Unified Data Foundation with Fabric](07-activities.md#unified-data-foundation-accelerator)
8. [Outcome: Build a Foundation for Enterprise Intelligence](08-outcome-build-a-foundation-for-enterprise-intelligence.md)
    - 8.1 [Scenario 02 — Build business context your AI can use](08-outcome-build-a-foundation-for-enterprise-intelligence.md#scenario-02)
    - 8.2 [Key Discussion Areas](08-outcome-build-a-foundation-for-enterprise-intelligence.md#scenario-02-discussion)
    - 8.3 [What Good Looks Like](08-outcome-build-a-foundation-for-enterprise-intelligence.md#scenario-02-good)
    - 8.4 [Suggested Workshop Flow](08-outcome-build-a-foundation-for-enterprise-intelligence.md#scenario-02-flow)
    - 8.5 [Optional Modular Deep-Dive Tracks (A–D)](08-outcome-build-a-foundation-for-enterprise-intelligence.md#scenario-02-tracks)
    - 8.6 [Expected Outputs](08-outcome-build-a-foundation-for-enterprise-intelligence.md#scenario-02-outputs)
    - 8.7 [Intelligence + Trust — Microsoft IQ Platform](08-outcome-build-a-foundation-for-enterprise-intelligence.md#microsoft-iq-platform)
    - 8.8 [The Challenge — Why AI Stalls Without Unified Context](08-outcome-build-a-foundation-for-enterprise-intelligence.md#the-challenge)
    - 8.9 [AI Adoption Is Accelerating](08-outcome-build-a-foundation-for-enterprise-intelligence.md#ai-adoption)
    - 8.10 [Essentials for High-Performance Agents](08-outcome-build-a-foundation-for-enterprise-intelligence.md#essentials-agents)
    - 8.11 [What Every Employee and Every Agent Needs to Know](08-outcome-build-a-foundation-for-enterprise-intelligence.md#employee-agent-context)
9. [Fabric IQ](09-fabric-iq.md)
10. [Work IQ](10-work-iq.md)
11. [Web IQ](11-web-iq.md)
12. [Foundry IQ](12-foundry-iq.md)
13. [Demos — Microsoft IQ Demos](13-demos-microsoft-iq-demos.md)
14. [Workshop Activities](14-workshop-activities.md)
    - 14.1 [Rapid Prototyping](14-workshop-activities.md#rapid-prototyping-2)
    - 14.2 [Whiteboarding Experience](14-workshop-activities.md#whiteboarding-2)
15. [Hands on Labs — Microsoft IQ](15-hands-on-labs-microsoft-iq.md)
    - 15.1 [Program Overview — Three Labs, One Intelligence Journey](15-hands-on-labs-microsoft-iq.md#labs-program-overview)
    - 15.2 [Lab One · Fabric IQ](15-hands-on-labs-microsoft-iq.md#lab-one-fabric-iq)
    - 15.3 [Lab Two · Foundry IQ](15-hands-on-labs-microsoft-iq.md#lab-two-foundry-iq)
    - 15.4 [Lab Three · Work IQ](15-hands-on-labs-microsoft-iq.md#lab-three-work-iq)
16. [Solution Accelerator — Microsoft IQ](16-solution-accelerator-microsoft-iq.md)
17. [GitHub Repos](17-github-repos.md)
    - 17.1 [Microsoft IQ GitHub Repos — Quick Access](17-github-repos.md#github-repos-quick-access)
    - 17.2 [Summary: Key Outcomes](17-github-repos.md#summary-key-outcomes)
    - 17.3 [Resources](17-github-repos.md#resources)

---

<table width="100%">
  <tr>
    <td align="right">
      <a href="./01-overview-for-the-sellers.md">Next ➡️</a>
    </td>
  </tr>
</table>
