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
## Today — 2026-09-14

Unbundling the coding agent — weights, serving, and harness each become a part you can swap.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **OpenSAS** | An open-source SAS 9.4 interpreter, written by agents | Zig, built by a team of seven coding agents from public docs only, claiming byte-for-byte output parity on clinical pipelines (SDTM, ADaM) — regulated trial output is where "close enough" fails, which makes it a far sharper test of agent-written software than another todo app; the parity claim is the project's own, so check it against your pipeline |
| **GLM-5.3-Flash** | Z.ai's first natively multimodal GLM-5, MIT-licensed | 320B MoE with 18B active, 1M context, text/image/video/file in, fp8 weights on Hugging Face — it ran anonymously on OpenRouter as "Ox Alpha" before Z.ai claimed it; the license with no revenue thresholds or field-of-use strings is what lets you ship on it, more than any benchmark chart |
| **Magnitude** | A local inference server that plugs into the agent you already use | Profiles chip, memory, and bandwidth, estimates fit and tok/s per model, then downloads, tunes, and serves the pick for Pi, OpenCode, Hermes, Codex, Claude Code, or Cline — it answers where local users actually get stuck: not "can I run a model" but "which one is good enough on this machine for an agent loop" |
| **Pi** | An agent toolkit you can take apart | Unified multi-provider LLM API, agent runtime, TUI components, and coding-agent CLI shipped as separate pieces, embeddable in Node or driven over RPC — trending right next to Magnitude, and the pairing is the story: the harness is turning into a library, so loop, model, and UI stop being one vendor's call |

<sub>Sources for today are in <a href="archive/2026-09-14.md">archive/2026-09-14.md</a>.</sub>
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
