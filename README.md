# Sebastián Ibarra Herrera

**Computer Engineering student at TEC (Costa Rica) · Full-stack developer · Application security, performance and CI**

I build and maintain software that real people use. I like finding the root cause instead of patching the symptom, measuring before optimizing, and writing down why each technical decision was made.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sebastian--ibarra--herrera-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sebastian-ibarra-herrera-653909349)
[![Email](https://img.shields.io/badge/Email-ibarraherrerasebastian%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:ibarraherrerasebastian@gmail.com)
![Location](https://img.shields.io/badge/Costa_Rica-Spanish_%C2%B7_English_B2-555555)

---

## Featured project: inventory, orders and invoicing platform

A web application for a jiu-jitsu apparel startup that handles inventory, customer orders, PDF invoices and sales statistics. It is live, it has a real client, and I own it end to end: requirements, architecture, security, performance and deployment.

**Stack:** Next.js 15 (App Router) · React 19 · TypeScript · Tailwind CSS · Supabase (PostgreSQL, Auth, Storage) · GitHub Actions · Vercel

| Area | What I did | Result |
|---|---|---|
| **Security** | Ran a 40-check audit with file and line evidence for every finding, ranked by the real context of the product | Closed an unauthenticated RCE chain in Next.js, 82 database functions open to the public, and a pricing flaw where the client sent the order total |
| **Performance** | Set a measured baseline first, then found that every API call validated the same token twice | API latency down 45% to 54% on the 5 main routes (630 ms to 292 ms on orders) |
| **Database** | About 48 migrations, stored procedures and triggers; an audit log on 6 tables with user attribution read from request headers | Found and fixed schema drift (29 constraints existed in production but not in migrations) |
| **DevOps** | CI on GitHub Actions across 3 branches; upgrade to Next.js 15.5 and React 19; scripted deploy branch | First green pipeline in 1 min 43 s; deploys no longer clone the whole repo |
| **Frontend** | Diagnosed responsive bugs by measuring the DOM, not by eye; token-based color themes; 44 px touch targets and reduced-motion support | Two layout overflows (177 px and 128 px) traced to their real cause |

**What I would want a reviewer to notice:** I also documented two reasonable hypotheses that the measurements proved wrong, and I keep a log of decisions with the alternatives I rejected and why.

---

## How I work

- **Measure first.** Baseline numbers before any optimization, and a record of what the numbers disproved.
- **Root cause over symptom.** Including reverting a first fix that broke something else.
- **Decisions on paper.** Each choice written down with its reasoning and discarded alternatives.
- **Verification without a test framework (for now).** About 17 executable verification scripts, and automated tests are next on my list.
- **AI coding agents, with ownership.** I use Claude Code for implementation, and I keep architecture, review and deployment decisions myself.

---

## Tech stack

**Languages**

![Python](https://skillicons.dev/icons?i=py,ts,js,java,cpp&theme=light&perline=10)

**Frontend**

![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=light&perline=10)

**Backend and data**

![Backend](https://skillicons.dev/icons?i=postgres,supabase,mongodb,redis&theme=light&perline=10)

**Tools and delivery**

![Tools](https://skillicons.dev/icons?i=git,githubactions,docker,bash,vercel&theme=light&perline=10)

**Currently learning (hands-on projects coming):** Linux administration, Kubernetes, Terraform, AWS, observability.

---

## Community and experience

- **CoraMar** (coral conservation nonprofit, Aug 2026 to present): requirements and module scope for the public website and a laboratory data platform.
- **IEEE Student Branch, TEC**: Fiscal (Aug 2024 to Mar 2025). Helped first-time council members take ownership of their responsibilities.
- **IEEE Region 9 SBRM 2024**, San Salvador: represented TEC among 210 participants from 57 student branches and presented a concept paper.

## Certifications

Introduction to Git (DataCamp, Jun 2023) · Introduction to Shell (DataCamp, May 2023)

---

*Open to part-time roles and internships. The best way to reach me is email or LinkedIn.*
