# 🛠️ GEO Toolkit

> Audit any website's AI-readiness. Score 0–100.

## Installation

```bash
pip install geo-hub
```

## Usage

```bash
geo-audit https://yourwebsite.com
```

## What It Checks

| Check | Description | Weight |
|-------|-------------|--------|
| `llms.txt` | Presence, format, and completeness | 20% |
| Schema.org | JSON-LD structured data coverage | 20% |
| Authority Signals | Citations, statistics, expert quotes | 20% |
| FAQ Structure | Question-answer markup | 15% |
| AI Crawler Access | robots.txt, sitemap, crawlability | 15% |
| Content Freshness | Last updated dates, recency signals | 10% |

## Output Example

```
GEO Audit Report: yourwebsite.com
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Overall Score: 72/100

✅ llms.txt found (18/20)
✅ Schema.org markup detected (16/20)
⚠️  Authority signals: missing citations (12/20)
✅ FAQ structure present (13/15)
⚠️  AI crawlers partially blocked (10/15)
✅ Content freshness OK (10/10)

Top Recommendations:
1. Add citation sources to key claims
2. Unblock GPTBot in robots.txt
3. Add statistics to support main arguments
```

## Coming Soon
- JSON export
- CI/CD integration
- Batch URL scanning
- Historical tracking
