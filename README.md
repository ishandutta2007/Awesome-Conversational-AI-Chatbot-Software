# Awesome Conversational AI & Chatbot Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated directory of the best **Conversational AI platforms**, **AI chatbot software**, **open-source customer support platforms**, and **visual flow builders**.

**Last updated: November 2026**

[![GitHub Stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Conversational-AI-Chatbot-Software?style=social)](https://github.com/ishandutta2007/Awesome-Conversational-AI-Chatbot-Software)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Conversational-AI-Chatbot-Software#how-to-contribute)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)

This repository tracks top-tier **SaaS platforms** and **open-source conversational AI projects**. Whether you are building self-hosted LLM customer support agents, designing multi-channel visual conversation flows, or integrating live agent handoff and RAG-powered knowledge bases, this guide covers the entire landscape.

---

## Table of Contents

- [Quick Comparison: Open Source vs SaaS](#quick-comparison-open-source-vs-saas)
- [SaaS & Hosted Conversational AI Platforms](#saashosted-platforms)
- [Open-Source Chatbot & Support Projects](#open-source-github-projects)
  - [Core Open-Source Projects](#core-open-source-projects)
  - [Additional Open-Source Options & Frameworks](#additional-strong-open-source-options)
- [Architecture & Selection Guide](#architecture--selection-guide)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & Evaluation Notes](#disclaimer)

---

## Quick Comparison: Open Source vs SaaS

| Category | Primary Focus | Representative Solutions | Best For |
|:---|:---|:---|:---|
| **Enterprise SaaS Support** | Turnkey AI agents + helpdesk inbox | Intercom, Zendesk AI, Ada | Fast deployment, enterprise SLAs, managed infra |
| **B2B Marketing & Lead Capture** | Qualified leads, meeting scheduling, conversational forms | Drift, Qualified, Typebot | Inbound marketing, sales pipeline acceleration |
| **Social & E-commerce Chatbots** | Automated DMs on IG, WhatsApp, Messenger | ManyChat, Chatfuel, Tidio | DTC brands, social commerce, SMB marketing |
| **Self-Hosted Support Inbox** | Multi-channel inbox with human handoff & bots | Chatwoot, Chaskiq | Full data ownership, privacy, GDPR compliance |
| **Custom NLU / ML Frameworks** | Full dialogue management & on-prem model training | Rasa | Regulated industries, deep NLP customization |
| **Visual LLM Builders & Agents** | Flow orchestration, hybrid AI + agent handoff | Botpress, Tiledesk, LangBot | Complex agent workflows, hybrid human-in-the-loop |

---

## SaaS/Hosted Platforms

| Platform | Category / Primary Focus | Pricing Model | Free Tier Limits | Key Highlights & Best For |
|:---|:---|:---|:---|:---|
| **[Intercom](https://www.intercom.com/)** | AI-first customer service & helpdesk | Quote-only; resolution-based pricing for Fin AI | **No free tier** (Free trial available) | Mature Fin AI Agent + unified support inbox. Premium pricing; best for scaling support teams. |
| **[HubSpot Chatbot Builder](https://www.hubspot.com/)** | Inbound marketing, CRM & live chat | Included in Free/Starter/Pro/Enterprise Sales & Service Hubs | **Yes** (Free CRM tier includes basic bot builder) | Seamless CRM integration, lead qualification, and automated ticketing. |
| **[Drift](https://www.drift.com/)** *(Salesloft)* | Conversational marketing & B2B sales | Custom quote / annual contracts | **No free tier** | B2B lead acceleration, pipeline routing, and automated calendar scheduling. |
| **[Tidio](https://www.tidio.com/)** | SMB live chat & Lyro AI customer service | Tiered plans per seat/agent + AI add-ons | **Yes** (Free plan includes up to 50 Lyro AI conversations/mo) | Turnkey live chat and conversational bot setup for e-commerce and SMBs. |
| **[Zendesk AI](https://www.zendesk.com/)** | Omnichannel enterprise ticketing & AI agents | Per-agent subscription + AI bundle add-ons | **No free tier** (Trial available) | Deeply unified ticketing, knowledge base integration, and enterprise triage workflows. |
| **[Ada](https://www.ada.cx/)** | Enterprise agentic CX & resolution automation | AWS Marketplace entry at ~$33k/yr (60k convos); enterprise tiers $60k+/yr | **No free tier** (Consultation-only) | Action-taking agents connecting deeply with back-end enterprise APIs and CRMs. |
| **[LivePerson](https://www.liveperson.com/)** | Enterprise conversational cloud & voice/messaging | Quote-only custom contracts | **No free tier** | High-volume multi-channel messaging and call-center voice automation. |
| **[ManyChat](https://manychat.com/)** | Social media chat marketing (Instagram, WhatsApp, Messenger) | Free tier; Pro scaling with contact list volume | **Yes** (Up to 1,000 contacts with basic features) | Creator economy and e-commerce campaigns across Meta direct messaging channels. |
| **[Chatfuel](https://chatfuel.com/)** | No-code chatbot builder for social platforms | Tiered plans by conversations/contacts | **Yes** (Trial/starter tier with limited conversations) | Rapid no-code bot creation for Facebook Messenger and Instagram DMs. |
| **[Qualified](https://www.qualified.com/)** | Conversational marketing & AI SDR for B2B | Custom enterprise pricing | **No free tier** | Real-time website visitor identification, automated inbound SDR qualification, and Salesforce syncing. |

---

## Open-Source GitHub Projects

### Core Open-Source Projects

#### [Chatwoot](https://github.com/chatwoot/chatwoot)
- **License**: MIT
- **GitHub Stars**: ~38k+
- **Tech Stack**: Ruby on Rails, Vue.js, PostgreSQL, Redis
- **Deployment**: Self-hosted (Docker, Kubernetes, Heroku, 1-Click) or Chatwoot Cloud
- **Overview**: The leading open-source Intercom alternative. Provides an omnichannel customer support inbox connecting website live chat, email, WhatsApp, Telegram, Facebook, and Twitter. Features Captain AI for LLM-powered response generation, multi-agent collaboration, private notes, auto-assignment, and seamless human agent handoff.
- **Trade-off**: Advanced autonomous agent capabilities require external webhooks or the Captain AI add-on.

#### [Rasa](https://github.com/RasaHQ/rasa)
- **License**: Apache-2.0
- **GitHub Stars**: ~21k+
- **Tech Stack**: Python, TensorFlow/PyTorch
- **Deployment**: Self-hosted, Kubernetes / Helm
- **Overview**: The enterprise-grade machine learning framework for conversational AI, contextual dialogue management, and intent classification. Ideal for engineering and ML teams requiring complete control over language models, offline on-prem execution, and zero third-party data leaks.
- **Trade-off**: Developer framework, not an out-of-the-box product. Does not include an agent inbox or prebuilt UI widget.

#### [Botpress](https://github.com/botpress/botpress)
- **License**: MIT (Integrations & Devtools) / Proprietary Cloud
- **GitHub Stars**: ~14k+
- **Tech Stack**: TypeScript, Node.js, React
- **Deployment**: Botpress Cloud (primary); legacy v12 available for self-hosting
- **Overview**: A visual conversation studio and agent developer ecosystem. Features a flow editor, autonomous LLM agent execution, knowledge base vector indexing, and prebuilt integrations for messaging channels (Slack, WhatsApp, Teams).
- **Trade-off**: Main repository focuses on cloud-first devtools and integrations rather than fully sovereign on-prem server deployments.

#### [Typebot](https://github.com/theluckystrike/typebot.io)
- **License**: Fair Source / Functional Source License (FSL)
- **GitHub Stars**: ~18k+
- **Tech Stack**: TypeScript, Next.js, Docker
- **Deployment**: Self-hosted (Docker Compose) or Typebot Cloud
- **Overview**: A conversational flow builder tailored for lead qualification, interactive surveys, and conversational forms. Includes 34+ building blocks (conditional branching, payments, file uploads, webhooks, OpenAI triggers, and analytics).
- **Trade-off**: Not designed for multi-tier helpdesks or live ticket management. FSL license limits direct commercial hosting competition.

#### [Tiledesk](https://github.com/tiledesk/tiledesk)
- **License**: AGPL / Open-source components
- **GitHub Stars**: ~1k+ ecosystem stars
- **Tech Stack**: Node.js, JavaScript, MongoDB
- **Deployment**: Docker Compose, Kubernetes Helm Charts
- **Overview**: Open-source customer engagement platform combining visual LLM flow design with integrated human agent routing. A sovereign alternative to Voiceflow and Drift with native web chat widgets and live agent escalation.
- **Trade-off**: Smaller community compared to Chatwoot or Rasa.

---

### Additional Strong Open-Source Options

- **[Chaskiq](https://github.com/chaskiq/chaskiq)** — Full-featured conversational marketing and customer support platform (Ruby on Rails). Includes web messenger, automated messaging campaigns, bots, help center, and omnichannel integrations.
- **[LangBot](https://github.com/langbot/langbot)** — LLM-native chatbot framework with interactive WebUI, multi-agent execution pipelines, passkey security, and plugins connecting to Dify, Coze, n8n, and Claude.
- **[MaxKB](https://github.com/1Panel-dev/MaxKB)** — Ready-to-use RAG (Retrieval-Augmented Generation) knowledge base assistant for internal enterprise documentation and semantic document search.

---

## Architecture & Selection Guide

When selecting conversational software, align your technical requirements with the right layer of the conversational stack:

```
+-------------------------------------------------------------------------+
|                              END USER                                   |
+-------------------------------------------------------------------------+
                                    |
      +-----------------------------+-----------------------------+
      | (Visual Forms & Surveys)    | (Live Web/Omnichannel Chat) |
      v                             v                             v
+-------------+              +--------------+             +---------------+
|   Typebot   |              |   Chatwoot   |             |    Tidio /    |
| (Lead Gen)  |              | (Inbox + AI) |             |   Intercom    |
+-------------+              +--------------+             +---------------+
                                    |
                    +---------------+---------------+
                    |                               |
                    v                               v
          +-------------------+           +-------------------+
          |  Rasa / Custom ML |           |  Botpress Cloud / |
          |   (NLU / On-Prem) |           |  LangBot / RAG    |
          +-------------------+           +-------------------+
```

1. **Need sovereign data and on-prem compliance?** Build around **Chatwoot** (inbox/handoff) connected with **Rasa** or self-hosted LLM endpoints.
2. **Need fast lead qualification on web forms?** Embed **Typebot** or **HubSpot Chatbots**.
3. **Need turnkey support with minimal engineering overhead?** Evaluate **Intercom**, **Zendesk AI**, or **Tidio**.
4. **Need complex multi-turn LLM reasoning?** Leverage **Botpress** or **Tiledesk** with retrieval-augmented generation (RAG).

---

## How to Contribute

Contributions are welcome! Please follow these guidelines:

1. Fork this repository.
2. Add your suggested tool under the appropriate section in alphabetical order.
3. For SaaS platforms, include: tool name, pricing model, free tier availability/limits, and target use case.
4. For open-source tools, include: repository link, license, tech stack, deploy methods, and trade-offs.
5. Create a descriptive pull request explaining why the project adds value to the community.

---

## Disclaimer

- This list is community-curated for informational purposes and does not imply official endorsement.
- Ensure all conversational AI deployments handling sensitive customer data comply with regulatory standards (GDPR, CCPA, HIPAA, SOC 2).
- Commercial pricing is subject to frequent vendor changes. Always verify latest tier structures directly with vendor sales teams.

---

*Curated with care for developers, support leaders, and AI architects.*
