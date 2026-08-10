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
## Today — 2026-08-10

The week agents stopped borrowing infrastructure and got their own — a machine, durable state, a memory of the loop — while the systems layer underneath got rewritten by the same models.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **pgrust** | Postgres reimplemented in Rust, line by line, mostly by a model | Wire- and dialect-compatible with Postgres 18.3 and passing all 46,066 regression tests — the only number here that means anything; the write-ups are the real artifact (four attempts, three dead ends, ~$100k of model spend before a repeatable translation process worked), and the speed claims are the author's own, unreplicated |
| **celld** | Self-hosted, distributed Durable Objects, from Deno Land | Each object is its own SQLite database replicated to an S3 bucket you own, and nodes coordinate through that bucket alone — no control plane, no consensus to operate; sharding stops being a migration you plan and becomes a property of the model, though at v0.1.0 this is an architecture to read, not to load |
| **@cloudflare/computer** | A Durable Object workspace that gives an agent a machine, not a container | One filesystem behind several backends — fast isolates for file shuffling, full Linux via FUSE when the task needs a package manager — betting that "one container per agent" was the wrong primitive and the runtime should route per task rather than make you pick up front |
| **LoopX** | A provider-neutral state kernel for agent work that outlives the session | Durable goals, executable todos, evidence logs, quota-aware auto-wake and explicit human gates, sitting beside Codex or Claude Code rather than replacing them — the least glamorous problem in agent tooling and the one that bites hardest, since long-running work still dies at context boundaries and hands off as chat scrollback |
| **book-to-skill** | Turns a technical book into a skill your agent loads on demand | Chapter files load only when you ask about that topic, for a measured 24×–51× fewer tokens than dumping the book into context — the framing matters more than the tool, since it quietly shows skills working as an index format for reference material |

<sub>Sources for today are in <a href="archive/2026-08-10.md">archive/2026-08-10.md</a>.</sub>
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
