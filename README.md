# Available .NET One-Word Domains (37,055)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-37%2C055%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .net one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **37,055 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 37,055 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/net`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/net?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./net.csv">CSV</a> / <a href="./net.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .NET search](https://unique.domains/domains/tld/net?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .NET search](https://unique.domains/domains/tld/net?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .NET one-word domain catalog.

### Files

- `net.csv` — public CSV extract (10,000 rows)
- `net.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/net-oneword-domains/main/net.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar                                   |
| ------------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| getoutthevote.net   | available | $16.49      | $23.99        | 74             | 80     | 16     | name.com                                    |
| mathematics.net     | resell    | $19,550     | $23.99        | 64             | 92     | 11     | Network Solutions, LLC                      |
| sundries.net        | premium   | $2,861.20   | $23.99        | 68             | 92     | 8      | Annulet LLC                                 |
| cocktailcabi.net    | available | $16.49      | $19.99        | 64             | 80     | 16     | name.com                                    |
| maincourse.net      | resell    | $2,286.20   | $23.99        | 70             | 84     | 11     | GoDaddy.com, LLC                            |
| mint.net            | premium   | $264,498.85 | $23.99        | 72             | 78     | 4      | GoDaddy.com, LLC                            |
| affiance.net        | available | $16.49      | $19.99        | 85             | 76     | 8      | name.com                                    |
| stamping.net        | resell    | $2,171.20   | $23.99        | 60             | 84     | 8      | GoDaddy Online Services Cayman Islands Ltd. |
| takeout.net         | premium   | $1,150,000  | $23.99        | 88             | 72     | 7      | Wild West Domains, LLC                      |
| monoclonal.net      | available | $16.49      | $23.99        | 70             | 76     | 10     | name.com                                    |
| welding.net         | resell    | $27,600     | $23.99        | 58             | 84     | 7      | Sea Wasp, LLC                               |
| april.net           | premium   | $43,826.50  | —             | 74             | 63     | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| mapprojection.net   | available | $16.49      | $23.99        | 56             | 72     | 14     | name.com                                    |
| carhire.net         | resell    | $17,582.35  | $23.99        | 58             | 84     | 8      | Tucows Domains Inc.                         |
| proof.net           | premium   | $148,062.50 | —             | 74             | 38     | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| batchproduction.net | available | $16.49      | $23.99        | 56             | 72     | 16     | name.com                                    |
| privateequity.net   | resell    | $201,250    | $23.99        | —              | 84     | 14     | GoDaddy.com, LLC                            |
| urban.net           | premium   | $52,670     | $23.99        | 62             | 35     | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| abdominalwall.net   | available | $16.49      | $23.99        | 54             | 72     | 14     | name.com                                    |
| contracting.net     | resell    | $5,493.55   | $23.99        | 78             | 72     | 11     | GoDaddy.com, LLC                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 37,055 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/net?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/net?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NET One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NET page](https://unique.domains/domains/tld/net?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
