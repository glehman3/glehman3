# Gregory Lehman - [LinkedIn](https://www.linkedin.com/in/gregory-lehman)

Senior Software Quality Engineer / SDET at **Intuit** — Playwright automation, API and RBAC validation, CI/CD quality gates, and structured test design in the open.

*12 public repos · 9 showcased here · CI on utility repos · pytest · Playwright · GitHub Actions*

I favor deterministic checks over hand-wavy quality claims: local rubrics, structural validators, and flake-aware test discipline.

## What I work on

- Playwright framework patterns, release test strategy, and customer-facing SaaS quality
- REST API validation and role-based permission testing (matrix-driven, no production secrets in public repos)
- Cursor Agent Skills for test jam generation, risk analysis, and Jira workflows (`/qforge` via **qe-skill**)
- Structured test-case CSV pipelines with column-alignment and formula-injection guards
- Static QE gates: Playwright smell scoring, posting analysis CLIs, and scoped accessibility scans on demo SUTs
- Recruiter-friendly posting parsers: one-page screen briefs, phone-screen stems, and two-req diffs (deterministic, no ATS hooks)

## Flagship

| Repo | What it is | Highlights |
|------|------------|------------|
| [qe-skill](https://github.com/glehman3/qe-skill) | Quality Engineering Suite for Cursor | `/qforge` menu, test case/jam generation, GitHub MCP, CSV and Jira export |

## Supporting tools

| Repo | What it is | Why it's here |
|------|------------|----------------|
| [jd-kit](https://github.com/glehman3/jd-kit) | JD fetch + analyze + skills match CLI | SSRF-safe posting fetch, keyword rubric, posting smell flags |
| [pw-smell](https://github.com/glehman3/pw-smell) | Playwright smell scorer | Static gate for `waitForTimeout`, `networkidle`, brittle selectors, weak assertions |
| [todo-qa](https://github.com/glehman3/todo-qa) | TodoMVC Playwright demo | Seven E2E tests + scoped axe scan on the public Playwright demo — CI-ready |

## Recruiter utilities

Paste or fetch a posting; get screen-ready output in seconds — built by an SQE who reads reqs all day.

| Repo | What it is | Recruiter win |
|------|------------|----------------|
| [recruit-brief](https://github.com/glehman3/recruit-brief) | One-page screening brief (Markdown) | Title, level signal, must-haves, red flags, plain stack summary |
| [screen-stem](https://github.com/glehman3/screen-stem) | Phone-screen question stems | 10–12 deterministic questions tied to JD keywords |
| [jd-compare](https://github.com/glehman3/jd-compare) | Two-posting diff | Overlap / unique requirements when juggling similar reqs |

## QE craft

| Repo | What it is | Why it's here |
|------|------------|----------------|
| [jam-lint](https://github.com/glehman3/jam-lint) | Test jam CSV structural validator | Column alignment, required headers, numbered-list rules, formula-injection detection |
| [role-gate](https://github.com/glehman3/role-gate) | RBAC matrix validator | YAML roles/permissions + optional allow/deny matrix checks — generic examples only |

## Internal work

Most production impact lives in employer repos. At **Intuit** (Mailchimp), that has included a unified QE platform, Playwright framework patterns, AI-assisted structured test design, release strategy for support and self-service surfaces, REST API and RBAC validation, and observability tooling for production debugging. Details stay internal; the public repos above show how I build similar systems in the open.

## Scope notes

- **qe-skill** is a Cursor workflow pack (skills + commands), not a hosted SaaS.
- **jd-kit**, **recruit-brief**, **screen-stem**, **jd-compare**, **pw-smell**, **todo-qa**, **jam-lint**, and **role-gate** are portfolio demos — useful utilities, not production employer systems or ATS integrations.
- **todo-qa** targets the public [Playwright TodoMVC demo](https://demo.playwright.dev/todomvc/#/) (toy SUT).

## Stack

Python · TypeScript · JavaScript · Node · Playwright · pytest · GitHub Actions · Cursor Agent Skills · Jenkins · GCP · AWS

## Contact

[LinkedIn](https://www.linkedin.com/in/gregory-lehman)

**Suggested pins (6 max):** `qe-skill`, `jam-lint`, `role-gate`, `todo-qa`, `pw-smell`, `jd-kit`

For recruiter-facing outreach, you can swap **`jd-kit`** for **`recruit-brief`** on pins (same posting DNA, faster screen brief). Adjust pins manually on your profile — GitHub allows six pinned repos.
