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
## 🔥 Latest edition — 2026-11-17

> Theme: *Agents on every side — attackers automating intrusions, defenders plugging threat intel into their assistant, a self-hosted platform that lets agents only propose, and a cloud outage that came from a quiet gateway bug.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Google GTIG AI Threat Tracker** | Google's report on attackers using LLM frameworks (ARTEX, CAIRN, HexStrike AI and others) to automate vulnerability discovery and exploitation | First reported run with no human in the loop; Google projects mostly-agent attacks in ~3 months. Projections, not measurements |
| **VirusTotal connector for Claude** | MCP connector that pulls file, URL, domain and IP threat-intel reports into the assistant | Defender-side counterpart to the above. Submissions are shared with VirusTotal's community; zero detections isn't proof of safety |
| **Sutra-OS** | Self-hosted ontology platform with typed objects, lineage and branching; agents can only propose changes | Puts "agents can't write directly" in the data layer. AGPL-3.0, beta, one maintainer; untested by me |
| **Microsoft 365 outage post-mortem** | July gateway-server bug behind the Nov 12–13 global outage | Load tests ran on weaker hardware than production. Final report still pending |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-17.md">archive/2026-11-17.md</a>.</sub>
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
