# AGENTS.md — 给 AI Agent 的工作指引

本文件面向自动化 AI Agent（编码助手、文档机器人、内容巡检）。人类读者请看 [README.md](README.md)。

## 这个仓库是什么

`synomosai-company-vision` 是一个**纯内容仓**（立场文档仓），不是可运行的 SDK、不是可执行的检查器。核心资产是自包含 HTML 远景页 `gov_vision_zh_v0.1-company-vision.html`，外加 `远景图.png` 与 `logo.svg`。它陈述 SynomosAI 的四支柱世界观（身份/溯源/治理/共生），是生态的立场锚点。

## 可用的工作命令

```bash
# 列出仓内文件
ls -lh

# 查看远景主文档标题与版本
grep -E "<title>|<meta name=\"description\"" gov_vision_zh_v0.1-company-vision.html

# 在浏览器打开远景页（人工阅读用）
start gov_vision_zh_v0.1-company-vision.html
```

前置依赖：无运行时依赖；只需一个能打开 HTML 的浏览器。

## 约定（Do）

- 修改远景 HTML 时保持自包含（不引入需要额外构建的外部资源）。
- 修改四支柱措辞时，在 PR 描述中说明理由，并同步更新 `README.md` / `README.en.md` 的对应表格。
- 新增文件后，在 `README.md` 的「仓库结构」段登记。

## 禁止（Don't）

- 不要改动 `LICENSE` 的版权主体（Copyright (c) 2026 SynomosAI）与许可口径——**权属字段只由维护者变更**。
- 不要在仓内提交任何密钥、令牌或真实客户数据。
- 不要声称本仓「已认证 / 已商用交付 / 已服务特定客户」。
- 不要把本仓当作可执行检查器使用——它只陈述立场。

## 边界

本仓专注**公司远景与立场陈述**；不覆盖具体的合规检查、审计流程或工具执行。需要可运行的检查时，指向生态内工具仓（`traceability-audit`、`ai-governance-audit-chain` 等）。
