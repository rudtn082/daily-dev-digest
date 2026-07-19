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
## Today — 2026-07-19

The scaffolding for running agents on hardware you own is filling in — sandbox them, herd them from one terminal, give them durable memory, and keep the boxes it all runs on under management.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **CubeSandbox** | Instant, secure sandbox for AI agents | Sub-60ms boots, <5MB per instance — thousands of agents on one node, making cheap per-agent isolation the thing that decides if a fleet is affordable |
| **herdr** | An agent multiplexer that lives in your terminal | tmux for agents — run and switch between several coding agents at once, keyboard-driven, no heavy desktop app or middleman billing |
| **Statewave** | A memory runtime built on reproducibility | Provenance-tagged context bundles instead of query-time RAG — every memory traces to its source with an audit trail, so you can actually debug what the agent knew |
| **Alien** | Self-hosting with built-in remote management, in Rust | Software runs inside your environment with data staying local, but you still get a clean way to administer the boxes remotely — the layer where on-prem friction shows up |

<sub>Sources for today are in <a href="archive/2026-07-19.md">archive/2026-07-19.md</a>.</sub>
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
