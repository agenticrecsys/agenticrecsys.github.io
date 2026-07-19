---
layout: home
title: Multi-Agentic Recommender Systems — SIGIR 2026
permalink: /sigir2026/
description: "SIGIR 2026 tutorial on multi-agentic recommender systems: foundations, perspectives, and lessons from large-scale deployments."
eyebrow: "SIGIR 2026 · Melbourne · Tutorial"
hero_title: "Multi-Agentic<br>Recommender Systems"
hero_subtitle: "Foundations, Perspectives, and Lessons from Large Scale Deployments"
hero_lede: "Bringing together <strong>information retrieval</strong>, <strong>recommender systems</strong>, and <strong>large-scale industrial practice</strong>, with foundational concepts, reusable design patterns, and lessons learned from deploying agentic and multi-agent recommenders at scale."
hero_meta:
  - label: "When"
    value: "Mon 20 Jul 2026"
  - label: "Where"
    value: "Melbourne, Australia"
  - label: "Room"
    value: "Eureka 3"
nav:
  - label: "About"
    href: "#about"
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
| **Conference**           | SIGIR 2026, the 49th International ACM SIGIR Conference       |
| **Date**                 | Monday, 20 July 2026                                         |
| **Location**             | Melbourne Convention and Exhibition Centre, Melbourne, Australia |
| **Room**                 | Eureka 3                                                     |
| **Session time**         | 9:00 am to 12:00 pm (local time)                            |
| **Official listing**     | [SIGIR 2026 accepted tutorials](https://sigir2026.org/en-AU/pages/program/accepted-tutorials) |

## About the tutorial
{: #about }

This tutorial covers **multi-agentic recommender systems**: recommender systems augmented with **large language models (LLMs)** and **multi-agent orchestration** to enable multi-step reasoning, tool use, and interactive decision-making. It emphasizes foundational concepts, reusable design patterns, and practical lessons learned from large-scale e-commerce deployments.

We begin with background and recent trends in generative recommender systems and their connection to agentic approaches. We then survey major deployment areas in industry and review the agent-orchestration frameworks developed to support them. Finally, we walk through a project that traces the full lifecycle of an agentic recommender system, from scoping and data definition through modeling, deployment, and monitoring, to provide actionable deployment insights.

The tutorial brings together perspectives from **information retrieval (IR)**, **recommender systems (RecSys)**, and **large-scale industrial practice**, and aims to give attendees practical insight into how these paradigms shape the design of next-generation user-facing IR and RecSys deployments.

## What we'll cover

The tutorial runs from foundations through to practice, drawing on what we've learned building and deploying these systems at scale. In particular:

* The move from **generative to agentic recsys**, with working definitions, levels of agent autonomy, and a survey of the key work in the area.
* **Four major use cases** for agents in recommendation, drawn from real search and personalization deployments, plus a look at the current agentic recsys startups.
* **Memory for agents**: ontology-driven memory, and retrieving from long, tool-heavy trajectories without being derailed by context noise.
* Keeping **self-improving evolution agents** from high variance and loops, and getting **feature-engineering agents** to describe items consistently.
* **Harness and RL-based design** that specifies the "what" rather than the "how," and the practical side of putting agentic recsys into production.
* From open-source multi-agent frameworks to a **single personal agent**: one kernel adapting into many roles, coordinating a growing fleet across many owners, and a **six-axis framework** for characterizing agents.
* **Evaluation metrics** for agentic pipelines used in industry, with sample code where time allows.

## Presenters
{: #presenters }

| Presenter                 | Affiliation                            |
| ------------------------- | -------------------------------------- |
| **Reza Yousefi Maragheh** | Walmart Global Tech                    |
| **Yashar Deldjoo**        | Polytechnic University of Bari         |
| **Benjamin Coleman**      | Google DeepMind                        |
| **Jason Cho**             | PreTask AI                             |
| **Chi Wang**              | AG2AI                                  |

Full presenter bios: <span class="tbd">TBD</span>.

## Who this is for
{: #audience }

This tutorial is aimed at SIGIR attendees working on IR, recommendation, and LLM or agentic systems. Familiarity with basic RecSys and IR concepts is assumed. It is well suited for:

* **Researchers and PhD students** exploring agentic and multi-agent systems for recommendation and retrieval.
* **Senior researchers and practitioners** working with generative and LLM-based RecSys and IR.
* **Industry teams** looking for practical patterns and lessons to move from prototypes to reliable, large-scale deployments.

## Materials
{: #materials }

* **Slides / materials:** <span class="tbd">TBD</span>. The <span class="link-disabled">Slides (PDF)</span> will be posted here after the tutorial. *(Link to be added.)*
* **Supplementary material** *(planned)*: sample pseudocode for the different stages of productionizing a use case; example prompts, agent-role templates, and orchestration skeletons; and, where feasible, small toy datasets or public data excerpts suitable for demonstration.
* **Curated reading list** *(planned)*: a survey plus representative papers to help attendees continue learning after the tutorial.

The accompanying material for the tutorial series can be found at [agenticrecsys.github.io]({{ '/' | relative_url }}).

## Citation

If you find this tutorial useful in your research or work, feel free to cite it:

```bibtex
@inproceedings{yousefi2026multi,
  title={Multi-Agentic Recommender Systems: Foundations, Perspectives, and Lessons from Large Scale Deployments in eCommerce},
  author={Yousefi Maragheh, Reza and Deldjoo, Yashar and Coleman, Benjamin and Cho, Jason and Wang, Chi},
  booktitle={Proceedings of the 49th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  pages={5354--5356},
  year={2026}
}
```


Yousefi Maragheh, R., Deldjoo, Y., Coleman, B., Cho, J., & Wang, C. (2026). Multi-Agentic Recommender Systems: Foundations, Perspectives, and Lessons from Large Scale Deployments in eCommerce. In *Proceedings of the 49th International ACM SIGIR Conference on Research and Development in Information Retrieval* (pp. 5354–5356). ACM.
