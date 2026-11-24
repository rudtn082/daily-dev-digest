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
## 🔥 Latest edition — 2026-11-24

> Theme: *Fence the agent, shield the host*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Shirudo** | Cisco and OpenAI's open-source project where AI agents write signed eBPF "shields" to protect live Linux systems before a patch exists | Agent-written, verified mitigations for the disclosure-to-patch gap. Release cites only two demos and no stated limits |
| **External sandboxes for coding agents** | Prime Radiant and Simon Willison's pattern and three prototypes: agent stays outside, only its executed code runs in an isolated sandbox | Separates the agent from what runs its commands. Not every tool call crosses the boundary, and the prototypes are unaudited |
| **Infrastructure Agent Skills** | Itential's Apache 2.0 library of operational skills for agents doing network and infrastructure work | Brings Agent Skills into ops, where verification before change matters. Third-party skills keep their own licenses |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-24.md">archive/2026-11-24.md</a>.</sub>
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
