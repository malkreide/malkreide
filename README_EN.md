🇩🇪 [Deutsch](README.md) | 🇬🇧 English

# Hi, I'm Hayal 👋

**Head of Marketing & Communications, Member of Executive Management | Zurich City School Department**  
**Member of the AI Task Force, City of Zurich Administration**

I build open-source tools for AI that serves the public interest — not the other way around. My work connects critical theory, open data, and pragmatic process optimization to help public administration and education digitalize on their own terms.

> *"No algorithmic system is neutral. No bureaucratic process is without alternatives. And no data sovereignty happens by itself."*

---

## What I believe

AI in public administration doesn't fail because of technology — it fails because of missing reflection, blind processes, and the illusion that cloud dependency is inevitable.

Four principles guide my work:

**Think critically before you implement.** If you don't understand the bias and power structures embedded in AI systems, you're automating inequality. Critical theory isn't academic luxury — it's a prerequisite for responsible technology decisions.

**Fix the process first, then add technology.** The biggest risk is putting new software on a broken process. Question first, eliminate second, digitalize — maybe — third.

**Data sovereignty is non-negotiable.** Public institutions that hand their data to proprietary platforms hand over agency. Local processing, open interfaces, and open source aren't technical preferences — they're democratic necessities.

**Evidence over assertion — and a human decides.** Every statement an AI system makes must be traceable to a verifiable source; what can't be grounded is flagged, not shown. Tests and deterministic rules are the source of truth, not a model's self-assessment. The final approval always rests with a human.

---

## What I build

More than 60 repositories of my own, five themes. All open source, almost all MIT-licensed.

### 🏛️ Civic tech: making public administration visible and understandable

