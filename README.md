# Syed Ali Abbas

**Software Engineer** — Open edX platform engineering

I build and maintain large-scale open-source learning platforms. I maintain
[`openedx-scorm-xblock`](https://github.com/overhangio/openedx-scorm-xblock) for
[Overhang.IO](https://github.com/overhangio) — the organization behind Tutor, the official
[Open edX](https://openedx.org) distribution — and contribute across the wider Tutor plugin
ecosystem. Day to day I work on [Wikimedia's WikiLearn](https://github.com/wikimedia), where I
focus on platform internals, internationalization and RTL, certificates, and SCORM.

---

## What I work on

- **Open edX platform engineering** — `edx-platform` internals, XBlocks, and the Studio/LMS authoring experience
- **Deployment & DevOps** — Tutor plugins, Docker-based distributions, Kubernetes, AWS
- **Internationalization** — translation pipelines, `translatewiki.net` integration, and full RTL support
- **Micro-frontends** — React/TypeScript MFEs for authoring, discussions, and learner-facing apps
- **Backend services** — Django and NestJS APIs, REST and GraphQL

Outside of work I build games in Unity.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**Platform & Learning Tech**

![Open edX](https://img.shields.io/badge/Open%20edX-2D3B45?style=flat&logo=edx&logoColor=white)
![Tutor](https://img.shields.io/badge/Tutor-1E3A5F?style=flat)
![XBlock](https://img.shields.io/badge/XBlock-4A4A4A?style=flat)
![SCORM](https://img.shields.io/badge/SCORM-6E4C9F?style=flat)

**Backend**

![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)

**Infrastructure & Data**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Game Development**

![Unity](https://img.shields.io/badge/Unity-FFFFFF?style=flat&logo=unity&logoColor=black)

---

## Open Source

Maintainer of an official Open edX package, with **54 merged pull requests across 22 upstream
repositories** — including 15 in [Overhang.IO](https://github.com/overhangio), the organization
behind Tutor, the official Open edX distribution.

### Maintainer

**[overhangio/openedx-scorm-xblock](https://github.com/overhangio/openedx-scorm-xblock)** — the
SCORM XBlock used across the Open edX ecosystem. I took over maintainership of the package and
have since shipped fixes for the problems that hurt most in production: SCORM block files now
survive OLX export/import and course reruns instead of being silently dropped, large package
uploads report their real outcome in Studio rather than failing quietly, and completion tracking
reports accurate state back to the LMS.

### Ecosystem-wide maintenance

**Python 3.9 → 3.14 migration across the Tutor plugin ecosystem.** Planned and executed the
runtime upgrade across **15 Overhang.IO repositories** — `tutor` core plus the `mfe`, `indigo`,
`discovery`, `credentials`, `cairn`, `forum`, `notes`, `minio`, `xqueue`, `jupyter`, `android`,
`deck`, and `livedeps` plugins — coordinating the rollout and the breaking-change notices so
downstream operators upgraded without surprises.

**[overhangio/tutor](https://github.com/overhangio/tutor)** — migrated Kubernetes manifests from
the deprecated `commonLabels` to `labels`, keeping backward compatibility so existing deployments
continued to work through the transition.

### Platform engineering — [Wikimedia WikiLearn](https://github.com/wikimedia)

**Identity & integrations.** Built WikiLearn ↔ Wikimedia username synchronization, keeping a
learner's identity consistent by reconciling it on every OAuth login. Fixed a Meta fetch cron that
was rate-limiting itself into repeated failure, and set up Credentials issuance with catalog sync
and a scheduled backfill.

**Internationalization & RTL.** Led right-to-left support across the platform theme and fixed the
translation pipeline feeding `translatewiki.net` — preserving fuzzy flags on English source
templates and resolving empty message groups that were blocking translators.

**Core platform.** Contributed to [`edx-platform`](https://github.com/wikimedia/edx-platform),
hardening HTML sanitization against malformed input, backporting an upstream fix that restored
broken discussion threads, and correcting instructor-issued certificate reports.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syed-ali-abbas-b80294183/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Syed-Ali-Abbas-568)
