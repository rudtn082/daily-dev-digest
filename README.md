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
## 🔥 Latest edition — 2026-10-07

> Theme: *Agent plumbing — sandboxes, identities, inboxes and shared skills.*

| Pick | What it is | Why it's on the radar |
|------|-----------|-----------|
| **bVisor** | Zig sandbox that runs agent bash on the host by intercepting syscalls in userspace, ~2 ms spin-up, Linux only | Show HN this month — a no-VM, no-container take on agent isolation (early proof of concept, per its authors) |
| **sx** | Apache 2.0 Go CLI that works as a private registry for skills, MCP configs and commands across Claude Code, Cursor, Copilot and more | Skills are piling up in personal dotfiles; this gives teams a versioned way to share them |
| **MachineAuth** | Open-source auth server issuing short-lived tokens to agents and services instead of long-lived API keys | Agents now hold real credentials, and leaked static keys are the weak link |
| **e2a** | Apache 2.0 email gateway giving each agent an address, with SPF/DKIM checks, signed sender headers and optional human approval for outbound mail | A concrete answer to how an agent safely talks to people over email |

<sub>📎 Sources for this edition are listed in <a href="archive/2026-10-07.md">archive/2026-10-07.md</a>.</sub>
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
