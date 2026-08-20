# Follow-Back Data

Computed from the Instagram data export `instagram-keving107-2026-05-24-l6OnFqZ7.zip` (exported **2026-05-24**).

| File | Meaning | Count |
|---|---|---|
| `not-following-back.txt` | You follow them, they don't follow you back | 796 |
| `fans-not-followed-back.txt` | They follow you, you don't follow them back | 37 |
| `mutual.txt` | Mutual follows | 178 |

Totals: 974 following, 215 followers (as of the export date — will drift from live counts over time).

**Before unfollowing:** per the criteria in the main README, this is not a mass cleanup of the real network (school/church/family). The `not-following-back` list is mostly intentional follows that were never going to reciprocate. The actual target is the narrower case: people you don't know personally, followed mainly because they're attractive, who don't follow back.

Re-run via [`instagram-follower-tracker.html`](../instagram-follower-tracker.html) once a fresh **JSON**-format export is available, for an up-to-date pass.
