# Awesome-Embedded-Ui-Component-Framework

## Top Embedded UI Component Framework Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Embeddable UI, Low-Code Integration & Developer SDKs*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded UI Component Frameworks**. These tools enable developers to embed interactive UIs, analytics dashboards, forms, and low-code applications directly into their existing products without building from scratch.



**Examples** include Salesforce Lightning Out, Retool Embed, SingleStore Embed, ThoughtSpot Everywhere, Sisense Compose SDK, Looker Embed SDK, Power BI Embedded, Appsmith Embed, Superblocks Embed, and DronaHQ Embed (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom UI component libraries, and open embedding SDKs — ideal for developers, product teams, and organizations seeking transparent, vendor-independent embedded UI solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The embedded analytics and UI component integration market is estimated at approximately **$70B–$78B** (with broader projections reaching $165B+ by the mid-2030s at an estimated CAGR of 13–15%). The market is **moderately fragmented**: mega-cap cloud providers (Microsoft, Alphabet, Salesforce) hold strong gravity in enterprise BI infrastructure, while specialized low-code platforms and API-first analytics pure-plays (Retool, ThoughtSpot, Sisense, Superblocks) vigorously compete and capture market share through developer agility and customizable embedded SDKs.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Pricing Tier | Free Tier / Trial Limits | Key Features & Embedding Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Power BI Embedded](https://docs.azure.cn/zh-cn/power-bi/developer/embedded/power-bi-playground)** | Microsoft (~$3.1T market cap / ~$245B annual revenue) | Starts at **$1.008/hour** (~$735.84/month for dedicated A1 capacity node: 1 v-Core, 3 GB RAM); standalone Pro license starts at **$10/user/month** | **Free Trial**: 60-day Power BI Pro trial (capped at 10 GB workspace per user, up to 1 GB dataset size); Power BI Embedded also offers testing sandbox tokens in developer playground | Embed Power BI reports, dashboards, and Q&As into applications. Developer sandbox provides hands-on coding experience with JavaScript and TypeScript SDKs. |
| **[Looker Embed SDK](https://codelabs.developers.google.cn/codelabs/looker-embed-sdk)** | Alphabet / Google Cloud (~$2.1T market cap / ~$350B annual revenue; Looker acquired for $2.6B) | Starts at **$5,000/month** (Standard Cloud platform fee + user licenses: Developer user at $125/user/month, Standard user at $60/user/month, Viewer at $30/user/month) | **Free Trial**: 30-day Google Cloud free trial with **$300 in free credits**; dedicated Looker POC trial available through sales (typically 14–30 days) | JavaScript library for embedding Looker dashboards and Looks into web applications. Automatically creates iframes and handles communication between parent page and embedded content. |
| **[Salesforce Lightning Out](https://developer.salesforce.com/)** | Salesforce (~$270B market cap / ~$34.9B annual revenue) | Starts at **$25/user/month** (Starter Suite / Sales Cloud Starter, billed annually) | **Free Trial**: 30-day free trial of Salesforce Enterprise/Starter Edition (unrestricted platform features, no credit card required); Developer Edition org is free forever (limited to 5 MB data storage, 20 MB file storage) | Embed Lightning components and apps into external web applications. Enables Salesforce UI components to render outside Salesforce, with authentication via OAuth. |
| **[ThoughtSpot Everywhere](https://developers.thoughtspot.com/docs/tsembed)** | ~$4.2B valuation / ~$150M+ ARR | Starts at **$25/user/month** (Essentials Plan, billed annually; Pro plan starts at $50/user/month or $0.10/credit consumption model) | **Free Trial**: 14-day free trial on Essentials & Pro plans (supports up to 5 users, sample datasets, full Search & Liveboard embed testing; no credit card required) | Visual Embed SDK for embedding ThoughtSpot components (Liveboards, Search, App) into web pages. Features component-level control, custom styling, and event handling. |
| **[Retool Embed](https://docs.retool.com/3.300/apps/guides/app-management/embed-apps)** | ~$3.2B valuation / ~$100M+ ARR | Starts at **$10/user/month** (Standard plan: $10/builder + $5/end-user/month; Business plan at $50/builder + $15/end-user/month; dedicated Retool Embed is available as a Business/Enterprise add-on) | **Free Plan**: Free forever for up to **5 users** (unlimited apps, 500 workflow runs/month, community support; does not include production white-label embed) | Embed Retool apps into existing web applications with React and JavaScript SDKs. Supports custom authentication with single-use embed URLs, permission groups, and session management. |
| **[SingleStore Embed](https://docs.singlestore.com/cloud/container-services/dashboard-apps/)** | ~$1.3B valuation / ~$100M+ ARR | Starts at **$0.99/hour** (on-demand compute credits at $3.96/credit; S-00 workspace consumes 0.25 credits/hour: 2 vCPU, 16 GB RAM) | **Free Plan**: Free Starter Workspace ($0/month, permanent shared tier capped at **1 GB compressed data storage** / ~4 GB uncompressed, 1 SQL database) plus $500 in signup trial credits | Publish Jupyter notebooks as Dashboard Apps using Plotly DashApps. Enables interactive dashboards embedded directly into applications with real-time query capabilities. |
| **[Sisense Compose SDK](https://developer.sisense.com/guides/choosing-an-integration.md)** | ~$1.0B+ valuation / ~$100M+ ARR | Starts at **~$10,000/year** (~$833/month) for entry-level Self-Serve / small-team configuration via custom annual contract | **Free Trial**: 7-day free trial of Sisense Fusion & Compose SDK (full developer toolkit and AI assistants access upon request) | Code-first, component-based SDK for React, Angular, Vue, and Web Components. Replaces legacy Sisense.JS for building custom analytics experiences programmatically. |
| **[Superblocks Embed](https://docs.superblocks.com/hosting/embedded-apps/quickstart)** | ~$150M+ valuation (raised $37M Series A) | Starts at **$100/month** (Teams plan billed annually at $1,200/year, or $125/month month-to-month; bundles up to 15 builder seats, unlimited end users, 1 hosted app) | **Free Trial**: 14-day free trial of Teams plan (unrestricted cloud builder features, staging & prod environments, 100 Governed Agent Units; no permanent free tier) | React and JavaScript SDKs for embedding Superblocks applications. Supports two-way communication with properties and events for theme, search, and navigation. |
| **[Appsmith Embed](https://docs.appsmith.com/advanced-concepts/embed-appsmith-into-existing-application)** | ~$120M+ valuation (raised $51.5M funding) | Starts at **$0.40/user/hour** (Business Cloud plan capped at $20/user/month); self-hosted Enterprise starting at ~$40/user/month | **Free Plan**: Free forever Community edition (unlimited users, unlimited apps, public embeds included; self-hosted open source Apache-2.0 or Community cloud) | Embed Appsmith applications in public or private mode. Private embeds require self-hosted instance or enterprise SSO configuration. |
| **[DronaHQ Embed](https://docs.dronahq.com/agents/getting-started/share-and-access-overview/standard-embed/)** | ~$30M+ valuation / ~$5M+ ARR | Starts at **$100/month** (Starter plan billed annually at $1,200/year, or $140/month billed monthly; unlimited users, 25,000 tasks/month) | **Free Trial**: 30-day free trial of Business Plan (unrestricted feature access, unlimited users, no credit card required; legacy free tier discontinued) | Embed public agents via iFrame or floating chat bubble script. Chat bubble provides least intrusive integration for customer support widgets. |



## Open-Source GitHub Projects



- **[Forest Admin](https://github.com/ForestAdmin/django-forestadmin)**  

  Open-source admin panel framework (MIT for core) that integrates directly into existing Django, Rails, Laravel, and Node.js backends . Provides embeddable admin UI components with automatic CRUD generation.



- **[NeoApps.AI-CodeGenerator](https://github.com/Neopric-Inc/NeoApps.AI-CodeGenerator)**  

  Open-source no-code/low-code app builder (license varies) focusing on data-first approach . Generates drag-and-drop React applications with .NET Core API and MySQL database.



- **[FiveUI](https://github.com/wqy2dev/five-ui)**  

  Beautiful, modern, open-source UI toolkit (MIT) built with Svelte 5 and Tailwind CSS . Features 40+ reusable components including Accordion, Button, Form, Modal, Table, Tabs, and more .



- **[Appsmith](https://github.com/appsmithorg/appsmith)**  

  Open-source low-code platform (Apache-2.0) for building internal tools. Features drag-and-drop UI builder, 45+ widgets, and embeddable applications via iframe.



- **[ToolJet](https://github.com/ToolJet/ToolJet)**  

  Open-source low-code platform (AGPL-3.0) for building internal tools. Features visual app builder, 50+ UI components, and embeddable apps.



- **[Budibase](https://github.com/Budibase/budibase)**  

  Open-source low-code platform (GPL-3.0) with powerful form and app building capabilities. Forms auto-generate from database schemas with validation and multi-column layouts.



- **[Baserow](https://github.com/baserow/baserow)**  

  Open-source no-code database tool (MIT) with Form view for creating shareable web forms. Transforms table structure into embeddable forms.



- **[Directus](https://github.com/directus/directus)**  

  Open-source data platform (BUSL-1.1) wrapping SQL databases with admin app and APIs. Can serve as backend for embedded UI components.



- **[Refine](https://github.com/refinedev/refine)**  

  Open-source React framework (MIT) for building admin panels, dashboards, and internal tools. Provides headless UI components for CRUD operations.



- **[React Admin](https://github.com/marmelab/react-admin)**  

  Open-source frontend framework (MIT) for building B2B applications on top of REST/GraphQL APIs. Features 100+ UI components and embeddable admin interfaces.



- **[Vue Form Making](https://github.com/gavinzhulei/vue-form-making)**  

  Open-source visual form designer (license varies) for Vue.js. Generates runnable code and JSON for embedding dynamic forms.



- **[form-create](https://github.com/xaboy/form-create)**  

  Open-source JSON-driven form generator (MIT) for dynamic web forms. Low-code form builder with Vue integration.



- **[Puck](https://github.com/measuredco/puck)**  

  Open-source visual editor for React (MIT). Drag-and-drop page building inside your own application with zero vendor lock-in.



### Additional Strong Open-Source Options



- **[GrapesJS](https://github.com/GrapesJS/grapesjs)** — Open-source web builder framework (BSD-3-Clause) for embedding visual editors.

- **[Plasmic](https://github.com/plasmicapp/plasmic)** — Open-source visual builder and headless CMS (MIT for core).

- **[Strapi](https://github.com/strapi/strapi)** — Leading open-source headless CMS (MIT) with embeddable admin UI.

- **[Payload CMS](https://github.com/payloadcms/payload)** — Open-source headless CMS (MIT) with customizable admin UI.

- **[KeystoneJS](https://github.com/keystonejs/keystone)** — Open-source headless CMS (MIT) with GraphQL API.

- Community **n8n** workflows for embedding automation and data routing.



**Frameworks for building custom systems**: Combine **Appsmith** or **ToolJet** as the low-code platform with **Forest Admin** for backend integration, **FiveUI** or **Refine** for custom UI components, and **Strapi** or **Directus** for data management — creating a fully self-hosted, enterprise-grade embedded UI platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Embedded UI frameworks handling user data must comply with data protection regulations (GDPR, CCPA, etc.).

- Self-hosted open-source solutions require proper security hardening, SSL configuration, and ongoing maintenance for production reliability.



---



**Made for developers, product engineers, and organizations building transparent embedded UI solutions.**  

Let's make Embedded UI Component Frameworks more open, data-driven, and flexible.
