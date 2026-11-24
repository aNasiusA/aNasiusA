### Hi, I'm Anasius 👋

I'm a software engineer who builds whole products end to end: Java and TypeScript backends, React and React Native frontends, native macOS apps in Swift, and AI systems that run **locally** rather than through a cloud API.

Right now I mostly work on **multi-agent AI** and **security**: making LLM agents that can be checked, kept within limits and trusted with real decisions.

🌐 [anasiusa.dev](https://anasiusa.dev) · 🎓 Computer Science & Engineering, UMaT

---

### What I've built

**🛡️ AI defence for a cyber range**: Python · React · local LLM
An AI defence engine for a simulated power-grid OT network. Three detectors raise alerts, and a local LLM drafts a containment plan from a fixed playbook, citing its sources. A safety gate dry-runs the plan on the grid model and an analyst approves it. Then the system contains the attacker, recovers and records metrics for the research.

**🧠 MAKO, a multi-agent orchestrator built on a knowledge graph**: Python · RDF · LLMs
My final-year project. Agents, tools and handoffs live in an RDF knowledge graph. A ReAct-style LLM picks the next step, and each choice is checked against the graph before it runs.
→ [**HestiaHealth**](https://github.com/aNasiusA/hestia-studio-adtc) runs MAKO for clinical use entirely offline on an 8GB laptop with Qwen2.5-3B. It was my entry to the Africa Deep Tech Challenge 2026.

**🎵 [Nocta](https://github.com/aNasiusA/nocta)**: Swift · macOS
Controls Spotify and Apple Music from the macOS **Lock Screen** without unlocking. It shows artwork, live progress and working play/pause, skip and seek on a Liquid Glass card.

**📋 Nokware Console**: Bun · React · SQLite · Ollama
Compliance tooling for crypto exchanges. It pulls data from KYC, sanctions, trading and MoMo systems and strips personal data on the way in. A local model maps the data to each regulator's format, an engineer approves the mapping, and everything sent to a regulator goes into a signed, hash-chained audit trail.

**📄 [umat-thesis-guide](https://github.com/aNasiusA/umat-thesis-guide)**: LaTeX · Claude Code skill
A LaTeX class and a format checker that make UMaT theses follow the university's formatting rules. It also works as a Claude Code skill.

**⚽ [Inposibal](https://inposibal.anasiusa.dev)**: JavaScript
A browser football game with an AI opponent, live commentary and a sound engine, built without a framework.

**🐚 [Rheo](https://github.com/aNasiusA/rheo)**: Java
A Unix-style shell written from scratch, with its own command parser, built-ins and process execution.

I've also built full-stack products: **evnt** (events: mobile, web and a Java backend), **Drop** (mobile app, admin panel and backend) and **Moola** (personal finance, React Native).

---

### Tools I use

**Languages:** TypeScript · Python · Java · Swift · SQL
**Backend:** Spring Boot · Node/Express · Bun · FastAPI · PostgreSQL · MongoDB · SQLite
**Frontend & mobile:** React · Next.js · React Native/Expo · Tailwind
**AI:** local LLMs (Ollama, llama.cpp) · multi-agent systems · knowledge graphs (RDF) · MediaPipe
