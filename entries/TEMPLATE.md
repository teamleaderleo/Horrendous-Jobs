# [Company] — [Role]

**Horrendous Score v2:** X.X / 10  
**Legacy v1 score:** X.X / 10 (omit for brand-new entries)  
**Award(s):** [emoji Award Name]  
**Location:** [City, Region, Country]  
**Listed pay:** [currency + range + period]  
**Employment type:** [full-time / part-time / contract / etc.]  
**Expected hours:** [schedule when stated]  
**First observed:** YYYY-MM-DD  
**Last observed:** YYYY-MM-DD  
**Posting status:** active / disappeared / reposted / unknown  
**Repost count:** 0  
**Days in the Wild:** 0  
**Source:** [Job posting](https://example.com)

## The posting

Summarize the role faithfully in a short paragraph. Focus on the actual combination of duties, requirements, availability, physical exposure, dependency, and compensation.

### Advertised responsibilities

- Responsibility one
- Responsibility two
- Responsibility three

### Advertised requirements

- Requirement one
- Requirement two

## Scorecard

| Dimension | Score / 5 | Evidence |
|---|---:|---|
| Scope creep | X | |
| Responsibility / authority gap | X | |
| Coordination burden | X | |
| Urgency & interruption load | X | |
| Experience / credential tax | X | |
| Emotional labor | X | |
| Time capture & availability | X | |
| Compensation penalty | X | |
| Physical danger | X | |
| Exit / dependency / coercion | X | |

**Worst four dimensions:** X, X, X, X  
**Base score:** **X.X / 10**  
**Human-harm floor:** none / 9.3 / 9.6 / 9.8 — [reason]  
**Horrendous Score v2:** **X.X / 10**

Use the canonical rules in [`SCORING.md`](../SCORING.md):

```text
Base = 2 × (0.50×h1 + 0.30×h2 + 0.15×h3 + 0.05×h4)
Final = max(Base, applicable human-harm floor)
```

where `h1 >= h2 >= h3 >= h4` are the four highest dimension scores. Catastrophic 5/5 physical danger and severe 4–5/5 coercion can impose score floors; document the floor explicitly when one applies.

## Why it belongs here

Explain the worker bargain in a few sentences. Keep facts and commentary clearly distinguishable.

## Signature crime

> One short sentence describing the essence of the posting.

## Posting history

| Date | Event | Details |
|---|---|---|
| YYYY-MM-DD | First observed | Initial title and pay |

Track later sightings, disappearance, reposts, salary changes, title changes, and source changes here. Mirror current state in [`tracking/jobs.csv`](../tracking/jobs.csv) and append observations to [`tracking/events.csv`](../tracking/events.csv).

## Notes

Add corrections, alternate listings, legacy-v1 migration notes, human-harm-floor notes, or other useful context here.
