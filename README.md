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
## 🔥 Latest edition — 2026-11-13

> Theme: *Agents get sharper on both sides of the firewall — attackers run swarms, vendors gate cyber models, and a small mask beats full fine-tuning.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------|
| **Deletion Tuning** | arXiv method that adapts an LLM by learning a mask that zeroes <0.05% of weights | Reported to match full fine-tuning with a mask hundreds to thousands of times smaller, and less forgetting under RL. v1 preprint, unreplicated |
| **Dream's agent-campaign report** | State-linked intrusion run by waves of up to eight sub-agents on Hermes and OpenClaw | Concrete case of off-the-shelf agent frameworks doing multi-step intrusion, per Dream via Recorded Future. Dream says "Asia"; Taiwan is the outlet's wording |
| **GPT-6 Cyber** | OpenAI's fourth cyber model this year, limited to approved Daybreak Red customers | Rated "Critical" under OpenAI's Preparedness Framework; 48.5% on ExploitGym vs 32.1% for its predecessor. Vendor-reported numbers |
| **PostgreSQL 19** | Release candidate stage: RC 2 listed Nov 12, GA planned Nov 19 | Betas brought parallel autovacuum, REPACK CONCURRENTLY and SQL/PGQ graph queries; some features were reverted. Time to test upgrades |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-13.md">archive/2026-11-13.md</a>.</sub>
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
