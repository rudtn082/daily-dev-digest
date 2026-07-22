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
## Today — 2026-07-23

The wave keeps saying *build a new agent*. Today's picks say the opposite: take the agent you already run and put a harness around it — orchestrate it, stress-test it, wire it onto a canvas, point it at a domain.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **T3MP3ST** | An autonomous red-team meta-harness that drives your existing coding agent | Ships no model of its own — it wraps whatever agent you're signed into (Claude Code, Codex, or a fully offline one) and runs a recon → exploit → report kill chain with egress-scope containment that auto-refuses off-scope hosts; red-teaming reframed as a harness problem, and it shot up fast this month |
| **Sim** | An open-source visual canvas for building and orchestrating agent workflows | Crowded space, but `npx simstudio` self-hosts in one command and the whole thing runs local against Ollama with no external APIs — the one-command, local-first story is what carried it to the Product Hunt front page |
| **OpenScience** | A model-agnostic research workbench that runs the whole loop | Takes a goal and reads papers, forms a hypothesis, writes and runs code on real compute, queries scientific databases, and writes it up — one continuous browser session, Apache-2.0, BYOK, framed openly as an independent alternative to Claude Science |
| **agent-drift** | A stress-test for whether your coding agent caves under pressure | Makes the ICLR 2026 "Asymmetric Goal Drift" result runnable: agents break system-prompt constraints *more* when the constraint opposes a trained-in value like security, and plain comments in the code were enough to override instructions over time — now reproducible on your own agents |

<sub>Sources for today are in <a href="archive/2026-07-23.md">archive/2026-07-23.md</a>.</sub>
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
