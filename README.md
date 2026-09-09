# Horrendous Jobs Index

> Cataloguing extraordinary demands for ordinary compensation.

**Horrendous Jobs** is a public archive of job postings with spectacular effort-to-reward ratios: enormous scope, thin authority, relentless coordination, heroic availability, physical peril, tied residence, and compensation that makes the whole thing sing.

The goal is comedy **and** a usable dataset. Every entry records the advertised pay, requirements, responsibilities, source, observation history, and a subjective **Horrendous Score**.

## Scoring v2

**Horrendous Score v2 is now canonical.** The old formula averaged every dimension together, which let easy dimensions cancel catastrophic ones. A narrow 84-hour security job could therefore score lower than a busy office coordinator.

V2 scores ten dimensions and lets the **four worst harms dominate**:

```text
Score = 2 × (0.50×h1 + 0.30×h2 + 0.15×h3 + 0.05×h4)
```

where `h1 >= h2 >= h3 >= h4` are the four highest dimension scores.

Physical danger and exit/dependency/coercion now live inside the main score. Older dossiers can preserve their old number as a **Legacy v1 score** while they are migrated.

Full rubric and ceiling calibration: [`SCORING.md`](SCORING.md)

## Global Job-Board Abyss — v2

These are the public listings and recruiter posts that forced the scoring rewrite.

| Score v2 | Specimen | Listed pay | Schedule / condition |
|---:|---|---:|---|
| **9.6** | [Construction-Site Security Guard — Mumbai](entries/2026-09-08-jobmygoal-security-guard-mumbai.md) | INR 15k–20k/month | 12-hour shift · live on construction site |
| **9.6** | [IRATA Level 1 Technician — Dubai](entries/2026-09-08-skyperz-irata-level-1-technician-dubai.md) | AED 1.6k–1.9k/month | Certified high-rise rope access |
| **9.6** | [Live-In Housekeeper — Durban](entries/2026-09-08-debt-relief-group-live-in-housekeeper-durban.md) | ZAR 4k–4.25k/month | Five years' experience · must live on property full-time |
| **9.2** | [Plant Security Guard — Durgapur](entries/2026-09-08-job-resource-point-security-guard-durgapur.md) | INR 15k–17k/month | 12-hour duty · employer lodging · home 35 km+ away |
| **9.1** | [Security Guard — Chennai](entries/2026-09-08-mss-facility-management-security-guard-chennai.md) | INR 18k/month | **12 hours/day · 7 days/week** |
| **9.1** | [High Rise Window Cleaner — Toronto/GTA](entries/2026-09-08-himalayas-building-maintenance-high-rise-window-cleaner.md) | From CAD $18/hour | Exterior high-rise fall exposure |
| **9.1** | [Cleaner — Bahrain recruiter post](entries/2026-09-08-sky-rise-enterprises-cleaner-bahrain.md) | BHD 110/month | 12 hours/day · 2 days off/month |
| **9.1** | [General Cleaner — Dubai recruiter post](entries/2026-09-08-sky-rise-enterprises-general-cleaner-dubai.md) | AED 900/month + food | 12 hours/day · one weekly off |
| **9.1** | [Cleaner — UAE recruitment post](entries/2026-09-08-khin-shin-thant-cleaner-uae.md) | AED 900/month | 12 hours/day · one weekly off |
| **7.9** | [SkyCargo Loader — UAE recruitment drive](entries/2026-09-08-amco-enterprise-skycargo-loader-uae.md) | AED 1,008/month | Hours omitted; overseas airport-logistics recruitment |

The ceiling is calibrated against research cases rather than pretending LinkedIn contains the whole labor market: **debt-bonded brick kilns ≈ 10.0**, **Bangladesh shipbreaking ≈ 9.8–9.9**, and **hazardous sewer/septic entry ≈ 9.6–9.8**.

See [`ABYSS.md`](ABYSS.md) for the cabinet and [`research/global-danger-pay.md`](research/global-danger-pay.md) for the broader global reference set.

## Legacy v1 Toronto leaderboard

The table below preserves the original scores until each dossier receives a v2 pass. Treat these numbers as **v1**, not directly comparable to the v2 Abyss table above.

