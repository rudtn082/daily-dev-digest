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
## 🔥 Latest edition — 2026-11-26

> Theme: *Old code, fresh exploits*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Hex.pm RCE** | CVSS 10.0 pre-auth parser flaw, reportedly used to compromise six Hex.pm registry servers | A registry is the root of trust for every install. Single-outlet report (The Hacker News); not corroborated yet |
| **Idunno.AntiCsrf** | Legacy ASP.NET anti-CSRF library with a CVSS 9.3 unauthenticated RCE | A security helper old apps still carry as a dependency. Researchers say stop using it |
| **Microsoft agent-framework (PyPI)** | Versions 1.26.1 and 1.26.2 of the Python package were poisoned with a credential stealer | The target was an AI agent SDK in build pipelines. 1.26.0 is reported as the last clean release |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-26.md">archive/2026-11-26.md</a>.</sub>
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
