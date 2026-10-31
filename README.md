# InsightfulPipe Analytics & CRO Skills

**38 free Claude skills for Google Analytics 4, conversion tracking and CRO: GA4 audits and reports, UTM and attribution audits, A/B and incrementality tests, funnel drop-off, landing page, form and signup audits.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills/measurement); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/analytics-cro-skills
/plugin install insightfulpipe-analytics-cro@insightfulpipe-analytics-cro
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/analytics-cro-skills
```

Add `--skill attribution-model-auditor` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (38)

| Skill | What it does | |
|---|---|---|
| [A/B Test Designer](skills/ab-test-designer/) | Designs and reads out A/B tests on Google Ads, GA4 pages and email, with sample size, duration, significance and a winner verdict. | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ab-test-designer) |
| [Ad Landing Page Match Scorer](skills/ad-landing-page-match-scorer/) | Scores each active Google Ads or Meta ad against its landing page for headline, offer, keyword and audience match plus mobile speed, ranked by spend. | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/ad-landing-page-match-scorer) |
| [Attribution Model Auditor](skills/attribution-model-auditor/) | Audits attribution windows, models and click vs view credit across Google Ads, Meta, LinkedIn, Microsoft Ads, TikTok and GA4, then recommends a model and source of truth. | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/attribution-model-auditor) |
| [B2B Pipeline and Revenue Attribution](skills/pipeline-revenue-attribution/) | Credits CRM pipeline and closed revenue to every source and campaign from a CRM export plus ad spend, with cost per opportunity and won deal, first vs last touch… |  |
| [Bulk UTM Link Builder](skills/bulk-utm-links/) | Builds UTM links in bulk for launches, newsletters, creators, partners and QR codes, reusing GA4 spellings and showing each link's channel, plus matching campaign names… |  |
| [Call Tracking Analyst](skills/call-tracking-analyst/) | Analyses phone calls from CallRail or any call log CSV, grading real leads by source, campaign and keyword, pricing missed calls by hour, and checking Google Ads call… |  |
| [Checkout Optimization Auditor](skills/checkout-cro-auditor/) | Audits an online store checkout step by step in GA4, checks Shopify, WooCommerce or Magento orders and checkout screenshots, and ranks fixes by revenue at stake. |  |
| [Consent Mode Auditor](skills/consent-mode-auditor/) | Audits Google Consent Mode v2 and the cookie banner from HAR files or Tag Assistant, checks what fires before consent, and estimates the GA4 sessions and Google Ads… |  |
| [Conversion Tracking Auditor](skills/conversion-tracking-auditor/) | Audits conversion tracking across Google Ads, GTM, GA4, Meta and LinkedIn, checking what counts, broken tags, double counting, lag and offline imports, plus tracking QA… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/conversion-tracking-auditor) |
| [Cross Channel Attribution Analyst](skills/cross-channel-attribution-analyst/) | Compares first-touch, last-click and GA4 model credit per channel against spend and claims from Google Ads, Meta, LinkedIn, Microsoft Ads and TikTok, with CPA and ROAS… | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/cross-channel-attribution-analyst) |
| [Form CRO](skills/form-cro/) | Audits lead, contact, demo and quote forms field by field and checks the GA4 form_start to form_submit funnel, giving keep, cut or make optional verdicts. | [Page](https://insightfulpipe.com/marketing-claude-skills/cro/form-cro) |
| [Funnel Dropoff Diagnostician](skills/funnel-dropoff-diagnostician/) | Finds where a signup, checkout or lead funnel loses people, from GA4 events plus Google Ads, Meta, LinkedIn and Search Console steps, and ranks leaks by conversions lost. | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/funnel-dropoff-diagnostician) |
| [GA4 Audience Retention](skills/ga4-audience-retention/) | Analyses GA4 users with new vs returning trends, weekly retention cohorts, user value by first channel, device, browser, country and city splits, the mobile gap and… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ga4-audience-retention) |
| [GA4 BigQuery Query Writer](skills/ga4-bigquery-query-writer/) | Writes, explains, fixes and runs BigQuery SQL on the GA4 export for sessions, page paths, ordered funnels, multi-touch attribution, cohort LTV and Google Ads cost per… |  |
| [GA4 Channel Performance](skills/ga4-channel-performance/) | Reports GA4 channel and source/medium performance with spend from Google Ads, Meta, LinkedIn, Microsoft Ads and TikTok for cost and ROAS, and checks referral quality… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ga4-channel-performance) |
| [GA4 Ecommerce Funnel](skills/ga4-ecommerce-funnel/) | Analyses a store's GA4 ecommerce, with the purchase funnel, checkout drop-off by device, cart abandonment, product and channel revenue and the AOV trend, after checking… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ga4-ecommerce-funnel) |
| [GA4 Landing Page Analyst](skills/ga4-landing-page-analyst/) | Analyses GA4 landing pages for engagement, key events and leaks, paid vs organic fit with Google Ads cost and Search Console clicks, scroll depth, 404 pages and site… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ga4-landing-page-analyst) |
| [GA4 Property Audit](skills/ga4-property-audit/) | Audits a GA4 property's setup and data quality, from streams, key events, retention and links to Unassigned traffic, bots and coverage against Search Console, or walks… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ga4-property-audit) |
| [GA4 Weekly Report](skills/ga4-weekly-report/) | Builds a GA4 weekly or monthly report with week over week and year over year change, real vs noise verdicts, channel and page drivers, daily anomalies and key events. | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/ga4-weekly-report) |
| [Gtm Container Auditor](skills/gtm-container-auditor/) | Audits a Google Tag Manager container for dead tags, trigger logic, consent settings, naming, versions and workspace conflicts, and builds missing GA4 event tracking… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/gtm-container-auditor) |
| [Heatmap and Session Recording Analyst](skills/heatmap-session-analyst/) | Ranks Microsoft Clarity or Hotjar rage clicks, dead clicks, quick backs and scroll depth by the GA4 conversions each costs, and names the Clarity recording filters to… |  |
| [How Did You Hear About Us Survey Analyst](skills/self-reported-attribution/) | Writes or fixes a how did you hear about us question, codes every answer into channels with margins of error, and matches answers to GA4 orders to show what tracking… |  |
| [Incrementality Test Designer](skills/incrementality-test-designer/) | Designs incrementality tests before launch, geo holdout, audience holdout or platform lift, from Google Ads, GA4 and Meta data, sized from your own volume, with a dated… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/incrementality-test-designer) |
| [Junk Lead and Form Spam Investigator](skills/junk-lead-investigator/) | Finds where spam, bot and poor-fit leads come from, grading each lead in a CRM or form export and tracing junk to campaign, placement, page and form, then ranks form… |  |
| [Landing Page Auditor](skills/landing-page-auditor/) | Audits a landing page, homepage or sales page for conversion using GA4, Search Console, Google Ads and desktop and mobile renders, scoring seven pillars and ranking… | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/landing-page-auditor) |
| [Marketing Data Warehouse and SQL Builder](skills/marketing-data-warehouse/) | Designs and checks a cross-channel marketing data warehouse, writes staging, union and MERGE SQL, finds missing days and duplicates and reconciles spend with ad… |  |
| [Marketing Forecast](skills/marketing-forecast/) | Forecasts leads, spend and revenue for the next two months or a 12-month plan year by channel, from Google Ads, Meta, LinkedIn, Microsoft Ads, GA4 or pasted history… |  |
| [Marketing Mix Model Builder](skills/marketing-mix-model-builder/) | Builds a marketing mix model from weekly channel spend and total sales or leads, with carryover, diminishing returns and lift test calibration, giving ROI ranges… |  |
| [Measurement Plan Builder](skills/measurement-plan-builder/) | Builds a measurement plan from what GA4, Search Console, Google Ads, Meta, LinkedIn and Tag Manager track today, with a North Star metric, a KPI tree with baselines and… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/measurement-plan-builder) |
| [Offline Conversion Setup](skills/offline-conversion-setup/) | Sets up offline conversion imports so Google Ads, Microsoft Ads, Meta, LinkedIn and ChatGPT Ads bid on CRM stages, valuing each stage and writing a GCLID hidden field… |  |
| [Onboarding CRO](skills/onboarding-cro/) | Maps the new user journey in GA4 from first visit to activation and return, finds the biggest drop and designs the onboarding fix and emails, reading Klaviyo flows. | [Page](https://insightfulpipe.com/marketing-claude-skills/cro/onboarding-cro) |
| [Pricing Page Auditor](skills/pricing-page-auditor/) | Audits a pricing page from GA4 behaviour (reach, scroll, next pages, plan clicks) and eight pillars like tier architecture, anchoring and CTA clarity, with rewrites and… | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/pricing-page-auditor) |
| [Server-Side Tracking Planner](skills/server-side-tracking-planner/) | Decides if a site needs server-side tracking by weighing orders GA4 and ad platforms miss against hosting cost, then plans the server GTM container, Conversions API… |  |
| [Signup Flow CRO](skills/signup-flow-cro/) | Audits a signup or registration flow, checks GA4 sees sign_up, measures the funnel and tears down the signup page fields, SSO and password rules. | [Page](https://insightfulpipe.com/marketing-claude-skills/cro/signup-flow-cro) |
| [TV, Offline Media and Geo Lift Analyst](skills/offline-media-lift-analyst/) | Measures lift from TV, CTV, radio, billboards, events and sponsorships, and reads out finished geo holdout tests, with a 95% interval, a placebo check and cost per… |  |
| [Utm Auditor](skills/utm-auditor/) | Audits UTM tagging in GA4 and tracking templates, URL suffixes and URL tags in Google Ads, Meta and LinkedIn, finds case splits and untagged ads, and writes one naming… | [Page](https://insightfulpipe.com/marketing-claude-skills/measurement/utm-auditor) |
| [Website Conversion Rate Benchmark](skills/conversion-rate-benchmark/) | Benchmarks a website or store conversion rate against dated, sourced industry figures by channel, device and landing page type, from GA4 or pasted numbers, and prices… |  |
| [Website Personalization Planner](skills/website-personalization-planner/) | Plans website and landing page personalization from GA4, Google Ads and LinkedIn data, picking visitor groups that convert below the rest, writing their headline and… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
