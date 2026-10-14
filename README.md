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
## 🔥 Latest edition — 2026-10-14

> Theme: *Keeping agents honest — measuring code bloat, linting AI slop, packaging engineering habits as skills, plus two Rust builds.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Parsimony** | Open-source benchmark that ranks AI models by how much code they add to solved tasks | Puts a number on agent over-writing — though more code correlates with more solves, and size isn't quality |
| **ai-deslop** | Oxlint rules that reject low-signal patterns in AI-generated TypeScript | Turns "review the agent's output" into a lint step that can fail CI |
| **mattpocock/skills** | ~27 installable agent skills (spec, tickets, TDD, bug diagnosis) for Claude Code, Codex, Copilot, Gemini CLI | On GitHub's weekly trending list — a well-known engineer's agent workflow, published as-is |
| **SolidCraft** | Parametric CAD in pure Rust: desktop, browser, CLI, plus an MCP server for agents | Show HN pick; the README itself says "early but usable for simple parts" |
| **mosh-rs** | Mosh rewritten in Rust, wire-compatible with mosh 1.4, with scrollback and a native Windows client | Adds the two things mosh users keep asking for — but it's pre-alpha |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-10-14.md">archive/2026-10-14.md</a>.</sub>
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
