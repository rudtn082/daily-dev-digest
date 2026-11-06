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
## 🔥 Latest edition — 2026-11-06

> Theme: *Defaults that bite, defaults that get fixed — and cheap things getting cheaper.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------------------|
| **Alpine OpenSSH bypass** | Advisory: sshd builds without PAM accept a 257–1024 byte password for passwordless accounts (musl `crypt()` returns `*`) | Hit HN front page same day; fix needs a daemon restart, workaround is `PasswordAuthentication no`. No CVE yet |
| **Go encoding/json/v2** | `encoding/json/v2` and `jsontext` go stable in Go 1.27; v1 stays supported | Stricter defaults and options-as-arguments; Go team claims up to 10x faster Unmarshal (their benchmarks) |
| **Pyramid-JiT (pjit-21k)** | Linum's Apache-2.0 2B text-to-image model, stated training cost $21,038 on 64 H100s | Data point on how cheap a usable open image model is; authors admit weak text and multi-person scenes. Not tried |
| **Rivet** | Apache-2.0 agent orchestrator; actors with SQLite state backed by S3, object storage the only dependency | Launch HN today; drops the Postgres/queue stack for agent state. Perf figures are the project's own |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-11-06.md">archive/2026-11-06.md</a>.</sub>
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
