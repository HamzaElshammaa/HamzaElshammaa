<div align="center">

# Hey there, I'm Hamza El-Shammaa 👋

### **Computer Engineer · Full-Stack & Mobile/TV Developer · AI/ML Engineer**

*Building fast, high-craft digital products and intelligent AI systems — from multi-provider LLM pipelines and reinforcement learning agents to 60fps Smart TV applications and cross-platform web & mobile products.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hamza_El--Shammaa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hamzaelshammaa)
[![Email](https://img.shields.io/badge/Email-hamzahelshammaa%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hamzahelshammaa@gmail.com)
[![Schedule a Call](https://img.shields.io/badge/Calendly-Book_a_Chat-006BFF?style=for-the-badge&logo=calendly&logoColor=white)](https://calendly.com/hamzahelshammaa)
[![Location](https://img.shields.io/badge/📍_Cairo,_Egypt-181717?style=for-the-badge)](#)

</div>

---

## ⚡ Who I Am

I'm a Computer Science & Engineering graduate from the **German University in Cairo (GUC)** and a **Junior AI/ML Engineer at ElisaPolystar**, where I integrate LLM capabilities, benchmark & deploy local models, and architect internal RAG and data platforms.

Alongside my core engineering role, I partner with startups and brands to ship **end-to-end production systems** that combine **deep systems performance** with **visual polish**:
- 🧠 **AI & Machine Learning Systems:** Designing multi-provider LLM structured extraction pipelines, cross-lingual semantic retrieval with `pgvector`, and Hierarchical Reinforcement Learning (PPO) agents (my Bachelor Thesis improved autonomous strategy scores in *Freeciv* by **550%**).
- 📱 **Web, Mobile & Living-Room TV Engineering:** Architecting full-stack web & mobile platforms (**Next.js 16**, **NestJS 11**, **React Native / Expo**, **Supabase**) and 60fps D-pad-navigated Smart TV apps across **Android TV (Kotlin / Compose for TV)**, **Samsung Tizen**, and **LG webOS (SolidJS)**.
- 🎤 **Leadership & Communication:** Former **Coaching Lead at TEDxGUC** (led a 20-person team and coached 10 TEDx speakers) and **Best Delegation Award** winner at GUCMUN.

---

## 💼 Freelance & Client Engineering Highlights *(Private / NDA)*

*Below is an architectural overview of commercial and client systems I have architected and delivered under NDA:*

### 1. AI-Powered Talent Acquisition & Cross-Lingual Vector Matching Ecosystem
* **Stack:** `Next.js 16` · `NestJS 11` · `Expo (React Native)` · `Supabase (PostgreSQL 17 + pgvector)` · `HuggingFace Transformers` · `TypeScript`
* **What I Built:**
  * Architected a **three-package monorepo** (Web client, REST/WebSocket API backend, and cross-platform iOS/Android mobile app with full English/Arabic RTL localization and real-time translated chat).
  * Engineered a **fault-tolerant 5-stage PDF resume ingestion pipeline** combining regex pre-extraction, Arabic-Indic normalization, and schema-enforced native PDF extraction across **Anthropic Claude, OpenAI, and Google Gemini**.
  * Built an **in-process multilingual embedding engine** (`multilingual-e5-base`, 768-dim) paired with **PostgreSQL `pgvector` HNSW indexes** to perform cross-lingual (Arabic ↔ English) multi-vector cosine matching across candidate skills, role history, and work descriptions.

### 2. Cross-Platform Living-Room Smart TV Streaming Suite (Android TV, Tizen & webOS)
* **Stack:** `Kotlin 2.x` · `Jetpack Compose for TV` · `AndroidX Media3 (ExoPlayer)` · `Custom FFmpeg NDK Extension` · `Room (SQLite FTS5)` · `SolidJS` · `Go`
* **What I Built:**
  * Engineered a **native Android TV & Fire TV media player** achieving **60fps D-pad remote navigation on constrained 1GB RAM devices**, featuring zero-allocation streaming playlist parsers, **Room FTS5** instant search across **100,000+ records**, a 2D virtualized Electronic Program Guide (EPG) timeline grid, and a custom **Media3 + FFmpeg audio decoder extension** (`AC3`, `E-AC3`, `TrueHD`, `DTS`).
  * Built a companion **SolidJS + TypeScript Smart TV monorepo** targeting **Samsung Tizen 5.5+** and **LG webOS 5+** (compatible down to Chromium 68 engines over `file://`), maintaining 1:1 visual and frame-time parity with the Android TV app, backed by a Dockerized **Go** metadata aggregation service and static edge storefront.

---

## 🚀 Public Open-Source Projects & Repositories

### 🌐 Web & Mobile Applications

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`3D-Portfolio-Website`](https://github.com/HamzaElshammaa/3D-Portfolio-Website)** | **Interactive 3D & Multi-Theme Developer Portfolio** — Dual-mode portfolio blending an interactive 3D Spline WebGL scene state machine (with hardware/FPS watchdog fallback) and a pluggable 2D multi-theme architecture. | `Next.js 16` `React 19` `Spline 3D` `Tailwind CSS 4` `Vitest` |
| **[`xsquare-feast-menu`](https://github.com/HamzaElshammaa/xsquare-feast-menu)** | **Xsquare Artisanal Food Truck Digital Experience** — High-converting interactive digital menu and brand showcase engineered for sub-second mobile QR load times and fluid motion. | `React` `TypeScript` `Vite` `Tailwind CSS` `Framer Motion` |
| **[`RamadanApp`](https://github.com/HamzaElshammaa/RamadanApp)** | **Cross-Platform Ramadan Companion App** — Mobile application for live prayer countdowns, astronomical Hijri date calculation, and custom Adhan audio notifications. | `React Native` `Expo Router` `TypeScript` `Reanimated` |

---

### 🤖 AI Pipelines & Workflow Automation

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`unimail-ai-assistant`](https://github.com/HamzaElshammaa/unimail-ai-assistant)** | **Headless AI University Email Pipeline** — Automated EWS/OWA fetcher that navigates legacy Exchange firewall restrictions, extracts structured course deadlines & urgency via Gemini/OpenAI, and dispatches alerts to Telegram and Google Calendar via n8n webhooks. | `Python` `Gemini API` `Exchange EWS` `n8n` `Telegram Bot API` |
| **[`markitdown-pdf-ocr-pipeline`](https://github.com/HamzaElshammaa/markitdown-pdf-ocr-pipeline)** | **Vision LLM PDF-to-Markdown & Slide OCR Pipeline** — Hybrid document ingestion utility combining `pdfminer.six` sparse-text page detection with Microsoft `MarkItDown`, Google Gemini Vision, and local OpenAI-compatible LLMs. | `Python` `MarkItDown` `Gemini API` `OpenAI SDK` `PDFMiner` |
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

### 🥽 Spatial Computing (AR / VR) & Computer Architecture

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
Languages      :: TypeScript · JavaScript · Python · Kotlin · Java · Swift · C · SQL · VHDL
Frontend & UI  :: Next.js 16 · React 19 · SolidJS · Tailwind CSS · Framer Motion · Three.js / Spline
Mobile & TV    :: React Native (Expo) · Jetpack Compose for TV · Media3/ExoPlayer · Tizen · webOS · SwiftUI
Backend & Data :: NestJS · Node.js · Go · Supabase · PostgreSQL (pgvector) · Room (SQLite FTS5) · Docker
AI / ML        :: Anthropic / OpenAI / Gemini SDKs · Local LLMs · HuggingFace Transformers · RL (Gymnasium / SB3)
```

---

## 📬 Let's Connect

Whether you're recruiting for an **AI/ML**, **Full-Stack**, or **Mobile/Connected-TV** engineering role — or looking to collaborate on an ambitious product — I'd love to chat!

- 💼 **LinkedIn:** [linkedin.com/in/hamzaelshammaa](https://linkedin.com/in/hamzaelshammaa)
- 📧 **Email:** [hamzahelshammaa@gmail.com](mailto:hamzahelshammaa@gmail.com)
- 📅 **Schedule a Call:** [calendly.com/hamzahelshammaa](https://calendly.com/hamzahelshammaa)
