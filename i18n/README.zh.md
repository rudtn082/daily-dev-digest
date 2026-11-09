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
## 今天 — 2026-11-09

智能体的栖息地 —— 沙箱、推理服务运行时、记忆格式、纯 CPU 推理。

| 精选 | 是什么 | 为何上榜 |
|------|-----------|-----------|
| **Agent Substrate + gVisor** | Google 的 Kubernetes 智能体运行时与沙箱内核,捐赠给 CNCF(Sandbox) | 空闲智能体快照到存储并释放 Pod。Google 称恢复时间低于 500ms(厂商数据)。文章未说明许可证 |
| **XLA Serving Engine** | 无需 Python 即可服务已导出 JAX/XLA 模型的 C++ 运行时(Apache 2.0) | Google 称吞吐量是其最佳 Python 服务器的 2–5 倍。主要面向非 LLM 模型,PyTorch 支持尚在计划中 |
| **LoreKit 智能体记忆格式** | 为智能体记忆提出的通用记录格式 + 5 个 MCP 操作 | 早期草案,尚无工作组。各工具存储记忆的方式不一,互操作话题正热 |
| **llama-modchip** | 让 284B MoE 在纯 CPU、64GB 机器上运行的 llama.cpp 补丁(Apache 2.0) | README 称单台 Ryzen 解码约 9–15 tok/s。需要打补丁的构建,质量数据来自作者自测 |

<sub>今日来源见 <a href="../archive/2026-11-09.md">archive/2026-11-09.md</a>。</sub>
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
