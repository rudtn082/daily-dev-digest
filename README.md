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
## Today — 2026-07-27

Nothing today is a new idea. Every pick is the missing piece that finally makes an old one practical — the cache, the license, the preprocessing, the compose file, the lifecycle.

| Pick | What it is | Why it caught my eye |
|------|-----------|----------------------|
| **oMLX** | An MLX inference server that stops your Mac recomputing the same context | Agents shift the prompt prefix every turn and every other MLX server throws away the KV cache, costing 30–90s a response; oMLX pages KV blocks to SSD and restores them instead, dropping time-to-first-token to a few seconds — the thing that had to exist before local agents on Apple Silicon were usable |
| **Inkling** | Thinking Machines Lab's first model: 975B MoE, open weights, Apache 2.0 | 41B active per token, 1M context, native text/image/audio reasoning, 45T pretraining tokens — but the story is the license on a model this size from a US lab, shipped as a base to fine-tune rather than an endpoint to call |
| **Infini-News** | 1.36B Common Crawl news articles, queryable in milliseconds | News research has been gated by price or by terabytes of raw CC-News; this does the extraction, cleaning, language tagging and country attribution once (83.4% of articles, 222 countries) and ships infini-gram indexes so you can pattern-search the whole archive sub-second |
| **Fruitbox** | Docker Compose for Apple's container runtime | Apple's `container` hit 1.0, but nobody runs one container — they run a compose file with five services; the interesting part is the ecosystem now forming around the native runtime, which is what turns it from curiosity into a real Docker alternative on a Mac |
| **Frond** | A frontend runtime for your app's dependency graph | Not a router or renderer — the layer under them, where each node declares how it's acquired, cancelled and released, so React just consumes something already ready; built on Effect, so evicting a node actually aborts fetches, clears timers and closes streams |

<sub>Sources for today are in <a href="archive/2026-07-27.md">archive/2026-07-27.md</a>.</sub>
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
