# Available .RICH One-Word Domains (12,898)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C898%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rich one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,898 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,898 domains · **Median ask:** $138.71 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/rich`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rich?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rich.csv">CSV</a> / <a href="./rich.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RICH search](https://unique.domains/domains/tld/rich?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RICH search](https://unique.domains/domains/tld/rich?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RICH one-word domain catalog.

### Files

- `rich.csv` — public CSV extract (1,000 rows)
- `rich.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rich-oneword-domains/main/rich.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| tips.rich        | available | $149.99   | —             | 80             | 26     | 4      | name.com  |
| homes.rich       | available | $149.99   | —             | 86             | 34     | 5      | name.com  |
| Chanel.rich      | premium   | —         | —             | 80             | 77     | 6      | —         |
| finals.rich      | available | $94.99    | $1,999        | 80             | 7      | 6      | namesilo  |
| playon.rich      | available | $149.99   | —             | 80             | 14     | 7      | name.com  |
| makers.rich      | available | $94.99    | $1,999        | 62             | 67     | 6      | namesilo  |
| online.rich      | available | $149.99   | —             | 70             | 62     | 7      | name.com  |
| Ryan.rich        | premium   | —         | —             | 60             | 44     | 4      | —         |
| jobs.rich        | available | $149.99   | —             | 79             | 42     | 4      | name.com  |
| William.rich     | premium   | —         | —             | 74             | 31     | 7      | —         |
| shortcuts.rich   | available | $149.99   | —             | 48             | 41     | 10     | name.com  |
| Places.rich      | premium   | —         | —             | 74             | 22     | 6      | —         |
| whynot.rich      | available | $149.99   | —             | 74             | 39     | 7      | name.com  |
| HarryPotter.rich | premium   | —         | —             | 72             | 20     | 12     | —         |
| prompts.rich     | available | $94.99    | $1,999        | 54             | 39     | 7      | namesilo  |
| Phillip.rich     | premium   | —         | —             | 70             | 14     | 7      | —         |
| justin.rich      | available | $149.99   | —             | 58             | 38     | 7      | name.com  |
| IChing.rich      | premium   | —         | —             | 68             | 14     | 7      | —         |
| BRAS.rich        | premium   | —         | —             | 70             | 13     | 4      | —         |
| tickets.rich     | available | $94.99    | $1,999        | 64             | 34     | 7      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,898 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rich?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rich?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is made up of one-word .rich domains. The set spans literal terms, consumer words, and category-style names such as tips.rich, homes.rich, jewels.rich, and finals.rich. The median ask is 138.71, which keeps price comparison straightforward across a large pool. When comparing these domains, start with memorability and word clarity. Then check whether the term fits a premium, wealth, luxury, advice, property, or status-led use case that matches the .rich extension. Be stricter with names that may raise trademark concerns, especially terms that look tied to established brands. Short, generic, easy-to-pronounce words usually make the cleanest shortlist.

- Prioritize clear one-word terms that fit the .rich meaning
- Use the 138.71 median ask as a simple pricing anchor
- Favor generic words over terms with trademark exposure
- Short, memorable words tend to be easier to evaluate

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RICH One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RICH page](https://unique.domains/domains/tld/rich?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rich_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
