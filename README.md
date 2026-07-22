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
## Today — 2026-07-22

The agent's plumbing gets serious. Instead of producing more, today's picks turn inward — making agents observable, giving them memory, running them on your own machine, and pointing them at security.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **mcpsnoop** | "Wireshark for MCP" — a transparent proxy for tool calls | MCP Inspector connects as its own client and sits *beside* the channel; mcpsnoop drops into the actual pipe, so you finally see the real JSON-RPC, server stderr, and slow or hung calls between your production client and server |
| **Strix** | Open-source AI agents for penetration testing | Runs your app dynamically and validates each finding with a working proof-of-concept instead of static-analysis false positives, fanning specialized agents across targets in parallel — offense as a first-class autonomous workflow |
| **Juggler** | An open-source GUI coding agent, from the creator of JUCE | Bucks the CLI-agent wave with a graphical UX, and it's from a veteran framework author — worth watching because someone with real UX credibility is arguing the terminal isn't the right home for coding agents |
| **LM Studio Bionic** | A full local agent for open models, not just a chat window | Pushes past chat into an agent that edits documents, runs agentic code search with inline diffs, and transcribes voice on-device — routing only heavy tasks to the cloud, local-first with zero data retention |
| **TencentDB-Agent-Memory** | Fully local long-term memory for agents, zero external API | A four-tier local pipeline (local LLM + SQLite vectors) that condenses tool logs into compact symbols and distills conversations into structured personas and scenes instead of a flat vector pile |

<sub>Sources for today are in <a href="archive/2026-07-22.md">archive/2026-07-22.md</a>.</sub>
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
