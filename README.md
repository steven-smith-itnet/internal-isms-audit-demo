# Internal ISMS Audit — Pre-Certification Readiness (Demonstration)

A self-contained, single-page demonstration of an **internal information security
management system (ISMS) audit** aligned to **ISO/IEC 27001:2022** and **SOC 2 Type II**.
It is a reusable **work-sample template** that walks through a complete internal audit
deliverable set:

- **Audit report** — scope, objective, methodology, executive summary, and a finding
  severity distribution (Major / Minor / Observation).
- **Internal audit checklist** — 15 controls with status, framework mapping, evidence
  reviewed, auditor findings, and identified gaps (filterable, expandable).
- **Corrective Action Plan (CAP)** — one remediation item per non-conformity, each with
  an owner, deadline, and milestones.
- **Key learning outcomes.**

## 🔗 Live demo

**https://steven-smith-itnet.github.io/internal-isms-audit-demo/**

## About

The organization, evidence, and findings are **fictional** and included only to
demonstrate audit methodology and deliverables. Methodology is aligned to
[ISO 19011:2018](https://www.iso.org/standard/62085.html) auditing guidelines and
[AICPA SOC 2](https://www.aicpa.org/resources/landing/system-and-organization-controls-soc-suite-of-services)
criteria.

## Tech

A single `index.html` — no build step, no dependencies. All styles and interactivity
(status filtering, expandable control rows, CAP accordions) are inline vanilla
HTML/CSS/JS, so it deploys anywhere static files are served (GitHub Pages, S3/CloudFront, etc.).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

---

Part of the portfolio of Steven Smith — Information Security Consultant.
