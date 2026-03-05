# CLAUDE.md

This file provides guidance to Claude Code when working in this repository.

## Project Overview

This is a **strategic research knowledge base** for a Chengdu-based AI hardware startup. It is a living repository that grows as the company evolves — from competitor analysis to go-to-market execution to product/community planning.

**Repository:** `ChachiQ/ai-hardware-strategy`

**Target company:** A Chengdu AI hardware company building edge AI devices for developers/makers and the education market (universities, K12, government demonstration projects). Founded 2025, going global from zero.

**Closest comparables:** M5Stack (most similar model), DFRobot (education pathway reference), Seeed Studio (platform model reference).

## Content Categories

The repository contains and will expand to include:

| Category | Description | Example |
|----------|-------------|---------|
| **Competitor Case Studies** | Deep-dive analysis of peer companies (10-chapter template) | DFRobot, M5Stack, Seeed Studio |
| **Go-to-Market Guides** | Step-by-step playbooks for overseas expansion | Crowdfunding → DTC → Amazon → distributors |
| **Product Strategy** | Hardware/software architecture, SDK design, AI model strategy | _(future)_ |
| **Community Planning** | Developer community building, open-source strategy | _(future)_ |
| **Creative Exploration** | Brainstorming sessions, positioning exercises | _(future)_ |

## Repository Structure

```
research/                              — External company case studies
  dfrobot-case-study.md                — DFRobot growth path analysis (~1,400 lines)
  m5stack-case-study.md                — M5Stack growth path analysis (~1,400 lines)
  seeed-case-study.md                  — Seeed Studio growth path analysis (~1,400 lines)

strategy/                              — Company strategy documents
  ai-hardware-go-global-guide.md       — Master go-to-market playbook (~1,500 lines)
  mimiclaw-product-analysis.md         — MimiClaw product analysis (~857 lines)
  domestic-market-strategy.md          — Domestic market strategy (~1,275 lines)

idea/                                  — Future idea exploration (currently empty)
```

Case studies go into `research/`, strategy docs into `strategy/`, new ideas into `idea/`.

## Writing Standards

### Language & Style
- All documents in **Chinese** with English brand names/technical terms kept as-is
- Heavy use of **tables** (~30+ per document) for comparisons and data
- **ASCII diagrams** for timelines, architecture, decision trees, and flywheel models
- Bold **key numbers** on first appearance

### Case Study Template (10 Chapters)
Each case study follows a consistent structure:
1. Company overview & key metrics
2. Relevance comparison ("对比你的公司")
3. Founding story & early decisions
4. Product strategy & iteration
5. Channel strategy (crowdfunding, DTC, Amazon, distributors)
6. Community & ecosystem building
7. Brand building (CBBE pyramid framework)
8. Funding & financial strategy
9. Manufacturing & supply chain
10. Summary & action items

Each chapter ends with **"对你的启示"** section split into `可以直接照做` and `需要调整` with `- [ ]` checklists.

### Data Integrity
- Cross-reference data across documents — the same company's metrics must be identical everywhere they appear
- Key consistency checkpoints:
  - StackChan: HK$3,582,197 / 4,142 backers / 4,593%
  - DFRobot: 8,544 Hackster members / $6.99M funding / 478 GitHub repos
  - M5Stack: 5,856 Hackster members / ~35% Japan market share / 615+ SKUs
  - Seeed Studio: 24,097 Hackster members / $15.71M funding / 492 GitHub repos / RMB 7.49亿 revenue (2022) / 91.49% overseas
- All data from public sources. Estimates must be labeled as such
- When adding new data, verify it doesn't contradict existing documents

### Company References
- The reader's company is in **成都** (Chengdu), not 深圳
- References to 深圳 supply chain, manufacturing, 华强北 etc. are geographical facts — keep as-is
- DFRobot, M5Stack, Seeed Studio etc. ARE 深圳 companies — keep their location references as-is
- Only the reader's company location should reference 成都

## Research Workflow

When creating new case studies or updating existing ones:
1. Use WebFetch/WebSearch to gather data from official sources
2. Cross-check numbers against existing documents and MEMORY.md for consistency
3. Follow the established 10-chapter case study template
4. After writing, verify: line count, table count, ASCII diagram count, data cross-references
5. Commit and push — documents are the deliverable

## Key Strategic Context

Five core conclusions established across the research:
1. **Packaging = Brand** (M5Stack proved it with ESP32)
2. **Partner-led global expansion** beats opening overseas offices (initially)
3. **SDK open-source / AI model closed-source** — the new paradigm
4. **Crowdfunding before VC** — zero dilution + validation + seed users
5. **Unified SDK locks in ecosystem** (M5Unified pattern)

Time window: **2023-2028** is the optimal entry period for edge AI hardware.
