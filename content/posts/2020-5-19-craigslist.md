---
title: "Craigslist search operators"
date: 2020-05-19T23:15:21Z
---

I'm currently searching for a second vehicle and have been trolling Craigslist postings.
I have [saved searches](https://www.craigslist.org/about/saved_searches_and_alerts) set up, but was receiving a lot of false positives because nothing stops unrelated postings from keyword stuffing.

I found that Craigslist has surprising robust [search operators](https://www.craigslist.org/about/help/search).

For example, I used this search:

```
hybrid -truck -.com -ford -buick -dodge -chrysler -hyundai -lincoln -kia -cadillac
```

I'm looking for a `hybrid`, and don't want any post with `truck` or various manufacturers or `.com` (which is typically a dealer, I'm looking for a private seller).

I could explicitly look for `honda` or `toyota`, but I don't want to miss out on the small chance that someone misspells one of those brands.

## Other operators

From the Craigslist docs, other search operators include:
- Exact match using quotes: `"honda"`
- Exclusion: `-ford`
- Or: `honda | toyota`
- Wildcards: `h*nda`
