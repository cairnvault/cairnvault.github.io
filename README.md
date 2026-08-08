# research.cairnvault.app

The source of **[research.cairnvault.app](https://research.cairnvault.app/)** — CairnVault
Research's open, primary-source research on what actually happens to your accounts, passwords and
photos when you die.

This repository holds only the root of the site. The research itself lives in two repositories,
served under the same domain:

| Published at | Source |
|---|---|
| [research.cairnvault.app/digital-legacy-teardown/](https://research.cairnvault.app/digital-legacy-teardown/) | [cairnvault/digital-legacy-teardown](https://github.com/cairnvault/digital-legacy-teardown) |
| [research.cairnvault.app/digital-legacy-answers/](https://research.cairnvault.app/digital-legacy-answers/) | [cairnvault/digital-legacy-answers](https://github.com/cairnvault/digital-legacy-answers) |

Also here:

- **[/sitemap.xml](https://research.cairnvault.app/sitemap.xml)** — a sitemap index covering both
  child sitemaps and the root
- **[/llms.txt](https://research.cairnvault.app/llms.txt)** — a summary written for language models,
  because answer engines were reading this research before any search engine ranked it
- **[/robots.txt](https://research.cairnvault.app/robots.txt)** — everything here is meant to be
  crawled, quoted and cited

## What is published

- **[The digital-legacy teardown](https://research.cairnvault.app/digital-legacy-teardown/)** —
  every digital-legacy service, password manager and platform legacy-contact feature, on two axes:
  does the provider verify that you died, and can the provider read your data. With
  [a source for every claim](https://research.cairnvault.app/digital-legacy-teardown/sources.html).
- **[The comparison as an open dataset](https://research.cairnvault.app/digital-legacy-teardown/dataset.html)**
  — sixteen providers as [JSON](https://research.cairnvault.app/digital-legacy-teardown/data/digital-legacy-comparison.json)
  and [CSV](https://research.cairnvault.app/digital-legacy-teardown/data/digital-legacy-comparison.csv),
  every field carrying the source URL it was read from, `unknown` as a first-class value.
- **[Thirty questions, answered from primary sources](https://research.cairnvault.app/digital-legacy-answers/)**
  — one page per question people actually type into a search box.

## How to read it honestly

The publisher is **[CairnVault](https://cairnvault.app)**, which sells a product in this category.
That is stated at the top of every document, our own product appears in the dataset tagged as a
self-reported vendor claim rather than as research, and roughly a third of the claims we started
with did not survive checking and are published as dated retractions rather than quietly deleted.
Every claim links to somebody else's words for exactly that reason. Check us.

Everything is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Republish it, quote it,
translate it, contradict it.

*The research compares how products work. It is not legal advice.*
