<div align="center">

### `xevrion` /ˈzɛv.ri.ən/

<sup><i>systems engineering • automation • AI infrastructure • 19</i></sup>

<samp>
/ <a href="https://xevrion.dev">xevrion.dev</a>  
/ <a href="https://x.com/xevrion_the1">x.com/xevrion</a>  
/ <a href="mailto:youremail@example.com">email</a>
/ <a href="https://www.linkedin.com/in/yash-bavadiya-a598a224b/">linkedin.com/in/xevrion</a> /

</samp>

</div>

---

I design and ship intelligent systems, from AI-driven automation engines to institutional backend platforms and low-level utilities.

Clean architecture. Operational rigor. Systems thinking across layers.

---

### DaemonDoc — AI-Powered README Generator  
An autonomous documentation engine that analyzes live repositories and generates structured, production-grade READMEs.

Uses webhook-driven automation, background job queues (Redis + BullMQ), and large language models to keep documentation synchronized with every push.

Repository → https://github.com/xevrion/DaemonDoc<br>
Live →  https://www.daemondoc.online/

---

### PHC Integrated Digital System  
A production-grade healthcare management system built for the IIT Jodhpur Primary Health Centre.

Implements full clinical workflow orchestration — visit lifecycle management, digital prescriptions, lab request pipelines, pharmacy billing, and attendance tracking — with strict role-based access control (RBAC) and LDAP-backed authentication.


Repository →  https://github.com/xevrion/iitj-phc-system<br>
Live →  (in progress)

---

### BreathClean — Health-Aware Route Optimization Engine  
A full-stack, multi-service navigation system that scores routes using live AQI, weather, and traffic data.

Implements a real-time scoring pipeline with Redis caching, MongoDB geospatial indexing, background re-computation schedulers, and an optional Django + Pathway microservice for batch processing. 

Repository → https://github.com/xevrion/BreathClean<br>
Live →  https://breathe.daemondoc.online/

---

### DocuMentor — Offline RAG Study System  
A fully local retrieval-augmented generation (RAG) pipeline that performs document ingestion, vector indexing (FAISS), and GPU-accelerated LLM inference without external APIs.

Implements quantized Phi-3 summarization, embedding-based semantic search (BGE), and structured quiz generation — all running on consumer GPUs with 4-bit optimization.

Repository →  https://github.com/xevrion/DocuMentor

---

### Motixion — Behavioral Accountability System  
A real-time gamified execution platform built on Supabase (PostgreSQL + RLS) with deterministic point calculation and leaderboard orchestration.

Implements row-level security policies, database-side scoring functions, streak tracking, and 5AM rolling daily resets for structured performance measurement between accountability partners.

Repository →  https://github.com/xevrion/Motixion<br>
Live →  https://motixion.vercel.app/

---

### IITJ LAN Auto Login — Captive Portal Automation Daemon  
A reverse-engineered authentication client for IIT Jodhpur’s FortiGate captive portal.

Extracts dynamic session tokens, replays credentialed POST flows, and runs as a systemd user service with AES-256 encrypted local credential storage — preventing forced 10,000-second session expiry.

Repository →  https://github.com/xevrion/iitj-lan-autologin<br>
Post →  https://xevrion.dev/posts/IITJEthernetLoginIssue

---

### Peek-a-Repo — GitHub Hover Preview Extension  
A Chrome extension that injects dynamic hover previews into GitHub’s file tree using the GitHub GraphQL API.

Implements client-side DOM interception, syntax-highlighted code previews (Prism.js), image rendering, and local token storage via chrome.storage with intelligent response caching.

Repository →  https://github.com/xevrion/peek-a-repo

---

### Chronapse — Cross-Language Timelapse Engine  
A Linux-native timelapse recording system combining a Go (Bubbletea) terminal UI with a Python + OpenCV capture pipeline and FFmpeg rendering layer.

Designed for long-duration, low-overhead recording with clean process orchestration and controlled frame scheduling.

Repository →  https://github.com/xevrion/Chronapse

---

### echo-go — Peer-to-Peer Terminal Chat  
A lightweight P2P chat application written in Go using direct socket communication and a terminal-based interface.

Implements decentralized message exchange without intermediary servers, focusing on minimal transport-layer overhead and real-time bidirectional streaming.

Repository →  https://github.com/xevrion/echo-go

---

### FluxFetch — RPC-Based High-Throughput Download Manager  
A Python-driven download orchestration tool that interfaces with aria2 via RPC for parallel, resumable, multi-connection file transfers.

Implements headless link extraction, configurable connection splitting, and a lightweight PyQt6 control interface with graceful fallback when RPC is unavailable.

Repository →  https://github.com/xevrion/FluxFetch

---

### Straight Hockey — RL Agent vs Human  
A Python + Pygame air hockey environment featuring both heuristic AI and a trained Soft Actor-Critic (SAC) reinforcement learning agent.

Integrates a Stable-Baselines3 policy directly into the game loop, enabling real-time inference and human-vs-trained-agent gameplay within a lightweight 2D physics simulation.

Repository →  https://github.com/xevrion/StraightHockey

---

### Shot Ninja — Cross-Platform Hotkey Capture Utility  
A lightweight background screenshot daemon built with Python, implementing global keyboard hooks and cross-platform screen capture via `mss`.

Abstracts OS-specific input handling (keyboard vs. pynput) to support root-free Linux operation while maintaining low-latency capture and timestamped file persistence.

Repository →  https://github.com/xevrion/shot-ninja
