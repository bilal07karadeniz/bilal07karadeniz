<p align="center">
  <img src="https://raw.githubusercontent.com/bilal07karadeniz/bilal07karadeniz/2679e3ffbd645fcc6403a6281cb0a38757fc5bc5/assets/banner.svg" width="100%" alt="Bilal Karadeniz — Rust, real-time voice AI and full-stack products." />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bilal-karadeniz-8539b1169/"><b>LinkedIn</b></a> &nbsp; / &nbsp;
  <a href="https://hellobilal.com"><b>Portfolio</b></a> &nbsp; / &nbsp;
  <a href="https://github.com/bilal07karadeniz/brisvox"><b>brisvox</b></a> &nbsp; / &nbsp;
  <a href="https://klawbi.app/"><b>Klawbi</b></a>
</p>

### Building the product and the systems behind it

I'm Bilal, a software developer based in Ankara, Türkiye. I build **real-time voice systems, AI applications, full-stack products and developer tools** with Rust, Python and TypeScript — connecting interfaces, APIs, data and deployment into complete user workflows.

My largest project is **Veloquence**, an AI voice and text platform for business websites. I work across its frontend, backend, knowledge retrieval and real-time voice systems. The project began under Curately and continued under Veloquence.

### Featured open source · [brisvox](https://github.com/bilal07karadeniz/brisvox)

**A Rust engine for real-time voice agents, with Python and TypeScript SDKs.**

I'm building the engine behind phone and browser conversations: streaming speech recognition, LLM responses, tool execution and speech synthesis, with callers able to interrupt mid-answer.

- **Runtime:** isolated asynchronous call sessions, bounded queues and dedicated inference pools for Silero VAD and Smart Turn.
- **Interruptions:** turn epochs reject stale audio; conversation history retains the words actually played to the caller.
- **Tools:** schema validation, separate read-only and side-effect policies, and scoped idempotency protection during retries and interruptions.
- **Connectivity:** WebSocket, WebRTC, Twilio/Telnyx media streams and optional SIP, with cloud and local speech/model providers.
- **Developer experience:** Python/TypeScript agent SDKs, a browser client, TOML/YAML configuration, deterministic simulations and reproducible benchmark scripts.

> **Repository benchmark:** 325 concurrent sessions in a 4-CPU / 4-GiB Linux container, with real VAD/turn-detection models and **mock STT/LLM/TTS providers**, within a p95 voice-to-voice SLO of 1.2 s. This measures framework capacity; real-provider results and methodology are documented separately.

[Source & quickstart](https://github.com/bilal07karadeniz/brisvox) · [Documentation](https://bilal07karadeniz.github.io/brisvox/) · [Benchmark evidence](https://github.com/bilal07karadeniz/brisvox/tree/main/bench/results) · [Tool safety design](https://github.com/bilal07karadeniz/brisvox/blob/main/docs/TOOLS.md)

---

### Selected work

<table>
<tr><td colspan="2" valign="top"><h3>Klawbi / AI agent marketplace</h3><b><a href="https://klawbi.app/">Klawbi</a></b><br />My own product, built end to end. Hire AI agents for coding, design, writing and research; set task budgets, follow progress and collect deliverables.<br /><br /><sub>Next.js · TypeScript · Fastify · PostgreSQL / pgvector · Modal · WebSockets</sub></td></tr>
<tr>
<td width="50%" valign="top">
<h3>01 / Conversational AI</h3>
<b><a href="https://www.veloquence.ai/">Veloquence</a></b><br />
Voice and text agents, knowledge retrieval and visitor qualification.<br /><br />
<sub>Next.js · FastAPI · PostgreSQL · Qdrant · Pipecat</sub>
</td>
<td width="50%" valign="top">
<h3>02 / Developer tools</h3>
<b><a href="https://github.com/bilal07karadeniz/Grafyx">Grafyx</a></b><br />
MCP tools for exploring code relationships, callers, dependencies and project structure.<br /><br />
<sub>Python · MCP · Source analysis · Semantic search</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>03 / SaaS products</h3>
<b><a href="https://foodlex.co/">Foodlex</a></b><br />
An AI-assisted platform for dietitians: client records, diet plans, appointments and reporting.<br /><br />
<sub>Next.js · FastAPI · PostgreSQL · LLM APIs</sub>
</td>
<td width="50%" valign="top">
<h3>04 / Mobile applications</h3>
<b><a href="https://apps.apple.com/us/app/tustrack-tus-takip-deneme/id6785279438">TusTrack</a></b><br />
Study planning, timers, revision cards and progress tracking, with iOS release work.<br /><br />
<sub>React Native · Expo · TypeScript · Supabase</sub>
</td>
</tr>
</table>

### Tools I work with

**Web & mobile** &nbsp; — TypeScript · React · Next.js · React Native · Expo  
**Systems & voice** &nbsp; — Rust · Tokio · WebRTC · WebSockets · SIP · ONNX  
**Backend & data** &nbsp; — Python · FastAPI · PostgreSQL · Redis · Celery  
**AI & voice** &nbsp; — RAG · Qdrant · pgvector · Pipecat · Speech APIs · MCP  
**Delivery** &nbsp; — Docker · GitHub Actions · Railway · Netlify · Deterministic simulation · Property testing · pytest · Vitest

### How I work

Clear interfaces, maintainable systems and verification suited to the change. I use AI-assisted development alongside source inspection, automated checks and visual testing.

---

<p align="center"><b>Open to software engineering and paid contract opportunities.</b><br /><a href="https://hellobilal.com">hellobilal.com</a> · <a href="mailto:contact@hellobilal.com">contact@hellobilal.com</a></p>
