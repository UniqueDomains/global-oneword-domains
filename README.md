# Available .GLOBAL One-Word Domains (13,605)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C605%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .global one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,605 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,605 domains · **Median ask:** $470.63 · **High-demand under $2,500:** 1

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/global`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/global?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./global.csv">CSV</a> / <a href="./global.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GLOBAL search](https://unique.domains/domains/tld/global?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GLOBAL search](https://unique.domains/domains/tld/global?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GLOBAL one-word domain catalog.

### Files

- `global.csv`, public CSV extract (1,000 rows)
- `global.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/global-oneword-domains/main/global.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| ane.global  | available | $34.98    | $127.98       | low            | low    | 3      | namecheap                                           |
| pure.global | resell    | $59,225   | —             | high           | medium | 4      | Chengdu West Dimension Digital Technology Co., Ltd. |
| aft.global  | premium   | $3,000    | $62.50        | low            | low    | 3      | name.com                                            |
| bum.global  | available | $34.98    | $127.98       | low            | low    | 3      | namecheap                                           |
| day.global  | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC                                        |
| Ann.global  | premium   | $3,000    | —             | high           | low    | 3      | name.com                                            |
| ixc.global  | available | $34.98    | $127.98       | low            | low    | 3      | namecheap                                           |
| door.global | resell    | —         | —             | high           | low    | 4      | Xiamen ChinaSource Internet Service Co., Ltd        |
| atp.global  | premium   | $3,000    | —             | medium         | low    | 3      | name.com                                            |
| xlv.global  | available | $34.98    | $127.98       | low            | low    | 3      | namecheap                                           |
| luck.global | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC                                    |
| awe.global  | premium   | $5,000    | —             | high           | low    | 3      | name.com                                            |
| acne.global | available | $59.99    | —             | medium         | low    | 4      | name.com                                            |
| move.global | resell    | —         | —             | high           | medium | 4      | Dynadot Inc                                         |
| bay.global  | premium   | $3,000    | $62.50        | low            | low    | 3      | name.com                                            |
| awny.global | available | $34.98    | $127.98       | low            | low    | 4      | namecheap                                           |
| rein.global | resell    | —         | —             | high           | low    | 4      | Xiamen ChinaSource Internet Service Co., Ltd        |
| bud.global  | premium   | $5,000    | —             | high           | low    | 3      | name.com                                            |
| belt.global | available | $59.99    | —             | high           | low    | 4      | name.com                                            |
| roll.global | resell    | —         | —             | medium         | low    | 4      | Xiamen ChinaSource Internet Service Co., Ltd        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,605 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/global?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/global?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=related_pricing)

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

This set covers one-word domain names registered under the .global TLD, spanning dictionary words, compound phrases, and character-style names such as Apples.global, DaffyDuck.global, and superhero.global. With 10,846 domains in this list and a median ask price of $697, .global offers broad naming room at accessible price points. Names range from literal terms like furnishings.global and dogwalking.global to action phrases like getmoving.global and makehappen.global, giving investors a wide field to compare spread and founders a clear shortlist of ownable, brandable names.

- 10,846 one-word .global domains, median ask ~$697
- Mix of dictionary, compound, and brandable names
- Examples: Superhero.global, Apples.global, DaffyDuck.global
- Updated daily for pricing and renewal comparison

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GLOBAL One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GLOBAL page](https://unique.domains/domains/tld/global?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_global_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