| Score v1 | Company | Role | Location | Listed pay | Signature crime |
|---:|---|---|---|---:|---|
| **9.8** | Sterling Karamar Property Management | [Resident Manager (Live-In) — North York](entries/2026-09-07-sterling-karamar-resident-manager-live-in-north-york.md) | North York, Toronto | CAD $30k–$34k | 🔥 Everything Is Urgent Award |
| **9.5** | Helia Capital | [Executive Assistant & Family Office Coordinator](entries/2026-09-07-helia-capital-executive-assistant-family-office-coordinator.md) | Toronto, ON | From CAD $70k | 👑 Royal Servant Award |
| **9.5** | PheedLoop | [Customer Service Specialist — Logistics](entries/2026-09-07-pheedloop-customer-service-specialist-logistics.md) | Toronto, ON | CAD $50k | 🏔 Moving Mountains Award |
| **9.5** | Ramachandran Law Holding Corporation | [Executive Assistant to Managing Director](entries/2026-09-07-ramachandran-law-executive-assistant-managing-director.md) | Scarborough, ON | CAD $45k–$55k | 👑 Royal Servant Award |
| **9.5** | No Small Feast | [Event Coordinator](entries/2026-09-07-no-small-feast-event-coordinator.md) | Etobicoke, ON | CAD $50k–$60k | 🔥 Everything Is Urgent Award |
| **9.5** | Impact Cleaning Services | [Quality and Service Specialist](entries/2026-09-07-impact-cleaning-quality-service-specialist.md) | Toronto, ON | CAD $45k–$50k + 5% bonus | 🏔 Moving Mountains Award |
| **9.5** | Acupuncture Center Toronto | [Clinic Coordinator](entries/2026-09-07-acupuncture-center-toronto-clinic-coordinator.md) | Toronto, ON | From CAD $23/hour | 🧢 Seven Jobs in a Trench Coat |
| **9.5** | Morguard | [Building Manager](entries/2026-09-07-morguard-building-manager.md) | Toronto, ON | CAD $45k–$60k | 🔥 Everything Is Urgent Award |
| **9.5** | Merrithew International Inc. | [Front Desk Coordinator](entries/2026-09-08-merrithew-front-desk-coordinator.md) | Toronto, ON | CAD $18/hour | 🧢 Seven Jobs in a Trench Coat |
| **9.5** | Massage Experts Vaughan | [Clinic Manager](entries/2026-09-08-massage-experts-vaughan-clinic-manager.md) | Concord, ON | CAD $20/hour | 🏔 Moving Mountains Award |
| **9.3** | The Students Commission of Canada | [Coordinator, Finance & Operations](entries/2026-09-07-students-commission-finance-operations-coordinator.md) | Canada / GTA hybrid | CAD $50k–$58k | 🧢 Seven Jobs in a Trench Coat |
| **9.3** | BT/A Advertising | [Account Coordinator](entries/2026-09-07-bta-account-coordinator.md) | Toronto, ON | CAD $45k–$55k | 👑 Royal Servant Award |
| **9.3** | Yonge Urgent Care Clinic | [Medical Office Administrator](entries/2026-09-08-yonge-urgent-care-medical-office-administrator.md) | Toronto, ON | From CAD $20/hour | 🔥 Everything Is Urgent Award |
| **9.3** | Spectrum Health Care | [Client Services Coordinator, PT](entries/2026-09-08-spectrum-health-care-client-services-coordinator-pt.md) | Toronto, ON | CAD $19–$20/hour | 📨 Human Router Award |
| **8.8** | Kotn | [Marketing Coordinator](entries/2026-09-07-kotn-marketing-coordinator.md) | Toronto, ON | CAD $45k–$55k | 🧢 Seven Jobs in a Trench Coat |
| **8.8** | Gambles Group of Companies | [HR Coordinator](entries/2026-09-07-gambles-hr-coordinator.md) | Toronto, ON | CAD $40k–$50k | 🎓 Degree Required to Send Follow-Ups Award |
| **8.8** | Bloor Pain Specialists | [Medical and Administrative Assistant](entries/2026-09-07-bloor-pain-specialists-medical-administrative-assistant.md) | Toronto, ON | CAD $20/hour | 🪙 Minimum Wage Megazord Award |
| **8.8** | Stark Wellness Clinic | [Client Care Coordinator](entries/2026-09-07-stark-wellness-client-care-coordinator.md) | Toronto, ON | From CAD $20/hour | 🎓 Degree Required to Send Follow-Ups Award |
| **8.8** | Curate Health | [Office Manager (Clinic Reception, Administration & Cafe Support)](entries/2026-09-07-curate-health-office-manager-clinic-cafe.md) | Toronto, ON | CAD $20–$24/hour | 🧢 Seven Jobs in a Trench Coat |
| **8.8** | WorkStaff360 | [URGENT: Personal Administrative Assistant](entries/2026-09-08-workstaff360-personal-administrative-assistant.md) | Toronto, ON / hybrid | USD $4→$5/hour | 🪙 Minimum Wage Megazord Award |
| **8.5** | Northcott Silk Inc. | [Licensing Marketing Coordinator](entries/2026-09-07-northcott-silk-licensing-marketing-coordinator.md) | Vaughan, ON | CAD $42k–$47k | 🏔 Moving Mountains Award |
| **8.5** | Painless Medicine and Therapeutics Inc. | [Administrative Assistant](entries/2026-09-07-painless-medicine-administrative-assistant.md) | Toronto, ON | From CAD $18/hour | 🪙 Minimum Wage Megazord Award |
| **8.5** | Activate Beauty | [Clinic Manager / Sales Manager](entries/2026-09-07-activate-beauty-clinic-manager-sales-manager.md) | Toronto, ON | From CAD $25/hour + bonus | 🔥 Everything Is Urgent Award |
| **8.3** | Cineplex | [Account Coordinator, Media Sales](entries/2026-09-07-cineplex-account-coordinator-media-sales.md) | Toronto, ON | CAD $50k–$55k | 📨 Human Router Award |
| **8.3** | Trevant | [Creator Operations Coordinator](entries/2026-09-07-trevant-creator-operations-coordinator.md) | Toronto, ON | CAD $45k–$60k | 🧢 Seven Jobs in a Trench Coat |
| **8.3** | CMiC | [Project Coordinator](entries/2026-09-07-cmic-project-coordinator.md) | Toronto, ON | CAD $45k–$55k incl. bonus | 🎓 Degree Required to Send Follow-Ups Award |
| **8.3** | Match Sports International Inc. | [Production Coordinator — Apparel](entries/2026-09-07-match-sports-production-coordinator-apparel.md) | Scarborough, ON | Minimum wage → CAD $40k–$50k | 🪙 Minimum Wage Megazord Award |
| **8.3** | Nascent | [Office Coordinator](entries/2026-09-07-nascent-office-coordinator.md) | Toronto, ON | CAD $40k–$50k | 🫠 Competence Tax Award |
| **8.3** | Renso Foods | [Executive Assistant, Events & Partnerships](entries/2026-09-07-renso-foods-executive-assistant-events-partnerships.md) | Etobicoke, ON | CAD $50k–$65k | 🧢 Seven Jobs in a Trench Coat |
| **7.8** | Canadian Health Providers | [Clinic Administrator](entries/2026-09-07-canadian-health-providers-clinic-administrator.md) | Mississauga, ON | CAD $17.60–$20/hour | 🪙 Minimum Wage Megazord Award |
| **7.8** | Hitters Fight Club | [Administrative Manager](entries/2026-09-07-hitters-fight-club-administrative-manager.md) | Toronto, ON | CAD $20–$28/hour | 🧢 Seven Jobs in a Trench Coat |
| **7.8** | Altima Fire Protection Inc. | [Fire Protection Office Manager](entries/2026-09-07-altima-fire-protection-office-manager.md) | Toronto, ON | CAD $20–$30/hour | 📊 Spreadsheet Atlas Award |
| **7.6** | Gensler | [Project Coordinator](entries/2026-09-07-gensler-project-coordinator.md) | Toronto, ON | CAD $65k–$72k | 📊 Spreadsheet Atlas Award |
| **7.5** | Pause Design Inc. | [Accounting Clerk](entries/2026-09-07-pause-design-accounting-clerk.md) | Toronto, ON | CAD $20–$25/hour | 🪙 Minimum Wage Megazord Award |

