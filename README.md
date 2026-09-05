# Kevin Ye

**Software engineer building mobile products, voice assistants, and coding-agent systems.**

Vancouver, BC · 10 years in software engineering · 8+ years shipping Android

I build the product and the systems behind it: native clients, realtime backends, agent runtimes, and the tooling that gets changes shipped and verified.

I led a multi-quarter Android modularization into 100+ feature modules and built an Android team's Claude Code practice from scratch. Before that, I delivered mobile systems across six consumer and fintech engagements at Konrad Group, from Compose architecture and offline-first apps to Bluetooth-connected fitness hardware.

My current open-source focus is making agents useful beyond a single conversation: durable state, reliable tools, explicit permissions, and execution that can recover when things go wrong.

## Featured projects

### [PiBox](https://github.com/dev32-io/PiBox)
**A development environment for supervised agentic software delivery, built on the [Pi coding agent](https://github.com/badlogic/pi-mono).**

PiBox brings multi-agent execution, visual design tools, and managed delivery workflows into one terminal environment. Work can stay lightweight and interactive, or move from a reviewed idea through implementation, integration, code review, and end-to-end verification.

- **Multi-agent orchestration:** bounded foreground and background agents, live progress, scoped tools, and model-tier routing.
- **Managed delivery:** dependency-aware stages, isolated Git worktrees, deterministic checks, and bounded review-and-repair loops.
- **Explicit control and recovery:** user-approved execution, enforced repository permissions, durable workflow state, and recovery after interrupted runs.
- **Visual tools:** live architecture diagrams, browser mockups, and a workflow board showing progress and verification evidence.

[![PiBox workflow board showing staged delivery and final verification](https://raw.githubusercontent.com/dev32-io/PiBox/develop/docs/assets/workflow-demo/workflow-dashboard.png)](https://github.com/dev32-io/PiBox#from-idea-to-working-product)

[Explore the code and workflow demo →](https://github.com/dev32-io/PiBox#from-idea-to-working-product)

### [Sentient](https://github.com/dev32-io/sentient)
**An open-source voice and text assistant I run for my family.**

Sentient connects a native Bun/TypeScript agent runtime with local speech services, persistent memory, and household tools on an Apple-silicon Mac mini. I own the system end to end: gateway, clients, shared SDKs, capability services, and deployment.

- **Native agent runtime:** streaming model responses, ReAct tool loops, provider routing, cancellation, and per-tool permissions with human confirmation.
- **Voice interaction:** local Whisper speech recognition and Qwen speech synthesis, streaming audio, and barge-in.
- **Memory and continuity:** durable sessions, scoped personal and household recall, and reconnectable realtime clients.
- **Multiple surfaces:** a web app serving my household, with Android and iOS clients under active development using Kotlin Multiplatform, Jetpack Compose, and SwiftUI.

Built for people I know—not just a demo prompt.

[Explore the code and live-stack demos →](https://github.com/dev32-io/sentient#demo)

## More tools I've built

- **[esp32-devtool](https://github.com/dev32-io/esp32-devtool)** — Hardware tooling that lets coding agents inspect device screens, send touch events, and transfer binary payloads on ESP32 boards.
- **[ccToolBox](https://github.com/dev32-io/ccToolBox)** — Claude Code skills and research tools extracted from my development practice.
- **[agentic-dev-harness](https://github.com/dev32-io/agentic-dev-harness)** — Agent workflow rules and quality gates, including frustration checks and end-to-end verification.

## Technical toolkit

| Area | Technologies and systems |
| --- | --- |
| Mobile | Kotlin, Jetpack Compose, Kotlin Multiplatform, SwiftUI, React Native, BLE |
| Agents | TypeScript, Bun/Node.js, tool calling, MCP, subagents, memory, evaluation and review loops |
| Backend & realtime | Python, FastAPI, WebSockets, SQLite, streaming audio, local speech services |
| Developer systems | Gradle, modularization, Git worktrees, GitHub Actions, CI/CD, Docker |

## Connect

[Website](https://blog.dev32.io/) · [LinkedIn](https://www.linkedin.com/in/kevin-ye-3167b2114/) · [Email](mailto:kevin.ye32@gmail.com)
