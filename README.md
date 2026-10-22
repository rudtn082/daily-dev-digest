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
## 🔥 Latest edition — 2026-10-22

> Theme: *Fences for agents — a permissions spec, a hands-off build plugin, and a language built to keep the models out.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Docker Sandbox Kit Spec v3** | Open Apache 2.0 spec that declares an agent's access (network, credentials, volumes) inside its container image | Permissions become signable and reviewable; a new version that asks for more access needs fresh approval. Docker plans to submit it to the CNCF |
| **Superlite** | Claude Code plugin: approve one plan, then it builds in parallel without stopping | The anti-Superpowers: one approval instead of many. The 16.1 vs 33.6 min benchmark is the author's single self-run |
| **KillSwitch** | Esoteric stack language built to be hard for LLMs: hidden lies in the spec, letter-count rules | A playful probe of how models fail on unfamiliar specs; author's own top score was 66.8 on simple tasks |
| **Timestral** | Mistral's first time-series foundation models, 5M–209M parameters, CPU inference | Mistral steps outside language models into small forecasting models; modified MIT license |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-10-22.md">archive/2026-10-22.md</a>.</sub>
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
