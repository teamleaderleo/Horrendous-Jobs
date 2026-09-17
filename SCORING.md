# Horrendous Score Rubric v2

The **Horrendous Score** runs from **0.0 to 10.0**. It measures how bad the worker bargain is when pay, time, danger, dependence, scope, authority, and human demands are considered together.

The governing idea in v2 is simple:

> **A benign dimension does not cancel a catastrophic one.**

A narrow job can still be a 9.5. A simple job can still be a 10. If an employer buys nearly all of a worker's waking life for very little money, ties housing or immigration status to the job, or sends somebody into lethal conditions, low scope creep is irrelevant consolation.

A second principle now sits beside it:

> **Threats to life, bodily integrity, and freedom outrank ordinary economic insult.**

A lethal confined space, severe toxic exposure, catastrophic fall risk, or documented coercion should not score below a merely cheap employer because the dangerous posting omits salary or has a narrow job description.

## Dimensions

Score each dimension from **0 to 5**.

| Dimension | 0 | 3 | 5 |
|---|---|---|---|
| **Scope creep** | Narrow, coherent role | Several adjacent functions | Multiple professions hiding under one title |
| **Responsibility / authority gap** | Clear ownership and decision rights | Owns outcomes with partial control | Carries severe consequences with little control, staffing, budget, or decision authority |
| **Coordination burden** | Mostly individual work | Frequent cross-team follow-up | Human router across clients, vendors, executives, workers, calendars, approvals, trackers, or sites |
| **Urgency & interruption load** | Predictable work | Competing priorities or incident response | Constant escalation, live emergencies, event-day chaos, or continual interruption |
| **Experience / credential tax** | Requirements fit scope and pay | Meaningful inflation | Specialized certification, years of experience, or education demanded for strikingly weak compensation |
| **Emotional labor** | Little interpersonal load | Regular customer/stakeholder management | Constant service recovery, executive care, conflict, household intimacy, or fragile-stakeholder work |
| **Time capture & availability** | Stable ordinary hours | Recurring evenings/weekends, on-call periods, or substantial spillover | 72+ scheduled hours/week, seven-day working, twelve-hour shifts with minimal rest, or live-in/24-hour availability with unclear boundaries |
| **Compensation penalty** | Strong pay/upside for the local bargain | Mediocre against duties and local context | Extremely low cash wage, near-floor pay for exceptional demands, severe danger for ordinary pay, or compensation that looks grotesque against the time purchased |
| **Physical danger** | Ordinary workplace exposure | Construction, heavy equipment, frequent heights, biohazards, roadside exposure, or emergency-response risk | Catastrophic-consequence work, lethal confined spaces, rope/high-rise exposure, severe toxic exposure, or routine conditions where one failure can kill |
| **Exit / dependency / coercion** | Ordinary ability to quit and leave | Live-in work, overseas placement, employer-controlled housing/transport/visa, or another arrangement that materially raises the cost of leaving | Forced labor, debt bondage, inherited debt, inability to leave, withheld identity documents, or equivalent control over the worker |

### Time-capture anchors

- **1** — occasional overtime or rare schedule spillover.
- **2** — regular non-standard hours, travel, or occasional weekends.
- **3** — recurring evenings/weekends, meaningful on-call exposure, or a schedule that regularly eats personal time.
- **4** — roughly 60–71 scheduled hours/week, frequent 12-hour shifts, or a live-in arrangement with reasonably defined off-time.
- **5** — 72+ scheduled hours/week, seven-day working, only a handful of rest days per month, or residence/on-call expectations that effectively erase the workday boundary.

### Exit/dependency anchors

- **1** — mild practical dependence on employer logistics.
- **2** — employer housing, transport, relocation, or worksite residence creates a meaningful dependency.
- **3** — overseas recruitment, employer-sponsored visa plus housing, or live-in residence materially raises the cost of leaving.
- **4** — strong evidence of wage withholding, document control, recruitment debt, restricted movement, or residence/work arrangements that make exit unusually difficult.
- **5** — forced labor, debt bondage, inherited debt, inability to leave, or equivalent coercion.

## Worst-four calculation

Score every dimension supported by the evidence, then sort the scores from highest to lowest. Let the four highest scores be `h1 >= h2 >= h3 >= h4`.

```text
Base Horrendous Score = 2 × (0.50×h1 + 0.30×h2 + 0.15×h3 + 0.05×h4)
```

Round to one decimal place.

This is deliberately **non-compensatory**. The two worst harms carry 80% of the base score. An easy-to-describe job with no credential requirement does not receive a giant discount for buying 84 hours of somebody's week at miserable pay.

## Human-harm floors

The worst-four calculation still treats every 5/5 dimension as mathematically interchangeable. Human life and freedom deserve additional priority. After calculating the base score, apply the strongest supported floor below.

### Catastrophic physical danger

If **Physical danger = 5/5**:

- Final score is at least **9.3**.
- If the job also has **one severe co-harm**, final score is at least **9.6**.
- If it has **two or more severe co-harms**, final score is at least **9.8**.

For this rule, a **severe co-harm** means any of:

