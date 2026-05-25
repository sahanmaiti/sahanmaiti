<div align="center">

<br />

# Sahan Maiti

**iOS · macOS · Backend · Automation · AI Systems**

<br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahan-maiti)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/sahan_maiti_)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/sahan_maiti_)

</div>

<br />

---

<br />

## About

I build systems — native Apple software, autonomous automation pipelines, and AI-powered products that solve real operational problems.

My work spans **iOS/macOS engineering** at the framework level, **backend architecture** built for scale and clarity, and **automation workflows** that eliminate human-in-the-loop inefficiencies. I think in layers: from Accessibility APIs and kernel events at the bottom, to product experience at the top.

Engineering, for me, is a design discipline. The architecture *is* the product.

<br />

---

<br />

## Currently Building

| Project | Description |
|---|---|
| **DevSignal** | Autonomous iOS internship radar — AI-scored, end-to-end, production-grade |
| **Nix** | Native macOS menu bar utility — AX observer-driven app lifecycle management |
| *Next* | Expanding deeper into the Apple ecosystem — watchOS, visionOS, developer tooling |

<br />

---

<br />

## Featured Projects

<br />

### DevSignal &nbsp;·&nbsp; `iOS · FastAPI · AI Pipeline · PostgreSQL`

> **An autonomous internship intelligence system — from scraping to SwiftUI, with zero manual steps in between.**

DevSignal is a production-grade full-stack system that orchestrates job discovery, AI scoring, recruiter enrichment, and application tracking — delivered through a native iOS app.

**System Architecture**

- Scrapes **13+ job platforms** on a scheduled pipeline via `n8n` orchestration
- Scores and filters opportunities using **Groq / Llama 3.1** with custom prompt engineering
- Auto-generates **personalized recruiter outreach** per opportunity
- Tracks the full application lifecycle through a **Kanban-style SwiftUI interface**
- Surfaces analytics and pipeline health through an embedded **Streamlit dashboard**

**Engineering Highlights**

- Zero-cost, fully containerised backend using **Docker + FastAPI + PostgreSQL**
- Native **SwiftUI** app with Keychain-based authentication, REST API integration, and optimistic UI updates
- AI scoring pipeline decoupled from scraping — independently scalable and replaceable
- Recruiter enrichment system runs asynchronously to avoid pipeline blocking
- Designed for eventual multi-platform expansion with a clean API contract

`SwiftUI` `Swift` `Python` `FastAPI` `PostgreSQL` `Docker` `Groq` `Llama 3.1` `n8n` `Streamlit`

<br />

---

<br />

### Nix &nbsp;·&nbsp; `macOS · SwiftUI · AppKit · Accessibility APIs`

> **Close the window. Quit the app.**

Nix solves a real macOS UX gap: apps that linger as background processes after their last window closes. It's a native menu bar utility that manages application lifecycle through system-level observation.

**System Architecture**

- Hooks into **AXObserver** and the macOS Accessibility API to watch per-app window state in real time
- Implements a **layered service architecture**: observer layer → rules engine → action dispatcher
- **SMAppService** integration for persistent login item behaviour without legacy launch agents

**Engineering Highlights**

- Near-zero idle CPU — purely **event-driven**, no polling
- Per-app **rules engine** with configurable grace periods, hide/ignore/prompt behaviours
- Operates entirely within the Accessibility framework — no private APIs, no hacks
- Built natively with **SwiftUI + AppKit** in a hybrid composition model
- Demonstrates deep understanding of macOS process management, session lifecycle, and window server events

`Swift` `SwiftUI` `AppKit` `AXObserver` `Accessibility APIs` `SMAppService` `macOS`

<br />

---

<br />

### Automated Certificate Generation System &nbsp;·&nbsp; `Automation · Document Processing`

> **A bulk document generation and delivery pipeline — zero manual intervention at scale.**

An end-to-end automation workflow for generating individualised certificates and delivering them via email at volume. Designed to handle real-world data variance, formatting edge cases, and delivery reliability.

- Reads structured participant data from Excel, generates personalised certificates via PowerPoint automation, exports to PDF, and dispatches via SMTP — fully automated
- Handles batch processing with per-record error isolation and delivery confirmation logging

`UiPath` `PowerPoint Automation` `Excel Integration` `PDF Generation` `SMTP`

<br />

---

<br />

### Automated Email Sender &nbsp;·&nbsp; `Automation · Workflow Engineering`

> **Precision bulk communication — personalised at scale.**

An automation workflow for constructing and dispatching context-aware, personalised emails to large recipient lists. Built with data-driven templating and delivery orchestration.

`UiPath` `Excel Integration` `SMTP Automation`

<br />

---

<br />

## Tech Stack

<br />

**Languages**

![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Apple Platforms**

![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat&logo=swift&logoColor=white)
![AppKit](https://img.shields.io/badge/AppKit-000000?style=flat&logo=apple&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)

**Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**AI & Automation**

![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=flat&logo=uipath&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white)

<br />

---

<br />

## Engineering Philosophy

Software architecture is not a deliverable — it's a decision framework that shapes every downstream outcome.

I build with a few principles that don't move:

**Native over abstracted.** Where the platform provides a first-class API, use it. AXObserver over polling. SwiftUI data flow over manual state sync. The framework knows the environment better than the workaround does.

**Event-driven over scheduled.** Systems that react are leaner, faster, and compositionally cleaner than systems that poll. This is true at the OS level, the backend level, and the product level.

**Architecture first, optimisation second.** A well-structured system is easier to profile, easier to debug, and easier to scale than a fast but tangled one. Clarity is a performance investment.

**Automation should disappear.** The best pipeline is the one users never think about. If a workflow requires human attention under normal conditions, it isn't finished.

**Product taste is an engineering skill.** How something feels — latency, transitions, error states, empty states — is not a design afterthought. It is part of the system spec.

<br />

---

<br />

## GitHub

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=sahanmaiti&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e&icon_color=58a6ff&include_all_commits=true&count_private=true" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahanmaiti&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e&langs_count=6" />

</div>

<br />

---

<br />

<div align="center">

*Built with Swift, Python, and an unhealthy curiosity for systems.*

</div>
