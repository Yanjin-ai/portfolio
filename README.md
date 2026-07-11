# Yanjin Li — AI Engineering Portfolio & CV

**Live:** https://yanjin-ai.github.io/portfolio/ · bilingual (EN / 中文) · [PDF (EN)](Yanjin-Li-CV-EN.pdf) · [PDF (中文)](Yanjin-Li-CV-ZH.pdf)

Eleven AI projects designed, built and evaluated solo over three months (May–Jul 2026) — training-method research, multi-device AI systems, applied decision systems, and shipped products. Self-taught, entirely from papers and online courses.

## Projects

**A · Research & Training Methods**
- **Zero Gradient** — a 4.16B-param content-routed MoE LM trained with *no backpropagation* on a single T4; a 5-phase capability-boundary study proving the bottleneck is architectural.
- **NeuroGolf (ARC-AGI)** — compiling 400 ARC tasks into minimal ONNX circuits; reframed as program synthesis + scorer reverse-engineering, with hard anti-overfitting discipline.
- **Nemotron Post-training** — a reproducible post-training pipeline for a 30B MoE reasoning model; a fully root-caused training failure with six postmortems.
- **Orbit Wars** — a multi-agent game player whose real contribution is evaluation methodology (bilateral self-play, opponent pools, an offline/online validity study).

**B · AI Systems & Architecture**
- **Gemma4all** — a cross-device task system: schema-first (42 JSON schemas), event-sourced, local-first, fail-closed human-in-the-loop approvals; LiteRT-LM on Metal GPU.
- **VoiceInput** — macOS push-to-talk speech input; pure Swift, zero dependencies, with pre-roll-buffer latency engineering and seamless Chinese-IME handling.

**C · Applied ML & Decision Systems**
- **TriageGeist** — an ED-triage decision stack; found 99.7% label leakage and refused to exploit it, building a text-blind model + conformal uncertainty + fairness audit instead.
- **Maze Crawler** — a layered multi-unit strategy agent (BFS planning, 3-round conflict resolution, CI) built and evaluated in a single day.

**D · AI Products & Tools**
- **AI Showrunner** — one sentence → subtitled vertical short film, via a vision-model critic loop and cross-shot character consistency.
- **Offline French Companion** — a full LLM language tutor running entirely in-browser (WebLLM + Whisper + OCR + TTS), fully offline.
- **Atelier Post** — a shipped art-to-Instagram tool; one vanilla-JS codebase across web, PWA and iOS.

## Background

Master in Management & Finance, **ESCP** (Paris & London, 2023–2026) · BA Language & Culture, **BISU** (2019–2023).
Internships: **BNP Paribas** (Global Corporate Banking) · **HSBC** (Global Markets, Liquidity) · **TikTok** (Growth Strategy) · **Uber China · DiDi** (Product & User Operations).

## Contact
[geraldineliyanjin@gmail.com](mailto:geraldineliyanjin@gmail.com) · [github.com/Yanjin-ai](https://github.com/Yanjin-ai)

---
*This repo is the source of the live site above; edit `index.html` and push to update. PDFs are generated from the same page via headless Chrome.*
