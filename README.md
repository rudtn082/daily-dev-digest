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
## Today — 2026-09-01

The local turn — models and the agents that drive them both shrinking to fit hardware you already own.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **Muse Glimmer** | Meta's 30B open-weight model built for always-on local agents | Apache 2.0 from Meta Superintelligence Labs, aimed at agent work that runs on a laptop rather than a datacenter — multi-step planning, sequential tool calls, failure recovery; the size isn't the story, the target is, since most open weights are tuned to look good on chat and reasoning evals while this one goes after the thing that actually breaks in production, the fifth tool call after something already went wrong |
| **Ante** | A coding agent that ships as one offline binary | A single Rust binary with no runtime dependencies, driving a dozen providers or local GGUF models with nothing phoning home, in TUI, headless, server, and gateway modes — the efficiency claims are the vendor's own and unreplicated, but the packaging argument stands alone: an agent you can scp onto a box is a different tool from one that needs a Node install and an account |
| **hax** | A terminal agent written in C that respects your scrollback | Native C binary, few dependencies, instant start, local models first-class via llama-server — the differentiator is terminal manners, redrawing only the streaming line or input area instead of seizing the alternate screen, so your scrollback survives the session; a small thing, and the reason people keep rewriting these tools |
| **MIDI autocomplete** | A 125M model that finishes your piano phrase on-device | One person trained a small model to predict the next few bars and shipped it running locally in the browser — a good look at what the local turn means below the agent layer, where 125M parameters buys a latency budget small enough for the model to sit inside an instrument's feedback loop rather than behind a request; read it as a build log, not a product |

<sub>Sources for today are in <a href="archive/2026-09-01.md">archive/2026-09-01.md</a>.</sub>
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
