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
## Today — 2026-08-03

The agent isn't the product anymore — the plumbing around it is: what it can see, what it can touch, what it can read, and who supervises it.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **Screenpipe** | A 24/7 local work ledger your agents can query | The July reframe is the whole pitch — stop selling screen recording, sell "record how you work → searchable memory → SOPs an agent can run"; screen and audio land in a local SQLite database and come back out over MCP, so an agent watching you repeat a task writes the steps down instead of being prompted through them again |
| **Coasty** | An API for computer-use agents, with the runtime open-sourced | Send a task, pick a machine or browser, hand over credentials, and the agent drives via screenshots, mouse and keyboard and verifies the result — but the reason to look is `open-computer-use`, which runs the same loop yourself on one API key instead of a hosted black box |
| **Context.dev** | Clean web context for agents, as one boring API | Scrape a URL to LLM-ready markdown, extract to your JSON schema, crawl a whole site — with JS rendering, anti-bot handling and stealth proxies on every request at no extra credit cost, which is the part everyone otherwise rebuilds and pays for in proxy bills |
| **OpenHands Agent Canvas** | A self-hosted control room for whatever agent you already use | It supervises rather than competes: OpenHands' own agent, Claude Code, Codex, Gemini, anything speaking the Agent Client Protocol, on one canvas — the ACP seam implies the next fight is over the orchestration surface, not the agent |

<sub>Sources for today are in <a href="archive/2026-08-03.md">archive/2026-08-03.md</a>.</sub>
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
