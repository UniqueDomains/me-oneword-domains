# Available .ME One-Word Domains (62,910)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-62%2C910%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .me one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **62,910 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 62,910 domains · **Median ask:** $2,278.69 · **High-demand under $2,500:** 180

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/me`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/me?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./me.csv">CSV</a> / <a href="./me.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ME search](https://unique.domains/domains/tld/me?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ME search](https://unique.domains/domains/tld/me?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ME one-word domain catalog.

### Files

- `me.csv`, public CSV extract (1,000 rows)
- `me.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/me-oneword-domains/main/me.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar       |
| ------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | --------------- |
| count.me      | premium   | $7,500     | —             | high           | low    | 5      | name.com        |
| clxv.me       | available | $9.99      | $19.99        | low            | low    | 4      | namesilo        |
| rogue.me      | resell    | $5,789.84  | —             | medium         | low    | 5      | NameSilo, LLC   |
| east.me       | premium   | $3,750     | $27.99        | high           | low    | 4      | name.com        |
| lvii.me       | available | $9.99      | $19.99        | low            | low    | 4      | namesilo        |
| advisory.me   | resell    | $6,541.20  | $26.99        | medium         | low    | 8      | Dynadot Inc     |
| high.me       | premium   | $35,533.82 | —             | medium         | low    | 4      | Dynadot Inc     |
| abbot.me      | available | $11.99     | $26.99        | medium         | high   | 5      | name.com        |
| treatment.me  | resell    | $19,548.85 | $27.99        | high           | low    | 9      | Dynadot Inc     |
| into.me       | premium   | $7,499.99  | —             | medium         | low    | 4      | name.com        |
| anile.me      | available | $9.99      | $19.99        | low            | low    | 5      | namesilo        |
| employment.me | resell    | $4,560.32  | —             | high           | low    | 10     | Dynadot Inc     |
| sort.me       | premium   | $7,500     | —             | high           | low    | 4      | name.com        |
| Rhoda.me      | available | $9.99      | $19.99        | medium         | low    | 5      | namesilo        |
| BOJ.me        | resell    | —          | —             | medium         | high   | 3      | Spaceship, Inc. |
| soppy.me      | available | $9.99      | $19.99        | low            | low    | 5      | namesilo        |
| NPR.me        | resell    | —          | —             | medium         | high   | 3      | Dynadot Inc     |
| debit.me      | premium   | $6,250     | $26.99        | high           | high   | 5      | name.com        |
| bardic.me     | available | $10.98     | $23.98        | low            | low    | 6      | namecheap       |
| ares.me       | resell    | —          | —             | medium         | high   | 4      | Edomains LLC    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 62,910 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 180 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/me?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/me?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=related_pricing)

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

One-word .me domains pair short, memorable names with a globally recognized personal-branding extension. This set includes names like shakehands.me, getmarried.me, and out.me — spanning lifestyle, emotion, and action-based one-word terms. With a median ask near $4,364 across 60,329 listings, pricing varies widely based on word commonality, syllable count, and category relevance. Whether the goal is resale potential or a future brand, renewal cost and search-friendly spelling remain the key differentiators among these domains.

- 60,329 one-word .me domains with median ask near $4,364
- Short, personal-branding names across lifestyle and action themes
- Compare pricing, renewal cost, and brandability before buying
- Updated daily to reflect current one-word .me availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ME One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ME page](https://unique.domains/domains/tld/me?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
