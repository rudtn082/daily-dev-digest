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
## 🔥 Latest edition — 2026-10-26

> Theme: *Agents leave the terminal — they click through your apps, ship as CLI-native models, and run into a Brotli bug and a Reddit ban.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Cursor Computer Use** | Cursor's agents can now click and type in desktop apps and the iOS Simulator | Closes the loop from "it compiles" to "the app works" in native and mobile apps. Needs macOS Accessibility and Screen Recording permissions |
| **IQuest-Q1** | A 320B sparse MoE (15B active, 512K context) built for command-line agent work | Authors say weights are out and the model helped build its successors. Scores are self-reported and the license is unconfirmed |
| **Node2Shell (CVE-2026-111497)** | A Brotli decoder out-of-bounds write reaching Node.js, Bun and Envoy | Node patched Oct 21 (22.23.4 / 24.22.1 / 26.12.1), a PoC exists, and apps bundling their own Brotli must update separately |
| **r/opensource AI ban** | Moderators bar projects that use, are made by, or target AI, and require year-old, multi-contributor projects | A signal of open-source gatekeeping pushing back on AI-generated project posts. One subreddit's policy, with a splinter community already formed |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-10-26.md">archive/2026-10-26.md</a>.</sub>
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
