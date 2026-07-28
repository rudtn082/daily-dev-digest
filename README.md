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
## Today — 2026-07-28

Agents stopped visiting your environment and moved into it — your browser session, your team chat, your docs, your own hardware.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **ego-lite** | A browser that hands your logged-in session to a coding agent | Most agent automation starts from a cold profile and dies at the first login wall; ego-lite offers to migrate your Chrome data on launch, so the agent inherits your cookies and extensions while working in its own Space instead of stealing your tabs — and it topped GitHub trending this week on a claim of beating Vercel's agent-browser on four tasks with less time and fewer tokens |
| **Buzz** | Block's self-hostable workspace where agents are first-class members | Chat, git hosting and agents on one Apache-2.0 surface with a Rust Nostr relay underneath; the part that matters isn't the Slack-plus-GitHub pitch but that agents get their own cryptographic keys and channel memberships, so a patch or a review approval lands as a signed event in an audit trail rather than an anonymous bot action |
| **Kimi K3** | The largest open-weights model ever shipped: 2.8T parameters | Moonshot put it on Hugging Face ungated at 00:00 UTC July 27 — 96 shards, roughly 1.56 TB in MXFP4 — but the thing to read before you build on it is the bespoke "Kimi K3 License" tagged `license:other`, carrying a revenue-triggered separate-agreement clause and a UI attribution mandate; no independent benchmarks at release |
| **OpenWiki** | LangChain's CLI that writes docs for agents, not humans | It generates a structured `openwiki/` folder tuned for LLM context windows, with Mermaid diagrams where a picture beats prose; what makes it more than another README generator is the shipped GitHub Action that opens a daily PR, turning documentation drift from a discipline problem into a merge queue item |

<sub>Sources for today are in <a href="archive/2026-07-28.md">archive/2026-07-28.md</a>.</sub>
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
