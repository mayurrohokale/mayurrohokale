<h1 align="center">Hi, I'm Mayur Rohokale</h1>

<p align="center">
  <b>Full-Stack Software Engineer · Generative AI</b><br/>
  Pune, India. I build multi-tenant SaaS at CentraLogic and run <a href="https://spendlymoney.com">Spendly</a>, an AI personal finance app.
</p>

<p align="center">
  <a href="https://mayurportfolio-five.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/mayur-rohokale"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://spendlymoney.com"><img src="https://img.shields.io/badge/Spendly-spendlymoney.com-16A34A?style=for-the-badge" alt="Spendly"/></a>
  <a href="mailto:contact.mayurrohokale@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://twitter.com/mayurrohokale25"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
</p>

---

### About me

- **Software Engineer at CentraLogic** (Feb 2026 – now). Multi-tenant SaaS for the UK energy supply market. I designed a staged RBAC and identity migration from Neo4j to PostgreSQL, and built the broker portal, a work queue and the pricing matrix generator.
- **Full Stack Engineer at DexyAI** (Apr 2025 – Jan 2026). Built an AI auto-reply system for Udemy instructors with Next.js and FastAPI, with a human review step before anything is sent.
- **Builder of Spendly** (Jun 2026 – now). I designed, built and run it on my own.
- MCA and B.E. from Savitribai Phule Pune University.

### What I'm building: Spendly

[Spendly](https://spendlymoney.com) is a personal finance app for India, on the web and Android. It covers accounts, budgets, bills, goals, investments with XIRR and bill splitting. The AI parts:

- **Ask Spendly** is an LLM assistant (Gemini) that answers from a snapshot of the user's own accounts, spending, goals and loans. A guard checks every rupee figure in the reply against that data and flags any number it can't trace.
- **Auto-capture** reads Gmail and SMS bank alerts with per-bank parsers. When a parser misses, Claude extracts the transaction as strict JSON that is validated with Zod.
- **Cost control** comes from a deterministic quick-answer layer, a 15-minute response cache, per-plan daily AI allowances, and fallback across API keys and models when rate limits hit.

`Next.js` `React` `Node.js` `MongoDB` `Gemini API` `Claude API` `Capacitor` `Razorpay` `Vercel`

### Tech I work with

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,nodejs,express,fastapi,postgres,mongodb,prisma,tailwind,docker,kubernetes,azure,gcp,vercel,git&perline=9" alt="Tech stack"/>
</p>

**Generative AI:** LLM apps with the Gemini and Claude APIs, prompt engineering, context grounding, structured outputs (JSON Schema + Zod), hallucination checks, cost and rate-limit handling.

### Some public repos

| Repo | What it is |
| --- | --- |
| [Customised-Virtual-File-System](https://github.com/mayurrohokale/Customised-Virtual-File-System) | A Linux-style file system in C++ with its own shell and system calls |
| [QuizMaster](https://github.com/mayurrohokale/QuizMaster) | Quiz app in React, TypeScript and Vite, with a [Node.js backend](https://github.com/mayurrohokale/Quiz-Master-Backend) |
| [DSA](https://github.com/mayurrohokale/DSA) | Data structures and algorithms practice in C++ and Python |

### GitHub stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=mayurrohokale&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" height="165"/>
  <img src="https://streak-stats.demolab.com/?user=mayurrohokale&hide_border=true" alt="GitHub streak" height="165"/>
</p>

<p align="center"><sub>Open to conversations about full-stack and AI engineering roles. The quickest way to reach me is <a href="mailto:contact.mayurrohokale@gmail.com">email</a>.</sub></p>
