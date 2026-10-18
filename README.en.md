# SynomosAI Company Vision

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-roadmap%20%7C%20v1.0.0-informational.svg)
![Four Pillars](https://img.shields.io/badge/pillars-Identity%20%C2%B7Traceability%20%C2%B7Governance%20%C2%B7Symbiosis-4f8cff.svg)

> Chinese version: [README.md](README.md)

SynomosAI's four-pillar system — **Identity · Traceability · Governance · Symbiosis** — holds that when AI enters commerce, trust is the only hard currency.

This repository holds SynomosAI's **company vision document (Chinese, v0.1)**: a self-contained interactive HTML vision page, a PNG overview diagram, and the brand logo. It is the **stance anchor** of the whole SynomosAI ecosystem; every other governance, audit and process repo refers back to the four-pillar worldview stated here.

## What is inside

- `gov_vision_zh_v0.1-company-vision.html` — the main vision document (Chinese, self-contained HTML, dark theme, four-pillar cards + ASCII architecture diagram).
- `远景图.png` — vision overview diagram (PNG).
- `logo.svg` — SynomosAI brand mark (SVG).

| Pillar | Meaning | External reference |
|---|---|---|
| Identity | AI passport: every AI entity identifiable and accountable | ISO/IEC 42001 asset-management thinking |
| Traceability | XCGS governance system: full-chain logging of decisions and outputs | NIST AI RMF Govern/Map |
| Governance | A³ laws: Alignment / Audit / Accountability | GB/Z 185 governance reference |
| Symbiosis | AI-world symbiosis theory: long-term human–AI coexistence ethics | public literature |

## Quick Start

This is a **content-only repo** (static docs + images). No runtime is needed.

```bash
git clone --depth 1 https://github.com/SynomosAI/synomosai-company-vision.git
cd synomosai-company-vision
# open the vision page in a browser
open gov_vision_zh_v0.1-company-vision.html   # macOS
xdg-open gov_vision_zh_v0.1-company-vision.html # Linux
```

```bash
# inspect contents from the CLI
ls -lh
grep -E "<title>|<meta name=\"description\"" gov_vision_zh_v0.1-company-vision.html
```

## Repository layout

```text
synomosai-company-vision/
├── README.md / README.en.md                 # bilingual docs
├── gov_vision_zh_v0.1-company-vision.html   # main vision doc (Chinese)
├── 远景图.png / logo.svg                     # diagrams and brand mark
├── LICENSE                                  # MIT
├── llms.txt / llms-full.txt                 # AI-facing index
├── AGENTS.md / SECURITY.md
└── .github/workflows/                       # CI gates
```

## Relation to the ecosystem

This repo **states the stance; it does not run checks**. For tooling that turns the stance into runnable checks, see:

- Ecosystem map: [`SynomosAI/synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)
- Theoretical stance / audit trace: [`SynomosAI/traceability-audit`](https://github.com/SynomosAI/traceability-audit)
- AI governance audit chain: [`SynomosAI/ai-governance-audit-chain`](https://github.com/SynomosAI/ai-governance-audit-chain)

## License

Released under the **MIT** license; see [`LICENSE`](LICENSE). Copyright (c) 2026 SynomosAI.

## Security

See [`SECURITY.md`](SECURITY.md) to report issues privately.

## Disclaimer

This repository records SynomosAI's theoretical stance and tooling exploration. It is not a claim of certification, commercial delivery, or service to any specific customer. External standards cited (ISO/IEC 42001, NIST AI RMF, GB/Z 185) are paraphrases of public material — verify independently before formal citation. APIs, authorization codes and ambassadors are roadmap items, not yet live.
