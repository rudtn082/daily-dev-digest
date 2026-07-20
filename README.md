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
## Today — 2026-07-21

The agent stack grows up — instead of just generating more code and UI, today's tools put guardrails and coordination around what the models produce, and a trillion-parameter open model shows up trained off NVIDIA's silicon.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **Hallmark** | Anti-AI-slop design skill for Claude Code, Cursor, Codex | Encodes rules that refuse the purple-gradient defaults every model was trained into, then runs slop-test gates and a self-critique pass before handing UI back — a concrete answer to "all AI designs look the same" |
| **Aura** | Git-native provenance layer for AI coding agents | Parses your repo to an AST locally and tracks an agent's edits at the function level, so it can compare the change to your stated intent and block the commit when they diverge — plus `rewind` a single broken function and wipe an AI's hallucinated memory |
| **Mozaik** | TypeScript runtime where agents self-organize | Drops the up-front DAG: every message, tool call, and error is an event on a shared bus that agents subscribe to and react to, so coordination emerges at runtime and agents run concurrently on the same goal |
| **LongCat-2.0** | 1.6T open MoE trained entirely on Chinese chips | MIT-licensed at trillion scale, with a native 1M-token context — and Meituan says it's the first model this size to pre-train and serve entirely on domestic AI ASICs, not NVIDIA GPUs |

<sub>Sources for today are in <a href="archive/2026-07-21.md">archive/2026-07-21.md</a>.</sub>
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
