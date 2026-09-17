# Scoring v2 — human-harm floor notes

Observation: the worst-four formula treats every dimension score of 5 as numerically interchangeable. That can underrate jobs whose central downside is death, catastrophic injury, toxic exposure, lethal confined-space exposure, or severe coercion when pay/hours are unknown or otherwise ordinary.

The intended correction is a post-calculation floor, not a replacement for the worst-four score.

## Proposed floors

1. Calculate the ordinary v2 worst-four score.
2. Apply the strongest supported human-harm floor:
   - **Physical danger 5/5:** minimum **9.3**.
   - **Physical danger 5/5 + one severe co-harm:** minimum **9.6**.
   - **Physical danger 5/5 + two or more severe co-harms:** minimum **9.8**.
   - **Exit/dependency/coercion 4/5:** minimum **9.3**.
   - **Exit/dependency/coercion 5/5:** minimum **9.8**.
3. Final score is the greater of the worst-four score and the applicable floor.

For the danger rule, a **severe co-harm** means any of:

- Compensation penalty **4–5**
- Time capture & availability **4–5**
- Exit/dependency/coercion **3–5**

These floors make catastrophic risk to life and severe loss of freedom categorically worse than ordinary low pay, credential inflation, or office-scope creep.

## Ceiling

An exact **10.0** remains reserved for cases where the scale genuinely runs out of room: typically several maximum-severity harms stacked together, especially documented coercion or inability to leave combined with extreme danger, time capture, or near-zero effective compensation.

## Immediate rescoring examples

- **Acid Tank Cleaner:** base 8.2; Physical danger 5; no verified severe co-harm because pay/hours are undisclosed → **9.3**.
- **Toronto/GTA High Rise Window Cleaner:** base 9.1; Physical danger 5 + Compensation 5 → **9.6**.
- **Dubai IRATA Level 1 Technician:** already 9.6; Physical danger 5 + Compensation 5 → remains **9.6**.

This note exists to make the reasoning auditable before the rule is folded into `SCORING.md`.
