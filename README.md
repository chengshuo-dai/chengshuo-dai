# Chengshuo (Lucas) Dai

I build AI products and agent systems. M.S. Biostatistics (Data Science) at Yale, and a Forward Deployed Engineer intern working on a platform for enterprise agents.

[lucasdai.cn](https://www.lucasdai.cn) · [LinkedIn](https://www.linkedin.com/in/chengshuo-dai) · [Email](mailto:chengshuo.dai23@gmail.com) · New Haven, CT

## Now

- **Vinote**, a Mac app that turns YouTube and Bilibili videos into study notes with clickable timestamps. Transcription runs on-device with whisper.cpp; the app is signed, notarized and updates itself. Builds will be published at [vinote-releases](https://github.com/chengshuo-dai/vinote-releases).
- **SpeakEase**, voice dictation for macOS that also coaches spoken English: it checks what you actually said against the audio and scores pronunciation with a local phoneme model.
- At work: evaluating agents after they are built and turning the ones that hold up into reusable templates.

## Selected work

| Project | What it does | Built with |
| --- | --- | --- |
| [Study Abroad Buddy](https://github.com/chengshuo-dai/study_abroad_buddy) | AI companion for Chinese students moving to the US: multi-tool agent with web search, visible steps and sources, voice, persistent to-dos | LangGraph, FastAPI, React |
| [MediCareAI Agent](https://github.com/chengshuo-dai/medicare_agent) ([live](https://medicare-agent.lucasdai.cn)) | Structured clinical interview across 23 dimensions with ranked differential diagnoses | FastAPI, React, Postgres |
| [EvoSearch Agent](https://github.com/chengshuo-dai/Evo-SearchAgent) | Knowledge search with hybrid retrieval (Postgres FTS + pgvector, RRF) and cross-encoder reranking | LangGraph, pgvector, Next.js |
| [SnapNote](https://github.com/chengshuo-dai/SnapShot) | Screenshot to structured AI note, local-first on macOS | Tauri, Rust, Vue |
| [Life.OS](https://github.com/chengshuo-dai/life.os) ([live](https://lifeos.lucasdai.cn)) | Interactive narrative console with three branching life paths | Next.js |
| VC Fellow | Deal-screening agent from PMAI Hack For Impact NYC 2026: scores a pitch deck with page-cited evidence and books the follow-up. I owned the backend and agent logic | Claude API, OpenAI Agents SDK |

## Case studies

Write-ups with architecture and evaluation at [lucasdai.cn/solutions](https://www.lucasdai.cn/solutions):

- Policy-aware IT access-request agent for AWS S3 and Snowflake. First-pass approval readiness went from 52.8% to 83.6% on a 500-case benchmark.
- Enterprise multimodal search, from POC to internal pilot. Recall@10 went from 0.55 to 0.78 and P95 latency from 1.8s to 700ms.
- Personalized patient outreach for a multi-clinic healthcare provider.
- Multi-agent medical assistant with a router, a single-agent fast path and a parallel swarm.
- Distilling coding-agent trajectories into a small model with LoRA.

## Writing

Notes on agents, RAG and LLM systems at [lucasdai.cn/blog](https://www.lucasdai.cn/blog).
