# Chengshuo (Lucas) Dai

I build AI products and agent systems. M.S. Biostatistics (Data Science) at Yale, and a Forward Deployed Engineer intern working on a platform for enterprise agents.

[lucasdai.cn](https://www.lucasdai.cn) · [LinkedIn](https://www.linkedin.com/in/chengshuo-dai) · [Email](mailto:chengshuo.dai23@gmail.com) · New Haven, CT

## Now

- **Vinote**, a note app for videos. Paste a YouTube or Bilibili link and get study notes with clickable timestamps, filed in a folder tree as deep as the subject goes. Transcription runs on-device with whisper.cpp; the Mac app is signed, notarized and updates itself. Builds will be published at [vinote-releases](https://github.com/chengshuo-dai/vinote-releases).
- **SpeakEase**, dictation for non-native English speakers. Instead of a separate study app, it puts speaking English into the work you already do: it keeps what you actually said, then shows grammar, more natural phrasing and pronunciation feedback next to the text. The goal is to think in English every day.
- At work: evaluating agents after they are built and turning the ones that hold up into reusable templates.

## Selected work

| Project | What it does | Built with |
| --- | --- | --- |
| [Study Abroad Buddy](https://github.com/chengshuo-dai/study_abroad_buddy) | Companion for Chinese students heading to the US for the first time: answers with sources you can inspect, turns next steps into to-dos, voice practice for the CBP interview | LangGraph, FastAPI, React |
| [MediCareAI Agent](https://github.com/chengshuo-dai/medicare_agent) ([live](https://medicare-agent.lucasdai.cn)) | Structured clinical interview across 23 dimensions with ranked differential diagnoses | FastAPI, React, Postgres |
| [EvoSearch Agent](https://github.com/chengshuo-dai/Evo-SearchAgent) | Knowledge search with hybrid retrieval (Postgres FTS + pgvector, RRF) and cross-encoder reranking | LangGraph, pgvector, Next.js |
| [SnapNote](https://github.com/chengshuo-dai/SnapShot) | Screenshot to structured AI note, local-first on macOS | Tauri, Rust, Vue |
| [Life.OS](https://github.com/chengshuo-dai/life.os) ([live](https://lifeos.lucasdai.cn)) | Interactive narrative console with three branching life paths | Next.js |
| VC Fellow | Agent between a VC and applying startups, from PMAI Hack For Impact NYC 2026: screens pitch decks against the firm's criteria with page-cited evidence, follows up on missing information and books the meeting. I owned the backend and agent logic | Claude API, OpenAI Agents SDK |

## Case studies

Write-ups with architecture and evaluation at [lucasdai.cn/solutions](https://www.lucasdai.cn/solutions):

- Policy-aware IT access-request agent for AWS S3 and Snowflake. First-pass approval readiness went from 52.8% to 83.6% on a 500-case benchmark.
- Enterprise multimodal search, from POC to internal pilot. Recall@10 went from 0.55 to 0.78 and P95 latency from 1.8s to 700ms.
- Personalized patient outreach for a multi-clinic healthcare provider.
- Multi-agent medical assistant with a router, a single-agent fast path and a parallel swarm.
- Distilling coding-agent trajectories into a small model with LoRA.

## Writing

Notes on agents, RAG and LLM systems at [lucasdai.cn/blog](https://www.lucasdai.cn/blog).
