# AI PM Playbook

> A comprehensive practice handbook for AI Product Managers — Skills, Workflows, and Insights on Vibe Coding & Harness Engineering

[![GitHub Stars](https://img.shields.io/github/stars/wenhaoyu-bryan/AI-PM-Playbook?style=social)](https://github.com/wenhaoyu-bryan/AI-PM-Playbook)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/wenhaoyu-bryan/AI-PM-Playbook)](https://github.com/wenhaoyu-bryan/AI-PM-Playbook)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**English** | **[中文](README.zh-CN.md)**

---

## 📖 About This Repository

This is a **living knowledge base** for AI Product Managers who want to bridge the gap between product thinking and technical implementation. It's not a tutorial or a course — it's a real practitioner's **field notes** from daily work, capturing what actually works (and what doesn't) when building AI-powered products.

### What You'll Find Here

🎯 **Practical Skills**: Battle-tested workflows for turning ideas into prototypes in hours, not weeks. From requirements gathering to AI-generated code, every skill has been validated in real projects.

🔄 **Vibe Coding Insights**: How to effectively collaborate with LLMs as a PM — not by learning to code, but by learning to think architecturally. Includes real examples of building full-stack prototypes with just a PM and an AI model.

🧠 **Cognitive Frameworks**: The mental models that separate good AI PMs from great ones. How to think about ontologies, agent architectures, and the difference between data models, schemas, and knowledge graphs.

🛠️ **Harness Engineering**: The emerging discipline of directing AI to write code. Learn how to design prompts, architect systems, handle errors, and ensure quality — all without writing a single line of code yourself.

📊 **Real Project Cases**: Concrete examples from semiconductor manufacturing to enterprise knowledge graphs. See how these principles apply in practice, with full technical details and architecture decisions.

### Who This Is For

- **Aspiring AI PMs**: Product managers looking to transition into AI-native roles
- **Technical PMs**: Those who want to understand AI/ML without becoming engineers
- **Vibe Coders**: Anyone interested in PM + LLM collaboration patterns
- **Startup Founders**: Those building AI products with limited engineering resources
- **Engineers**: Understanding the PM perspective on AI system design

### Core Philosophy

> "The hardest part of building an AI system is not the code, but the mental model. Understanding that a graph database is not an ontology, an ontology is not a schema, and a schema is not a data model — these are concentric circles of abstraction levels, and getting them right is a product problem, not an engineering problem."

---

## 🗂️ Repository Structure

```
AI-PM-Playbook/
├── README.md                    # English version (you are here)
├── README.zh-CN.md              # 中文版
├── skills/                      # Reusable skills & workflows
│   ├── pm-prototype-workflow/   # AI Native prototype development (React)
│   ├── vue3-x6-prototype-stack/ # Vue 3 + Element Plus + AntV X6 (B-side)
│   ├── requirements-breakdown/  # Requirements → structured tasks framework
│   └── ...
├── workflows/                   # Detailed workflow guides
│   ├── vibe-coding.md          # PM + LLM collaboration methodology
│   ├── harness-engineering.md  # Directing AI to write code
│   └── ...
├── insights/                    # Cognitive frameworks & reflections
│   ├── ai-pm-role.md           # How the PM role evolves with AI
│   └── ...
├── projects/                    # Real-world project case studies
│   └── Prompt-to-Ontology/     # Enterprise ontology platform (open source)
└── resources/                   # Curated learning resources
    ├── books.md                # Essential reading list
    └── courses.md              # Online courses & tutorials
```

---

## 🎯 Key Skills

### 1. AI Native Product Development

**The Core Shift**: PRDs are no longer documents for humans — they're instruction sets for AI.

```
Traditional: Requirements → PRD → Design → Dev → Test → Launch (2-4 weeks)
AI Native:   Requirements → AI PRD → AI Prototype → Iterate → Ship (1-2 hours)
```

**Efficiency Gain**: 15-20x faster from idea to working prototype

**Details**: [skills/pm-prototype-workflow/](skills/pm-prototype-workflow/)

---

### 2. Vibe Coding

**Definition**: A methodology where a PM defines product intent, architecture boundaries, and design constraints, while an LLM handles code generation, debugging, and iteration.

**Key Insights**:
- You're not "learning to code" — you're "learning to think architecturally"
- The output isn't code — it's a cognitive framework for understanding systems
- One PM + one LLM can deliver full-stack prototypes that previously required a team

**Real Example**: Ontology OS — built entirely through Vibe Coding in 2 weeks, no traditional engineers involved.

**Details**: [workflows/vibe-coding.md](workflows/vibe-coding.md)

---

### 3. Harness Engineering

**Definition**: The practice of directing AI to write code, not writing it yourself.

**Core Skills**:
- **Prompt Engineering**: Designing instructions that AI can execute correctly
- **Architecture Design**: Defining system boundaries and data flows
- **Quality Assurance**: Judging and improving AI output
- **Rapid Iteration**: Learning from failures and optimizing quickly

**Details**: [workflows/harness-engineering.md](workflows/harness-engineering.md)

---

## 💡 Key Insights

### The AI PM Role Evolution

```
Traditional PM: Requirements → Documents → Design → Dev → Test → Launch
AI PM:          Requirements → AI Instructions → AI Generation → Verify → Iterate
```

**What Changes**:
- From "writing documents" to "writing instructions"
- From "managing developers" to "harnessing AI"
- From "linear process" to "rapid iteration"

**What Stays the Same**:
- Understanding user needs
- Making product decisions
- Ensuring quality and value

---

### Ontology Thinking

> "The hardest part of building an ontology system is not the code, but the mental model."

**Key Distinctions**:
- Graph Database ≠ Ontology
- Ontology ≠ Schema  
- Schema ≠ Data Model

These are concentric circles of abstraction. Getting them right is a **product problem**, not an engineering problem.

---

## 🛠️ Project Cases

### Prompt to Ontology

**What**: An enterprise ontology operating system that transforms flat data into living knowledge graphs

**Why**: To understand how platforms like Palantir AIP actually work under the hood — not by reading whitepapers, but by building one yourself

**Tech Stack**:
- Frontend: React 18 + D3.js + Tailwind CSS 4
- Backend: FastAPI + Neo4j + NetworkX  
- LLM: MiniMax / OpenAI / Anthropic

**Key Architecture Decisions**:
- Neo4j is the data source, NetworkX is the compute engine, LLM is the reasoning layer
- Fact tables are nodes, not edges (get this wrong and your entire graph topology collapses)
- Actions are attached to objects, state drives behavior

**GitHub**: [Prompt-to-Ontology](https://github.com/wenhaoyu-bryan/Prompt-to-Ontology)

**Details**: [projects/Prompt-to-Ontology/](projects/Prompt-to-Ontology/)

---

## 📚 Learning Resources

### Essential Reading

1. **"Thinking in Systems"** — Donella H. Meadows
   - Foundation for understanding complex systems
   - Why: AI products are systems, not features

2. **"The Design of Everyday Things"** — Don Norman
   - User experience design principles
   - Why: AI products still need great UX

3. **"Inspired"** — Marty Cagan
   - Modern product management
   - Why: AI PM is still PM at its core

### Online Courses

1. **Prompt Engineering for Developers** (DeepLearning.AI)
   - Foundation for working with LLMs
   - Essential for Vibe Coding

2. **LangChain for LLM Application Development** (DeepLearning.AI)
   - Building production LLM applications
   - Practical implementation skills

3. **AI Product Management** (Coursera)
   - Business perspective on AI products
   - Strategy and execution

---

## 📈 Roadmap

### ✅ Done
- [x] Core skill frameworks
- [x] Vibe Coding methodology
- [x] Harness Engineering guide
- [x] Prompt to Ontology case study
- [x] Learning resource curation

### 🚧 In Progress
- [ ] Weekly learning notes
- [ ] More project case studies
- [ ] Community discussions

### 📋 Planned
- [ ] AI PM interview prep guide
- [ ] Tool comparison framework
- [ ] Team scaling playbook
- [ ] Industry-specific templates

---

## 🤝 Contributing

This is primarily a personal knowledge base, but contributions are welcome:

1. **Issues**: Share ideas, suggestions, or corrections
2. **Pull Requests**: Add your own practice cases or improvements
3. **Discussions**: Share your experience and learn from others

---

## 👥 Contributors

- **[Wenhao Yu](https://github.com/wenhaoyu-bryan)** — Creator & maintainer
- **Hermes Agent** — AI assistant (content generation, architecture design, code implementation)

---

## 📝 License

MIT License — use freely, share widely

---

## 🙏 Acknowledgments

- **Open Source Community** — For building the tools that make this possible
- **Hermes Agent** — For being an exceptional AI coding partner
- **Everyone** who shares their AI PM journey publicly — we learn faster together

---

**Last Updated**: 2026-05-18  
**Status**: 🟢 Actively maintained  
**Stars**: If you find this useful, please star the repo!
