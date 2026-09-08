# Posting Persistence Tracking

The archive records more than what an employer asks for. It also tracks **how long the posting survives in the wild and how it mutates over time**.

The current-state table lives at [`tracking/jobs.csv`](tracking/jobs.csv). Observation history lives at [`tracking/events.csv`](tracking/events.csv).

## Fields

| Field | Meaning |
|---|---|
| `first_seen` | First date the posting was observed publicly available |
| `last_seen` | Most recent date the posting was confirmed available |
| `status` | `active`, `disappeared`, `reposted`, or `unknown` |
| `repost_count` | Number of observed reappearances after a disappearance |
| `pay_original` | Compensation advertised at first observation |
| `pay_latest` | Most recently observed advertised compensation |
| `pay_changed` | Whether advertised compensation changed |
| `role_original` | Original advertised title |
| `role_latest` | Most recently observed title |
| `title_changed` | Whether the title changed materially |
| `days_in_wild` | Calendar days between `first_seen` and the most recent confirmed sighting |

## Days in the Wild

```text
Days in the Wild = last_seen - first_seen
```

This is an **observed span**, not a claim that the listing stayed continuously active every hour between checks. When a listing disappears, `last_seen` remains the last confirmed sighting. If it later returns, increment `repost_count`, mark it `reposted`, update `last_seen`, and append a new event.

A posting seen only once begins at **0 days in the wild**.

## Event log

`tracking/events.csv` is append-only. Useful event types:

- `first_observed`
- `still_active`
- `disappeared`
- `reposted`
- `pay_changed`
- `title_changed`
- `source_changed`

One check can produce several events. For example, a repost may also arrive with a higher salary and a softened title.

## Matching reposts

Treat a listing as the same specimen when the employer, work, location, and core responsibilities are substantially the same, even if the URL or wording changes.

When uncertain, preserve both records and explain the possible relationship in the event notes.

## Why track this?

Persistence adds a second axis to the index. A grotesque posting that disappears in three days may have filled immediately, been withdrawn, or been rewritten. A grotesque posting that reappears every six weeks for half a year tells a different story.

Over time this can support measurements such as:

- median days in the wild by Horrendous Score
- repost rate by salary band
- frequency of salary increases after prolonged vacancy
- title softening or inflation between reposts
- which award categories persist longest

The archive records what can actually be observed. Disappearance alone does not prove that a role was filled.