- Compensation penalty **4–5**
- Time capture & availability **4–5**
- Exit / dependency / coercion **3–5**

Examples of 5/5 physical danger include lethal confined-space exposure, severe toxic or corrosive exposure, exterior rope/high-rise work where a single failure can kill, or similarly catastrophic industrial work.

### Severe coercion

If **Exit / dependency / coercion = 4/5**, final score is at least **9.3**.

If **Exit / dependency / coercion = 5/5**, final score is at least **9.8**.

This gives documented wage withholding, document control, recruitment debt with meaningful exit restriction, forced labor, debt bondage, or equivalent control the weight it deserves even when the job is otherwise narrow.

### Final calculation

```text
Horrendous Score v2 = max(Base Horrendous Score, applicable human-harm floor)
```

Round to one decimal place after applying the floor.

There is no generic ±0.5 editorial adjustment in v2. If a dimension needs a different score, change that dimension and explain the evidence. If a human-harm floor applies, state which floor was used.

## Interpretation

| Score | Reading |
|---:|---|
| **0.0–3.9** | Ordinary employment bargain |
| **4.0–5.9** | Mildly cursed |
| **6.0–7.4** | Serious employment friction |
| **7.5–8.4** | Horrendous |
| **8.5–9.2** | **The Abyss** |
| **9.3–9.8** | Extreme human-cost bargain |
| **9.9–10.0** | Ceiling specimen |

## Ceiling calibration

The ceiling is intentionally reserved for work arrangements where several extreme harms stack together. These are **calibration references**, not ordinary posting scores unless a specific public posting supplies the evidence.

| Reference | Approximate v2 reading | Why |
|---|---:|---|
| **Debt-bonded brick-kiln labor** | **10.0** | Near-zero effective compensation can combine with extreme hours, severe danger, and inability to leave or inherited debt. |
| **Bangladesh shipbreaking** | **~9.8–9.9** | Catastrophic industrial danger and toxic exposure paired with very weak compensation and long hours. |
| **Hazardous sewer / septic-tank entry** | **~9.6–9.8** | Lethal confined-space gas exposure can sit inside extremely low-status, weakly compensated contracting arrangements. |
| **12h × 7-day security at INR 18,000/month** | **~9.1** | Time capture and compensation are both maximum-severity even though the job itself is narrow and lacks a documented lethal hazard. |
| **Certified high-rise rope access for AED 1,600–1,900/month** | **~9.6** | Catastrophic physical exposure plus weak compensation triggers the 9.6 danger floor. |
| **Experienced full-time live-in housekeeping at ZAR 4,000–4,250/month** | **~9.6** | Compensation, time/residence capture, experience demands, and dependency all land near the top of the scale. |

An exact **10.0** should feel like the scale has run out of room. The floors stop at 9.8 on purpose; 10.0 still requires an extraordinary stack of evidenced harms rather than a single dangerous feature.

## Danger Premium migration

The old rubric used a separate **Danger Premium** because physical peril barely moved the main score. V2 first fixed that defect by making **Physical danger** a first-class scoring dimension. The human-harm floor now fixes the remaining problem: a catastrophic 5/5 danger can no longer be numerically dragged down by missing salary data or a narrow scope.

Older dossiers may retain a Danger Premium line as historical annotation. New and substantively revised dossiers should score danger directly inside v2 and apply the human-harm floor when warranted. The same applies to live-in, migrant, and coercive arrangements through **Exit / dependency / coercion**.

## Legacy v1 scores

The original v1 score averaged eight dimensions across a raw total out of 40. Existing dossiers can preserve that number as `Legacy v1 score` during migration. New or rescored entries should make the v2 number the primary Horrendous Score.

Do not silently reinterpret an old v1 number as v2.

## Evidence rules

- Record the **date observed**.
- Preserve the **currency, pay period, and stated hours** exactly enough to understand the offer.
- Distinguish advertised requirements from editorial interpretation.
- Summarize duties; keep direct excerpts short.
- Link to the source posting or recruitment post.
- Score only what the evidence supports. Overseas housing does not automatically prove passport confiscation or forced labor.
- Missing pay or hours stay unscored, but missing economic data does not erase a documented lethal hazard.
- If the listing disappears, keep the entry and mark the source inactive when known.
- Score the **employment bargain**, never the people doing the job.

## Common score boosters

Office and service postings often reveal themselves through phrases such as:

- “wear many hats”
- “no two days are the same”
- “nothing falls through the cracks”
- “anticipate needs before they arise”
- “multiple competing priorities”
- “occasional evenings and weekends”
- “serve as the key point of contact”
- “go-to resource”

The global abyss adds a second vocabulary worth hunting for:

- “12 hours duty”
- “7 days working”
- “2 days off per month”
- “live on site” / “must live on property”
- employer-provided accommodation tied to overseas placement
- active rope-access / high-rise certification
- emergency, confined-space, hazardous-material, or heavy-equipment exposure
- recruitment debt, wage withholding, document retention, or inability to leave

None of these proves a score by itself. The evidence determines the dimension values; the worst four produce the base score; documented catastrophic danger or severe coercion can then raise the final score through the human-harm floors.
