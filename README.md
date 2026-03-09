# 🌐 GEO Hub — Generative Engine Optimization

> **The most complete open resource for making your content visible in AI-powered search engines.**
> Tools · Guides · Templates · Benchmarks · Research

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/erennc/geo-hub?style=social)](https://github.com/erennc/geo-hub/stargazers)

---

## What is GEO?

**Generative Engine Optimization (GEO)** is the practice of optimizing your content to be cited, referenced, and recommended by AI-powered search engines — ChatGPT, Perplexity, Google AI Overviews, Claude, and Gemini.

Unlike traditional SEO (ranking in SERPs), GEO focuses on **being the source AI engines trust and quote**.

> 📊 AI Overviews now appear in 52% of tracked searches (Feb 2025, up from 6.49% in Jan 2025).
> AI search traffic grew 300% in unique domains in 2024.
> Traditional search volume projected to drop 25% by 2026.

---

## 📦 What's Inside

| Section | Description |
|---------|-------------|
| [🛠️ Toolkit](#toolkit) | CLI tools & scripts to audit your AI-readiness |
| [📚 Awesome List](#awesome-list) | Curated tools, platforms, and services |
| [📄 Templates](#templates) | Ready-to-use `llms.txt`, Schema.org, FAQ templates |
| [📊 Benchmarks](#benchmarks) | Citation pattern analysis across AI platforms |
| [📖 Guides](#guides) | Step-by-step GEO implementation guides |
| [🔬 Research](#research) | Academic papers and key findings |

---

## 🛠️ Toolkit

> Audit any website's AI-readiness. Score 0–100.

```bash
pip install geo-hub
geo-audit https://yourwebsite.com
```

**What it checks:**
- `llms.txt` presence and quality
- Schema.org / JSON-LD structured data
- Content authority signals (citations, statistics, authorship)
- FAQ structure
- AI crawler accessibility

📁 [`/toolkit`](./toolkit)

---

## 📚 Awesome List

### 🔍 Monitoring & Analytics

| Tool | Description | Pricing |
|------|-------------|---------|
| [Otterly.AI](https://otterly.ai) | Real-time dashboard for ChatGPT, Perplexity, Google AI Overviews | From $29/mo |
| [Peec AI](https://peec.ai) | Benchmarks visibility across ChatGPT, Claude, Gemini, Perplexity | — |
| [Profound](https://profound.com) | Enterprise AI mention analytics | From $499/mo |
| [ZipTie](https://ziptie.dev) | Brand visibility monitoring across generative AI platforms | — |
| [Knowatoa](https://knowatoa.com) | Tracks brand mentions across ChatGPT, Claude, Perplexity | — |

### ⚡ Optimization Platforms

| Tool | Description |
|------|-------------|
| [Geo Builder](https://geo-builder.com) | AI-powered e-commerce GEO platform — generates `llms.txt`, Schema.org markup, and optimizes product catalogs for AI search engines (Shopify, Amazon, WooCommerce) |
| [AutoGEO](https://github.com/AutoGEO) | Automated framework that rewrites content for AI search |
| [Daydream](https://daydream.wtf) | AI visibility optimization with content discoverability focus |
| [Scrunch AI](https://scrunch.ai) | Explains how AI interprets each page, gives step-by-step fixes |

### 📊 Rank Tracking

| Tool | Description |
|------|-------------|
| [ChatGPT Rank Tracker](https://chatgptranktracker.com) | Dedicated SearchGPT/ChatGPT visibility tracking |
| [Ahrefs Brand Radar](https://ahrefs.com) | 100M+ prompt database from real search data |
| [HubSpot AI Search Grader](https://hubspot.com) | Free AI Search Grader tool |

### 🆓 Open Source

| Repo | Description | Stars |
|------|-------------|-------|
| [GEO (Princeton)](https://github.com/GEO-optim/GEO) | Original KDD 2024 paper implementation | ⭐ |
| [Awesome-GEO](https://github.com/DavidHuji/Awesome-GEO) | Academic research list | ⭐ |
| [awesome-generative-engine-optimization](https://github.com/amplifying-ai/awesome-generative-engine-optimization) | Curated GEO resources | ⭐ |

---

## 📄 Templates

Ready-to-use templates for immediate GEO implementation.

### `llms.txt` Template
```
# [Your Company Name]

> [One sentence description of what you do]

## About
[2-3 sentences about your company, products, and unique value]

## Products
- [Product 1]: [Description]
- [Product 2]: [Description]

## Key Resources
- [Docs URL]
- [Blog URL]
- [API Reference URL]
```

📁 Full templates: [`/templates`](./templates)

---

## 📊 Benchmarks

> How do ChatGPT, Perplexity, Google AI Overviews, and Claude cite sources differently?

| Platform | Wikipedia Cite Rate | Prefers | Avoid |
|----------|-------------------|---------|-------|
| ChatGPT | 47.9% of top citations | Authority, statistics | Thin content |
| Gemini | Lower | Reddit, forums | — |
| Perplexity | Lower | Recent, cited sources | — |
| Claude | — | Structured, authoritative | — |

📁 Full analysis: [`/benchmarks`](./benchmarks)

---

## 📖 Guides

- [GEO Quickstart — From 0 to AI-visible in 1 hour](./docs/quickstart.md)
- [llms.txt — Complete Implementation Guide](./docs/llms-txt.md)
- [Schema.org for GEO — Which types matter](./docs/schema.md)
- [Content Authority Signals — What AI engines trust](./docs/authority.md)
- [GEO for E-commerce](./docs/ecommerce.md)
- [GEO for SaaS](./docs/saas.md)
- [Measuring GEO Success — Metrics & Tools](./docs/metrics.md)

---

## 🔬 Research

| Paper | Authors | Key Finding |
|-------|---------|-------------|
| [GEO: Generative Engine Optimization](https://arxiv.org/abs/2311.09735) | Princeton / Georgia Tech / Allen AI | GEO boosts visibility up to 40% |
| [AutoGEO (ICLR 2026)](https://github.com/AutoGEO) | — | Up to 50% improvement via automated rewriting |
| [C-SEO Bench, NeurIPS 2025](https://github.com/DavidHuji/Awesome-GEO) | — | Conversational SEO benchmark |

---

## 🤝 Contributing

All contributions welcome.

- **Add a tool** → Edit the Awesome List section and open a PR
- **Add a guide** → Create a file in `/docs` and link it above
- **Fix something** → Just open a PR

See [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📬 Stay Updated

This repo is actively maintained. Watch it to get notified of new tools, guides, and benchmarks.

**Built and maintained by [@erennc](https://github.com/erennc)**

---

*If this resource helped you, consider starring ⭐ — it helps others find it.*
