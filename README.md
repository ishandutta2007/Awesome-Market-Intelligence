# Awesome-Market-Intelligence

# Top Market Intelligence Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Competitive Intelligence, Market Research & Self-Hosted Intelligence Pipelines*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Market Intelligence**. These tools help organizations understand their competitive landscape, track market shifts, and synthesize research from public and proprietary sources—ranging from financial terminals and expert networks to AI-powered competitive intelligence platforms and open-source OSINT workbenches.

**Examples** include AlphaSense, Bloomberg Terminal, FactSet, Meltwater, Crayon, Klue, PitchBook, CB Insights, and Similarweb (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding five-figure annual contracts, and building custom intelligence pipelines. The open-source landscape is anchored by **last30days-skill** (multi-source research synthesis across Reddit, X, YouTube, and prediction markets), **OmniSight** (autonomous competitive intelligence with web scraping and audio transcription), and **Intelwatch** (terminal-based due diligence and OSINT), with **JingXi** and **InfoEdge** providing structured competitive analysis and trend discovery respectively.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[AlphaSense](https://www.alpha-sense.com/)** | AI-powered market intelligence platform with search across broker research, expert transcripts, filings, and news. | Quote-based enterprise pricing; no public list prices. | No permanent free tier. **Trial available** via sales request. |
| **[Bloomberg Terminal](https://www.bloomberg.com/professional/)** | The financial data standard with real-time market data, news, analytics, and the IB Chat network. | **~$24,000–$31,980/year per seat** (varies by contract and region) . | **No free tier**. Bloomberg offers a 30-day trial for qualified institutional prospects only. |
| **[FactSet](https://www.factset.com/)** | Financial data and analytics platform with earnings call transcripts, estimates, and portfolio tools. | Quote-only; modular pricing based on data entitlements and seat count. | **No free tier**. Trial available via sales engagement. |
| **[Meltwater](https://www.meltwater.com/)** | Media monitoring and social listening platform for brand and market intelligence. | Quote-based; pricing scales with mentions, seats, and modules. | **No free tier**. Demo available on request. |
| **[Crayon](https://www.crayon.co/)** | Competitive intelligence platform with automated tracking, battlecards, and sales enablement. | Quote-only; annual contracts. Typical mid-market deployments ~**$30,000/year** based on transaction data . | **No free trial**. Evaluation requires enterprise sales process . |
| **[Klue](https://klue.com/)** | Competitive intelligence and win-loss analysis platform for go-to-market teams. | Quote-only; annual contracts. Reported around **$40,000/year** for enterprise deployments . | **No free trial**. No self-serve signup . |
| **[PitchBook](https://pitchbook.com/)** | Private markets data platform covering VC, PE, M&A, and company profiles. | Quote-only. Typical team licenses **$25,000–$40,000/year**; enterprise with API **$70,000+** . | **No free tier**. Demo required. |
| **[CB Insights](https://www.cbinsights.com/)** | Tech market intelligence platform with predictive analytics, company data, and proprietary research. | Quote-only. Reported contracts **$40,000–$100,000/year** . | **10-day free trial** available for qualified prospects . |
| **[Similarweb](https://www.similarweb.com/)** | Digital intelligence platform for traffic analysis, competitor benchmarking, and market sizing. | Quote-based. Entry-level **~$15,000–$40,000/year**; enterprise **$90,000–$200,000+** . | **Free account** available with limited data; paid tiers required for full intelligence. |

## Open-Source GitHub Projects

- **[last30days-skill](https://github.com/mvanhorn/last30days-skill)** [![GitHub Stars](https://img.shields.io/github/stars/mvanhorn/last30days-skill?style=social&color=white)](https://github.com/mvanhorn/last30days-skill/stargazers)  
  **The multi-source research synthesis standard.** Researches any topic across Reddit, X, YouTube, Hacker News, Polymarket, and the web from the last 30 days, then synthesizes a grounded narrative with real citations . **Sources**: Reddit (with comments), HN, Polymarket, GitHub work free with zero config; X, YouTube, TikTok, Instagram available via API keys . **Use cases**: pre-meeting research, hiring signals, tool comparisons, and community sentiment analysis . **Caveat**: designed for Claude Code/Codex skill environments; not a standalone web app. Best for analysts and researchers wanting fast, citation-backed intelligence on any topic without enterprise contracts.

- **[OmniSight](https://github.com/HamzaKhanBUIC/OmniSight-Autonomous-Corporate-Strategy-Disruption-Radar)** [![GitHub Stars](https://img.shields.io/github/stars/HamzaKhanBUIC/OmniSight-Autonomous-Corporate-Strategy-Disruption-Radar?style=social&color=white)](https://github.com/HamzaKhanBUIC/OmniSight-Autonomous-Corporate-Strategy-Disruption-Radar/stargazers)  
  **The autonomous competitive intelligence radar.** Synthesizes live web telemetry, audio transcripts, and knowledge graphs into dynamic strategy dashboards . **Pipeline**: concurrent web scraping (pricing pivots, hiring trends, customer sentiment), audio transcription with speaker diarization (earnings calls), graph memory synthesis via Cognee, and dual-layered radar comparisons. **Tech**: Python FastAPI, Google Gemini/Groq, Bright Data, Speechmatics. MIT licensed. Best for teams wanting automated, multi-modal competitive monitoring with a visual dashboard.

- **[Intelwatch](https://github.com/ishandutta2007/intelwatch)** [![GitHub Stars](https://img.shields.io/github/stars/ishandutta2007/intelwatch?style=social&color=white)](https://github.com/ishandutta2007/intelwatch/stargazers)  
  **The terminal-based due diligence toolkit.** Competitive intelligence, M&A due diligence, and OSINT directly from your command line . **Commands**: `profile` (financials, group structure, governance, OSINT, tech stack), `discover` (competitor discovery), `track` (competitor/keyword monitoring), `check`/`digest` (change detection), `ai-summary` (competitive briefs). **Privacy**: local-first, no intermediary servers, BYOK. MIT licensed; Pro tier ($49/mo) unlocks PDF/Excel exports and AI due diligence reports. Best for developers and analysts wanting fast, privacy-respecting intelligence without dashboards.

- **[JingXi](https://github.com/geyuzi11/jingxi-competitive-intelligence)** [![GitHub Stars](https://img.shields.io/github/stars/geyuzi11/jingxi-competitive-intelligence?style=social&color=white)](https://github.com/geyuzi11/jingxi-competitive-intelligence/stargazers)  
  **The structured competitive analysis tool.** Paste a competitor URL and get a traceable five-dimension report in ~60 seconds: Positioning & Monetization, Growth Archaeology, Channels & Reach, Next Moves, Evidence & Sources . **Features**: 8 parallel data sources, 16 signal scores, six-axis radar, growth timeline from Wayback snapshots, competitor comparison (up to 6), scheduled monitoring with weekly reports. **Caveat**: requires Node.js ≥18; real analysis needs local server. Best for product and strategy teams wanting repeatable, evidence-backed competitor profiles.

- **[InfoEdge](https://github.com/gaoyu666/infoedge)** [![GitHub Stars](https://img.shields.io/github/stars/gaoyu666/infoedge?style=social&color=white)](https://github.com/gaoyu666/infoedge/stargazers)  
  **The open-source intelligence workbench.** Trend discovery, data-source tracking, and opportunity scoring from public and authorized sources . **Features**: source dashboard, opportunity cards from news/communities/finance/supply chain signals, FastAPI pipeline with normalization and scoring, model settings for OpenAI-compatible providers. **Tech**: React/Vite frontend, Python FastAPI backend, Redis, PostgreSQL. Best for teams wanting a customizable workbench for opportunity research rather than a single-purpose competitor tracker.

### Additional Strong Open-Source Options

- **ai-dataset-radar** — Competitive intelligence specifically for AI training datasets, tracking 86 HF orgs, 50 GitHub orgs, 125 X accounts, with MCP server and REST API . Best for AI/ML teams monitoring dataset releases.
- **intelwatch** (alternate repo) — Terminal-first OSINT with French corporate data (Pappers) and international fallback (Apollo, OpenCorporates) . Best for European market due diligence.
- **Company Researcher (Exa)** — Company intelligence from a URL using Exa.ai search API with market intelligence endpoints . Best for quick company profiling with a free API tier.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Market intelligence SaaS is expensive and quote-only**: Bloomberg at ~$24K–$32K/seat/year; Crayon and Klue around $30K–$40K/year; CB Insights $40K–$100K; Similarweb enterprise $90K–$200K+ . None offer permanent free tiers; trials require sales engagement.
- **Open-source tools are not drop-in replacements for enterprise platforms**: last30days-skill and Intelwatch cover OSINT and research synthesis, but lack the licensed content libraries (broker research, expert transcripts, private company financials) that AlphaSense and PitchBook provide.
- **"Free" open-source tools still have costs**: API keys for X, YouTube, and LLM providers are required for full functionality; self-hosting requires infrastructure and maintenance.
- **Data quality varies**: OSINT tools surface community sentiment and public signals, not verified financial data. Cross-reference with primary sources before making investment or strategic decisions.

---

**Made for analysts, competitive intelligence teams, and developers building market research workflows.**  
Let's make market intelligence more open, evidence-backed, and accessible.
