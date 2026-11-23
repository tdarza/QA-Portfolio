# Astoria Philippine Ube Powder Website – Final QA Summary

**Project:** Astoria Philippine Ube Powder Website  
**Testing period:** November 9–23, 2026  
**Testing type:** Manual website testing and Lighthouse performance testing

## 1. Project Overview

The purpose of this testing was to evaluate the functionality, usability, responsiveness and performance of the website across desktop and mobile devices.

## 2. Testing Scope

Testing covered website navigation, links, content, shop listings, product pages, shopping cart functionality, search, cookies, language switching and mobile responsiveness. Lighthouse audits were also performed on the homepage and Ube Powder product page.

An additional AI-assisted review was conducted using Codex. Relevant findings were manually retested on desktop and mobile before being added to Jira.

## 3. Test Results

A total of **13 issues** were documented in Jira (KAN-1 to KAN-13):

- 9 issues identified during the original manual testing.
- 4 additional issues identified through the AI-assisted follow-up review and independently reproduced.

The original nine issues were classified as Low severity and Low priority. The four additional tickets received their own classifications during the follow-up review.

Key issues included:

- Inconsistent navigation behaviour and an incorrect Google Maps destination.
- Content spelling errors and a product sorting issue.
- Incorrectly persistent messages and layout shifts on product pages and in the shopping cart.
- Unnecessary blank space on the left side of pages in mobile landscape orientation.
- Search results leading to 404 pages and displaying irrelevant, internal-looking snippets.
- Non-functional recovery links on the 404 error page.
- The Discounts page returning an HTTP 500 Server Error despite being listed in the sitemap.

Several important functions also passed testing, including basic product search queries, cookie preferences, language switching and core shopping cart operations such as quantity changes, subtotal calculations, item removal and cart persistence.

## 4. Lighthouse Performance Results

Five Lighthouse runs were conducted for each page and device combination. The average Performance scores were:

| Page | Desktop | Mobile |
|---|---:|---:|
| Homepage | 83.6 | 36.6 |
| Ube Powder product page | 87.2 | 56.6 |

Mobile performance was notably lower than desktop performance, particularly on the homepage. The homepage's mobile Largest Contentful Paint (LCP) averaged **30.54 seconds**, indicating a significant loading performance concern.

## 5. Testing Limitations

Contact forms were not submitted, and checkout, order placement, payment processing and security testing were excluded from the agreed testing scope.

## 6. Conclusion and Recommendations

Testing identified 13 issues, alongside several areas of successful functionality. The additional AI-assisted review helped uncover further defects, which were manually verified before documentation.

Prioritise the reported issues, particularly mobile performance, search functionality and layout behaviour. Retest affected areas after fixes are implemented.
