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
## 🔥 Latest edition — 2026-11-08

> Theme: *The plumbing under coding agents — shared libraries, leaky defaults, and benchmarks that crack.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **libghostty-vt 1.0** | Ghostty's terminal core as a stable, MIT-licensed C library | Stable C ABI shipped Nov 6; JetBrains terminals, Konsole experiments and agent tools like herdr and cmux build on it |
| **Claude Code "don't ask again"** | Apiiro's scan of public `.claude/settings.local.json` files | Real credentials in 1,122 of 104,185 files, because approved commands are saved verbatim. Only bites if the file is committed to a public repo |
| **MaxxBench** | DeepSWE's 89 tasks with small requirement tweaks | Per its authors, two Flash-class models drop from ~74% to 53–56% while Claude Opus 5.5 rises to 76.4%. One team's benchmark |
| **GitHub Project Rubicon** | GitHub's rebuilt Git storage: blob-stored packs plus a replicated ref log | Aimed at thousands of agents pushing to one repo; 5,000 agents and 7,200 pushes/s are GitHub's internal figures |
| **ERNIE 5.5 Flash Base** | Baidu's 280B MoE base checkpoint (~14B active), FP8 and BF16 weights | Released Nov 5. Weights are downloadable, but the license is custom, not OSI-approved. Read it first |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-08.md">archive/2026-11-08.md</a>.</sub>
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
