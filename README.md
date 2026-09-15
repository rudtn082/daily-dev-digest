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
## Today — 2026-09-15

Instruments for the agent's machine — see what's installed, keep sessions alive, undo the bad write.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **DeepSeek-V4.1-Flash** | A 552B MoE that reads with 8B and writes with 16B, MIT-licensed | Causal Encoder-Decoder: prefill activates 8B per token, decode 16B; 1M context, image+text in, weights on Hugging Face the day it replaced V4 Flash on the API — the number that matters is on the model card: ~890 bytes of KV cache per token, about a quarter of V4 Flash, and long agent loops run out of cache memory before they run out of benchmark |
| **Hydra** | An agentic terminal whose sessions outlive the window | The desktop app is only a client of a local PTY daemon, so shells and agents keep running after you close it, reachable from a browser with no inbound port; it finds and resumes existing Claude Code, Codex, Copilot CLI, OpenCode and Cursor Agent sessions — the durable object is the agent session, not the tab. Local code MIT, Remote service proprietary |
| **Geiger** | See every agent on your machine and what it can touch | Read-only `npx geiger-scan` inventories Claude Code settings, MCP host configs, IDE/browser extensions and global npm packages, tagging each EXECUTES, HOLDS-SECRETS, BROAD-FILESYSTEM and so on, with drift detection against a baseline — config not runtime, so it shows blast radius rather than what happened, which is still more than most dev machines can tell you |
| **EterDB** | Undo one bad transaction without restoring the whole database | Postgres 18-based, append-only history: reverse only the rows a given transaction touched, recover dropped tables with values, trace downstream writes that read the bad data, time-travel queries — PITR throws away every good write after the mistake, and more of those mistakes now come from agents holding a connection string. Apache 2.0 |

<sub>Sources for today are in <a href="archive/2026-09-15.md">archive/2026-09-15.md</a>.</sub>
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
