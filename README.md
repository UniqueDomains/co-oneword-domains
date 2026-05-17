# Available .CO One-Word Domains (50,613)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-50%2C613%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .co one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **50,613 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 50,613 domains · **Median ask:** $16,523.27 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
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

- `co.csv` — public CSV extract (1,000 rows)
- `co.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/co-oneword-domains/main/co.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status  | ask_price | renewal_price | attractiveness | demand | length | registrar              |
| -------------- | ------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------- |
| croptop.co     | premium | —         | —             | 80             | 4      | 8      | —                      |
| sundeck.co     | premium | $17.99    | —             | 80             | 5      | 8      | name.com               |
| rolemodel.co   | premium | $700      | $700          | 85             | 6      | 10     | namecheap              |
| tips.co        | resell  | —         | —             | 80             | 26     | 4      | GoDaddy.com, LLC       |
| thick.co       | resell  | —         | —             | 80             | 10     | 5      | GoDaddy.com, LLC       |
| geton.co       | resell  | —         | —             | 82             | 10     | 6      | GoDaddy.com, LLC       |
| getup.co       | resell  | —         | —             | 82             | 15     | 6      | Network Solutions, LLC |
| around.co      | resell  | —         | —             | 84             | 22     | 6      | Porkbun                |
| Apples.co      | resell  | —         | —             | 90             | 16     | 6      | GoDaddy.com, LLC       |
| surebet.co     | resell  | —         | —             | 82             | 7      | 8      | Dynadot Inc            |
| chaitea.co     | resell  | —         | —             | 86             | 3      | 8      | Dynadot Inc            |
| bedframe.co    | resell  | —         | —             | 80             | 3      | 9      | Spaceship, Inc.        |
| getlucky.co    | resell  | —         | —             | 84             | 10     | 9      | Dynadot Inc            |
| cuddleup.co    | resell  | —         | —             | 89             | 4      | 9      | Dynadot Inc            |
| bonvoyage.co   | resell  | —         | —             | 88             | 16     | 10     | Dynadot Inc            |
| shoparound.co  | resell  | —         | —             | 80             | 3      | 11     | Network Solutions, LLC |
| affirmation.co | resell  | —         | —             | 82             | 10     | 11     | Dynadot Inc            |
| getmarried.co  | resell  | —         | —             | 88             | 5      | 11     | Spaceship, Inc.        |
| MickeyMouse.co | resell  | —         | —             | 86             | 11     | 12     | Sav.com, LLC - 1       |
| maximum.co     | resell  | —         | —             | 98             | 22     | 7      | Spaceship, Inc.        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 50,613 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/co?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/co?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=related_pricing)

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

This set is centered on .co domains, with many names leaning short, dictionary-based, and brandable. Examples such as sundeck.co, rolemodel.co, tips.co, and around.co show the range: literal words, broad concepts, action-oriented terms, and flexible brand names. For founders, the main question is whether a name is memorable, easy to say, and credible enough to build on. For investors, the key test is whether the ask leaves room versus comparable quality and likely buyer demand. With a median ask of 16,489, discipline matters. Strong .co names can feel modern and concise, but weaker matches may struggle if the word is awkward, overly narrow, or carries avoidable trademark risk.

- Prioritize clear, memorable words over clever but unclear terms
- Use ask price to separate premium names from speculative pricing
- Check plural, brand, and product-word trademark exposure carefully
- Favor .co names that sound natural when spoken aloud

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CO One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CO page](https://unique.domains/domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_co_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
