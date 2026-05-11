# Available .NET One-Word Domains (37,561)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-37%2C561%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .net one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **37,561 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 37,561 domains · **Median ask:** $19,878.21 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `net.csv` — public CSV extract (1,000 rows)
- `net.json` — public JSON extract (1,000 rows)
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

| domain          | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                                   |
| --------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| makehappen.net  | available | $16.49     | —             | 80             | 3      | 11     | name.com                                    |
| settledown.net  | available | $16.49     | —             | 80             | 2      | 11     | name.com                                    |
| year.net        | premium   | $65,147.50 | —             | 88             | 14     | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| Mario.net       | premium   | $59,225    | —             | 80             | 35     | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| refresh.net     | premium   | $41,457.50 | —             | 80             | 26     | 7      | GoDaddy Online Services Cayman Islands Ltd. |
| pierogi.net     | premium   | $3,065.49  | —             | 82             | 7      | 7      | Annulet LLC                                 |
| butterflies.net | premium   | $20,136.50 | —             | 90             | 8      | 11     | GoDaddy Online Services Cayman Islands Ltd. |
| primarycare.net | premium   | $10,660.50 | —             | 81             | 11     | 12     | GoDaddy Online Services Cayman Islands Ltd. |
| Acup.net        | resell    | —          | —             | 80             | 5      | 5      | GoDaddy.com, LLC                            |
| gearup.net      | resell    | —          | —             | 80             | 16     | 7      | Wild West Domains, LLC                      |
| chaitea.net     | resell    | —          | —             | 86             | 3      | 8      | GoDaddy.com, LLC                            |
| keepfit.net     | resell    | —          | —             | 86             | 9      | 8      | GoDaddy.com, LLC                            |
| backyard.net    | resell    | —          | —             | 80             | 27     | 9      | GoDaddy Online Services Cayman Islands Ltd. |
| takepart.net    | resell    | —          | —             | 80             | 5      | 9      | GoDaddy.com, LLC                            |
| cometrue.net    | resell    | —          | —             | 82             | 5      | 9      | Spaceship, Inc.                             |
| makelove.net    | resell    | —          | —             | 88             | 10     | 9      | SNAPNAMES 4, LLC                            |
| commercial.net  | resell    | —          | —             | 81             | 26     | 10     | GoDaddy.com, LLC                            |
| getmarried.net  | resell    | —          | —             | 88             | 5      | 11     | GoDaddy.com, LLC                            |
| information.net | resell    | —          | —             | 88             | 26     | 11     | GoDaddy.com, LLC                            |
| comicrelief.net | resell    | —          | —             | 80             | 5      | 12     | Dynadot Inc                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 37,561 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This set is entirely focused on .net domains. The names range from short dictionary words such as year.net and refresh.net to more descriptive or phrase-led options like primarycare.net, makehappen.net, and settledown.net. For founders, the main question is whether a .net version is memorable enough for direct brand use. For investors, the key is whether the word quality, category fit, and ask leave room relative to likely end-user demand. With a median ask of $17,818, price discipline matters. When comparing these domains, weigh brevity, spelling ease, commercial intent, and whether the wording feels timeless rather than niche or trend-bound.

- Single-word .net names tend to be clearer and more reusable
- Phrase .net domains can fit exact-use cases but narrow buyer depth
- Median ask is $17,818, so price selectivity matters
- Check spelling, category fit, and trademark exposure first

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NET One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NET page](https://unique.domains/domains/tld/net?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_net_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
