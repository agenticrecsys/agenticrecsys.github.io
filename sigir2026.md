---
layout: home
title: Multi-Agentic Recommender Systems — SIGIR 2026
permalink: /sigir2026/
description: "SIGIR 2026 tutorial on multi-agentic recommender systems — foundations, perspectives, and lessons from large-scale deployments."
eyebrow: "SIGIR 2026 · Melbourne · Tutorial"
hero_title: "Multi-Agentic<br>Recommender Systems"
hero_subtitle: "Foundations, Perspectives, and Lessons from Large Scale Deployments"
hero_lede: "Bridging <strong>information retrieval</strong>, <strong>recommender systems</strong>, and <strong>large-scale industrial practice</strong> — foundational concepts, reusable design patterns, and lessons learned from deploying agentic and multi-agent recommenders at scale."
hero_meta:
  - label: "When"
    value: "Mon 20 Jul 2026"
  - label: "Where"
    value: "Melbourne, Australia"
  - label: "Length"
    value: "~3 hours · half-day"
nav:
  - label: "About"
    href: "#about"
  - label: "Outline"
    href: "#outline"
  - label: "Presenters"
    href: "#presenters"
  - label: "Materials"
    href: "#materials"
  - label: "RecSys 2025 edition →"
    href: "/recsys2025/"
footer_citation: "10.1145/3805712.3808643"
footer_support: "Walmart Global Tech · Google DeepMind · Polytechnic University of Bari · AG2AI"
---

> **SIGIR 2026 edition.** This is the SIGIR 2026 edition of the tutorial. See also the [RecSys 2025 edition]({{ '/recsys2025/' | relative_url }}).

