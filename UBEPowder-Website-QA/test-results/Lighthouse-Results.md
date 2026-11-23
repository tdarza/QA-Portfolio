# UBEPowder Website – Lighthouse Performance Results

## 1. Overview

Google Lighthouse was used to assess the website's performance, accessibility, best practices and SEO across desktop and mobile devices.

Testing covered two pages:

- Homepage
- Ube Powder product page

Five Lighthouse runs were conducted for each page and device combination, resulting in **20 total audits**.

The results below represent the average scores and metrics from those five runs.

## 2. Average Lighthouse Scores

| Page | Device | Performance | Accessibility | Best Practices | SEO |
|---|---|---:|---:|---:|---:|
| Homepage | Desktop | 83.6 | 88 | 77 | 92 |
| Homepage | Mobile | 36.6 | 88 | 73.8 | 92 |
| Ube Powder product page | Desktop | 87.2 | 81 | 76.2 | 100 |
| Ube Powder product page | Mobile | 56.6 | 81 | 77 | 100 |

## 3. Average Performance Metrics

| Page | Device | FCP | LCP | TBT | CLS | Speed Index |
|---|---|---:|---:|---:|---:|---:|
| Homepage | Desktop | 1.14 s | 2.16 s | 38 ms | 0 | 2.06 s |
| Homepage | Mobile | 5.20 s | 30.54 s | 996 ms | 0.0104 | 9.58 s |
| Ube Powder product page | Desktop | 1.06 s | 2.00 s | 18 ms | 0 | 1.54 s |
| Ube Powder product page | Mobile | 4.04 s | 8.60 s | 378 ms | 0 | 4.18 s |

**Metric definitions:**
- **FCP:** First Contentful Paint – time until the first content appears.
- **LCP:** Largest Contentful Paint – time until the largest visible content element loads.
- **TBT:** Total Blocking Time – time the main thread is blocked and unable to respond to user input.
- **CLS:** Cumulative Layout Shift – measures unexpected movement of page elements.
- **Speed Index:** Measures how quickly visible page content is populated.

## 4. Key Observations

- Desktop Performance scores were higher than mobile scores on both tested pages.
- The homepage had the lowest Performance score, averaging 36.6 on mobile.
- Homepage mobile LCP averaged 30.54 seconds, indicating a significant loading performance concern.
- The Ube Powder product page performed better than the homepage on mobile, with an average Performance score of 56.6.
- Accessibility and SEO scores were consistent across desktop and mobile for each tested page.

## 5. Conclusion

The Lighthouse results indicate that mobile performance is the main area requiring attention, particularly on the homepage.

The results provide a baseline for future comparison after performance improvements are implemented.

*Note: Lighthouse scores and metrics can vary between runs depending on network conditions, device emulation and other environmental factors.*
