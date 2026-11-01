# Awesome-Conversational-AI-Chatbot-Software

# Awesome-Conversational-AI-Chatbot-Software

# Awesome-Conversational-AI-Chatbot-Software

**Top Conversational AI Chatbot Software (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Visual Flow Builders, Live Chat Handoff, RAG Chatbots & Self-Hosted Support Platforms*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversational AI & Chatbot Software**. These tools enable teams to build chatbots, automate customer support, qualify leads, and hand off conversations to humans—from fully managed platforms with AI-native agent building to self-hosted frameworks that give organizations complete control over their conversation data and LLM choice.



**Examples** include HubSpot Chatbot Builder, Intercom, Drift, Tidio, Zendesk AI, Ada, LivePerson, ManyChat, Chatfuel, and Qualified (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted chatbots, live chat, and open support infrastructure. **Critical note**: The open-source landscape splits by function—**Rasa** is the enterprise NLU framework for teams training custom models , **Botpress** now points users to its Cloud platform while keeping integrations and devtools open source , **Typebot** excels at conversational forms but is not a support tool , and **Chatwoot** provides the full support inbox with bot handoff . No single open-source project matches Intercom's all-in-one polish, but a composed stack covers most needs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Intercom](https://www.intercom.com/)**

  **AI-first customer service platform** with Fin AI Agent, helpdesk, and messaging. **Pricing**: Quote-only; Fin resolution-based pricing. **Free tier**: None. **Best for**: teams wanting the most mature AI agent + inbox combination—**trade-off**: premium pricing.



- **[HubSpot Chatbot Builder](https://www.hubspot.com/)**

  **Chatbot and live chat** within HubSpot CRM. **Pricing**: Included with Sales Hub or Service Hub tiers; free tier limited. **Free tier**: Limited bots on free CRM. **Best for**: HubSpot users wanting chatbots integrated with CRM data and workflows.



- **[Drift](https://www.drift.com/)** (Salesloft)

  **Conversational marketing and sales chatbot** platform. **Pricing**: Quote-only. **Free tier**: None. **Best for**: B2B teams wanting lead qualification and meeting booking via chat.



- **[Tidio](https://www.tidio.com/)**

  **Live chat and chatbot platform** for SMBs with Lyro AI. **Pricing**: Free tier; paid plans per agent. **Free tier**: Yes, limited Lyro conversations. **Best for**: small businesses wanting accessible chat automation with multi-channel support.



- **[Zendesk AI](https://www.zendesk.com/)**

  **AI agents and chatbot** within Zendesk support suite. **Pricing**: Quote-only; bundled with Zendesk. **Free tier**: None. **Best for**: Zendesk customers wanting AI resolution integrated with their existing helpdesk.



- **[Ada](https://www.ada.cx/)**

  **Agentic customer experience** platform with action-taking AI agents. **Pricing**: **AWS Marketplace entry at $33,000/year for 60,000 conversations**; Capterra/GetApp list starting at **$60,000 annually** . **Free tier**: **No free plan, no free trial** . **Best for**: enterprises wanting deep system integrations for end-to-end resolution—**trade-off**: high entry price; consultation-only sales process.



- **[LivePerson](https://www.liveperson.com/)**

  **Conversational AI and messaging** for enterprise customer engagement. **Pricing**: Quote-only. **Free tier**: None. **Best for**: large enterprises wanting messaging-first customer engagement at scale.



- **[ManyChat](https://manychat.com/)**

  **Chat marketing automation** for Instagram, WhatsApp, and Messenger. **Pricing**: Free tier; paid by contacts. **Free tier**: Yes, limited contacts. **Best for**: creators and marketers wanting social channel automation.



- **[Chatfuel](https://chatfuel.com/)**

  **No-code chatbot builder** for social messaging channels. **Pricing**: Free tier; paid plans by contacts. **Free tier**: Yes, limited. **Best for**: SMBs wanting simple Facebook/Instagram bots without coding.



- **[Qualified](https://www.qualified.com/)**

  **Conversational marketing and AI SDR** for B2B websites. **Pricing**: Quote-only. **Free tier**: None. **Best for**: B2B companies wanting AI-driven lead qualification and meeting booking on their website.



## Open-Source GitHub Projects



- **[Rasa](https://github.com/RasaHQ/rasa)**

  **Open-source machine learning framework for automated text and voice conversations** (Apache-2.0) — **the enterprise-grade NLU framework for teams training custom models**, with deep control over language understanding and dialogue management . **Features**: NLU and dialogue management; connect to Slack, Facebook, and more; create chatbots and voice assistants; ~21,300 GitHub stars . **Tech stack**: Python. **Deploy**: Self-hosted. **Trade-off**: **Framework, not a product**—no inbox, no widget, no helpdesk; you build most of it. **Best for**: banks and regulated enterprises with ML teams needing full control over their NLU pipeline.



- **[Chatwoot](https://github.com/chatwoot/chatwoot)**

  **Open-source live-chat, email support, omni-channel desk** (MIT) — **the most complete open-source Intercom alternative**, with live chat, email, social channels, and bot handoff . **Features**: Omnichannel inbox (website live chat, email, Facebook, Instagram, Twitter, WhatsApp, Telegram, Line, SMS); **Captain AI Agent** for automated responses ; help center portal; private notes and @mentions; labels; canned responses; auto-assignment; CSAT reports . ~38,300 GitHub stars . **Tech stack**: Ruby on Rails, Vue.js. **Deploy**: Self-hosted (Docker, Heroku, DigitalOcean 1-Click) or Chatwoot Cloud . **Trade-off**: **Bot capabilities require Captain or external integration**—AI is not as deep as Intercom's Fin. **Best for**: teams wanting a self-hosted support inbox with live chat and bot handoff—the foundation for a full open-source support stack.



- **[Botpress](https://github.com/botpress/botpress)**

  **Open-source hub to build & deploy GPT/LLM Agents** (MIT for integrations/devtools) — **the visual builder ecosystem**, now Cloud-first with open-source devtools . **Features**: This repository contains **Integrations** (public integrations on Botpress Hub), **Devtools** (CLI, SDK, API Client), **Bots** (examples as code), and **Plugins** (coming soon) . **Critical note**: Botpress Cloud is the primary platform; **on-premise Botpress v12 is in a separate repository** and is not the focus of this repo . **Tech stack**: TypeScript, Node.js. **Deploy**: Botpress Cloud for most users; self-hosted v12 exists but is not the primary path. **Trade-off**: **Cloud-first**—the open-source repo is devtools and integrations, not the full platform. **Best for**: teams wanting a visual builder on Botpress Cloud with open-source integrations and CLI tooling—**not** for self-hosted sovereignty.



- **[Typebot](https://github.com/theluckystrike/typebot.io)**

  **Powerful chatbot builder that you can self-host** (Fair Source / Functional Source License) — **the best tool for conversational forms and lead capture**, not full support . **Features**: **34+ building blocks** (text, image, video, inputs, buttons, payment via Stripe, file picker); **logic** (conditional branching, URL redirections, JavaScript scripting, A/B testing); **integrations** (webhook/HTTP, OpenAI, Google Sheets, Google Analytics, Meta Pixel, Zapier, Make.com, Chatwoot); **theming** with custom CSS and reusable templates; **analytics** with drop-off and completion rates; CSV export . **Tech stack**: TypeScript, Next.js. **Deploy**: Self-hosted or Typebot Cloud . **Trade-off**: **Not a support tool**—won't run a help desk or answer deep product questions from docs. **FSL license restricts competing commercial use** before converting to open source . **Best for**: marketing and sales teams wanting friendly chat-style forms for lead capture—not customer support.



- **[Tiledesk](https://github.com/tiledesk/tiledesk)**

  **Open-source platform for LLM-powered chatbots with human-in-the-loop** (license per repo) — **the Voiceflow alternative with integrated human handoff** . **Features**: **LLM-enabled chatbot creation** with seamless transition to human agents when needed ; **Helm charts for Kubernetes** and **Docker Compose** for deployment ; RESTful API, Node.js/Python SDK, and CLI ; visual editor or JSON/Mustache templates; Prometheus/Grafana monitoring . ~304 stars for the main repo, ~379 for the server component . **Tech stack**: JavaScript/Node.js, Mustache. **Deploy**: Self-hosted (Helm for Kubernetes, Docker Compose) . **Trade-off**: **Smallest community** of the major options; licensing and security audit still need verification per third-party analysis . **Best for**: teams wanting an open-source Voiceflow alternative with built-in human handoff and Kubernetes deployment.



### Additional Strong Open-Source Options



- **Chaskiq** — Full-featured live chat, support, and marketing platform (license: Other, ~3.6K stars). Alternative to Intercom/Drift with web messenger, bots, help center, email campaigns, and WhatsApp/Slack integrations. **Note**: Comprehensive but smaller community than Chatwoot. **Best for**: teams wanting marketing + support in one self-hosted platform.

- **LangBot** — LLM-native bot platform with WebUI, pipelines, and plugin marketplace (v4.11.0, October 2026). Passkeys, 2FA, operation trace, and runner plugins for Dify, Coze, n8n, Claude Code. **Note**: Actively developed; more complex than simple chatbots. **Best for**: developers wanting a modern LLM bot platform with plugin extensibility.

- **MaxKB** — Knowledge base and agent platform for RAG chatbots over your own documents. **Note**: RAG/document chat focus, not live support. **Best for**: teams wanting self-hosted document Q&A chatbots.



**Frameworks for building custom systems**: Combine **Chatwoot** for the support inbox and human handoff with **Rasa** for custom NLU and **Typebot** for lead-capture forms—creating a composable open-source stack. **None of these match Intercom's all-in-one polish**, but for teams prioritizing data sovereignty, the core capabilities are achievable.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Chatbot platforms handling customer conversations must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "NLU framework" vs. "visual builder" vs. "support inbox" vs. "conversational forms" vs. "LLM chatbot platform" distinction is critical.** **Rasa** is an **NLU framework**—deep control, no product UI . **Botpress** is a **visual builder**—but the open-source repo is devtools/integrations, with Cloud as the primary platform . **Chatwoot** is a **support inbox**—live chat and handoff, with Captain AI for responses . **Typebot** is **conversational forms**—lead capture, not support . **Tiledesk** is an **LLM chatbot platform** with human-in-the-loop . **Choose based on whether you need custom NLU, visual flows, support inbox, forms, or LLM agents with handoff.**

- **Botpress is Cloud-first now.** The main repository contains integrations, devtools, and examples—**not the full self-hosted platform**. On-premise Botpress v12 is in a separate, legacy repository . **Do not plan a new self-hosted Botpress deployment based on this repo.**

- **Rasa is for teams with ML resources.** It requires training custom models and building the product layer yourself; ~21,300 stars but no product UI . **For banks and regulated enterprises with ML teams, it remains the strongest choice.**

- **Chatwoot is the best open-source support inbox foundation.** MIT licensed, omnichannel, with Captain AI for automated responses and a help center . **Pair it with an external bot for deeper AI capabilities.**

- **Typebot's FSL license is not OSI-approved.** Check compatibility before building a commercial product on it .

- **Ada has no free trial and starts at $33,000/year** on AWS Marketplace for 60,000 conversations; Capterra lists $60,000 annually . **Implementation adds $15,000–$100,000+** depending on deployment size . **Do not evaluate without enterprise budget approval.**

- Pricing opacity is universal across commercial vendors. Intercom, Drift, Zendesk, LivePerson, and Qualified require sales contact. Tidio, ManyChat, and Chatfuel publish tiered pricing with free tiers. **Validate with direct vendor conversations against your conversation volume.**



---



**Made for developers, support teams, and organizations building transparent conversational AI solutions.**

Let's make Conversational AI & Chatbot Software more open, data-driven, and handoff-friendly.
