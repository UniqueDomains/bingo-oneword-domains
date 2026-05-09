# Available .BINGO One-Word Domains (12,579)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C579%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .bingo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,579 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,579 domains · **Median ask:** $20.58 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/bingo`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/bingo?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./bingo.csv">CSV</a> / <a href="./bingo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BINGO search](https://unique.domains/domains/tld/bingo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BINGO search](https://unique.domains/domains/tld/bingo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BINGO one-word domain catalog.

### Files

- `bingo.csv` — public CSV extract (1,000 rows)
- `bingo.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bingo-oneword-domains/main/bingo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Tools.bingo        | available | $68.98    | —             | 56             | 40     | 5      | namecheap |
| matcha.bingo       | available | $14.99    | —             | 86             | 39     | 6      | name.com  |
| justin.bingo       | available | $14.99    | —             | 58             | 38     | 7      | name.com  |
| WiFi.bingo         | available | $68.98    | —             | 83             | 37     | 5      | namecheap |
| aliens.bingo       | available | $14.99    | —             | 56             | 35     | 6      | name.com  |
| homes.bingo        | available | $14.99    | —             | 86             | 34     | 5      | name.com  |
| spectra.bingo      | available | $14.99    | —             | 62             | 34     | 7      | name.com  |
| partners.bingo     | available | $14.99    | —             | 61             | 32     | 8      | name.com  |
| William.bingo      | available | $68.98    | —             | 74             | 31     | 7      | namecheap |
| solutions.bingo    | available | $14.99    | —             | 56             | 31     | 9      | name.com  |
| videos.bingo       | available | $14.99    | —             | 52             | 30     | 6      | name.com  |
| heroes.bingo       | available | $14.99    | —             | 68             | 29     | 6      | name.com  |
| cams.bingo         | available | $14.99    | —             | 52             | 29     | 4      | name.com  |
| Jim.bingo          | available | $68.98    | —             | 78             | 28     | 3      | namecheap |
| doctors.bingo      | available | $14.99    | —             | 56             | 26     | 7      | name.com  |
| schools.bingo      | available | $14.99    | —             | 72             | 24     | 7      | name.com  |
| boats.bingo        | available | $14.99    | —             | 52             | 24     | 5      | name.com  |
| deeplearning.bingo | available | $14.99    | —             | 74             | 23     | 13     | name.com  |
| inhouse.bingo      | available | $14.99    | —             | 70             | 23     | 8      | name.com  |
| pls.bingo          | available | $14.99    | —             | 60             | 23     | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,579 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bingo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bingo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .bingo domains. The naming mix is wide: some are short and flexible, such as usual.bingo or pilot.bingo, while others are longer and more specific, such as nationalanthem.bingo. For founders, the key question is whether the word still feels memorable and ownable when paired with .bingo. For investors, the main test is whether the term has enough clarity and commercial relevance to support resale interest at the current ask. Median ask is 20.58, so comparison should focus less on headline price and more on word quality, fit with the .bingo extension, and obvious trademark risk in names like disney.bingo.

- All names in this selection use the .bingo extension
- Median ask across the set is 20.58
- Best fits are clear words that pair naturally with .bingo
- Avoid obvious trademark exposure such as brand-linked terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BINGO One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BINGO page](https://unique.domains/domains/tld/bingo?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bingo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
