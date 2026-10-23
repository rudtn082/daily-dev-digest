<!-- LANG-SWITCH -->
**English** · [한국어](i18n/README.ko.md) · [日本語](i18n/README.ja.md) · [中文](i18n/README.zh.md)

# Daily Dev Digest

A short daily list of new tools, repos, and ideas worth a look — across dev and AI.
A few picks a day, one line each on why they caught my eye, kept in four languages.

<sub>Read in: English · [한국어](i18n/README.ko.md) · [日本語](i18n/README.ja.md) · [中文](i18n/README.zh.md) · License: [CC0-1.0](LICENSE)</sub>

---

## The idea

Too much ships every day to keep up with. This is my filter: three to five things a day,
one line each on why they're worth a click. No single topic — agents, infra, small clever
tools, models, the occasional odd experiment. Every day's list is frozen in the archive,
so nothing gets quietly rewritten later.

Not affiliated with anything listed. A mention here is a pointer, not a recommendation —
go look and decide for yourself.

---

<!-- LATEST:START -->
## 🔥 Latest edition — 2026-10-23

> Theme: *Local and durable — a laptop-sized coding model, a long-term-support database, and agents whose state survives a crash.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Flint** | Recursive's open-weight coding MoE (~40B total, ~2.5B active), Apache 2.0, built to run locally | Recursive says its own research system did most of the build. Speed and benchmark figures are vendor-reported |
| **DuckDB 2.0.0 LTS** | First 2.x long-term release of the embedded analytics database: VARIANT, triggers, async I/O, agent mode | Supported until at least October 2027. New storage format that older versions can't open, so test on a copy first |
| **Omnara** | Apache 2.0 control plane for durable agents, with state kept in your own Postgres | Agents recover from crashes and disconnects, and history stays queryable. One of several self-hostable takes on Claude Managed Agents |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-10-23.md">archive/2026-10-23.md</a>.</sub>
<!-- LATEST:END -->

---

## Archive

Past days live in [`archive/`](archive/) as `YYYY-MM-DD.md`. Browse back, diff the days,
or grep for something you half-remember.

---

## How picks are chosen

- Three to five a day, five at most. Fewer when nothing really stands out.
- No repeats — each pick is checked against everything already in the archive.
- Prefer things on the way up over the giants everyone already knows.
- No sponsored slots, no affiliate links, no exceptions.

Want to suggest one, or run your own copy? See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

Text here is [CC0-1.0](LICENSE) — public domain, use it however. Tool names and trademarks
belong to their owners.
