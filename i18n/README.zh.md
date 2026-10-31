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
## 今天 — 2026-10-31

少信任一点工具链:被植入后门的扩展,以及让 AI 基础设施摆脱单一厂商的开源栈。

| 精选 | 是什么 | 为何上榜 |
|------|-----------|-----------|
| **Claude Code 扩展后门(Cursor Marketplace)** | Claude Code for VS Code 扩展的 2.1.312/2.1.313 版本被植入 SSH 后门 | Phorion 通报:加载即执行,写入攻击者密钥、建立反向隧道并持久化。Cursor 已下架这些版本,仅卸载并不能清除 |
| **TorchTPU** | Google 与 Meta 合作的开源原生 PyTorch 后端,面向 Google TPU | TPU 过去是 JAX/TensorFlow 的天下,这次想让 PyTorch 不用重写就能跑。性能说法来自作者自己 |
| **llm-d 1.0** | CNCF Sandbox 中的 Kubernetes 原生分布式 LLM 推理栈,可配合 vLLM 与 SGLang | 1.0 新增多租户流控、零停机升级和会话感知的 KV 缓存路由,支持 GPU 与 TPU |
| **Sleep framework** | Google Research 的持续学习思路:清醒之后进入睡眠阶段整合记忆 | 报告称几乎不遗忘,长上下文结果可达 1000 万 token。属作者主张,尚无独立复现 |

<sub>本期来源见 <a href="../archive/2026-10-31.md">archive/2026-10-31.md</a>。</sub>
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
