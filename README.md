# SynomosAI 公司远景 · Company Vision

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-roadmap%20%7C%20v1.0.0-informational.svg)
![Language](https://img.shields.io/badge/prose-Chinese%20%7C%20%E4%B8%AD%E6%96%87-red.svg)
![Four Pillars](https://img.shields.io/badge/pillars-Identity%20%C2%B7Traceability%20%C2%B7Governance%20%C2%B7Symbiosis-4f8cff.svg)
![Companion](https://img.shields.io/badge/companion-traceability--audit-3ddc97.svg)
![Org](https://img.shields.io/badge/org-SynomosAI-8a2be2.svg)

> English version: [README.en.md](README.en.md)

SynomosAI 四支柱体系：**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**——当 AI 进入商业，可信是唯一的硬通货。

> 本仓库属于 [SynomosAI](https://github.com/SynomosAI) 生态技能包的一员。生态全景见 [`synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)，理论站位见 [`traceability-audit`](https://github.com/SynomosAI/traceability-audit)。
>
> This repo is part of the [SynomosAI](https://github.com/SynomosAI) ecosystem. See [`synomosai-skills`](https://github.com/SynomosAI/synomosai-skills) for the full map and [`traceability-audit`](https://github.com/SynomosAI/traceability-audit) for the theoretical stance.

本仓库存放 SynomosAI 的**公司远景图与理念文档（中文）**：一张可在浏览器直接打开的交互式 HTML 远景图，配合远景示意图与品牌 Logo，集中陈述「人与 AI 治理」的四支柱世界观。它是整个 SynomosAI 生态的**立场锚点（stance anchor）**——其它规范仓、审计仓、流程仓在引用价值取向时，都回到本仓所陈述的四支柱。

---

## ✨ 仓内内容 / What is inside

- [`gov_vision_zh_v0.1-company-vision.html`](gov_vision_zh_v0.1-company-vision.html)：公司远景主文档（中文，自包含 HTML，深色主题，含四支柱卡片与 ASCII 架构图）。
- [`远景图.png`](远景图.png)：远景示意图（PNG）。
- [`logo.svg`](logo.svg)：SynomosAI 品牌标识（SVG）。
- `README.md` / `README.en.md`：本说明的中、英双版。
- `llms.txt` / `llms-full.txt`：给 AI Agent 的索引与完整说明。
- `AGENTS.md`：给 AI Agent 的工作指引。
- `SECURITY.md`：安全策略与上报渠道。

四支柱一句话：

| 支柱 | 含义 | 对标外部参考 |
|---|---|---|
| Identity 身份 | AI 护照机制：每个 AI 实体可被识别、可被追责 | ISO/IEC 42001 资产管理思路 |
| Traceability 溯源 | XCGS 治理系统：决策与产出全链路留痕 | NIST AI RMF Govern/Map |
| Governance 治理 | A³ 法则：Alignment / Audit / Accountability | GB/Z 185 治理参考 |
| Symbiosis 共生 | AI 世界共生论：人与 AI 长期共存的伦理与制度 | 公开理论文献 |

---

## 🚀 快速开始 / Quick Start

本仓库是**纯内容仓（文档 + 静态图）**，无需安装任何运行时。最快的阅读方式是直接在浏览器打开远景 HTML：

```bash
# 1. 克隆本仓库（浅克隆即可，仓内只有静态文件）
git clone --depth 1 https://github.com/SynomosAI/synomosai-company-vision.git
cd synomosai-company-vision

# 2. 直接用浏览器打开远景主文档（Windows 示例）
start gov_vision_zh_v0.1-company-vision.html
# macOS: open gov_vision_zh_v0.1-company-vision.html
# Linux: xdg-open gov_vision_zh_v0.1-company-vision.html
```

如果你只是想在命令行里看一眼仓内有什么：

```bash
# 列出根目录文件与体积
ls -lh

# 看远景主文档的标题与 meta 描述（确认版本）
grep -E "<title>|<meta name=\"description\"" gov_vision_zh_v0.1-company-vision.html
```

期望输出（节选）：HTML `<title>` 为 `SynomosAI · 公司远景｜人与 AI 治理`，`meta description` 提及四支柱——即说明你拿到的是 v0.1 远景文档。

---

## 🧩 仓库结构 / Repository layout

```text
synomosai-company-vision/
├── README.md                              # 本文件（中文主说明）
├── README.en.md                           # 英文版说明
├── gov_vision_zh_v0.1-company-vision.html # 公司远景主文档（中文，自包含 HTML）
├── 远景图.png                              # 远景示意图
├── logo.svg                               # 品牌标识
├── LICENSE                                # MIT 许可证全文
├── CODEOWNERS                             # 代码/内容 owners
├── llms.txt                               # 给 AI 的最小索引
├── llms-full.txt                          # 给 AI 的完整说明
├── AGENTS.md                              # 给 AI Agent 的工作指引
├── SECURITY.md                            # 安全策略
└── .github/workflows/                     # CI 门禁（lgd-ci-gate 等）
```

---

## 🧭 与生态其它仓的关系 / Relation to the ecosystem

本仓**只陈述立场，不执行检查**。需要「把立场变成可跑的检查」时，请使用生态内对应的工具仓：

- 生态全景与技能索引：[`SynomosAI/synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)
- 理论站位与审计溯源：[`SynomosAI/traceability-audit`](https://github.com/SynomosAI/traceability-audit)
- AI 治理审计链：[`SynomosAI/ai-governance-audit-chain`](https://github.com/SynomosAI/ai-governance-audit-chain)

---

## 仓库内容

公司远景图与理念（中文）

## 元信息

- **技能名**：`synomosai-company-vision`
- **版本**：1.0.0
- **署名**：SynomosAI
- **许可**：MIT（详见仓库 LICENSE）

## 使用方式

1. 克隆本仓库或将该技能目录放入你的 Agent 技能目录（如 `~/.workbuddy/skills/`）；
2. 在 Agent 中按 `SKILL.md` 的描述触发对应能力；
3. 需要审计/合规证据的场景，参考 `SKILL.md` 内模板产出工件。

---

## License / 许可

本仓库以 **MIT** 许可证发布，全文见根目录 [`LICENSE`](LICENSE)。版权声明：Copyright (c) 2026 SynomosAI。

> 原 README 中的权利声明（「许可：MIT（详见仓库 LICENSE）」）逐字保留于上方「元信息」段，未作改动。

---

## 🔒 安全 / Security

如发现本仓库的安全问题（例如远景 HTML 内嵌脚本异常、资源引用指向第三方），请按 [`SECURITY.md`](SECURITY.md) 的方式私下报告，不要在公开 issue 中披露。

## 🤝 贡献 / Contributing

内容改动请走 PR；本仓为立场文档，任何对四支柱措辞的修改请在 PR 描述中说明理由。owners 见 [`CODEOWNERS`](CODEOWNERS)。

---

## 免责声明

本仓库内容为 SynomosAI 的**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的 ISO/IEC 42001、NIST AI RMF、GB/Z 185 等外部标准与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。
