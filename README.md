# Available .ME One-Word Domains (34,047)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-34%2C047%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .me one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **34,047 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 34,047 domains · **Median ask:** $1,018.77 · **High-demand under $2,500:** 409

**Last updated:** 2026-09-28
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

| domain          | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                                               |
| --------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| bilk.me         | available | $1.98      | $23.98        | medium         | low    | 4      | namecheap                                               |
| room.me         | resell    | $25,286.20 | $27.99        | high           | low    | 4      | Dynadot Inc                                             |
| upon.me         | premium   | $20,010    | $16.52        | high           | low    | 4      | namesilo                                                |
| dour.me         | available | $9.99      | $19.99        | medium         | low    | 4      | namesilo                                                |
| bosses.me       | resell    | $23.98     | —             | high           | low    | 6      | Dominet (HK) Limited                                    |
| below.me        | premium   | $8,280     | $16.52        | high           | low    | 5      | namesilo                                                |
| sewn.me         | available | $1.98      | $23.98        | high           | low    | 4      | namecheap                                               |
| sirens.me       | resell    | $9.99      | $19.99        | medium         | low    | 6      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| women.me        | premium   | $7,500.01  | —             | high           | low    | 5      | name.com                                                |
| ascus.me        | available | $9.99      | $19.99        | high           | low    | 5      | namesilo                                                |
| factories.me    | resell    | $9.99      | $19.99        | medium         | low    | 9      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| member.me       | premium   | $3,750     | —             | high           | low    | 6      | name.com                                                |
| aunts.me        | available | $9.99      | $19.99        | medium         | low    | 5      | namesilo                                                |
| solutions.me    | resell    | $17,248.85 | $27.99        | high           | low    | 9      | Dynadot Inc                                             |
| despite.me      | premium   | $3,749.99  | —             | high           | low    | 7      | name.com                                                |
| frore.me        | available | $9.99      | $19.99        | medium         | low    | 5      | namesilo                                                |
| underwriting.me | resell    | $2,298.85  | $27.99        | high           | high   | 12     | Dynadot Inc                                             |
| confusion.me    | premium   | $1,667.50  | $27.99        | high           | low    | 9      | name.com                                                |
| roily.me        | available | $1.98      | $23.98        | medium         | low    | 5      | namecheap                                               |
| azo.me          | resell    | —          | —             | high           | low    | 3      | Spaceship, Inc.                                         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 34,047 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 409 high-demand names under $2,500         |
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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

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
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ME One-Word Domains*. Version 2026-09-28. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ME page](https://unique.domains/domains/tld/me?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
