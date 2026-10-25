<div align="center">

# Hey there, I'm Hamza El-Shammaa 👋

### **Computer Engineer · Full-Stack & Mobile/TV Developer · AI/ML Engineer**

*Building fast, high-craft digital products and intelligent AI systems — from LLM pipelines and MCP servers to 60fps Smart TV players and cross-platform web & mobile apps.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hamza_El--Shammaa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hamzaelshammaa)
[![Email](https://img.shields.io/badge/Email-hamzahelshammaa%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hamzahelshammaa@gmail.com)
[![Schedule a Call](https://img.shields.io/badge/Calendly-Book_a_Chat-006BFF?style=for-the-badge&logo=calendly&logoColor=white)](https://calendly.com/hamzahelshammaa)
[![Location](https://img.shields.io/badge/📍_Cairo,_Egypt-181717?style=for-the-badge)](#)

</div>

---

## ⚡ Who I Am

I'm a Computer Science & Engineering graduate from the **German University in Cairo (GUC)** and a **Junior AI/ML Engineer at ElisaPolystar**, where I integrate LLM capabilities, benchmark & deploy local models, and architect internal RAG and data platforms.

Outside of my day job, I love shipping **end-to-end products** that Obsess over both **systems performance** and **visual polish**:
- 🧠 **AI & Agentic Systems:** Designing multi-provider LLM extraction pipelines, Model Context Protocol (MCP) servers with 99+ live tools, and Hierarchical Reinforcement Learning (PPO) agents (my Bachelor Thesis improved autonomous game strategy scores in *Freeciv* by **550%**).
- 📱 **Web, Mobile & Living-Room TV Apps:** Shipping full-stack platforms (**Next.js 16**, **NestJS 11**, **React Native / Expo**) and 60fps D-pad-navigated Smart TV apps across **Android TV (Kotlin / Compose for TV)**, **Samsung Tizen**, and **LG webOS (SolidJS)**.
- 🎤 **Beyond the Terminal:** Former **Coaching Lead at TEDxGUC** (led a 20-person team and coached 10 TEDx speakers) and **Best Delegation Award** winner at GUCMUN. I care deeply about clear communication, product storytelling, and clean engineering.

---

## 🚀 Featured Projects & Repositories

### 🌐 Full-Stack & AI Product Platforms

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`cv-matcher`](https://github.com/HamzaElshammaa/cv-matcher)** | **Full-Stack AI Talent & Job Matching Ecosystem** — 3-package monorepo featuring a 5-stage hybrid PDF CV ingestion pipeline (Anthropic/OpenAI/Gemini + regex fallback), in-process multilingual vector embeddings (`Xenova/multilingual-e5-base`), pgvector HNSW cosine matching, and feature-complete Web & Mobile clients. | `Next.js 16` `NestJS 11` `Expo (React Native)` `Supabase` `pgvector` `TypeScript` |
| **[`3D-Portfolio-Website`](https://github.com/HamzaElshammaa/3D-Portfolio-Website)** | **Interactive 3D & Multi-Theme Developer Portfolio** — Dual-mode portfolio blending an interactive 3D Spline scene state machine (with hardware/FPS watchdog fallback) and a multi-theme 2D architecture. | `Next.js 16` `React 19` `Spline 3D` `Tailwind CSS 4` `Vitest` |
| **[`xsquare-feast-menu`](https://github.com/HamzaElshammaa/xsquare-feast-menu)** | **Xsquare Artisanal Food Truck Digital Experience** — High-converting interactive digital menu and brand showcase engineered for sub-second mobile load times and fluid motion. | `React` `TypeScript` `Vite` `Tailwind CSS` `Framer Motion` |

---

### 📺 Smart TV & Cross-Platform Mobile Engineering

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`MyPTV`](https://github.com/HamzaElshammaa/MyPTV)** | **HiPTV for Android TV & Fire TV** — High-performance IPTV player engineered for 60fps D-pad navigation on 1GB RAM devices. Features streaming M3U8/Xtream parsers, Room FTS5 search over 100k+ channels, custom Media3 + FFmpeg audio decoding, 2D virtualized EPG grid, and a Go metadata backend. | `Kotlin 2.x` `Jetpack Compose for TV` `Media3 / ExoPlayer` `FFmpeg` `Room FTS5` `Go` |
| **[`hiptv-tv`](https://github.com/HamzaElshammaa/hiptv-tv)** | **HiPTV for Samsung Tizen & LG webOS** — Monorepo Smart TV player targeting Tizen 5.5+ and webOS 5+ (down to Chrome 68 engines), maintaining 1:1 visual and frame-time parity with the Android TV client. | `SolidJS` `TypeScript` `Tizen SDK` `webOS Luna` `Vite` |
| **[`HiPT-Player-Website`](https://github.com/HamzaElshammaa/HiPT-Player-Website)** | **HiPTV Product Website & Interactive Web Demo** — Static marketing storefront, pricing portal, and browser-based TV player preview deployed on Cloudflare Pages. | `HTML5` `CSS3` `JavaScript` `Cloudflare Pages` |
| **[`RamadanApp`](https://github.com/HamzaElshammaa/RamadanApp)** | **Cross-Platform Ramadan Companion App** — Mobile application for daily spiritual tracking, prayer schedules, and habits built with file-based routing and native animations. | `React Native` `Expo Router` `TypeScript` `Reanimated` |

---

### 🤖 AI Agents, Developer Tooling & Automation

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`pob-mcp`](https://github.com/HamzaElshammaa/pob-mcp)** | **Path of Building MCP Server (99 Tools)** — Fork-free Model Context Protocol server with a custom LuaJIT stdio bridge that drives Path of Building's real calculation engine for live build optimization, passive tree pathfinding, anointment ranking, crafting simulation, and weighted Trade API queries. | `TypeScript` `MCP SDK` `LuaJIT` `Node.js` |
| **[`unimail-ai-assistant`](https://github.com/HamzaElshammaa/unimail-ai-assistant)** | **Headless AI University Email Pipeline** — Automated EWS/OWA fetcher that navigates legacy Exchange firewall restrictions, extracts structured course deadlines & urgency via Gemini/OpenAI, and dispatches alerts to Telegram and Google Calendar via n8n webhooks. | `Python` `Gemini API` `Exchange EWS` `n8n` `Telegram Bot API` |
| **[`markitdown-pdf-ocr-pipeline`](https://github.com/HamzaElshammaa/markitdown-pdf-ocr-pipeline)** | **Vision LLM PDF-to-Markdown & Slide OCR Pipeline** — Hybrid document ingestion utility combining `pdfminer.six` sparse-text page detection with Microsoft `MarkItDown`, Google Gemini Vision, and local OpenAI-compatible LLMs. | `Python` `MarkItDown` `Gemini API` `OpenAI SDK` `PDFMiner` |
| **[`figma-to-claude-plugin`](https://github.com/HamzaElshammaa/figma-to-claude-plugin)** | **Figma-to-AI Design Token & Frame Exporter** — Custom Figma plugins (`FigmaToJSON` & `FigmaToClaude`) that serialize top-level frames, local variables/styles, and 2x PNG renders directly from Figma's sandbox for AI-assisted UI implementation. | `TypeScript` `Figma Plugin API` `HTML5` |
| **[`Scripting`](https://github.com/HamzaElshammaa/Scripting)** | **Automated Academic Portal Evaluation Suite** — Headless browser automation scripts that streamline repetitive university course and staff evaluation forms. | `Python` `Selenium WebDriver` |

---

### 🧮 Machine Learning, Optimization & Systems Engineering

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`ddos-mitigation-pipeline`](https://github.com/HamzaElshammaa/ddos-mitigation-pipeline)** | **Real-Time DDoS Detection & Graduated Mitigation Engine** — 4-stage network security pipeline on CICIDS traffic: statistical benign baseline modeling, composite Z-score anomaly detection, Token-Bucket/iptables graduated mitigation, and a live Streamlit telemetry dashboard. | `Python` `Streamlit` `Pandas` `Scapy` `Docker` |
| **[`autonomous-intersection-optimization`](https://github.com/HamzaElshammaa/autonomous-intersection-optimization)** | **Autonomous Intersection Vehicle Scheduling** — Multi-objective metaheuristic optimization comparing First-Come First-Served (FCFS), Simulated Annealing (SA), and Genetic Algorithms (GA) to minimize intersection delay and energy consumption across conflict matrices. | `Python` `NumPy` `Jupyter` `Genetic Algorithms` `Simulated Annealing` |
| **[`hotel-booking-graph-analytics`](https://github.com/HamzaElshammaa/hotel-booking-graph-analytics)** | **Hotel Booking & Review Knowledge Graph Analytics** — Relational and graph-oriented exploratory data analysis over multi-table hospitality datasets, user demographics, and sentiment reviews. | `Python` `Jupyter` `SQLite` `Pandas` |
| **[`tactical-battle-minimax-ai`](https://github.com/HamzaElshammaa/tactical-battle-minimax-ai)** | **Turn-Based Tactical Combat Solver** — Adversarial search engine in Java implementing Minimax and Alpha-Beta Pruning over game-state trees to compute optimal combat sequences. | `Java` `Minimax` `Alpha-Beta Pruning` |

---

### 🥽 Spatial Computing (AR / VR) & Systems Architecture

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`unity-ar-battle-adventure`](https://github.com/HamzaElshammaa/unity-ar-battle-adventure)** | **Unity 6 Augmented Reality Multi-Stage Game** — Mobile AR experience built with AR Foundation & XR Interaction Toolkit featuring real-world plane-tracked number puzzles, physics-based creature capture, and interactive AR combat. | `C#` `Unity 6` `AR Foundation` `XR Interaction Toolkit` |
| **[`phantom-range-vr-shooter`](https://github.com/HamzaElshammaa/phantom-range-vr-shooter)** | **Phantom Range VR Tactical Shooter** — Immersive Virtual Reality shooting range and training simulation with 6DoF weapon handling, reactive targets, and spatial audio. | `C#` `Unity` `XR Interaction Toolkit` `VR` |
| **[`unity-vr-knight-interactions`](https://github.com/HamzaElshammaa/unity-vr-knight-interactions)** | **Unity 6 VR Interactive Sandbox** — VR locomotion, grab interactions, and custom 3D medieval character animation triggers built on Unity 6 and XR Interaction Toolkit 3.3. | `C#` `Unity 6` `XR Interaction Toolkit` `FBX Animation` |
| **[`Tomasulo`](https://github.com/HamzaElshammaa/Tomasulo)** | **Tomasulo's Algorithm Microprocessor Simulator** — Cycle-accurate out-of-order instruction scheduling simulator with reservation stations, register renaming, and common data bus (CDB) execution. | `Java` `Computer Architecture` |
| **[`OpenGL_2D_Game`](https://github.com/HamzaElshammaa/OpenGL_2D_Game)** | **Space Infinite Runner** — Custom 2D arcade game rendered from scratch with OpenGL primitives, collision physics, and dynamic obstacle spawning. | `C` `C++` `OpenGL` |

---

## 🛠️ Tech Stack & Toolbox

```text
Languages      :: TypeScript · JavaScript · Python · Kotlin · Java · Swift · C · SQL · Lua · VHDL
Frontend & UI  :: Next.js 16 · React 19 · SolidJS · Tailwind CSS · Framer Motion · Three.js / Spline
Mobile & TV    :: React Native (Expo) · Jetpack Compose for TV · Media3/ExoPlayer · Tizen · webOS · SwiftUI
Backend & Data :: NestJS · Node.js · Go · Supabase · PostgreSQL (pgvector) · Room (SQLite FTS5) · Docker
AI / ML        :: Anthropic / OpenAI / Gemini SDKs · Local LLMs · HuggingFace Transformers · RL (Gymnasium / SB3) · MCP
```

---

## 📬 Let's Connect

Whether you're recruiting for an **AI/ML**, **Full-Stack**, or **Mobile/Connected-TV** engineering role — or looking to collaborate on an ambitious product — I'd love to chat!

- 💼 **LinkedIn:** [linkedin.com/in/hamzaelshammaa](https://linkedin.com/in/hamzaelshammaa)
- 📧 **Email:** [hamzahelshammaa@gmail.com](mailto:hamzahelshammaa@gmail.com)
- 📅 **Schedule a Call:** [calendly.com/hamzahelshammaa](https://calendly.com/hamzahelshammaa)
