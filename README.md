# New Shopify Stores: aggregate statistics (US)

Aggregate statistics on newly launched US Shopify stores, updated regularly by [Ecommerce Store Leads](https://ecommercestoreleads.com/new-shopify-stores/).

We take newly registered domains, keep those whose DNS points to Shopify (23.227.38.0/24), and audit each open store's public `/meta.json` and live homepage for 8 marketing gaps: email/SMS capture, Google tag, Meta pixel, reviews app, social links, homepage meta description, free default theme and homepage speed.

**This repository contains aggregate numbers only.** No store names, domains or contact details.

## Files

| File | Contents |
|---|---|
| `data/new-shopify-stores-stats.csv` | Funnel (domains scanned → on Shopify → open US stores audited), share of stores with each gap, niches, states, themes, with the date of the data |

## Latest report

[New Shopify Stores Report: October 2026](https://ecommercestoreleads.com/reports/new-shopify-stores-october-2026/): key findings, method and limits.

## Method and limits

Full method: https://ecommercestoreleads.com/how-it-works/. Gaps are detected from known app and tag signatures in the public homepage, so a tool loaded in an unusual way can be missed. State is the store address set in Shopify; registered-agent addresses make some states (for example Wyoming) look larger.

## License

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit "Ecommerce Store Leads" with a link to https://ecommercestoreleads.com/new-shopify-stores/.
