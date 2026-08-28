## Hi, I'm Noah

CS undergrad at UIC, graduating May 2027. Currently doing undergraduate research at the
**Electronic Visualization Laboratory** and working as a **software engineer at Blaine County
Gaming Network**. Previously a software engineering intern at **Meta**.

Infrastructure is my favourite part — the tooling other people end up depending on — but the
work keeps pulling in backend platforms, applied ML, and more security engineering than I
expected to be doing.

### What I'm working on

**Electronic Visualization Laboratory** — Provisioning and access control for a 15-node NVIDIA
Jetson AGX Thor cluster. A Flask API over idempotent Ansible playbooks turned a 15-step manual
re-flash into one audited action, and an OAuth-backed SSH certificate authority replaced shared
credentials with short-lived, roster-scoped certificates so each student reaches only their
assigned nodes. I also rebuilt the assignment track for the lab's edge-computing course.
That code lives in private lab repos.

**Blaine County Gaming Network** — Backend work on a Node/Express + MySQL platform: a creator
marketplace with a peer-benchmarked pricing engine, a 911 dispatch subsystem I wrote end to
end, and a Discord-facing RAG assistant over internal documentation and the server codebase
with ingest-time secret scanning and redacted output.

**Side projects** — [Orbit Chat](https://github.com/orbit-chat) and
[Probis](https://github.com/npyrz/probis) are both active. Taking Machine Learning and
Computer Vision this term, which keeps feeding back into the on-device inference work.

### Selected work

**[Orbit Chat](https://github.com/orbit-chat)** — Desktop-first encrypted messaging.
Tech lead on a two-person team, owning the server data model and the cryptography layer.
Message content is unreadable to the server: libsodium X25519 sealed conversation keys,
secretbox message and attachment encryption, and key versioning that rekeys on membership
change. Ships signed Windows and macOS builds.
`Electron` `React` `TypeScript` `NestJS` `Prisma` `PostgreSQL` `Socket.IO`

**[Probis](https://github.com/npyrz/probis)** — Local-first Polymarket terminal.
Prices Chicago daily high-temperature markets by building a probability distribution from
NWS/NOAA observations and forecast vintages, fusing it with market-implied probabilities,
and ranking buckets by net edge after execution cost. Nothing is routed without a human click.
`Node` `Express` `React` `PostgreSQL` `WebSockets`

**[Syllab.ai](https://github.com/npyrz/syllab.ai)** — AI class management.
PDF/DOCX ingestion with timeout guardrails and a strict processing lifecycle, class-scoped
retrieval context, streamed source attribution, and per-user quotas so inference cost stays
predictable.
`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Groq`

**[Campus-Connect](https://github.com/npyrz/Campus-Connect)** — Meta University capstone.
A campus events platform with an 8-signal weighted ranking engine scoring text similarity to
attendance history, mutual-friend and shared-group affinity, host affinity, day-of-week
preference, and calendar conflicts — with weights that adapt to how much history a user has.
`React` `Node` `Express` `Prisma` `PostgreSQL`

**[Pixordle](https://github.com/npyrz/Pixordle)** — Daily image-word puzzle.
Object detection turns a photo into guessable words; solving reveals the image underneath.
`Next.js` `Python`

### Tech

**Languages** — Python · TypeScript · JavaScript · SQL · C++ · C · Java · Go · Lua

**Frameworks** — React · Next.js · Node/Express · NestJS · Flask · Prisma · Socket.IO · Electron · PyTorch · OpenCV · Vitest

**Infrastructure** — PostgreSQL · MySQL · Redis · Ansible · Docker · Linux · systemd · GitHub Actions · AWS S3

<p align="center">
  <img src="https://raw.githubusercontent.com/npyrz/npyrz/output/output/pacman-contribution-graph-dark.svg" alt="contribution graph" />
</p>
