<!-- LANG-SWITCH -->
[English](../README.md) · [한국어](README.ko.md) · [日本語](README.ja.md) · **中文**

# Daily Dev Digest

横跨开发与 AI，每天挑几个值得一看的新工具、仓库和想法，简短记录。
每天几条，各用一行说明为什么引起我注意。四种语言。

<sub>语言: [English](../README.md) · [한국어](README.ko.md) · [日本語](README.ja.md) · 中文 · 许可: [CC0-1.0](../LICENSE)</sub>

---

## 这是什么

每天上新的东西太多，跟不完。这就是我的过滤器 —— 每天 3~5 条，各用一行说明为何值得一点。
不限主题：智能体、基础设施、小而巧的工具、模型，偶尔还有奇怪的实验。
每天的清单都冻结在归档里 —— 不会事后悄悄改写。

与所列项目无关。这里的条目是指路，不是推荐 —— 自己去看，自己判断。

---

<!-- LATEST:START -->
## 今天 — 2026-10-06

本地推理走向严肃，模型开始用概率而不是文字作答。

| 入选 | 是什么 | 为什么值得关注 |
|------|-----------|-----------|
| **ds4** | 用 C 编写、MIT 许可的推理引擎，可在 Apple Silicon、CUDA 和 ROCm 上本地运行 DeepSeek V4.x、GLM 5.x 和 Qwen 3.8 Flash | 出自 Redis 作者之手，采用 2 比特专家量化并可把 KV 缓存流式写到 SSD——登上 HN 首页的"前沿级本地推理"方案 |
| **Clef / Clef-flash** | Cloudflare 的 27B 和 9B Apache 2.0 决策模型，对带类型的问题返回概率而非文字 | 智能体技术栈里的新位置——无需解析输出，用校准过的概率做低成本分支与路由(Amazon 同日也发布了 2B 的 Strands Decider) |
| **universal-modder** | 让 Claude Code 给几乎任何 PC 游戏做 MOD 的技能和 fal MCP 服务器 | 10 月 5 日登顶 GitHub 趋势榜——技能 + MCP 正在走进爱好者领域 |

<sub>本期来源见 <a href="../archive/2026-10-06.md">archive/2026-10-06.md</a>。</sub>
<!-- LATEST:END -->

---

## 归档

往期都在 [`archive/`](../archive/)，命名为 `YYYY-MM-DD.md`。往回翻、对比日期、grep 你依稀记得的工具。

---

## 怎么挑的

- 每天 3~5 条，最多 5 条。没什么亮眼的日子就少放。
- 不重复 —— 每条都对照归档里已有的。
- 比起人尽皆知的大项目，优先正在上升的。
- 没有付费位、没有联盟链接，没有例外。

想推荐一条，或自己复制一份来跑？见 [`CONTRIBUTING.md`](../CONTRIBUTING.md)。

## 许可

正文采用 [CC0-1.0](../LICENSE) —— 公有领域，随便用。工具名与商标归各自所有者。
