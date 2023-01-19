---
title: "PVLDB"
author: "Donatus Herre (SLUB Dresden)"
subtitle: "Bibliometric Analysis"
pagetitle: "PVLDB :: Bibliometric Analysis"
author-meta: "SLUB Dresden"
date: "2023-01-19"
lang: "en-US"
output:
  html_document:
    toc: true
    toc_depth: 3
    toc_float:
      collapsed: false
      smooth_scroll: false
    mathjax: null
    includes:
      after_body: assets/html/target.html
    keep_md: true
---





Branches: [main](https://github.com/slub/pvldb/tree/main) / [gh-pages](https://github.com/slub/pvldb/tree/gh-pages)

# Count Data





## Works



![](/home/runner/work/pvldb/pvldb/public/index_files/figure-html/crossref-works-count-plot-1.png)<!-- -->



![](/home/runner/work/pvldb/pvldb/public/index_files/figure-html/openalex-works-count-plot-1.png)<!-- -->

## Citations



![](/home/runner/work/pvldb/pvldb/public/index_files/figure-html/openalex-citations-count-plot-1.png)<!-- -->



![](/home/runner/work/pvldb/pvldb/public/index_files/figure-html/jcr-citations-count-plot-1.png)<!-- -->

# Raw Data

- Crossref
  - [prefixes](./data/crossref_prefixes_10-14778.json) (`10.14778`) [JSON, 135 B]
  - [members](./data/crossref_members_5777.json) (`5777`) [JSON, 4.78 KB] + [members](./data/crossref_members_320.json) (`320`) [JSON, 22.83 KB]
  - [journals](./data/crossref_journals_2150-8097.json) (`2150-8097`) [JSON, 4.43 KB]
  - [works](./data/crossref_works_filter-issn-2150-8097_works.json) (`filter=issn:2150-8097`) [JSON, 33.87 MB]
    - [prefixes](./data/crossref_works_filter-issn-2150-8097_prefixes.json) [JSON, 16 B]
    - [members](./data/crossref_works_filter-issn-2150-8097_members.json) [JSON, 21 B]
    - [dois](./data/crossref_works_filter-issn-2150-8097_dois.json) [JSON, 104.01 KB]
    - [dois-issue](./data/crossref_works_filter-issn-2150-8097_dois-issue.json) [JSON, 2.66 KB]
    - [dois-article](./data/crossref_works_filter-issn-2150-8097_dois-article.json) [JSON, 101.35 KB]
    - [citation](./data/crossref_works_filter-issn-2150-8097_citation.json) [JSON, 2.74 MB] (via OpenCitations)
      - [dois](./data/crossref_works_filter-issn-2150-8097_dois-citation.json) [JSON, 1.30 MB]
      - [issns](./data/crossref_works_filter-issn-2150-8097_issns-citation.json) [JSON, 44.19 KB]
      - [count-issns](./data/crossref_works_filter-issn-2150-8097_count-issns-citation.json) [JSON, 53.56 KB]
      - [count-issns](./data/crossref_works_filter-issn-2150-8097_count-issns-citation.csv) [CSV, 161.79 KB] (enriched via OpenAlex)
      - [year-types](./data/crossref_works_filter-issn-2150-8097_year-types-citation.json) [JSON, 1.02 MB]
    - [count-citation](./data/crossref_works_filter-issn-2150-8097_count-citation.json) [JSON, 116.22 KB] (via OpenCitations)
    - [reference](./data/crossref_works_filter-issn-2150-8097_reference.json) [JSON, 2.23 MB]
      - [dois](./data/crossref_works_filter-issn-2150-8097_dois-reference.json) [JSON, 0.88 MB]
      - [issns](./data/crossref_works_filter-issn-2150-8097_issns-reference.json) [JSON, 32.30 KB]
      - [count-issns](./data/crossref_works_filter-issn-2150-8097_count-issns-reference.json) [JSON, 39.06 KB]
      - [count-issns](./data/crossref_works_filter-issn-2150-8097_count-issns-reference.csv) [CSV, 119.58 KB] (enriched via OpenAlex)
      - [year-types](./data/crossref_works_filter-issn-2150-8097_year-types-reference.json) [JSON, 0.64 MB]
    - [count-reference](./data/crossref_works_filter-issn-2150-8097_count-reference.json) [JSON, 116.94 KB]
    - [year-types](./data/crossref_works_filter-issn-2150-8097_year-types.json) [JSON, 80.50 KB]
- OpenAlex
  - [journals](./data/openalex_journals_V4210226185.json) (`V4210226185`) [JSON, 6.40 KB]

# Data Sources

- [Crossref API](https://api.crossref.org)
  - members
    - [320](https://api.crossref.org/members/320?mailto=bibliometrie@slub-dresden.de)
    - [5777](https://api.crossref.org/members/5777?mailto=bibliometrie@slub-dresden.de)
  - prefixes
    - [10.14778](https://api.crossref.org/prefixes/10.14778?mailto=bibliometrie@slub-dresden.de)
  - journals
    - [2150-8097](https://api.crossref.org/journals/2150-8097?mailto=bibliometrie@slub-dresden.de)
  - works
    - [filter=issn:2150-8097](https://api.crossref.org/works?filter=issn:2150-8097&mailto=bibliometrie@slub-dresden.de)
- [OpenCitations API](https://opencitations.net/index/coci/api/v1) (COCI)
  - citations
- [OpenAlex API](https://docs.openalex.org/api)
  - venues
    - [V4210226185](https://api.openalex.org/journals/V4210226185?mailto=bibliometrie@slub-dresden.de)
  - works
    - [filter=host_venue.id:V4210226185](https://api.openalex.org/works?filter=host_venue.id:V4210226185&mailto=bibliometrie@slub-dresden.de)

# Content Access

- VLDB Endowment
  - [PVLDB (Proceedings of the VLDB Endowment)](https://vldb.org/pvldb/)
- ACM DL > Collections > Hosted Content
    - [Proceedings of the VLDB Endowment](https://dl.acm.org/journal/pvldb)
- DBLP > Journals
    - [Proceedings of the VLDB Endowment](https://dblp.org/db/journals/pvldb/)

# Usage Terms

[![Creative Commons License](https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by.svg)](http://creativecommons.org/licenses/by/4.0/) This [document](#) is licensed under a [Creative Commons Attribution 4.0 International License](./LICENSE.txt).  
[![Public Domain Dedication](https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) The [raw data](#raw-data) is made available under the [CC0 1.0 Universal Public Domain Dedication](./data/LICENSE.txt).