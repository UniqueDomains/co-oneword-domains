# Available .CO One-Word Domains (50,611)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-50%2C611%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .co one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **50,611 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 50,611 domains · **Median ask:** $3,149.23 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/co`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./co.csv">CSV</a> / <a href="./co.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CO search](https://unique.domains/domains/tld/co?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CO search](https://unique.domains/domains/tld/co?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CO one-word domain catalog.

### Files

- `co.csv`, public CSV extract (1,000 rows)
- `co.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/co-oneword-domains/main/co.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar            |
| ----------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | -------------------- |
| dogsick.co  | available | $17.99     | —             | high           | low    | 7      | name.com             |
| ego.co      | resell    | $11,498.85 | $36.40        | medium         | low    | 3      | GoDaddy.com, LLC     |
| cents.co    | premium   | $3,500     | $3,500        | medium         | low    | 5      | namecheap            |
| gopast.co   | available | $17.99     | —             | high           | low    | 7      | name.com             |
| ace.co      | resell    | —          | —             | high           | medium | 3      | Spaceship, Inc.      |
| facts.co    | premium   | $3,450     | $3,450        | high           | low    | 5      | namesilo             |
| gosing.co   | available | $11.99     | $33.99        | high           | low    | 7      | namesilo             |
| azo.co      | resell    | —          | —             | medium         | low    | 3      | GoDaddy.com, LLC     |
| basu.co     | premium   | $130       | $33.80        | medium         | high   | 6      | namecheap            |
| abbatial.co | available | $36.98     | —             | medium         | low    | 8      | namecheap            |
| BBQ.co      | resell    | —          | —             | high           | high   | 3      | Hello Internet Corp. |
| bangles.co  | premium   | $350       | $350          | medium         | low    | 7      | namecheap            |
| carefor.co  | available | $11.99     | $33.99        | high           | low    | 8      | namesilo             |
| BVI.co      | resell    | —          | —             | medium         | high   | 3      | 1API GmbH            |
| boarded.co  | premium   | $302.50    | $302.50       | medium         | low    | 7      | namesilo             |
| closein.co  | available | $11.99     | $33.99        | high           | low    | 8      | namesilo             |
| EMV.co      | resell    | —          | —             | medium         | high   | 3      | GoDaddy.com, LLC     |
| closely.co  | premium   | $640       | $640          | medium         | low    | 7      | namesilo             |
| sitabout.co | available | $11.99     | $33.99        | medium         | low    | 9      | namesilo             |
| ESB.co      | resell    | —          | —             | high           | high   | 3      | Domainbox Limited    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 50,611 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/co?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/co?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This is a list of one-word .CO domains, spanning everyday words, short nouns, and simple verbs such as "okay," "bingo," "come," and "cut." With 50,611 domains in this set and a median asking price near $3,149, pricing varies widely by word recognition, length, and search demand. These domains suit founders searching for a memorable, ownable name and investors comparing pricing patterns across a large one-word .CO pool.

- 50,611 one-word .CO domains in this selection
- Median asking price near $3,149 per domain
- Everyday words like okay.co, bingo.co, and room.co
- Updated daily to reflect current asking prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CO One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CO page](https://unique.domains/domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