See [`entries/`](entries/) for the dossiers.

## Days in the Wild

Each specimen has a persistence record. We track **first seen, last seen, disappearance, reposts, salary changes, title changes, and Days in the Wild**.

```text
Days in the Wild = last_seen - first_seen
```

A new specimen begins at Day 0. Repeated sightings extend its observed span. If a posting disappears and later returns, the repost count increases and the event history preserves the gap.

- Current state: [`tracking/jobs.csv`](tracking/jobs.csv)
- Append-only observation log: [`tracking/events.csv`](tracking/events.csv)
- Tracking methodology: [`TRACKING.md`](TRACKING.md)

## The Horrendous Score

V2 scores ten dimensions:

- **Scope creep**
- **Responsibility / authority gap**
- **Coordination burden**
- **Urgency & interruption load**
- **Experience / credential tax**
- **Emotional labor**
- **Time capture & availability**
- **Compensation penalty**
- **Physical danger**
- **Exit / dependency / coercion**

The four worst dimension scores determine the result. This makes the score intentionally non-compensatory: a low-danger office role can still score through scope and responsibility, while a narrow physical job can score through danger, time, dependency, and pay.

## Awards

Recurring achievements in the field of employment horror:

- 🏔 **Moving Mountains Award** — enormous responsibility, astonishingly modest pay.
- 📨 **Human Router Award** — the role exists to move information between people who could theoretically communicate.
- 🧢 **Seven Jobs in a Trench Coat** — one title concealing several professions.
- 🔥 **Everything Is Urgent Award** — permanent real-time escalation mode.
- 👑 **Royal Servant Award** — professional support expands into managing another person's earthly existence.
- 📊 **Spreadsheet Atlas Award** — personally responsible for maintaining the organization's canonical representation of reality.
- 🫠 **Competence Tax Award** — reliability earns additional responsibilities.
- 💰 **Surely There's Equity? Award** — startup-level scope with ordinary employee upside.
- 🎓 **Degree Required to Send Follow-Ups Award** — credential requirements wildly exceed the intellectual content of the role.
- 🪙 **Minimum Wage Megazord Award** — professional credentials or enormous human demands assembled around near-floor compensation.
- 🪂 **Mortal Peril Premium Award** — serious physical hazard paired with astonishingly ordinary compensation.