| Project | What it does |
|:--------|:-------------|
| **[Maschinerie Zürich](https://github.com/malkreide/maschinerie-zuerich)** | Interactive, accessible visualization of the Zurich city administration — departments, agencies, budgets and staff numbers from open data, with a life-situation search ("register a dog" → responsible office). Five languages including Easy Read. |
| **[Tessera](https://github.com/malkreide/tessera)** | Open AI agents that break public-sector processes into small, machine-readable building blocks. Every statement stays linked to its original source; every change goes through a pull request with human review. Feeds Maschinerie Zürich. |
| **[Zurich School Holidays ICS](https://github.com/malkreide/zuerich-schulferien-ics)** | Subscribable calendar feed for Zurich public school holidays, generated automatically from open data. |

### 🎓 Education and learning

| Project | What it does |
|:--------|:-------------|
| **[Future Skills Evidence Graph](https://github.com/malkreide/future-skills-evidence-graph)** | Open evidence catalog for future skills in AI and education, mapped to the Swiss Lehrplan 21. No skill recommendation without an evidence path. |
| **[Socratic Method](https://github.com/malkreide/socratic-method-skill)** | Claude as a Socratic tutor — guided knowledge discovery through systematic questioning instead of direct instruction. |
| **[Critical Pedagogy](https://github.com/malkreide/critical-pedagogy-skill)** | Examine curricula, school communications, and educational texts for hidden power dynamics and exclusion mechanisms. |
| **[Luanti Learning World](https://github.com/malkreide/luanti-lernwelt-template)** | Reusable framework for child-friendly educational worlds in Luanti (formerly Minetest), with Lehrplan 21 tagging. |
| **[Papercraft KI](https://github.com/malkreide/papercraft-ki)** | Educational papercraft templates built with free tools and local AI, mapped to the Lehrplan 21. |

### 🧰 Evidence-based tools for decisions

Shared pattern: AI extracts, rules compute deterministically, a human decides.

| Project | What it does |
|:--------|:-------------|
| **[personakit](https://github.com/malkreide/personakit)** · [MCP](https://github.com/malkreide/personakit-mcp) | Evidence-based, behaviour-first personas as versioned Markdown with Jobs-to-be-Done, lint rules, and prompt export; served read-only to AI sessions via an MCP server. |
| **[journeykit](https://github.com/malkreide/journeykit)** | Evidence-based user journeys for public administration — schema, lints, renderer, and Claude skill. |
| **[sentimentkit](https://github.com/malkreide/sentimentkit)** | Sentiment toolkit with swappable backends, evidence atoms, eval harness, and policy-as-code. |
| **[Methodos AI](https://github.com/malkreide/methodos-ai)** | Open catalog of management methods with CLI, RAG, provider-neutral architecture, and MCP interface — fully offline by default. |
| **[use-case-discovery](https://github.com/malkreide/use-case-discovery)** | Claude Code skill for systematic use case discovery from repos, papers, and tools — with cross-inspiration across freely configurable contexts. |
| **[dealkit](https://github.com/malkreide/dealkit)** | Real-estate deal screening with a deterministic valuation engine, evidence schemas, and red-flag checklists. Never says "buy". |

### 🔍 Claude skills: ways of thinking and working

Specialized instruction sets that turn Claude into a domain expert for a task — calibrated for Swiss public administration and education.

| Skill | What it does |
|:------|:-------------|
| **[Critical AI Literacy](https://github.com/malkreide/critical-ai-literacy-skill)** | Analyze AI systems for bias, power structures, and societal impact — Frankfurt School meets technology critique. |
| **[Musk Algorithm](https://github.com/malkreide/musk-algorithm-skill)** | 5-step process analysis (Question → Delete → Simplify → Accelerate → Automate), adapted for public administration. |
| **[Idea Cockpit](https://github.com/malkreide/idea-cockpit-skill)** · [Idea Synthesis](https://github.com/malkreide/idea-synthesis-skill) | Structured idea management using the Idea Flight Deck framework, and seed-based idea synthesis over a Notion knowledge base, with provenance. |
| **[UX Audit](https://github.com/malkreide/ux-audit-skill)** | Reproducible UX audits (Nielsen, WCAG 2.2 AA, Core Web Vitals) with hybrid browser and code verification. |
| **[GitHub Repo](https://github.com/malkreide/github-repo-skill)** | Create and maintain professional GitHub repositories — bilingual READMEs, standard files, releases, security check before pushing. |
| **[Raspberry Pi AI](https://github.com/malkreide/raspberry-pi-ai-skill)** | Raspberry Pi development with edge AI (Hailo NPU), hardware integration, and systematic debugging. |
| **[Notion AI Papers](https://github.com/malkreide/notion-ai-papers)** | Systematic analysis of AI research papers with automated Notion integration. |

### 🔌 Swiss Public Data MCP: public data for AI agents

The [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) is the open standard that connects AI models to data sources and tools — a universal adapter for the AI world. Public data deserves public interfaces.

The **[swiss-public-data-mcp](https://github.com/malkreide/swiss-public-data-mcp)** portfolio comprises **42 MCP servers for 41 Swiss data sources across 13 domains** — from [City of Zurich Open Data](https://github.com/malkreide/zurich-opendata-mcp) through [federal law (Fedlex)](https://github.com/malkreide/fedlex-mcp), [federal statistics (FSO)](https://github.com/malkreide/swiss-statistics-mcp), [geodata (swisstopo)](https://github.com/malkreide/swisstopo-mcp), [public transport](https://github.com/malkreide/swiss-transport-mcp), and [parliament](https://github.com/malkreide/parlament-mcp) to health, energy, education, and cultural data. It is maintained as an auditable inventory (`portfolio.json`, MCP Registry entries, publishing runbook), not a loose collection of experiments.

The portfolio comes with its own quality chain:

| Project | What it does |
|:--------|:-------------|
| **[mcp-audit-skill](https://github.com/malkreide/mcp-audit-skill)** | 120 checks in 12 categories against a curated best-practice corpus — OAuth 2.1, OWASP, Lethal Trifecta, Swiss compliance (DSG/ISDS). |
| **[mcp-continuous-auditor](https://github.com/malkreide/mcp-continuous-auditor)** | Continuous multi-agent auditor for MCP servers: promptfoo and CI as deterministic ground truth, probes for version identity and shipped releases, a human as the merge gate. |

Guiding principle: **"privacy by architecture"** — open data openly accessible, sensitive data locally protected.

---

## Why open source?

Public administration funded by public money should produce public tools. The projects here are free to use and free to adapt.

If a city administration in Berlin, Vienna, or Amsterdam faces the same challenges we face in Zurich, they shouldn't have to start from scratch.

---

## Independence

All repositories in this account are personal projects, developed in private time with private infrastructure. They are not projects of the Zurich City School Department, the City of Zurich, or the city administration's AI Task Force, and they imply no mandate, endorsement, or production use by any institution. References to municipal or federal strategies are context, not authority.

---

## Theoretical foundations

My work rests on four pillars:

- **Critical Theory** (Horkheimer, Adorno, Habermas, Honneth) — Ideology critique and power analysis as the basis for technology decisions
- **Critical Pedagogy** (Freire, Giroux) — Education as liberation practice, not an optimization problem
- **Critical Data Studies** (Buolamwini, Noble, Couldry) — Algorithmic justice and the political economy of data
- **Lean / First Principles** (Goldratt, Toyota, Musk) — Radically pragmatic process optimization that starts with questioning

---

## Context

<!-- Verify figures before publishing: previous profile stated 32,000 students, 4,500 teachers, 125 schools. -->
The [Zurich City School Department](https://www.stadt-zuerich.ch/ssd/de/index/volksschule/schulamt.html) supports schools and the seven district school boards in managing and developing Zurich's public school system — approximately 32,000 students, 4,500 teachers, 125 schools.

As a member of the **AI Task Force of the City of Zurich Administration**, I work on knowledge exchange, standards, and the assessment of AI initiatives across the entire city government.

---

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hayaloezkan-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/hayaloezkan/)

---

<sub>Most projects are MIT-licensed. Calibrated for Switzerland, adaptable to other contexts.</sub>
