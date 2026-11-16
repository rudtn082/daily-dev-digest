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
## 🔥 Latest edition — 2026-11-16

> Theme: *Trust you didn't know you were extending — a blocker's picker that took orders from any site, std-library code that safe Rust can break, short links anyone can re-register, and database branches for agent sandboxes.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **uBlock Origin (Firefox) universal XSS** | A malicious site could abuse the extension's element picker to run JavaScript on any domain | One click was enough per the write-up; reported patched, no version named. Keep extensions updated |
| **Hyenas (Microsoft FORGE Lab)** | AI-powered scanner that found soundness bugs in Rust's core and std libraries | Safe code could trigger undefined behavior. One fix reportedly lands in Rust 1.100; other fix status unconfirmed |
| **Bitly dead links** | Expired short links from old Burger King, McDonald's and Trump tweets were re-registered by strangers | No hack, just reclaimed endings, per one report. Any short link you published is a dependency you don't control |
| **db-branch** | Instant MySQL/PostgreSQL branches via ZFS clones, with CLI, REST and MCP server | Cheap disposable databases for agent sandboxes and per-PR CI. Apache-2.0; appears to need ZFS |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-16.md">archive/2026-11-16.md</a>.</sub>
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