## Add a specimen

**[Submit a horrendous job](https://github.com/teamleaderleo/Horrendous-Jobs/issues/new/choose)** by pasting the public posting into an issue. Raw copy-paste is welcome; parsing, cleanup, scoring, tracking, and dossier formatting can happen later.

Want to contribute a finished dossier directly? Copy [`entries/TEMPLATE.md`](entries/TEMPLATE.md), fill it in, and submit the change.

A strong finished entry includes:

1. A public source URL.
2. First and most recent observation dates.
3. Salary and schedule exactly enough to understand the offer.
4. Requirements and responsibilities summarized faithfully.
5. A v2 score with the dimension evidence shown.
6. Posting status and any repost/pay/title history.
7. Short excerpts only when the employer's own wording is especially revealing.

## Principles

- **Attack the posting, not the worker.** Many difficult jobs are performed by talented people doing extraordinary work.
- **Quote sparingly.** Summarize job descriptions and link to the original source instead of reproducing them wholesale.
- **Show your work.** Separate facts from commentary.
- **Keep historical entries.** A dead listing is still useful evidence; mark it inactive when known.
- **Pay is contextual.** Currency, location, hours, employment type, danger exposure, dependency, and date belong with the number.
- **The title proves nothing.** Score what the employer actually asks the person to do.
- **Do not infer coercion.** Employer housing or overseas placement can raise dependency without proving forced labor.
- **Track observed facts.** A disappearance records that the listing vanished from the checked source; it says nothing by itself about whether somebody was hired.

## Status

Started in Toronto in September 2026. **Forty-four posting/recruitment specimens** are indexed, the Global Job-Board Abyss is live, and v2 scoring migration has begun.

---

*This project is commentary on publicly advertised employment terms. Scores and award names are subjective editorial judgments.*
