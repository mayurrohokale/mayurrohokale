<div align="center">

# Hi, I'm Mayur Rohokale

<a href="https://mayurportfolio-five.vercel.app/"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Full-Stack+Software+Engineer;Forward+Deployed+Engineer;System+Design+%C2%B7+Multi-tenant+SaaS;Building+Spendly+%E2%80%94+spendlymoney.com" alt="Typing SVG"/></a>

<a href="https://mayurportfolio-five.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/mayur-rohokale"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://spendlymoney.com"><img src="https://img.shields.io/badge/Spendly-16A34A?style=for-the-badge&logoColor=white" alt="Spendly"/></a>
<a href="mailto:contact.mayurrohokale@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://twitter.com/mayurrohokale25"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>

<img src="https://visitor-badge.laobi.icu/badge?page_id=mayurrohokale.mayurrohokale&left_text=Profile%20views&right_color=%232F81F7" alt="Profile views"/>

</div>

---

### 👨‍💻 About me

Full-stack software engineer with 2 years of experience building and running production systems. At CentraLogic I work directly with clients on a multi-tenant SaaS platform for the UK energy market. I turn their requirements into a design, build it across backend and frontend, and support it in production. That client-facing, end-to-end way of working is what Forward Deployed Engineering roles ask for.

Outside work I build and ship my own products, from architecture to deployment.

**Focus:** System design · Multi-tenant SaaS · Access control and security · Client-facing delivery

- 🏢 **Software Engineer @ CentraLogic** (Feb 2026 – now): multi-tenant SaaS platform for the UK energy supply market
- 💼 **Full Stack Engineer @ DexyAI** (Apr 2025 – Jan 2026): Next.js and FastAPI product work for a US startup
- 🚀 **Founder and engineer, [Spendly](https://spendlymoney.com)** (Jun 2026 – now): personal finance app on the web and Android, 600+ commits
- 🎓 MCA and B.E., Savitribai Phule Pune University

### 🏗️ Products I work on

#### Energy Industry Control Tower · CentraLogic
**What it is:** a multi-tenant monitoring platform for UK energy suppliers. Suppliers exchange a constant stream of industry messages with the rest of the market: D-flows over the Data Transfer Network, switching messages with the Central Switching Service, half-hourly settlement (MHHS) messages and DCC smart meter traffic. When one of these fails or misses its deadline, a customer's switch, meter read or bill goes wrong. Control Tower ingests every flow, tracks each conversation against its regulatory SLA, detects exceptions and helps operations teams resolve them before they cause harm. It runs as microservices (Python/FastAPI, Kafka, Neo4j, PostgreSQL, Redis) with a React dashboard, on Azure Kubernetes Service.

**What I built on it:**
- **Access control and identity:** led the staged migration of roles and permissions from Neo4j to PostgreSQL, using dual-write, shadow comparison and a single entitlement resolver, behind feature flags. Added custom roles, per-user grants, route guards and token revocation, and fixed a cross-tenant cache leak in KPI data.
- **Work Queue:** a ticketing system that routes each exception to the team that owns it, with claim, assign and bulk actions, @mentions, in-app and email notifications, and a Kanban board, in 10 languages.
- **Dashboards:** MHHS settlement, KPI and flow-failure dashboards with period-over-period comparison and Excel export, plus a design-system and accessibility overhaul.

#### UtilityOS: CRM and Broker Portal · CentraLogic
**What it is:** a white-label, multi-tenant platform that runs an energy supplier's business: customer accounts, sales, pricing, quoting, billing and switching, for electricity and gas. Business customers often buy energy through brokers, who need prices and quotes fast.

**What I built on it:**
- **Broker Portal (end to end):** brokers get single and bulk quotes, set their commission, handle Letter of Authority and Change of Tenancy steps, and manage multi-user accounts with roles. Includes an Excel quoting tool secured with per-broker encrypted API keys.
- **CRM:** a quote approval workflow, notifications, broker analytics and portal access control for the supplier's own team.
- **Pricing Matrix generator:** builds Excel price books across 8 consumption bands from tariff and network costs. Fixed 14 critical pricing defects, with differential tests proving live quotes stayed unchanged.

#### Dexy · DexyAI
**What it is:** a product for online course creators (Udemy instructors) to manage student messages and email campaigns.

**What I built on it:** an auto-reply system that reads message threads and drafts replies for the instructor to review before sending, a move of the web app to React Query, FastAPI endpoints, and fixes across campaign and messaging flows.

#### Spendly · my own product
**What it is:** a personal finance app for India that shows how much of your balance is actually safe to spend. **What I built:** all of it, solo. One Next.js codebase serving the web app and an Android app, transaction capture from Gmail and SMS bank alerts, Razorpay and Google Play subscriptions, and field-level encryption of personal data.

### 🚀 Projects

| Project | What it is | Stack | Live | Code |
| --- | --- | --- | --- | --- |
| **Spendly** | Personal finance app for India, on the web and Android. Brings bank accounts, spending, investments, loans, bills and goals into one place, with transactions captured from bank-alert emails and SMS | Next.js, Node.js, MongoDB, Capacitor, Razorpay | [spendlymoney.com](https://spendlymoney.com) | Private |
| **The Neutral Post** | News platform built around "news beyond bias". Each story is broken into what happened, why it matters and what is still unknown, with sources. A pipeline drafts stories twice a day and an editor reviews every one before it goes live | Next.js, Payload CMS, PostgreSQL, Trigger.dev | [Visit](https://theneutralpost.vercel.app) | Private |
| **Customised Virtual File System** | Linux-style file system with its own shell, commands and system call implementations | C, C++ | n/a | [CVFS](https://github.com/mayurrohokale/Customised-Virtual-File-System) |
| **Kindness Corner** | Connects NGOs and donors through voting-based donations, so users vote for causes and funds are allocated transparently | React, Node.js, Express, MongoDB | [Visit](https://kindness-corner.vercel.app) | Private |
| **Rohokale Farm** | Website for my family's farm in Maharashtra: onions, organic Keshar mangoes and sweet lime | React, Supabase | [Visit](https://farm-main-gray.vercel.app) | [farm-main](https://github.com/mayurrohokale/farm-main) |


### 📊 GitHub stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=mayurrohokale&theme=tokyonight&hide_border=true" alt="GitHub streak" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mayurrohokale&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=swig,html,css" alt="Top languages" height="170"/>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mayurrohokale/mayurrohokale/output/snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/mayurrohokale/mayurrohokale/output/snake.svg" alt="Contribution snake" width="100%"/>
</picture>

<p align="center"><sub>Open to full-stack, backend and forward deployed engineering roles. Reach me at <a href="mailto:contact.mayurrohokale@gmail.com">contact.mayurrohokale@gmail.com</a>.</sub></p>

<p align="center"><a href="https://www.buymeacoffee.com/mayurrohokale"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=%E2%98%95&slug=mayurrohokale&button_colour=FFDD00&font_colour=000000&font_family=Inter&outline_colour=000000&coffee_colour=ffffff" alt="Buy me a coffee" height="45"/></a></p>
