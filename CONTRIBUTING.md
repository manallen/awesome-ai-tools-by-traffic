# Contributing

This repository aims to be a useful, source-aware research index. Contributions should make the mapping between a HuntAI-listed product and its associated traffic domain more accurate, not merely make the table longer.

## Good issues and pull requests

- A product profile points to the wrong official domain.
- A selected domain is actually a shared platform, social network, link shortener, or parent-company site and should be excluded.
- A newer HuntAI source snapshot is available and can update both the JSON file and README table.
- A visible title, product URL, or workflow label is factually incorrect.

## Required evidence

Please include the HuntAI product URL, the relevant source snapshot month, and a short explanation. For a domain correction, include a public official source that establishes the product-domain relationship.

Do not include private analytics, credentials, copied API keys, or unsupported traffic claims. This repository deliberately treats missing data as missing rather than estimating it from unrelated sources.

## Updating data

Keep the following fields synchronized:

1. `data/traffic-snapshot-YYYY-MM.json` contains exact numeric values and source metadata.
2. `README.md` contains the same selected rows in human-readable form.
3. The README's snapshot date and its caveats remain current.

One associated domain should appear at most once in a curated snapshot. If several HuntAI product records use the same domain, choose a representative record and explain any meaningful ambiguity in the pull request.