## When & where
{: #logistics }

| Detail | Information |
| ------------------------ | ------------------------------------------------------------ |
| **Conference**           | SIGIR 2026 — 49th International ACM SIGIR Conference          |
| **Date**                 | Monday, 20 July 2026                                         |
| **Location**             | Melbourne Convention and Exhibition Centre, Melbourne, Australia |
| **Room & session time**  | <span class="tbd">TBD</span> — to be confirmed in the final program |
| **Official listing**     | [SIGIR 2026 accepted tutorials](https://sigir2026.org/en-AU/pages/program/accepted-tutorials) |

## About the tutorial
{: #about }

This tutorial covers **multi-agentic recommender systems** — recommender systems augmented with **large language models (LLMs)** and **multi-agent orchestration** to enable multi-step reasoning, tool use, and interactive decision-making. It emphasizes **foundational concepts**, **reusable design patterns**, and **practical lessons learned from large-scale e-commerce deployments**.

We begin with background and recent trends in generative recommender systems and their connection to agentic approaches. We then survey major deployment areas in industry and review the agent-orchestration frameworks developed to support them. Finally, we present a project walkthrough that traces the full lifecycle of an agentic recommender system — from scoping and data definition through modeling, deployment, and monitoring — to provide actionable deployment insights.

The tutorial bridges perspectives from **information retrieval (IR)**, **recommender systems (RecSys)**, and **large-scale industrial practice**, and aims to equip attendees with actionable insights on how these paradigms shape the design of next-generation IR and RecSys user-facing deployments.

## What we'll cover

The tutorial runs from foundations through to practice, drawing on what we've learned building and deploying these systems at scale. In particular:

* The move from **generative to agentic recsys** — with working definitions, levels of agent autonomy, and a survey of the key work in the area.
* **Four major use cases** for agents in recommendation, drawn from real search and personalization deployments, plus a look at the current agentic-recsys startups.
* **Memory for agents** — ontology-driven memory, and retrieving from long, tool-heavy trajectories without being derailed by context noise.
* Keeping **self-improving evolution agents** from high variance and loops, and getting **feature-engineering agents** to describe items consistently.
* **Harness- and RL-based design** that specifies the "what" rather than the "how," and the practical side of putting agentic recsys into production.
* From open-source multi-agent frameworks to a **single personal agent** — one kernel adapting into many roles, coordinating a growing fleet across many owners, and a **six-axis framework** for characterizing agents.
* **Evaluation metrics** for agentic pipelines used in industry, with sample code where time allows.

## Tutorial outline
{: #outline }

A half-day tutorial (**≈3 hours**, including a break and interactive components), organized into five modules (A–E).

### A. Introduction and Background — 15 min

* Core properties of modern RecSys: accuracy, policy alignment, context awareness, and scalability (cost efficiency, development-time efficiency).
* A temporal view of how evolving LLM-oriented techniques address — or fail to address — these goals (vanilla prompting, chain of thought, self-refine, prompt chaining, single-agent frameworks, multi-agent frameworks).
* A motivating scenario (e.g., a personalized birthday planner) illustrating multi-step, autonomous workflows.

### B. Alphabets of Multi-Agentic AI — 45 min

* **Memory moderation & retrieval:** memory types and how/when to retrieve them.
* **Function calling & tool usage:** extending LLM pipelines with external APIs, databases, and knowledge bases.
* **Model context protocols:** standardizing orchestration.
* **Reasoning load balancing:** splitting complex tasks into manageable segments for efficient model usage; mainstream industrial orchestrations.
* **Revisiting the running example:** system design and how it improves using the components above.

### C. Industrial Agentic RecSys Implementations — 60 min

* Prominent tasks and design patterns:
  * (i) Conversational recommendation
  * (ii) Context-aware autonomous recommendation
  * (iii) Recommendation evaluation and user-behavior simulation
  * (iv) Explanation generation
* Best practices for large-scale agentic pipelines: standards, pitfalls, and optimization.

### D. Agentic Deployment Walkthrough — 30–45 min

* Overview of open-source and industrial frameworks (e.g., AG2).
* A walkthrough of the productionization steps for a multi-step recommendation scenario (e.g., a "Personalized Birthday Planner"):
  * Scoping and data definition
  * System components
  * System and architecture design
  * Initial implementation
  * Debugging and failure-point diagnosis
  * Monitoring and drift analysis

### E. Challenges & Future of Agentic AI for RecSys — 15 min

* Common issues: communication complexity and protocols, scalability, hallucinations, error propagation, fairness, and bias.
* Privacy, fairness, and unintended-behavior concerns, with possible mitigation strategies.
* Future directions: multi-agent synergy, advanced memory systems, and self-improving agentic systems.

## What you'll learn

By the end of the tutorial, attendees will be able to:

* **Define and differentiate** (i) LLM-based recommenders, (ii) tool-augmented LLM pipelines, (iii) single-agent recommenders, and (iv) multi-agentic recommender systems.
* **Understand the core building blocks** — memory types and retrieval, tool/function calling, planning, role specialization, orchestration protocols, and critique/refinement loops.
* **Apply design patterns** to common RecSys/IR tasks: conversational recommendation, context-aware autonomous recommendation, explanation generation, and evaluation via simulation.
* **Recognize practical pitfalls** (hallucinations, error propagation, agent miscoordination, cost/latency blowups, privacy/fairness issues) and mitigation strategies.
* **Understand the production aspects** of deploying agentic systems across scoping, data definition, modeling and design, deployment, and drift monitoring.

## Presenters
{: #presenters }

| Presenter                 | Affiliation                            |
| ------------------------- | -------------------------------------- |
| **Reza Yousefi Maragheh** | Walmart Global Tech                    |
| **Yashar Deldjoo**        | Polytechnic University of Bari         |
| **Benjamin Coleman**      | Google DeepMind                        |
| **Jason Cho**             | Walmart Global Tech                    |
| **Chi Wang**              | AG2AI                                  |

Full presenter bios: <span class="tbd">TBD</span>.

## Who this is for
{: #audience }

This tutorial targets SIGIR attendees working on IR, recommendation, and LLM/agentic systems; familiarity with basic RecSys/IR concepts is assumed. It is well suited for:

* **Researchers and PhD students** exploring agentic and multi-agent systems for recommendation and retrieval.
* **Senior researchers and practitioners** working with generative / LLM-based RecSys and IR.
* **Industry teams** looking for practical patterns and lessons to move from prototypes to reliable, large-scale deployments.

## Format and duration
{: #format }

* **Format:** Half-day tutorial with a break and interactive components.
* **Duration:** Approximately **3 hours**, organized into five modules (A–E).
* **Prerequisites:** Familiarity with basic RecSys/IR concepts.
* **Relevance to SIGIR:** Modern user experiences increasingly merge IR and recommendation in interactive workflows (search, browse, compare, refine constraints, decide). Agentic systems provide a concrete systems lens connecting retrieval/ranking, RAG, conversational interfaces, and recommendation under a unified interactive paradigm.

## Materials
{: #materials }

* **Slides / materials:** <span class="tbd">TBD</span> — <span class="link-disabled">Slides (PDF)</span> will be posted here after the tutorial. *(Link to be added.)*
* **Supplementary material** *(planned)*: sample pseudocode for the different stages of productionizing a use case; example prompts, agent-role templates, and orchestration skeletons; and, where feasible, small toy datasets or public data excerpts suitable for demonstration.
* **Curated reading list** *(planned)*: a survey plus representative papers to help attendees continue learning after the tutorial.

The accompanying material for the tutorial series can be found at [agenticrecsys.github.io]({{ '/' | relative_url }}).

## Citation

If you find this tutorial useful in your research or work, feel free to cite it:

```bibtex
@inproceedings{yousefimaragheh2026multiagentic,
  title     = {Multi-Agentic Recommender Systems: Foundations, Perspectives, and Lessons from Large Scale Deployments in eCommerce},
  author    = {Yousefi Maragheh, Reza and Deldjoo, Yashar and Coleman, Benjamin and Cho, Jason and Wang, Chi},
  booktitle = {Proceedings of the 49th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR '26)},
  year      = {2026},
  address   = {Melbourne, VIC, Australia},
  publisher = {ACM},
  doi       = {10.1145/3805712.3808643}
}
```


Yousefi Maragheh, R., Deldjoo, Y., Coleman, B., Cho, J., & Wang, C. (2026). Multi-Agentic Recommender Systems: Foundations, Perspectives, and Lessons from Large Scale Deployments in eCommerce. In *Proceedings of the 49th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR '26)*. ACM.
