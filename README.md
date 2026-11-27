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
## 🔥 Latest edition — 2026-11-27

> Theme: *Patched, but still being hit*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Drupal installer RCE** | CVE-2026-132165: a core installer flaw that lets a remote attacker rerun the installer on a live site | Fixes shipped Nov 18 (11.3.22, 10.6.22) and Drupal warns exploits may come fast. Exploitation of this exact CVE not confirmed in the sources I could load |
| **Apache Roller RCE** | CVE-2026-129448: unauthenticated XML-RPC deserialization, CVSS 9.8, versions 4.0.0–6.1.4 | Apache says it is being actively exploited, and a PoC has reportedly been public since Sep 28. Fixed version reported as 6.1.6 or 6.1.7; check the advisory |
| **Check Point PHP2Shell campaign** | Chained attacks on unpatched Check Point gateways, about 25 servers reported | Entry points were already-patched bugs on perimeter gear. AI-assisted, China-nexus attribution is uncertain; counts differ between reports |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-27.md">archive/2026-11-27.md</a>.</sub>
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
