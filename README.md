# Awesome Customer Journey Orchestration (CJO)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Customer-Journey-Orchestration/blob/main/README.md#how-to-contribute)

> A curated list of top **Customer Journey Orchestration (CJO)** SaaS tools, open-source software, marketing automation platforms, and developer frameworks for lifecycle marketing, cross-channel engagement, and real-time behavioral automation.

---

## What is Customer Journey Orchestration?

**Customer Journey Orchestration (CJO)** is the discipline and technology of dynamically planning, automating, and tailoring personalized interactions across multiple channels (Email, SMS, Mobile Push, In-App, WhatsApp, Webhooks) based on real-time customer behavior, journey stage, and lifecycle milestones.

Whether you are evaluating enterprise SaaS or building a self-hosted modern growth stack, this directory covers top category leaders and developer-friendly open-source alternatives.

---

## Table of Contents

- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source Platforms & Self-Hosted Alternatives](#open-source-platforms--self-hosted-alternatives)
- [Complementary Infrastructure & CDP Tools](#complementary-infrastructure--cdp-tools)
- [Architecting an Open-Source Journey Stack](#architecting-an-open-source-journey-stack)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## SaaS / Hosted Platforms

Leading proprietary customer journey orchestration, cross-channel engagement, and lifecycle marketing platforms:

| Platform | Key Focus & Capabilities | Pricing / Free Tier |
| :--- | :--- | :--- |
| **[Customer.io](https://customer.io/)** | Behavioral messaging, event-driven email, push, SMS, in-app workflows & visual canvas for product-led growth (PLG). | Starts at ~$100/mo (Essentials); free 14-day trial available. No permanent free tier. |
| **[Braze](https://www.braze.com/)** | Enterprise cross-channel customer engagement, Canvas journey builder, real-time segmentation, and AI predictive suite. | Enterprise custom pricing based on MAU & channel volume. No free tier. |
| **[Iterable](https://iterable.com/)** | Unified customer communication platform, cross-channel journey designer, rich APIs, mobile SDKs, and predictive AI. | Custom enterprise quote based on data volume & message counts. No free tier. |
| **[Salesforce Journey Builder](https://www.salesforce.com/)** | Enterprise marketing cloud journey orchestration with Einstein AI personalization and unified CRM data integration. | Included in Salesforce Marketing Cloud editions; custom annual enterprise contract. No free tier. |
| **[Adobe Campaign](https://business.adobe.com/products/campaign.html)** | Enterprise campaign management, omnichannel delivery, and complex profile orchestration. *(Adobe Campaign Classic sunsetting March 2027)* | Custom enterprise licensing. No free tier. |
| **[CleverTap](https://clevertap.com/)** | Mobile-first customer lifecycle management, real-time analytics, automated journey funnels, and retention optimization. | Starts with tiered growth plans based on Monthly Active Users (MAU). No permanent free tier (trial available). |
| **[MoEngage](https://www.moengage.com/)** | Customer engagement platform for mobile and web apps, Sherpa AI-driven journey mapping, and omnichannel delivery. | Tiered pricing based on MAU; free plan/trial available for qualified early-stage startups (up to 10k MAU on select programs). |
| **[Bloomreach Engagement](https://www.bloomreach.com/)** | E-commerce CDP and journey orchestration, personalized web recommendations, and real-time triggers. | Custom enterprise pricing. No free tier. |
| **[Insider](https://insiderone.com/)** | AI-native cross-channel customer experience orchestration, predictive segments, WhatsApp & Web push automation. | Custom enterprise pricing based on contact volume and features. No free tier. |
| **[Acoustic Journey Analytics](https://acoustic.com/)** | Customer path analytics, interaction insights, behavioral friction detection, and triggered outbound campaigns. | Custom enterprise quote based on event volume. No free tier. |

---

## Open-Source Platforms & Self-Hosted Alternatives

Open-source journey automation engines and privacy-first platforms for developers and growth engineers seeking vendor independence:

| Project | License | Tech Stack & Highlights | Stars / Repo |
| :--- | :--- | :--- | :--- |
| **[Helio](https://github.com/achref-soua/helio)** | AGPL-3.0 | Temporal, AI-native CDP + cross-channel journeys (Email, SMS, Push, WhatsApp), MCP server, sustains ~20k events/s. | [GitHub](https://github.com/achref-soua/helio) |
| **[Dittofeed](https://github.com/Hexlet/dittofeed)** | MIT | TypeScript, ClickHouse, Temporal. Git-based workflows, testing SDK, drag-and-drop journey builder (Customer.io alternative). | [GitHub](https://github.com/Hexlet/dittofeed) |
| **[Laudspeaker](https://github.com/laudspeaker/laudspeaker)** | AGPL-3.0 | Node.js, PostgreSQL. Visual no-code canvas, event triggers, PostHog integration, multi-channel messaging (Braze alternative). | [GitHub](https://github.com/laudspeaker/laudspeaker) |
| **[Mautic](https://github.com/mautic/mautic)** | GPL-3.0 | PHP, MySQL. Community-driven marketing automation, email drip campaigns, lead scoring, and web tracking with full GDPR compliance. | [GitHub](https://github.com/mautic/mautic) |
| **[Corteza](https://github.com/cortezaproject/corteza)** | Apache-2.0 | Go, Vue.js. Low-code CRM & BPMN workflow engine for 360-degree customer records and automated business processes. | [GitHub](https://github.com/cortezaproject/corteza) |
| **[LimeJourney](https://github.com/limejourney/limejourney)** | Source-available | TypeScript, Next.js, Temporal, Kafka, ClickHouse. AI-driven dynamic segments and custom event triggers. | [GitHub](https://github.com/limejourney/limejourney) |

---

## Complementary Infrastructure & CDP Tools

Essential open-source tools to build an end-to-end customer data pipeline and event infrastructure:

- **[Apache Unomi](https://github.com/apache/unomi)** (Apache-2.0) — Customer Data Platform (CDP) server for profile consolidation and real-time persona segmentation.
- **[RudderStack](https://github.com/rudderlabs/rudder-server)** (AGPL-3.0) — Privacy-first open-source customer data pipeline to collect, route, and transform behavioral events.
- **[Jitsu](https://github.com/jitsucom/jitsu)** (MIT) — High-throughput event collection engine and lightweight open CDP alternative to Segment.
- **[Metarank](https://github.com/metarank/metarank)** (Apache-2.0) — Real-time personalization and ranking service driven by customer interaction events.
- **[OpenClix](https://github.com/OpenClix/openclix)** (MIT) — Mobile app retention and user engagement automation tool.
- **[Fusion](https://github.com/fusion-hq/fusion)** — In-app engagement, live chat, and push notification infrastructure.
- **[n8n](https://github.com/n8n-io/n8n)** (Fair-code) — Workflow automation tool often paired with transactional providers for multi-step journey execution.

---

## Architecting an Open-Source Journey Stack

To deploy an enterprise-grade, privacy-respecting self-hosted journey orchestration architecture:

```
[ User Touchpoints ] (Web / App / Mobile)
        │
        ▼ (Event Ingestion)
[ RudderStack / Jitsu ]
        │
        ▼ (Storage & Real-Time Querying)
[ PostgreSQL + ClickHouse ]
        │
        ▼ (Journey Logic & Execution)
[ Dittofeed / Helio / Laudspeaker / Mautic ]
        │
        ▼ (Dispatch Deliverability)
[ Email (SES/Resend) | SMS (Twilio) | Push (FCM/APNs) | WhatsApp ]
```

---

## How to Contribute

Contributions are welcome! To add or update an entry:

1. Fork this repository.
2. Add your tool to `README.md` in the appropriate category with factual, unbiased descriptions.
3. If adding a SaaS product, please include relevant pricing / tier details.
4. Ensure all links point to authoritative domains or repository homes.
5. Submit a Pull Request with a clear summary.

---

## Disclaimer

This repository is an independently curated educational list. Product names and logos are trademarks of their respective owners. Self-hosted platforms require proper infrastructure hardening, consent tracking, and deliverability configuration to comply with data privacy regulations (GDPR, CCPA, CAN-SPAM).
