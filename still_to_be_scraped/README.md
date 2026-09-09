# ⏳ Still To Be Scraped — Timeout Queue (1,634,710 Stores)

During the rapid cluster harvest across 1,902,056 Shopify stores, **1,634,710 stores (85.9%)** timed out due to the high-concurrency 3-second network deadline.

These domains represent an untapped reservoir of potential DTC leads ready for re-crawling with increased latency tolerance or residential proxies.

---

## 📁 Files in this Directory

| Filename | Records | Size | Description |
| :--- | :---: | :---: | :--- |
| **`still_to_be_scraped_part1.csv`** | ~817,355 | ~65 MB | Part 1 of timed out stores (Domain, Brand, Niche) |
| **`still_to_be_scraped_part2.csv`** | ~817,355 | ~65 MB | Part 2 of timed out stores |
| **`still_to_be_scraped_all_timeouts.csv.gz`** | 1,634,710 | ~23 MB | Complete unified dataset compressed |

---

## 📋 Schema

- `Domain`: Root domain of the storefront.
- `Brand`: Discovered brand name.
- `Niche`: Classified product category guess.
- `HTTP_Status`: Network error code (`error:Timeout`).
- `Rejection_Reason`: Failure reason (`no_html:error:Timeout`).
- `Scraped_At`: Timestamp of initial crawl attempt.
