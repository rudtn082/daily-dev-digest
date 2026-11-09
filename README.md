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
## 🔥 Latest edition — 2026-11-09

> Theme: *Where agents live — sandboxes, serving runtimes, memory formats, CPU-only inference.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------|
| **Agent Substrate + gVisor** | Google's Kubernetes agent runtime and sandbox kernel, donated to the CNCF (Sandbox) | Idle agents snapshot to storage and free their Pod; Google claims resume in under 500 ms (vendor figure). License not stated in the post |
| **XLA Serving Engine** | C++ runtime that serves exported JAX/XLA models without Python (Apache 2.0) | Google reports 2–5x throughput over its best Python server. Aimed at non-LLM models; PyTorch support is planned |
| **LoreKit agent-memory format** | A proposed shared record format plus five MCP operations for agent memory | Early sketch, no working group yet. Every agent tool stores memory differently, so the interop question is live |
| **llama-modchip** | llama.cpp patches to run a 284B MoE on a CPU-only 64 GB machine (Apache 2.0) | README claims ~9–15 tok/s decode on one Ryzen box. Needs the patched build; quality numbers are the author's own |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-09.md">archive/2026-11-09.md</a>.</sub>
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
