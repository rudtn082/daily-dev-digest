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
## 🔥 Latest edition — 2026-11-18

> Theme: *The agent bill and the agent's homework — tools that cut coding-agent cost, grade the skills you hand them, run them as a daemon, and a default model swap that quietly costs 15x.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **TokenEconomizer** | Microsoft's MIT-licensed plugin that learns repo facts, prunes unused tools and nudges stuck turns to make coding agents cheaper | Cost is the complaint of the week. Works with Claude Code, Codex, Copilot CLI; savings not measured by me |
| **SkillEvaluator** | NVIDIA's tool that validates agent skills, checks overlap, and A/B tests them with and without the skill in a sandbox | Skills get installed like packages with little vetting; this is a test suite for them. Experimental |
| **agentproto** | Open TypeScript daemon that runs coding-agent sessions in the background and exposes tools over CLI, HTTP, MCP | Usage-cap failover across accounts and stale-CI filtering are the unglamorous problems of long-running agents. Release notes only; untested by me |
| **Browser Use 1.0.6** | Release that makes `bu-4.0` the default model for `Agent(task)` | Listed at 15x the price of `bu-fast`; pin your model before upgrading |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-18.md">archive/2026-11-18.md</a>.</sub>
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
