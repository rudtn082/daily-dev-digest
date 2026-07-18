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
## Today — 2026-07-18

Heavier work moves back onto hardware you own — agents editing real Office files, a GPU rendering millions of points, meetings transcribed on-device — plus tools to audit and archive what's yours.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **OfficeCLI** | An Office suite built for AI agents to drive | Single binary, no MS Office — agents read/edit Word, Excel, PowerPoint with a real formula engine and a render-and-fix loop |
| **Kage** | Shadows any website into a single offline binary | Snapshots the DOM, strips all JS, bundles CSS/images into one executable that serves the site offline — nothing installed on the other end |
| **Meetily** | Self-hosted, 100% local AI meeting note-taker | Rust + Tauri, Parakeet/Whisper live transcription, diarization and Ollama summaries — an open Otter/Granola that never leaves your machine |
| **Tailsnitch** | Security auditor for your Tailscale tailnet | 50+ checks across access, auth, device, network, SSH and DNS, with fix mode and SOC 2 mappings — a linter for "did we leave this too open?" |
| **ChartGPU** | WebGPU charting smooth at a million points | Whole pipeline on the GPU — downsampling compute shader, instanced draws — 1M points pan/zoom at 60fps, benchmarks into the tens of millions |

<sub>Sources for today are in <a href="archive/2026-07-18.md">archive/2026-07-18.md</a>.</sub>
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
