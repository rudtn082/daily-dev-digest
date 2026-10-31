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
## 🔥 Latest edition — 2026-10-31

> Theme: *Trust the toolchain less — a backdoored extension, and the open stacks moving AI infra off one vendor.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Claude Code extension backdoor (Cursor Marketplace)** | Versions 2.1.312/2.1.313 of the Claude Code for VS Code extension carried an SSH backdoor | Phorion's advisory: runs on load, adds an attacker key, reverse tunnel, persistence. Cursor pulled the versions; uninstalling alone doesn't clean up |
| **TorchTPU** | Open-source native PyTorch backend for Google TPUs, from Google and Meta | TPUs were a JAX/TensorFlow world; this aims to run PyTorch there without a rewrite. Performance claims are the authors' own |
| **llm-d 1.0** | Kubernetes-native distributed LLM inference stack in the CNCF Sandbox, works with vLLM and SGLang | 1.0 adds multi-tenant flow control, zero-downtime upgrades and session-aware KV-cache routing, on GPUs and TPUs |
| **Sleep framework** | Google Research approach to continual learning: wake, then sleep to consolidate memory | Reports near-zero forgetting and long-context results up to 10M tokens. Authors' claims, not independently reproduced |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-10-31.md">archive/2026-10-31.md</a>.</sub>
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
