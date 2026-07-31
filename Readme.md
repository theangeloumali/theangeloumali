# Hey, I'm Angelo 👋

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=28&duration=4000&pause=1000&color=0A7E73&center=true&vCenter=true&multiline=true&repeat=true&width=760&height=80&lines=CTO+%26+AI+Solutions+Architect+%7C+9%2B+Years;Agentic+AI+%7C+Claude+%7C+MCP+%7C+Multi-Agent+Systems;React+Native+%7C+Next.js+%7C+TypeScript+%7C+Supabase;300%2B+Apps+%7C+1%2C000%2B+Businesses+%7C+300K+Users" alt="CTO and AI Solutions Architect. Agentic AI, Claude, MCP, multi-agent systems. React Native, Next.js, TypeScript, Supabase." />
</div>

<a href="https://app.daily.dev/theangeloumali"><img src="https://github.com/theangeloumali/theangeloumali/blob/master/devcard.svg" width="360" alt="Angelo's daily.dev card"/></a>

**Chief Technology Officer at ZKidz Dev LLC.** I've been shipping production mobile and web software since 2017. These days most of that work runs through AI agents I direct like a dev team, with TDD and automated review enforced on every task.


Based in the Philippines, delivering across AU, NZ, US, CA, and PH.

[![Available for Work](https://img.shields.io/badge/Available_for_Work-brightgreen?style=flat-square)](mailto:angelo@theangeloumali.com)

[![GitHub](https://img.shields.io/badge/GitHub-theangeloumali-181717?style=flat-square&logo=github)](https://github.com/theangeloumali)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-christianangelo-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/christianangelo)
[![Email](https://img.shields.io/badge/Email-angelo@theangeloumali.com-EA4335?style=flat-square&logo=gmail)](mailto:angelo@theangeloumali.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-theangeloumali.com-0A7E73?style=flat-square&logo=vercel)](https://theangeloumali.com)

---

## 🤖 Building with AI

Two separate things, and I think the distinction matters: AI systems I ship for clients, and the AI system I use to ship everything else.

### AI products in production

| Project                | What the AI actually does                                                                                                                                                                                                                   |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Kitna** (ClearSpent) | Conversational finance agent with 20+ tools. Voice transactions, spend analysis, and a proposal step where nothing moves until you approve it. Gemini AI.                                                                                   |
| **My Business Coach**  | Real-time multilingual voice agent for a Singapore startup. A discovery agent runs structured intake, then hands off to specialized coaches using LLM chemistry scoring and deterministic switching across 7 languages. Pipecat and WebRTC. |
| **Lead Nurture Agent** | Scores webinar leads in real time with Claude, alerts closers in Slack, and runs personalized follow-up on cold leads. RAG pipeline, Inngest for durable workflows, GoHighLevel CRM.                                                        |
| **IdeaFlare**          | Turns a voice note or a raw thought into summaries, feature breakdowns, execution plans, and risk assessments. Gemini structured outputs.                                                                                                   |
| **Agency Partner Hub** | Generates client audit decks with Claude, rendered to PPTX, plus Stripe Connect commission payouts.                                                                                                                                         |
| **AI Bot Marketplace** | SMS and voice automation bot templates across 376+ business niches.                                                                                                                                                                         |

`Claude` `Gemini` `OpenAI` `Vercel AI SDK` `MCP` `Pipecat` `WebRTC` `Inngest` `pgvector` `RAG`

### How I build

I run an orchestration framework called SuperClaude on top of Claude Code. It routes work to 11 specialized agent personas (frontend, backend, security, QA, architecture, and so on), and it will not let a task close until the quality gates pass.

- Parallel agent teams handle independent slices of a feature at once, with exclusive file ownership so they don't collide
- MCP servers wired into the daily loop: Context7 for docs, Playwright and Chrome DevTools for verification, plus research and code-navigation servers
- Custom skills for the workflows I repeat: TDD feature builds, agent-team dispatch, deep research, automated code review
- Enforced gates on every task: format, lint, typecheck, tests, build, then a runtime smoke test before anything is called done

The honest version of the payoff: roughly 3 to 5x faster on feature delivery. The gates are what make that number real instead of just faster output.

---

## 💻 Tech stack

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

**Mobile**

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![EAS](https://img.shields.io/badge/EAS_Build-4630EB?style=flat-square&logo=expo)

**Backend and data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**AI**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat-square&logo=vercel)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**State, tooling, infra**

![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

---

## 🛠️ What I specialize in

**Agentic AI systems.** Multi-step reasoning with tool use, RAG pipelines over vector search, voice agents, and multi-provider setups across Claude, Gemini, and OpenAI. Durable workflows that survive crashes and retries.

**Multi-tenant SaaS.** Row-level security, per-tenant subdomains, custom theming, data isolation. Built it for dental clinics, mortgage brokerages, and a franchise partner network.

**Cross-platform mobile.** React Native and Expo, with Flutter where the client stack calls for it. Apps live on both stores under client company names.

**Monorepo architecture.** Turborepo with shared UI packages, backend hooks, and generated GraphQL artifacts across web and native targets.

**Release automation.** Fastlane, Bitrise, and EAS pipelines. Cut release cycles 50 to 80 percent across the client portfolio.

---

## 💼 Experience

| Period         | Role                             | Company                   | Location      |
| -------------- | -------------------------------- | ------------------------- | ------------- |
| 2026 - Present | Chief Technology Officer         | **ZKidz Dev LLC**         | Melbourne, AU |
| 2025 - 2026    | Founder & AI Solutions Architect | **ZKidz Dev LLC**         | Remote        |
| 2020 - 2025    | Lead Software Engineer           | **ZKidz Dev LLC**         | Remote        |
| 2022 - 2024    | Senior Software Engineer         | **Blackpepper**           | Auckland, NZ  |
| 2020 - 2022    | Senior Software Engineer         | **Adaca**                 | Sydney, AU    |
| 2017 - 2020    | Software Developer → Full Stack  | **Trends & Technologies** | Makati, PH    |

A few things I'm proud of from those years:

- **ZKidz Dev.** Set the engineering standards every client engagement runs on, and own architecture and trade-off calls across the portfolio. Clients include PropApp, My Business Coach, FTBLRLIFE, PickleBook, realestateprojects.au, Taply, and Urban.
- **Taply.** Architected a white-label e-commerce platform serving 1,000+ businesses across 300+ branded storefronts. Drove 23% user growth, cut support tickets 30%, and halved build time with an automated Fastlane pipeline.
- **Blackpepper.** Shipped and maintained 6 React Native e-commerce apps for Glassons, RedRat, and Hallensteins. CI/CD work made deployments 60% faster.
- **Adaca.** Delivered 7 products across mobile and web, and cut bundle size 35% with code-splitting and tree-shaking.
- **Urban.com.au.** Two mobile apps and a web platform. Image caching work reduced load times 40%.
- **Trends & Technologies.** Led a cross-functional team of five and shipped 4 to 10 projects a cycle.

---

## 📌 Featured work

<table>
<tr>
<td width="50%">

**💰 ClearSpent**

Agent-first finance app. Tell Kitna what happened, it proposes the action, nothing moves without your approval.

**Tech**: React Native, Next.js, Supabase, Gemini AI, Vercel AI SDK

[Site](https://clearspent.com) · [Web app](https://clearspent.zkidzdev.com)

</td>
<td width="50%">

**🎙️ My Business Coach**

Voice AI coaching platform for a Singapore startup. Discovery agent hands off to specialized coaches across 7 languages. ~9 months, 2,000+ commits.

**Tech**: Flutter, FastAPI, Pipecat, WebRTC, Supabase

[Learn more](https://mybusinesscoach.app)

</td>
</tr>
<tr>
<td width="50%">

**🎯 Lead Nurture & Qualification Agent**

Real-time lead scoring with Claude, Slack alerts to closers, automated nurture for cold leads.

**Tech**: Next.js, Claude AI, Inngest, Supabase, GoHighLevel

[Web app](https://lead-nurture-agent.vercel.app/)

</td>
<td width="50%">

**💡 IdeaFlare**

Voice or text in, structured execution plan out. Summaries, feature breakdowns, tasks, risk assessments.

**Tech**: React Native, Expo, Gemini AI, Supabase, Drizzle

[Website](https://ideaflare.app)

</td>
</tr>
<tr>
<td width="50%">

**🏠 PropApp**

Off-market property marketplace for Australia where agents compete to win your listing. Turborepo, AU-resident data (Sydney).

**Tech**: Next.js 16, React 19, Supabase, Drizzle, Stripe, Sentry

[Website](https://www.propapp.com.au/) · [Android](https://play.google.com/store/apps/details?id=au.com.propapp.app) · [iOS](https://apps.apple.com/au/app/propapp/id6475382641)

</td>
<td width="50%">

**🏦 Brokerverse**

White-label SaaS for Australian mortgage brokers. Per-broker subdomains, custom theming, block-based landing page editor.

**Tech**: Next.js 16, React 19, Supabase, Drizzle, Stripe, Leaflet

[Website](https://brokerverse.com.au/)

</td>
</tr>
<tr>
<td width="50%">

**🦷 CrownOS**

Multi-tenant dental practice management. Patient records, scheduling, billing, inventory, clinical charting, real-time chat. RLS per clinic.

**Tech**: Next.js, Supabase, Drizzle, TanStack Query, Zustand

[Web app](https://crownos.zkidzdev.com)

</td>
<td width="50%">

**🏘️ realestateprojects.au**

Australian property platform across 5 products: listings site, agency portal, buyer app, agent portal, and a NestJS campaign API.

**Tech**: Next.js, Vite, NestJS, Expo, Supabase, OpenAI, Google Maps

[Website](https://realestateprojects.au) · [Agency portal](https://agency.realestateprojects.au)

</td>
</tr>
<tr>
<td width="50%">

**📸 PICkle Book**

Monthly photo books with print-ready PDF export. 50 concurrent image uploads, 50-page layouts, Stripe payments.

**Tech**: React Native, Expo, Next.js, Supabase, Stripe

[Website](https://pickle-book.com)

</td>
<td width="50%">

**🔐 The Last Will**

Fully offline encrypted vault for wills, beneficiaries, and sensitive documents. Zero-knowledge, AES-256, biometric unlock.

**Tech**: React Native, Expo, AES-256, Biometrics, Fastlane

[Website](https://thelastwill.app)

</td>
</tr>
<tr>
<td width="50%">

**🤝 Agency Partner Hub**

Franchise control plane for AI automation agencies. Stripe Connect payouts, AI-generated audit decks, ROI calculator pages.

**Tech**: React, Vite, Supabase, Stripe Connect, Claude AI

[Web app](https://app.portal.aiagencylabs.io/)

</td>
<td width="50%">

**🛒 AI Bot Marketplace**

Pre-built AI bot templates across 376+ business niches. SMS and voice automation, Stripe checkout, GHL delivery.

**Tech**: Next.js, Supabase, Stripe, GoHighLevel, Drizzle

[Web app](https://marketplace.aiagencylabs.io/)

</td>
</tr>
<tr>
<td width="50%">

**📊 PulseTrack**

Project management with ticket tracking, time tracking, and billing in one loop. Turbo monorepo.

**Tech**: Next.js 15, Supabase, Drizzle, TanStack Query, Turborepo

[Web app](https://pulsetrack.zkidzdev.com)

</td>
<td width="50%">

**🏈 FTBLRLife**

Sports social platform. Networking, video, real-time messaging, and performance analytics for athletes, scouts, and coaches.

**Tech**: React Native, Firebase, Redux, GraphQL

[Android](https://play.google.com/store/apps/details?id=com.footballer.app) · [iOS](https://apps.apple.com/ph/app/ftblrlife/id6444323230)

</td>
</tr>
</table>

<details>
<summary><b>E-commerce and marketplace back catalog</b> (click to expand)</summary>

<br />

| Project            | What it is                                                                                                                                                             | Links                                                                                                                                                                             |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Glassons**       | E-commerce app for the NZ fashion retailer. Personalized recommendations, secure checkout. React Native, AWS Amplify, GraphQL.                                         | [Android](https://play.google.com/store/apps/details?id=com.glassons.customer.app) · [iOS](https://apps.apple.com/nz/app/glassons/id1525273016)                                   |
| **Hallensteins**   | Men's fashion e-commerce with loyalty program, size guides, and push notifications. React Native, AWS Amplify, GraphQL.                                                | [Android](https://play.google.com/store/apps/details?id=com.hallensteins.customer.app) · [iOS](https://apps.apple.com/nz/app/hallensteins/id6453358386)                           |
| **RedRat Fashion** | Fashion e-commerce with wishlists, size guides, and reviews. React Native, AWS Amplify, GraphQL.                                                                       | [Android](https://play.google.com/store/apps/details?id=nz.co.redrat.app) · [iOS](https://apps.apple.com/nz/app/red-rat/id1551890750)                                             |
| **ShoreTrade**     | B2B marketplace for Australia's largest fishery market. Real-time trading and inventory. Also shipped the SFM Blue buyer and seller apps on the same platform.         | [Buyer Android](https://play.google.com/store/apps/details?id=com.shoretradeapp.buyer) · [Seller Android](https://play.google.com/store/apps/details?id=com.shoretradeapp.seller) |
| **Urban.com.au**   | Real estate app with property search, map integration, and agent messaging. React Native, Firebase, Redux.                                                             | [Website](https://www.urban.com.au/)                                                                                                                                              |
| **Taply**          | White-label Shopify platform behind 300+ branded storefronts for 1,000+ businesses. Individual tenant apps have since been delisted. React Native, Shopify API, Redux. | Platform work                                                                                                                                                                     |

</details>

🎯 **Full portfolio, all 26 projects**: [theangeloumali.com](https://theangeloumali.com/)

---

## 📊 By the numbers

<div align="center">

| Metric                           | Figure             |
| :------------------------------- | :----------------- |
| White-label storefronts launched | 300+               |
| Businesses served                | 1,000+             |
| Monthly end users                | 300K               |
| Production systems delivered     | 15+                |
| Release cycle improvement        | 50 to 80% faster   |
| Bundle size reduction (Adaca)    | 35%                |
| Markets shipped to               | AU, NZ, US, CA, PH |

</div>

---

## 📈 Stats

### Streak and activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=theangeloumali&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub streak stats" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=theangeloumali&theme=tokyo-night&hide_border=true" alt="Contribution activity graph" />
</div>

### Profile summary

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=theangeloumali&theme=tokyonight" alt="Profile details" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=theangeloumali&theme=tokyonight" width="48%" alt="Repositories per language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=theangeloumali&theme=tokyonight" width="48%" alt="Most committed language" />
</div>

### Where the hours actually go

<!--START_SECTION:waka-->

```txt
From: 04 December 2022 - To: 29 July 2026

Total Time: 3,908 hrs 2 mins

TypeScript           2,583 hrs 6 mins      ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣀⣀⣀⣀⣀⣀⣀⣀   66.10 %
Markdown             282 hrs 18 mins       ⣿⣷⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   07.22 %
JSON                 223 hrs 53 mins       ⣿⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.73 %
Other                177 hrs 12 mins       ⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   04.53 %
Text                 90 hrs 55 mins        ⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.33 %
```

<!--END_SECTION:waka-->

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random dev quote" />
</div>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=theangeloumali&style=for-the-badge&color=7c3aed" alt="Profile views"/>
<img src="https://img.shields.io/github/stars/theangeloumali?style=for-the-badge&logo=github&logoColor=white&color=7c3aed" alt="GitHub stars"/>

</div>

---

## 📬 Get in touch

Open to CTO and AI architecture work, plus selective client builds through ZKidz Dev.

- **Email**: [angelo@theangeloumali.com](mailto:angelo@theangeloumali.com)
- **LinkedIn**: [linkedin.com/in/christianangelo](https://linkedin.com/in/christianangelo)
- **Portfolio**: [theangeloumali.com](https://theangeloumali.com)
- **Company**: [zkidzdev.com](https://zkidzdev.com)


---

<div align="center">

**Still learning, still building, still shipping.**

</div>
