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
## Today ??2026-09-19

Less noise, more parallel ??agents get a diet for their output, a home for their branches, and a model that loops on itself.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **i-have-adhd** | A skill that makes coding agents lead with the action, not the reasoning | Ten rules turn "let me think about this?? into `npm install jsonwebtoken@latest`, then edit `src/auth.ts:42` ??works across Claude, Cursor, Gemini, Kimi and Qwen, and it climbed GitHub trending this week because "the answer is buried" is a near-universal complaint |
| **context-mode** | An MCP server that keeps tool output out of the context window | Tool results are sandboxed in subprocesses so raw data never hits the conversation (claimed 98% reduction), and session state lives in SQLite so the agent recovers after compaction; 17 platforms supported. Attacks context burn at the tool boundary instead of inside one agent |
| **worktrunk** | A Rust CLI that makes git worktrees as easy as branches, built for parallel agents | `wt switch`, `wt list`, `wt remove` cover the whole loop. Run several agents at once and each needs its own checkout ??raw `git worktree` becomes the friction. MIT or Apache 2.0 |
| **Recurrent Looped Transformer** | An architecture that feeds the decoder's last hidden state forward to the next token | Self-reported, small-scale: on 256-bit parity some variants hit 100% on all three seeds while an 8-layer Transformer sat near 50%. Not a product ??a concrete sign that recurrence is coming back into LLM design |

<sub>Sources for today are in <a href="archive/2026-09-19.md">archive/2026-09-19.md</a>.</sub>
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
