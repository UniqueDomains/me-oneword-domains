# Available .ME One-Word Domains (60,302)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-60%2C302%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .me one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **60,302 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 60,302 domains · **Median ask:** $10,168.09 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `me.csv` — public CSV extract (1,000 rows)
- `me.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/me-oneword-domains/main/me.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar           |
| --------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------- |
| abbot.me        | available | $11.99     | $26.99        | 50             | 80     | 5      | name.com            |
| advisory.me     | resell    | $6,541.20  | $26.99        | 80             | 17     | 8      | Dynadot Inc         |
| debit.me        | premium   | $6,250     | $26.99        | 96             | 88     | 5      | name.com            |
| Westwood.me     | available | $23.98     | —             | 66             | 20     | 8      | namecheap           |
| treatment.me    | resell    | $19,548.85 | $27.99        | 78             | 15     | 9      | Dynadot Inc         |
| ice.me          | premium   | $59,225    | —             | 68             | 44     | 3      | Tucows Domains Inc. |
| goforgold.me    | available | $23.98     | —             | 74             | 15     | 11     | namecheap           |
| ribbit.me       | resell    | —          | —             | 104            | 88     | 6      | GoDaddy.com, LLC    |
| east.me         | premium   | $3,750     | $27.99        | 72             | 28     | 4      | name.com            |
| WikiLeaks.me    | available | $23.98     | —             | 53             | 13     | 9      | namecheap           |
| license.me      | resell    | —          | —             | 84             | 88     | 7      | GoDaddy.com, LLC    |
| butter.me       | premium   | $5,266.29  | —             | 78             | 27     | 6      | name.com            |
| facilitation.me | available | $23.98     | —             | 74             | 12     | 12     | namecheap           |
| neon.me         | resell    | —          | —             | 78             | 88     | 4      | Dynadot Inc         |
| childcare.me    | premium   | $7,105.82  | —             | 74             | 23     | 10     | name.com            |
| Amazons.me      | available | $9.99      | $19.99        | 60             | 12     | 7      | namesilo            |
| ignition.me     | resell    | —          | —             | 70             | 88     | 8      | Dynadot Inc         |
| fog.me          | premium   | $11,843.82 | —             | 68             | 19     | 3      | name.com            |
| businesses.me   | available | $23.98     | —             | 60             | 12     | 10     | namecheap           |
| Aga.me          | resell    | —          | —             | 60             | 88     | 6      | Dynadot Inc         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 60,302 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/me?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/me?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=related_pricing)

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

These domains are all .me names, a TLD often used for personal branding, direct calls to action, and memorable keyword phrases. In this selection, the range runs from concise terms like true.me and guts.me to descriptive names like happybirthday.me and sportsbar.me. That makes evaluation less about one single style and more about fit. When comparing these domains, focus on whether the phrase sounds natural with .me, whether the ask justifies the strength of the word, and whether the name carries trademark exposure. Names tied to famous brands or public figures need extra caution.

- Check whether the word reads naturally with .me
- Use the $10,168 median ask as a pricing reference
- Favor clear, memorable words over long literal phrases
- Avoid names with obvious brand or name-rights risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ME One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ME page](https://unique.domains/domains/tld/me?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_me_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
