# QualityTrack WP — Waterproofing Quality Control System

> A role-based interactive demo of a digital waterproofing inspection and quality control workflow built for real estate developers and construction teams across India.

**[→ View Live Demo](https://iammohith.github.io/qualitytrack-wp)** &nbsp;|&nbsp; **[→ Request a Demo](https://forms.gle/uaQC4HqngYENuAns9)** &nbsp;|&nbsp; **[→ Connect on LinkedIn](https://www.linkedin.com/in/mohith-sai-gorla-75930318b/)**

---

## What is QualityTrack WP?

QualityTrack WP is a digital quality control platform that governs the complete waterproofing activity lifecycle in multi-storey residential and commercial construction projects. It replaces paper-based inspection checklists with a structured, sequential digital workflow — ensuring every stage is inspected, every approval is tracked, and every failure is documented before it becomes a defect liability.

This repository contains a fully interactive HTML demo that simulates the real-time user experience of the application — no backend required, runs entirely in the browser.

---

## The Problem It Solves

Waterproofing failures in residential construction are one of the most common and costly post-handover defect claims. The root cause is almost always the same — stages were skipped, approvals were verbal, photos were never taken, and there is no paper trail when accountability is needed.

QualityTrack WP makes stage-skipping impossible, approval unambiguous, and the audit trail automatic.

---

## Key Features

- **5-stage sequential workflow** — RCC Readiness → MEP Core Cut → Surface Preparation → WP Coating → Protection Screed & Final Sign-Off
- **37 quality control checkpoints** across all stages, written as plain yes/no questions for field engineers
- **Mandatory QC approval gate** between every stage — next stage unlocks only after the prior stage is approved
- **Role-based views** — each role sees only what is relevant to them
- **Photo evidence** required per checklist item
- **Automatic consolidated quality record** generated on final approval
- **Zero paperwork** — fully digital, fully traceable

---

## Role-Based Experience

| Role | What They See |
|---|---|
| **Project Director** | Live dashboard — active activities, stage pipeline, pending QC decisions, overdue alerts, recent approvals |
| **QC Inspector** | Pending review panel with direct jump to submitted stage forms — approve or reject with comments |
| **Site Engineer** | Only their assigned stage checklist — pre-populated master data, sequential YES/NO/N/A items |
| **Full Specification** | Complete technical documentation — all 11 sections, all stages, traceability matrix, glossary |

---

## Workflow Overview

```
Civil RCC Creates Activity
        ↓
Stage 1 — RCC Structural Readiness       [Civil Finish Team → QC Review 1]
        ↓ QC Approved
Stage 2 — MEP Core Cut & Installation   [MEP Team → QC Review 2]
        ↓ QC Approved
Stage 3 — Surface Prep & Pre-Ponding    [WP Team → QC Review 3]
        ↓ QC Approved
Stage 4 — WP Coating Application        [WP Applicator → QC Review 4]
        ↓ QC Approved
Stage 5 — Protection Screed & Final     [Civil Finish Team → Final QC]
        ↓ QC Approved
Activity Closed — Consolidated Record Generated
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts — Spectral, Barlow, JetBrains Mono |
| Hosting | GitHub Pages (static, zero backend) |
| Lead Capture | Google Forms |

> The production application is planned on Python (FastAPI), PostgreSQL, and a React frontend with role-based access control, photo uploads to S3, and real-time notifications.

---

## Getting Started

### View the demo
Simply open the live URL: **[https://yourusername.github.io/qualitytrack-wp](https://yourusername.github.io/qualitytrack-wp)**

### Run locally
```bash
git clone https://github.com/yourusername/qualitytrack-wp.git
cd qualitytrack-wp
# Open index.html in any browser — no build step, no dependencies
open index.html
```

---

## Project Structure

```
qualitytrack-wp/
├── index.html          # Complete self-contained application (single file)
├── README.md           # This file
├── CODE_OF_CONDUCT.md  # Community standards
└── CONTRIBUTING.md     # How to contribute
```

---

## Planned Production Modules

- Super Admin Login & Authentication
- Role-Based Access Control (RBAC)
- Admin & Project Manager Panels
- Photo upload with geolocation tagging
- Non-Conformance Report (NCR) tracking
- Material register (batch numbers, DFT records)
- PDF export — consolidated quality record
- Push notifications on stage transitions
- Offline / PWA mode for field use
- Multi-project dashboard with analytics

---

## Request a Demo

Interested in deploying QualityTrack WP for your projects?

**[Fill the demo request form →](https://forms.gle/uaQC4HqngYENuAns9)**

Or connect directly on LinkedIn: **[Mohith Sai Gorla](https://www.linkedin.com/in/mohith-sai-gorla-75930318b/)**

---

## License

This project is proprietary software. The demo is shared publicly for evaluation purposes only. Reproduction, distribution, or commercial use without explicit written permission from the author is not permitted.

© 2026 Mohith Sai Gorla. All rights reserved.
