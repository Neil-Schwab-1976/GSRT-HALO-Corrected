# GSRT Figures Ledger

**Owner:** Neil J. Schwab · **Last updated:** October 18, 2026

This is the single source of truth for every number and claim in the GSRT / MASH / RWOB documents. **Before any document goes out, scrub it against this Ledger.** Use [scrub.html](scrub.html), or search the document for each Part B entry by hand.

**Rules**
1. A figure not in Part A doesn't go in a document until it's added here with its formula and source status.
2. When a figure changes, change it here first, then add a line to [CHANGES.md](CHANGES.md), then update the documents.
3. Every dollar figure names its track: **Observed**, **Conservative** or **Evidence Floor**. Never blend tracks. Conservative ($80,000) is the headline track.
4. W (wellbeing) and dollars are never added, multiplied or converted into each other.

**Status key:** **S** Sourced (published reference in the Addendum) · **D** Design (locked framework choice) · **M** Modelled (assumption the pilot will test) · **U** Unsourced (do not cite externally)

---

## Part A: Locked figures

### A1. Public cost per high-needs person per year

| Track | Value | Status | Basis |
|---|---|---|---|
| Observed | $120,000 | S (chronic group only) | Below Calgary chronic $134,642 (2008, Gaetz 2012) |
| **Conservative** | **$80,000** | D | Observed × 2/3 |
| Evidence Floor | $56,000 | S | Latimer et al. 2017, five-city At Home/Chez Soi |

### A2. MASH Antifragile

| Figure | Value | Formula | Status |
|---|---|---|---|
| Stay length | 3 months (~90 days) | Newcomer's month 1 overlaps a senior's month 3 | D (locked Oct 18 2026) |
| Cost per stay | $7,500 | 90 × $80 + 3 × $60 = $7,380, rounded up | D |
| Capacity | 200 beds, 20 nodes | Node = 8 participants + 2 Controllers | D |
| First stays per year | 600 | | D |
| Participant stream (40%) | $4,500,000 | 600 × $7,500 | D |
| Year 1 gross | $11,250,000 | $4.5M ÷ 0.40 | D |
| Operations / Community & Elders | $2,250,000 each | 20% each | D |
| Progression / Reserve | $1,125,000 each | 10% each | D |
| Returns per graduate | 0.875 | 0.5 + 0.25 + 0.125 | M |
| Return stays per year | 525 at 30 days | 600 × 0.875 | M |
| Return day rate | $82 | $80 + $60 ÷ 30 | D |
| Return cost, gross | +$3,228,750 | 525 × 30 × $82 = $1,291,500, ÷ 0.40 | M |
| Steady-state gross | $14,478,750 (~$14.48M) | $11.25M + $3.23M | M |
| Occupancy | 95.5% (~96%) | (54,000 + 15,750) ÷ 73,000 | M |
| Gross cost per person | $18,750 / $24,131 with returns | ÷ 600 | D |
| Break-even, Observed | 15.6% / 20.1% | $18,750 ÷ $120,000 | Arithmetic |
| **Break-even, Conservative** | **23.4% / 30.2%** | $18,750 ÷ $80,000 | Arithmetic |
| Break-even, Evidence Floor | 33.5% / 43.1% | $18,750 ÷ $56,000 | Arithmetic |
| Housing First savings | $9.60 per $10; $21.72 per $10 for top 10% | At Home/Chez Soi | S |

### A3. GSRT Earthworks

| Figure | Value | Formula | Status |
|---|---|---|---|
| Wage | $22/hr | | D |
| Hours | 1,500 a year | 6 h × 5 d × 50 wk | D |
| Annual wage | $33,000 | 1,500 × $22 | D |
| Workers | 200 | | D |
| Payroll / gross | $6.6M / $16.5M | 200 × $33,000; ÷ 0.40 | D |
| vs status quo (200 people) | Observed $7.5M less · Conservative $0.5M more · Evidence Floor $5.3M more | $24.0M / $16.0M / $11.2M vs $16.5M | Arithmetic |

### A4. Lighthouse Resilience Programme (20-person node)

| Figure | Observed | **Conservative** | Status |
|---|---|---|---|
| T / S / P / H / C per worker | $10,000 / $800 / $1,500 / $1,000 / $2,000 | $6,667 / $533 / $1,000 / $667 / $1,333 | M |
| Current cost | $306,000 | $204,000 | Arithmetic |
| Reduction rate r | 25% | 25% | M (pilot hypothesis) |
| Projected cost | $229,500 | $153,000 | Arithmetic |
| ΔCost | $76,500 | $51,000 | Arithmetic |
| Programme cost | $9,238 | $9,238 | D (not discounted) |
| Gross return | 8.28 | 5.52 | Arithmetic |
| Net return | 7.28 | 4.52 | Arithmetic |
| Payback | 44 days | 66 days | Arithmetic |
| 10-year value (no ripple factor) | $765,000 | $510,000 | Arithmetic |
| Benchmark to lead with | $1.62 per $1 (year 1), $2.18 (year 3) | | S (Deloitte 2019) |

### A5. Burnout exposure (E_ab): ceiling only, never a return

(20 × 0.20 × $93,000) + (12.5 × $238 × 20) + (4 × $2,500) + $15,000 = **$456,500**. Status: $93,000 and $15,000 are U; A_r = 4 is chosen to reproduce the canon figure.

### A6. Formulas and constants

| Item | Value | Status |
|---|---|---|
| W | (R + B + N + V + M + Gv + Fe + Fm) × Cs | D (illustrative) |
| Cs | 0.8 / 1.0 / 1.2 only | D |
| W worked example | 55 × 1.2 = 66 | Arithmetic |
| Marcus W (illustrative) | 11.2 intake → 48.0 Day 88 → 80.4 later | M |
| VVV | 3.16875; ΔS = 0.15 − (3.16875 × 0.12) = −0.23025 | D (designed, not evidence) |
| Justice Floor | 20 / 40 / 20 / 10 / 10 | D |
| Reverse revenue | R = P ÷ 0.40 | D |

