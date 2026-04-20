---
layout: default
title: Multi-Agentic Recommender Systems
permalink: /
---

# Multi-Agentic Recommender Systems

### Foundations, Design Patterns, and E-Commerce Applications (Industrial Tutorial)

Welcome! This website hosts the materials for the industrial tutorial **“Multi-Agentic Recommender Systems: Foundations, Design Patterns, and E-Commerce Applications.”** The tutorial shares a practical, industry-informed perspective on **LLM-powered agentic and multi-agent frameworks for recommender systems**, with an emphasis on real-world design patterns, orchestration workflows, and deployment considerations.

**Quick links (placeholders):** 

* [Start the tutorial](./tutorial)
* [Agenda](#tutorial-agenda)
* [Slides](./slides)
* [Hands-on notebooks](./notebooks)
* [Resources / reading list](./resources)

---

## About the tutorial

Modern recommender systems have made major progress, but many large-scale, user-facing solutions still behave like **static “one-shot” recommenders**. As user expectations shift toward **interactive, context-aware, and adaptive experiences**, recommender systems increasingly need to support **multi-step reasoning**, **tool use**, **memory**, and **autonomous orchestration**.

This tutorial focuses on how recent advances in **large language models (LLMs)** enable a new class of recommender systems: **agentic** (and often **multi-agent**) systems that can:

* reason over evolving user needs,
* interact through dialog and longer context,
* call tools and external APIs,
* orchestrate multi-step workflows,
* refine outputs using constraints and feedback,
* and support practical production requirements (reliability, scalability, transparency, safety).

Examples and patterns discussed include **context-aware recommendation**, **dynamic multi-step orchestration**, and **personalized recommendation pipelines**, culminating in a hands-on session that bridges concepts with implementation.

---

## Instructors

| Instructor                | Affiliation                            |
| ------------------------- | -------------------------------------- |
| **Reza Yousefi Maragheh** | Walmart Global Tech (USA)              |
| **Yashar Deldjoo**        | Polytechnic University of Bari (Italy) |
| **Chi Wang**              | Google DeepMind (USA / UK)             |
| **Jason Cho**             | Walmart Global Tech (USA)              |
| **Derek Cheng**           | Google DeepMind (USA / UK)             |

---

## What you’ll learn

By the end of this tutorial, you should be able to:

* Understand the shift from traditional recommenders to **LLM-powered, interactive, agentic systems**
* Recognize the core building blocks (“alphabets”) of multi-agentic systems, including:

  * **memory types and retrieval strategies**
  * **function calling and tool usage**
  * **orchestration protocols / interfaces**
  * **reasoning load balancing** across steps or agents
* Apply common **agentic RecSys design patterns** for:

  * conversational recommendation
  * context-aware autonomous recommendation
  * recommendation evaluation and user simulation
  * explanation generation
* Gain hands-on familiarity with frameworks commonly used for agentic pipelines (e.g., multi-agent and orchestration frameworks)
* Identify practical pitfalls and open challenges such as:

  * scalability and latency constraints
  * hallucinations and error propagation
  * transparency, fairness, bias, and privacy risks

---

## Tutorial format

* **Length:** ~3 hours (half-day format), including a hands-on session
* **Level:** Intermediate → Advanced (content is presented at an intermediate level to remain accessible)
* **Style:** Conceptual foundations + industrial patterns + live demo / notebook-based implementation

---

## Tutorial agenda

### A. Introduction and background (≈15 min)

* Key properties in modern RecSys (e.g., accuracy, alignment, context-awareness, scalability)
* How LLM-era techniques relate to these goals (from prompting to multi-agent systems)
* A motivating running example (e.g., a multi-step “personalized birthday planner” workflow)

### B. Alphabets of multi-agentic AI (≈45 min)

* Memory moderation & retrieval mechanisms
* Function calling & tool usage
* Orchestration protocols / standardization
* Reasoning load balancing and practical orchestration strategies
* Improving the running example via these components

### C. Industrial agentic RecSys implementations (≈60 min)

* Tasks and patterns (conversational, autonomous, evaluation/simulation, explanations)
* Best practices for large-scale agentic pipelines (standards, pitfalls, optimization)

### D. Hands-on demonstration (≈30–45 min)

* Overview of commonly used frameworks
* Live walkthrough of a multi-step recommendation scenario:

  * components & architecture
  * initial implementation
  * debugging and diagnosing failure points
  * iterative refinement

### E. Challenges & future directions (≈15 min)

* Communication complexity, scalability constraints, hallucinations, and robustness
* Fairness / privacy / unintended behaviors and mitigation strategies
* Future directions: multi-agent synergy, advanced memory, self-improving systems

---

## Who this is for

This tutorial is designed for:

* **PhD students and researchers** exploring agentic systems for recommendation
* **Senior researchers and practitioners** working with generative/LLM-based RecSys
* **Industry teams** looking for practical patterns to move from prototypes to scalable systems

---

## Materials and companion resources

This site is intended to host (or link to) the tutorial’s:

* slides
 
* demo architecture diagrams
 

> If you’re setting up the repository structure, a simple layout could be:
>
> * `/tutorial` (written modules)
> * `/slides`
 
> * `/resources`

---

## Citation

If you’d like to cite the tutorial, you can reference it using the DOI:

`10.1145/3705328.3748008`

---

## License and acknowledgements

This tutorial paper is released under **Creative Commons Attribution 4.0 (CC BY 4.0)**.
Open access support is provided by:

* Walmart Inc.
* DeepMind Technologies Limited
* Polytechnic University of Bari
