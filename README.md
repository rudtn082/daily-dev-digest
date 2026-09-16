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
## Today — 2026-09-16

The price of a token, a review, and a GPU-hour — three projects that make AI cost something you can check.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **Colibri** | Frontier MoE models on hardware you already own, experts streamed from disk | Pure C, zero deps, VRAM/RAM/disk as one hierarchy; runs nine families from OLMoE to Kimi K3, token-exact against transformers — and the README says outright that speed is set by your disk (~6 tok/s on six 5090s, ~1.8 on a 128 GB CPU desktop), which turns "can I load it" into "what is my SSD worth in tokens". Apache 2.0 |
| **Open Code Review** | Alibaba's internal code reviewer, open-sourced as a CLI | File selection, bundling, rule matching and comment placement are hard-coded; the LLM agent only does judgment and context lookup — the project reports ~1/9 the tokens of a general agent with better precision (their numbers, measure on your repo). Take every step that doesn't need a model away from the model. GitHub Actions, GitLab CI, Claude Code/Codex/Cursor plugins. Apache 2.0 |
| **Computable GPU Index** | An open, reproducible USD price for an H100/H200/B200/B300 hour | Weighted votes from a fixed provider panel, central band averaged so the tails can't drag it, and any published value re-derivable by cloning the repo; anonymous API, no key — GPU prices are mostly quoted by whoever sells the GPUs, so a number you can recompute yourself is worth having for budgets and contracts. Code Apache 2.0, data CC BY-NC |

<sub>Sources for today are in <a href="archive/2026-09-16.md">archive/2026-09-16.md</a>.</sub>
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
