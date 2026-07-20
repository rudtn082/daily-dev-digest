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
## Today — 2026-07-20

The anti-black-box day — instead of trusting a vendor runtime or logic that fires side effects out of sight, this batch hands you the source of the agent, keeps durable workflows on the Postgres you already run, makes I/O plain data you can read, and lets you host the edge platform yourself.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **Grok Build** | xAI's coding-agent CLI, open-sourced | The actual Rust source of the TUI, agent runtime, and ACP wiring under Apache-2.0 — read exactly how a frontier lab assembles context and dispatches tools (issues off, no outside PRs: a source drop, not a project) |
| **DBOSify** | Drop-in Temporal replacement built on Postgres | Import `dbosify` instead of `temporalio` and get durable workflows, retries, and recovery with no server to run — ports Temporal's own tests for conformance, so you can inspect the claim |
| **Pure Effect** | Business logic as plain data you can replay | Functions return objects describing the I/O they'd do instead of firing it — record what prod saw, replay the exact path on your laptop, no database touched |
| **OpenWorkers** | Self-hosted Cloudflare Workers, in Rust | The Workers programming model on your own boxes — `fetch`, KV, Postgres bindings, S3/R2, cron, `crypto.subtle` — an escape hatch when edge convenience meets lock-in and egress bills |

<sub>Sources for today are in <a href="archive/2026-07-20.md">archive/2026-07-20.md</a>.</sub>
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
