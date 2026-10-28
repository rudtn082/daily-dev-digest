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
## 今天 — 2026-10-28

在其之上搭建的底层设施:终端、操作系统和 GPU 调度器,都是本月发布或开源的。

| 精选 | 是什么 | 为何上榜 |
|------|-----------|-----------|
| **Ghostty 1.4** | GPU 终端模拟器的新版本:补全 Kitty 图形协议、滚动缓冲压缩、GTK 的 EGL 渲染器、`ghostty +ssh` | 10 月 27 日发布,在 HN 首页快照中获 841 分。发布说明称 macOS 上 pty I/O 吞吐提升 25%–55% |
| **Moxnox 1.0** | 把 Windows NT 风格的系统调用和 PE 可执行文件放在 Unix 布局上的业余操作系统,支持 x86-64 和 ARM64 | 出自 WinBtrfs 作者。Btrfs 测试不足,没有桌面和安全模型。许可证未能确认,请到仓库核实 |
| **NVIDIA Run:ai(开源)** | 面向 Kubernetes GPU 编排的 KAI Scheduler、GPU Fractioning Operator 等 | 原本商用的产品于 10 月 13 日开源。KAI 为 Apache 2.0,属 CNCF Sandbox 项目。各组件许可证不同 |

<sub>本期来源见 <a href="../archive/2026-10-28.md">archive/2026-10-28.md</a>。</sub>
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