### A7. Environmental and workforce evidence

| Claim | Use | Status |
|---|---|---|
| Land value from greening | 6% (peer-reviewed) to 17% (Wharton); 30% upper bound only | S |
| Flood-cost reduction from keeping wetlands | 29% rural, 38% urban (Ontario) | S |
| Prevention vs relief | 5× (framework); NIBS shows $6 per $1 | S |
| Worker sick days | 12.5 (framework); 18.0 published | S |
| Worker turnover | 20% (framework); ~17% published | S |

### A8. Names, safety and governance

| Item | Locked wording |
|---|---|
| Routing colour key | HALO-WBBRY (5 colours), inspired by NFPA 704. WHMIS appears only as mandatory safety training. |
| Curriculum colours | CCGBI colour wheel |
| Graduation badge | DEEDSPROOF (Trust · Stabilize · Begin) |
| Eligibility | Adults 18+ only |
| MASH pay | Not waged; paid work starts at Earthworks |
| Medical | Medical partnership is a condition of opening |
| Incidents | The person harmed decides whether police are called |
| Partners | "Proposed" or "in discussion with" until signed |
| Health privacy | PHIPA (plus OCAP® for First Nations data), not PIPEDA |
| Marks | Fish Bowl Method™ (not ®) until registered |
| PAWS hurdles | Always "adapted from Gorski (2013)" |
| Site | Crown land near Cobalt / Coleman Township, or an alternative (open) |

---

## Part B: Withdrawn. Scrub these out.

| If a document says | Replace with | Why |
|---|---|---|
| $918,000 (LRP 10-year) | $765,000 | Needs an unsourced ripple factor of 2 |
| $918,540 / $918,660 | Remove | Long-Term Projection withdrawn |
| 18.7:1 or 11.9:1 | Break-even 23.4% (Conservative) | Assumed 100% of costs avoided |
| 19.3% break-even | 23.4% / 33.5% / 15.6% | Old unitemized cost |
| $3.5M or $3.75M ask | $11.25M Year 1 (~$14.48M with returns) | Covered about one cycle |
| 4-month stay; $10,000 stay | 3-month stay, $7,500 | Locked Oct 18 2026 |
| 50-bed return node | Remove | Returns fit inside 200 beds |
| $105K–$130K; "CIHI / Public Safety Canada / ESDC" | Three tracks (A1) | Untraced |
| 30%–64% land value; 30% as "floor" or "minimum" | 6%–17% | 64% not located |
| 6×–10× flood; UNDRR; 60% flood reduction | 29%–38%; NIBS $6 per $1 | Not located / maximum scenario |
| Kenya; 500× | Remove | Simulation, never a field result |
| "verified" (by AI); "H-6/6"; "three AI systems" | Remove | AI review is not verification |
| "Mathematically verified"; "the math is verified" | "Every formula is shown so it can be checked" | Nothing is verified before pilot data |
| "Historically Unprecedented" | Remove | Self-rating |
| "$40,000 retires debt in 120 days" | Remove | No derivation |
| WHMIS as a colour category | HALO-WBBRY | WHMIS has no colour categories |
| 49.4× | Do not cite | Exposure ceiling ÷ cost |
| $3.27 per $1 "Harvard" | Do not cite | Source not located |
| $185,000 swing; $65,000 or $44,000 wage; $8,800 tax | $33,000 wage | Off-canon |
| "× 10" seed multiplier; $37M | Cascading Seed Model (10% reserve) | No source |
| Cs 1.1 or 1.15 | 0.8 / 1.0 / 1.2 | Outside locked set |
| TSB dollar figures | Do not cite | Formula and baseline open |
| "Supported by the Ontario Government" | Remove | Not true yet |
| "In partnership with" (unsigned) | "Proposed partners" | Not signed |
| "40 First Nations in network"; "veto on traditional territory" | Remove until a Nation agrees in writing | Speaks for Nations |
| "Academically validated" | "Built on validated frameworks (CENAPS, MI, CRA)" | SAF and OCI unvalidated |
| "Siegel 2012 … 50%" | Lieberman et al. 2007, no percentage | Wrong source |
| Fish Bowl Method® | Fish Bowl Method™ | Not registered |
| "No police. No court." | Incident line (A8) | Unsafe, uninsurable |
| "Paid participation"; "$22/hr on entry" | Not waged at MASH | Conflicts with canon |
| "Fixed camp, York Region" | Cobalt / Coleman (A8) | Off-canon site |
| Teens / youth in MASH | Adults 18+ | Needs a separate framework |
| PIPEDA for health records | PHIPA | Ontario health law |
| Gold = highest hourly pay | Gold = Elder mentors 55+ (canon update pending) | Neil's correction |
| "Field-validated" VVV | Designed constant | No field data |
| "Peer-reviewed" Taleb | Published book | Not peer-reviewed |
| "The real numbers will almost certainly be higher" | Remove | The pilot decides |

---

## Part C: Open (don't cite until settled)

- TSB formula and baseline (W = 25 vs 11.2)
- Block 10 name; Block 4 has two names; G.A.P.S. neurochemical mapping differs between documents
- Earthworks capacity: 200 jobs vs ~600 graduates a year
- Year 1 Controllers: 40 hires at ~$45K ≈ $1.8M of the $2.25M Operations stream
- Operator entity, site, medical partner, User Area (s. 56.1)
- Sourcing for LRP dollar inputs, $93,000 replacement cost and $15,000 injury claim
