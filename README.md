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
## 🔥 Latest edition — 2026-11-15

> Theme: *Trust at the edges — a package index that says when it can't vouch for a release, an app builder whose apps leaked data, and the plumbing (ggml, a browser for agents) that local AI runs on.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **PyPI provenance warnings** | PyPI now flags releases whose origin can't be verified | New security tab and warnings for missing, incomplete or changed provenance. Doesn't catch outright malicious packages; many older releases have no attestations |
| **Lovable apps leak** | Researchers scanned 159,041 Lovable projects and found Supabase-backed apps exposing data without login | Includes 200,000 private messages and passport numbers. Root cause per Lovable: weak Row-Level Security. Audit your RLS. Researchers' claims |
| **ggml 1.0.0** | Tensor library under llama.cpp-style local inference hits 1.0 | Removes legacy APIs (can break downstream), adds FP8 and broad backend speedups |
| **Agweb** | macOS WebKit browser for coding agents, driven by an `agweb` shell command | Never steals focus and avoids heavy headless browsers. License not stated on the page I found |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-15.md">archive/2026-11-15.md</a>.</sub>
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
