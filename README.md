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
## 🔥 Latest edition — 2026-11-01

> Theme: *Tiny models and big swarms — a 512-byte boot-sector LM, and fifty agents let loose in a world.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **bootgpt** | A character-level language model that runs from a 512-byte boot sector and prints fake kernel boot logs | 11.5 KB int8 weights, no OS, 386 real mode; the trainer simulates the assembly's integer math and the README says outputs match exactly |
| **YC Labs agent swarms** | 50 GPT-6.1 Sol agents in Minecraft, plus Claude Opus 5.5 vs GPT-6.1 Sol Bed Wars | Informal leaders, invented bureaucracy and growing caution emerged; the failure modes echo overcautious coding agents |
| **Simantic** | Firmware simulation (Rust engine) for engineers and AI agents, Launch HN YC F26 | Lets agents test embedded code per commit without hardware; no analog co-simulation yet, accuracy report still promised |
| **LFM3** | Liquid AI's six open-weight 2B-class models: text, vision, audio, omni, two decision models | 1.7B text model fits in ~1 GB at 4-bit for on-device use; benchmarks are Liquid's own, check the license |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-01.md">archive/2026-11-01.md</a>.</sub>
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
