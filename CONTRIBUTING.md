# Contributing

Two ways to help:

## 1. Suggest a pick (human curation)
Open an issue titled `pick: <tool name>` with:
- **Link** to the project/repo/paper
- **One line** on *why it matters* right now (not just what it is)
- **Category** (agent / infra / DX / model / experiment / other)

Good picks get merged into the next edition with a `by-hand` tag.

## 2. Run your own fork (automation)
This repo is refreshed by a single agent skill called `awesome-daily`. The daily cycle is:

```
scan → analyze (dedupe vs archive) → write (EN) → translate (KO/JA/ZH) → archive → commit + push
```

To run your own:
1. Fork this repo.
2. Copy the `awesome-daily` skill into your Claude Code skills dir.
3. Point it at your fork's local clone.
4. Schedule it (cron / Task Scheduler / cloud routine) to run once a day.

### Curation rules (keep the signal high)
- **3–5 picks/day max.** Fewer is fine. Padding kills trust.
- **No repeats** — dedupe against everything already in `archive/`.
- **"Why it matters" is mandatory** and must say something beyond the tagline.
- **No affiliate links, no sponsored slots.** Ever.
- **Inclusion is a pointer, not an endorsement.** Say so, mean it.
- Prefer things that are *rising now* over evergreen giants everyone already knows.

## Style
- Keep entries to one line in the table; details go in the archive file.
- Factual, skimmable, low-hype. No "revolutionary game-changer" language.
