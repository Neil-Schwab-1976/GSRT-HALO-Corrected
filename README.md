# HALO GSRT Pathway

### From street-level intake to a 3-month MASH recovery camp to paid work at GSRT Earthworks

**Author:** Neil J. Schwab, HALO Antifragile AI Framework Architect
**Status:** Proposal and prototype. Not funded, not in service, not clinically reviewed.
**Last updated:** October 18, 2026

## The pathway in one paragraph

A person caught in the cycle of emergency rooms, police contact and shelters meets a worker who uses the RWOB intake to understand what they need. At the **Choice Point** they get an honest choice between Path A, the existing system, and **Path B**. Path B is never assigned. Path B is **MASH Antifragile**: a 200-bed, peer-run, land-based recovery camp. The stay is three months, with medical care alongside it, never in place of it. Every newcomer spends their first month shadowing a senior who is in their final month. Graduates earn the DEEDSPROOF badge and move into paid work at **GSRT Earthworks** (environmental restoration at $22/hr). The aim is to turn a recurring public cost into a working member of the community.

```
Worker conversation → RWOB intake → Choice Point → Path B → MASH (3 months) → DEEDSPROOF → GSRT Earthworks
```

## About this repository

This repository holds the corrected versions of the GSRT / MASH / RWOB documents. Every dollar figure here was rechecked against the GSRT Mathematics Manual (corrected v2) and the Citations & Evidence Addendum. It replaces an earlier public repository, which contained claims and figures that have since been withdrawn (see [CHANGES.md](CHANGES.md)).

## Read this first: what is modelled and what is measured

- **Every dollar figure is a simulation.** Each is built on conservative published floors. None of it is pilot data. A figure counts as evidence only once a pilot's measured outcomes replace it.
- **Marcus and Laura are illustrative cases.** They are not real participants.
- **The W-score is a wellbeing index, not dollars.** It is never added to or multiplied with costs.
- **Nothing here has been "verified" by an AI system.** AI tools helped draft and check the arithmetic. Checking means re-running the numbers yourself; the [How to check the math](#how-to-check-the-math) section shows how.
- **Partnerships named in these documents are proposed.** None is signed.

## What's in here

| File | What it is |
| --- | --- |
| `index.html` | The homepage. With GitHub Pages turned on, it links to everything below. |
| `GSRT_Institutional_Dossier_24_One-Pagers.pdf` | **Start here.** 24 designed pages that follow one person, Marcus: the worker conversation, the Choice Point, Path B, MASH (one page per gear), then Earthworks and the numbers. |
| `MASH Antifragile Locked Specification` (.pdf, .docx) | The locked camp specification: who it's for, the site, the 3-month pathway, daily rhythm, graduation, the app, G.A.P.S. firmware, safeguards, measurement, costs and open decisions. |
| `GSRT_Citations_Evidence_Addendum` (.pdf, .docx) | Source trail for every figure, with what was traced, what wasn't, and what changed. |
| `LRP_Marcus_ROI_Workbook_AUDITED.xlsx` | Life Recovery Pathway ROI workbook. All inputs are editable, so anyone can enter their own numbers. |
| `RWOB_Intake_MERGED.html` | Merged RWOB intake prototype: member profile (contact optional), safety gate, RAFT, validated screens, 26-item check-in, HALO-WBBRY colour result, organization and clinician matches. Demo only: it stores nothing and contacts no one. |
| `RWOB_Outreach_ColourMatch_Tracking_V2_2.docx`, `TREATMENT_PATHWAY_MASTER_SEXTON_MANUAL_v2.docx` | Outreach tracker and Sexton treatment-pathway manual, with WHMIS wording replaced by the HALO-WBBRY colour key. |
| `CHANGES.md` | What was corrected from earlier versions, and why. |

**To open it as a website:** turn on GitHub Pages (Settings → Pages → Deploy from branch → `main`, folder `/ (root)`). The site address will be `https://neil-schwab-1976.github.io/GSRT-HALO-Corrected/`. Free accounts need the repository to be public for Pages.

## The core numbers (Conservative track unless noted)

**MASH: one camp, 200 beds, 3-month stays**

| Figure | Value | How it's derived |
| --- | --- | --- |
| Cost per stay | $7,500 | 90 days × $80 + 3 × $60 = $7,380, rounded up |
| Direct participant cost | $4.5M/yr | 600 stays × $7,500 |
| Gross Year 1 ask | $11.25M | $4.5M is the 40% stream of the Justice Floor (20/40/20/10/10), so R = P ÷ 0.40 |
| With return stays | about $14.48M/yr | 525 returns × 30 days × $82 = $1.29M, grossed up ÷ 0.40 to +$3.23M |
| Bed use | about 96% | 54,000 + 15,750 = 69,750 of 73,000 bed-days |
| Gross cost per person | $18,750 ($24,131 with returns) | $11.25M ÷ 600 |

**Break-even:** the share of a person's current public cost that MASH must avoid to pay for itself.

| Public cost per person per year | Track | First stays | With returns |
| --- | --- | --- | --- |
| $120,000 | Observed | 15.6% | 20.1% |
| **$80,000** | **Conservative** | **23.4%** | **30.2%** |
| $56,000 | Evidence Floor (Latimer et al. 2017) | 33.5% | 43.1% |

The three tracks are never blended.

**LRP (Marcus case):** ΔCost $76,500. Gross ratio 8.28, net 7.28. Payback 44 days. 10-year value $765,000, with no ripple factor. Conservative track: 5.52 gross, 4.52 net.

**Earthworks:** $33,000 per worker per year (6 h × 5 d × 50 wk × $22). 200 workers is $6.6M in payroll and $16.5M gross.

## How to check the math

1. Open `LRP_Marcus_ROI_Workbook_AUDITED.xlsx`. Change any input cell, and every result recalculates.
2. Re-run the MASH figures from the table above with a calculator. Every line shows its formula.
3. Look up each source in the Citations & Evidence Addendum. Where the Addendum says a figure could not be traced, it isn't used as an anchor.

## Still open (to settle before a costed proposal goes to a funder)

Each item is in section "Open decisions" of the MASH specification.

- Site, medical partner and operator (charity, non-profit, co-op or Nation-run). A government won't fund a sole proprietorship.
- Year 1 Controllers: hiring 40 peer workers at about $45K would take about $1.8M of the $2.25M Operations stream.
- The legal route for the supervised User Area (a Health Canada s. 56.1 exemption).
- Earthworks capacity: 200 jobs against about 600 graduates a year.
- Block 10 has no name, and Block 4 has two. The G.A.P.S. neurochemical mapping differs between documents.
- The week-by-week 3-Day Get-A-Way map for the 13-week stay, and the six DEEDSPROOF module fixes.
- The Mathematics Manual still carries errors ($918,000 should be $765,000; the $105–130K range; land and flood sources). It isn't included here until those are corrected.

## Rights

© 2026 Neil J. Schwab. All rights reserved unless a licence file says otherwise. G.A.P.S., HALO-WBBRY, DEEDSPROOF and Fish Bowl Method™ are the author's working names; none is a registered mark yet.

## Crisis resources (Canada)

Call or text **9-8-8** (Suicide Crisis Helpline, 24/7). Call **9-1-1** in an emergency.
