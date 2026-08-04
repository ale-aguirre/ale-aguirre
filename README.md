<div align="center">

**AI Engineer / Full-Stack Developer**

Córdoba, Argentina · Remote · UTC-3 (overlaps US Eastern)

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--aguirre--alexis.vercel.app-1c1b19?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-aguirre-alexis.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/alexisaguirre-aideveloper)
[![Email](https://img.shields.io/badge/Hire%20me-aguirrealexis.cba%40gmail.com-2f6f4e?style=flat-square&logo=gmail&logoColor=white)](mailto:aguirrealexis.cba@gmail.com)

</div>

---

I build products where the backend is an LLM: multi-agent systems, retrieval pipelines,
browser automation and the evaluation harnesses that tell you whether any of it actually works.

5+ years shipping production TypeScript. Currently building at
[Contenidos Digitales](https://contenidosdigitales.com) and running my own systems in production.

**Open to full-time remote roles.** [Let's talk →](mailto:aguirrealexis.cba@gmail.com)

---

## What I've built

**[Job Hunter](https://github.com/ale-aguirre/claude-job-hunter)** — an autonomous job search agent.
Scouts 17 job board APIs, scores each listing against a CV, tailors the CV per posting with a
zero-hallucination guardrail, and submits the application through the ATS.

> 1,212 leads processed. **316 applications submitted autonomously, 248 verified on the target page.**
> Measuring delivery per channel instead of in aggregate is what exposed one integration silently
> failing 100% of the time while the overall number looked fine.

`Node.js` `Playwright` `Claude API` `Groq` `SQLite`

**[Forgix](https://forgix.xyz)** — real-time multiplayer browser game with PvP combat, permadeath and
an in-game economy. Claude API drives chip generation and narrative; Supabase RLS enforces per-user
isolation. ~27k lines of TypeScript, live in production.

`Next.js` `Supabase` `Claude API` `Phaser 3` `Stripe`

**[SKUscribe](https://skuscribe.com)** — B2B SaaS that generates e-commerce product listings from an
LLM pipeline. Auth, subscription tiers, full billing. ~37k lines, deployed.

`Next.js` `Prisma` `Supabase` `Claude API` `Stripe`

**Cortex** *(private)* — multi-agent orchestration dashboard. Routes work through a
classify → route → human approval gate → execute pipeline, streaming results over SSE. A cheap Groq
classifier picks the model tier per request with automatic fallback on rate limits. ~21k lines of TypeScript.

`Next.js` `Claude Agent SDK` `Groq` `SQLite` `Zod`

---

## Stack

```
AI / Agents   →  Claude API · Groq · multi-agent orchestration · RAG (pgvector, ChromaDB)
                 tool calling · structured output · model routing · evals
Frontend      →  Next.js · React · TypeScript · Tailwind · Framer Motion
Backend       →  Node.js · GraphQL (Apollo) · Supabase · PostgreSQL · Prisma · SQLite
Automation    →  Playwright · Chrome CDP
Deploy        →  Vercel · GitHub Actions
```

---

<div align="center">
<sub>Open to full-time remote roles. Contractor in USD via Deel, Wise or Payoneer.</sub>
</div>
