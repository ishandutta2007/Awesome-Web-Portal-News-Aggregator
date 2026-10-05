# Awesome-Web-Portal-News-Aggregator

## Top Web Portal & News Aggregator Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Feed Aggregation, Personalized News & Self-Hosted Reading*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Web Portals and News Aggregation**. These tools collect, organize, and personalize news and RSS feeds — from algorithmically curated mainstream portals to self-hosted feed readers with full data ownership.



**Examples** include Microsoft MSN, Yahoo News, AOL, Google News, Apple News, Flipboard, SmartNews, Feedly, NewsBreak, and Inoreader (the category leaders).



**Open-source emphasis**: Feed reading is one of the strongest open-source domains, with a 25-year lineage from Google Reader through **FreshRSS**, **Miniflux**, **CommaFeed**, and **Tiny Tiny RSS**. Self-hosted aggregators offer full data ownership, no algorithmic filtering, and privacy-first reading — the ideological counterpoint to ad-driven portals.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

> **Market Intelligence**: The global news aggregator market is estimated at **~$2.15 Billion** (growing at ~11.2% CAGR), exhibiting **high concentration** dominated by major tech platforms (Google News, Apple News, Microsoft MSN, Yahoo News) with winner-take-most distribution dynamics.

| Platform | Description | Company Size / Valuation | Pricing (Starting Tier) | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple News](https://www.apple.com/apple-news/)** | Curated news app with human editors and algorithmic personalization. | ~$3.40 Trillion Market Cap (Apple Inc.) | $12.99/mo (Apple News+) | Free access to standard aggregated news feeds; paid publication access restricted to 1-month free trial |
| **[Microsoft MSN](https://www.msn.com/)** | Microsoft's consumer web portal aggregating news, weather, sports, finance, and lifestyle content from thousands of publishers. | ~$3.10 Trillion Market Cap (Microsoft Corp.) | Free ($0/mo) | Unlimited ad-supported news browsing (free Microsoft account required for feed personalization) |
| **[Google News](https://news.google.com/)** | Algorithmic news aggregator with full coverage, topic following, and local news using AI. | ~$2.10 Trillion Market Cap (Alphabet Inc.) | Free ($0/mo) | Unlimited ad-supported news browsing across web and mobile apps |
| **[Yahoo News](https://news.yahoo.com/)** | Long-standing news aggregator with editorial curation plus personalized "For You" feed. | ~$5.0 Billion Valuation (Yahoo / Apollo Global) | Free ($0/mo) | Unlimited ad-supported news browsing across categories and regional topics |
| **[AOL](https://www.aol.com/)** | Yahoo-owned portal with news aggregation, email, and lifestyle content. | ~$5.0 Billion Valuation (Yahoo / Apollo Global) | Free ($0/mo) | Unlimited ad-supported portal and news reading |
| **[SmartNews](https://www.smartnews.com/)** | News aggregator focused on discovering quality journalism with machine learning channels. | ~$2.0 Billion Valuation (SmartNews Inc.) | Free ($0/mo) | Unlimited news article reading and offline channel caching |
| **[NewsBreak](https://www.newsbreak.com/)** | Hyperlocal news aggregator with contributor network and local news focus. | ~$1.0 Billion Valuation (Particle Media Inc.) | Free ($0/mo) | Unlimited local and national news stream browsing |
| **[Flipboard](https://flipboard.com/)** | Magazine-style news aggregator with topic-based "Magazines" and community curation. | ~$800 Million Valuation (Flipboard Inc.) | Free ($0/mo) | Unlimited magazine creation, topic following, and feed reading |
| **[Feedly](https://feedly.com/)** | Commercial RSS reader with AI-powered "Leo" for prioritization and keyword filtering. | ~$15 Million Revenue (DevHD Inc.) | $6.00/mo ($72/yr billed annually) | Up to 100 total sources across 3 folders/feeds (no AI features or rules) |
| **[Inoreader](https://www.inoreader.com/)** | Powerful RSS reader with advanced automation rules, search, and team collaboration. | ~$4 Million Revenue (Innologica Ltd.) | $2.50/mo ($30/yr billed annually) | Up to 150 RSS feeds, 20 newsletter feeds, 20 web feeds, and 30-day search history |



## Open-Source GitHub Projects



- **[FreshRSS](https://github.com/FreshRSS/FreshRSS)**  

  The leading self-hosted RSS aggregator with 8,000+ GitHub stars and AGPL-3.0 license. PHP-based, supports WebSub, XPath scraping for sites without feeds, OPML import/export, and multi-user with per-user feed management. **Docker deployment** and extensive themes/plugins. **The most widely adopted open-source Google Reader replacement** — mature, actively maintained, and feature-complete.



- **[Miniflux](https://github.com/miniflux/v2)**  

  Minimalist, opinionated RSS reader with 7,000+ GitHub stars and Apache-2.0 license. Go-based single binary with PostgreSQL backend. **Lightweight and fast** — deliberately minimal feature set focused on reading. Supports Fever and Google Reader APIs for mobile app compatibility (Reeder, Unread, etc.). Excellent for users who want speed over feature breadth.



- **[CommaFeed](https://github.com/Athou/commafeed)**  

  Self-hosted Google Reader-inspired RSS reader with Java backend and Angular frontend. **Lightweight and simple** — closer to the original Google Reader experience than FreshRSS. Supports OPML, category organization, and mobile-friendly UI. Docker deployment.



- **[Tiny Tiny RSS](https://git.tt-rss.org/fox/tt-rss)**  

  Veteran self-hosted RSS reader (since 2005) with plugin architecture, filters, and mobile apps. PHP/PostgreSQL or MySQL. **Highly extensible** — plugin ecosystem supports custom scoring, filters, and integrations. Development shifted to a self-hosted Git repository.



- **[RSSHub](https://github.com/DIYgod/RSSHub)**  

  The most important open-source project for feed generation, with 39,000+ GitHub stars. **Generates RSS feeds for websites that don't offer them** — including Weibo, Bilibili, YouTube, Twitter/X, Telegram, and 1,000+ sources. Self-hostable or use public instances. **Essential companion to any self-hosted reader** — without RSSHub, many modern sites would be unfollowable.



- **[Feedly (open-source alternatives collection)](https://github.com/AboutRSS/ALL-about-RSS)**  

  Comprehensive curated list of RSS tools, readers, and services with 5,000+ stars. **The definitive resource for discovering RSS software** — includes readers, generators, filters, and protocol implementations.



- **[Winds](https://github.com/GetStream/Winds)**  

  Open-source personalized news and podcast app with RSS support and algorithmic ranking. React/Node.js stack. **Note**: development has slowed significantly; primarily a reference architecture for feed ranking and recommendation systems.



- **[Kriss Feed](https://github.com/tontof/kriss_feed)**  

  Simple, lightweight PHP RSS reader with MySQL/SQLite. **Minimalist and fast** — good for low-resource servers or users wanting the simplest possible self-hosted reader.



- **[Leed](https://github.com/ldleman/Leed)**  

  Self-hosted RSS aggregator with mobile-friendly interface and plugin architecture. PHP/MySQL. **French-origin project** with a clean, modern UI and notification support.



- **[Selfoss](https://github.com/fossar/selfoss)**  

  Open-source multi-purpose RSS reader, live stream, and mashup content aggregator with PHP backend. **Supports multiple feed types** — RSS, Atom, JSON, and HTML scraping. Docker deployment.



- **[Yarr](https://github.com/nkanaev/yarr)**  

  Simple, minimal RSS reader written in Go — single binary with embedded SQLite. **Extremely lightweight** — starts instantly and runs on minimal hardware. Good for Raspberry Pi and low-resource environments.



### Additional Strong Open-Source Options



- **RSS-Bridge** — Companion to RSSHub, generating feeds for sites without RSS using PHP bridges. Community-maintained with 200+ bridges.

- **Feedbin** — Open-source RSS reader (Ruby) powering the commercial Feedbin service. Self-hostable with advanced filtering and save-for-later.

- **NewsBlur** — Open-source RSS reader (Python/Django) with commercial hosting. Supports intelligence filtering, story training, and social sharing.

- **Fever** — Paid PHP RSS reader with self-hosted license; popular API-compatible target for mobile apps.



**Frameworks for building custom news aggregation solutions**: Combine **FreshRSS** for a full-featured, multi-user self-hosted reader with plugin ecosystem, **Miniflux** for minimal, fast reading with API compatibility, **RSSHub** for generating feeds from sites without RSS, and **RSS-Bridge** as a secondary feed generator. For mobile integration, Miniflux and FreshRSS support Fever/Google Reader APIs compatible with Reeder, Unread, and NetNewsWire. For personalization, **Winds** provides a reference architecture for ranking and recommendation, though active development has slowed.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- News aggregators and portals may filter, rank, or editorialize content. Self-hosted readers provide **full user control** over sources and reading order — the primary reason to choose them over algorithmic portals.

- Self-hosted solutions require proper infrastructure, regular feed updates, and ongoing maintenance. **RSSHub public instances may rate-limit or restrict access** — self-host for reliability.

- **Google Reader's shutdown in 2013** remains the canonical cautionary tale for relying on proprietary feed readers. Open-source self-hosted readers are immune to this risk.



---



**Made for RSS enthusiasts, privacy-conscious readers, researchers, and self-hosting advocates.**  

Let's make news aggregation more open, transparent, and user-controlled.
