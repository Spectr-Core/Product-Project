# Ground Truth

**Find engineering problems before they become obvious.**

![Ground Truth — search a technology, problem, or GitHub repository](screenshots/landing.png)

## What it is

Ground Truth searches thousands of GitHub issues, Stack Overflow questions, and technical discussions to answer one question honestly: is this a real, recurring problem — or a one-off? Search a technology, a specific problem, or a GitHub repository, and get back recurring issues, whether they're getting worse or fading, and — critically — the actual evidence behind every claim.

It isn't another AI chatbot answering from memory. Every conclusion is traced back to a real, dated discussion you can click through and read yourself.

## Not another AI answer engine

- **Answers are grounded in original technical discussions** — not a model's guess at what's plausible.
- **Every conclusion links back to evidence** — the GitHub issue, Stack Overflow thread, or forum post it came from.
- **Cross-source confirmation separates recurring pain from random noise** — one loud GitHub issue is a data point; the same root cause showing up independently on GitHub, Stack Overflow, *and* a vendor forum is a pattern.
- **Trends show whether a problem is growing, stable, or declining** — not just that it exists.

## What you get

![A single evidence-backed problem report, with ranked workarounds and linked sources](screenshots/problem.png)

- **Problem reports** — a clear description of the issue, a confidence badge, a growing/stable/declining trend, first-seen and last-confirmed dates, and the repositories it shows up in most.
- **Ranked workarounds** — not just a list, but ordered by how often the community actually recommends each one, so the first thing you see is the fix people reach for first.
- **Evidence, not vibes** — every report links straight back to the original GitHub issues, Stack Overflow answers, and forum threads it's built from, each dated and sourced.
- **Technology-wide health view** — search a technology like Docker and see overall health score, problems analyzed, independent sources, growth over the quarter, and which categories (networking, build & CI, security…) are hurting the most.

![A technology's ecosystem-wide problem landscape — categories, trending issues, most active repositories](screenshots/technology.png)

- **Repository drill-down** — pick a specific repo and see its problem clusters, categories, and recent issue activity over time.

![Per-repository breakdown — problem clusters, categories, and a timeline](screenshots/repository.png)

- **A personal workspace** — saved technologies, tracked problems, and search history in one place.

![Ground Truth dashboard — saved technologies and tracked problems at a glance](screenshots/dashboard.png)

## What makes it hold up

- **It doesn't answer from memory — it answers from evidence.** If Ground Truth can't point to the actual discussion behind a claim, it doesn't make the claim. That's the entire premise, not a footnote.
- **Corroboration is treated as a distinct, stronger signal.** A problem independently reported on GitHub, Stack Overflow, and a vendor forum isn't just "three mentions" — it's flagged differently from a single one-off complaint, because independent confirmation is what actually separates a real pattern from noise.
- **Every problem carries a trend, not just a count.** Knowing something happened 40 times tells you less than knowing whether it's happening more this quarter than last — Ground Truth tracks both.
- **It's honest about what it doesn't do yet.** Repository-level root-cause analysis and ongoing monitoring are clearly marked "coming soon" rather than shipped half-working — the whole value of an evidence-based tool falls apart the moment it starts overclaiming.

---

*This is a product showcase. Ground Truth's implementation is not included in this repository.*
