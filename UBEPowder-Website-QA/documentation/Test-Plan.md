# Test Plan – Astoria Philippine Ube Powder Website

**Tester:** Tristan Darza  
**Website:** https://ubepowder.com.ph/  
**Plan date:** November 9, 2026  
**Testing period:** November 9–23, 2026

## 1. Objective

Beta test the website to identify functional, usability, compatibility and performance issues through manual testing and an additional AI-assisted review.

## 2. Scope

### In scope
- Navigation and links
- Shop listings and product pages
- Shopping cart functionality (adding and removing items, quantity changes, coupons and promotions; excluding final order placement)
- Cookie banner and preferences
- Search and FAQ
- Language switcher
- Mobile layout and responsiveness
- Page performance using Google Lighthouse

### Out of scope
- Security testing
- External websites and domains
- Form submissions, order placement and payment processing (excluded pending site owner approval)

## 3. Test Environment

- **Website environment:** Live production website; no staging environment is available.
- **Desktop:** Windows PC, Google Chrome 156.0.8078.81.
- **Mobile:** iPhone 15, Google Chrome.

## 4. Test Approach

Manual exploratory and functional testing was performed across desktop and mobile devices. Defects were documented in Jira, while testing coverage and results were tracked in Google Sheets.

Google Lighthouse was used to assess page performance across desktop and mobile, with five runs conducted for each selected page and device combination.

An additional AI-assisted review was conducted using Codex to identify potential issues that may not have been found during the initial testing. Relevant findings were manually retested and reproduced before being added to the Jira defect log. Duplicate findings and issues outside the agreed testing scope were excluded.

## 5. Assumptions and Risks

Testing was performed on the live website, without access to a staging environment. Any website updates during the testing period may affect functionality and test results.

The AI-assisted review was conducted separately from the original manual testing and should be considered supplementary. Findings were not treated as confirmed defects until manually verified.

## 6. Deliverables

- Testing overview and results in Google Sheets
- Jira bug reports
- One-page final QA summary
