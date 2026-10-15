# Hi, I'm Josh

**Full-stack developer and technical SEO in Fort Worth, TX.** I lead development of a multi-tenant SaaS platform, and I build the data pipelines and tracking that connect marketing to revenue.

Most of my public code is at [git.turngear.dev](https://git.turngear.dev/explore/repos). My resume, services, and case studies are at [turngear.dev](https://turngear.dev).

---

## About me

I started in a dealership call center in 2014. The role grew into SEO, paid search, and then development, and I began writing code in 2016. Since 2023 I have worked as a full-stack developer, and I have led development of RE/AMP since March 2024.

I work mainly in Python, JavaScript and TypeScript, SQL, and Go. I like tight, readable codebases, tests before features, and systems that fail in ways you can see.

## A note on my public code

Most of my day-to-day work is in proprietary codebases, so my contribution graph understates what I ship. The case studies on my site describe the architecture and decisions without exposing code or customer data.

---

## Featured work: RE/AMP

[RE/AMP](https://reamp.co) is a multi-tenant platform for real estate transaction and investor operations. I started the codebase in March 2024 and lead its development across the database, backend, frontend, infrastructure, and production support.

- **Scale:** 2,500+ of the repository's 5,000+ commits on main are mine. The codebase is 180,000+ lines of React, Node/Express, and SQL, excluding migrations and generated code.
- **Tests:** 726 passing tests across 42 suites at one staging checkpoint. That is a snapshot, not a coverage figure.
- **Tenant isolation:** the company ID comes from the signed-in user, never from the request body.
- **Integrations:** Stripe webhooks, Twilio messaging with each company's own credentials, and email over IMAP.
- **Storage and releases:** private S3 documents served with short-lived pre-signed URLs, and staging rebuilt from the latest production backup before each release.

Read the full write-up: [RE/AMP case study](https://turngear.dev/projects/reamp-saas-platform/).

---

## Stack

| Area | Tools |
| --- | --- |
| Languages | Python, JavaScript, TypeScript, SQL, Go |
| Frontend | React, HTMX, Tailwind CSS |
| Backend | Django, Node.js with Express, REST APIs |
| Data | PostgreSQL, MySQL, Valkey |
| Infrastructure | AWS (EC2, S3, VPC), Docker, Nginx, Linux |
| Monitoring | Prometheus, Grafana, PostHog |

---

## Search and marketing

I have worked on SEO since 2015, including SEO and ad accounts for 13 dealerships at World Car Auto Group. I build city-targeted pages with structured data, tracking in GA4 and Tag Manager, and data pipelines that feed ad platforms.

---

## Case studies and notes

- [Distributed Playwright crawler](https://turngear.dev/projects/distributed-crawler/)
- [Phone scrubber with a rate-limited queue](https://turngear.dev/projects/phone-scrubber/)
- [Inventory feed pipeline for Google and Facebook ads](https://turngear.dev/projects/inventory-ad-feed-pipeline/)
- [Engineering notes](https://turngear.dev/engineering-notes/)

---

## Open source and side projects

- **[jeer](https://github.com/joshdevelopsIRL/jeer):** a small Go utility for clean, pragmatic testing.
- **[botprofiles-cs-source](https://github.com/joshdevelopsIRL/botprofiles-cs-source):** generates a bot profile database for Counter-Strike: Source by parsing config files.
- **[committy](https://git.turngear.dev/josh/committy):** a small utility for writing consistent commit messages.
- **[ssql3](https://gitlab.com/joshdevelopsIRL/ssql3):** a wrapper for handling sqlite3 updates in small programs and scripts.

My [GitLab activity](https://gitlab.com/joshdevelopsIRL) shows ongoing work on RE/AMP since March 2024.

---

## Get in touch

I am open to remote or hybrid roles, and I take freelance projects through [turngear.dev](https://turngear.dev).

- **LinkedIn:** [linkedin.com/in/jd-hayes](https://www.linkedin.com/in/jd-hayes)
- **Email:** [jd@turngear.dev](mailto:jd@turngear.dev)
- **Location:** Fort Worth, Texas
