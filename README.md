## Hi, I'm Noah

CS undergrad at UIC, graduating May 2027. Right now I'm doing undergraduate research at the
**Electronic Visualization Laboratory** and working as a **software engineer at Blaine County
Gaming Network**. Before that I interned as a software engineer at **Meta**.

Infrastructure is my favorite part of this, the tooling everyone else ends up depending on.
In practice it keeps dragging in backend platforms, applied ML, and a lot more security work
than I planned on.

### What I'm working on

**Electronic Visualization Laboratory.** Provisioning and access control for a 15-node NVIDIA
Jetson AGX Thor cluster. A Flask API over idempotent Ansible playbooks turned a 15-step manual
re-flash into one audited action. An OAuth-backed SSH certificate authority replaced shared
credentials with short-lived, roster-scoped certificates, so each student only reaches the
nodes they're assigned. I also rebuilt the assignment track for the lab's edge-computing
course. That code lives in private lab repos.

**Blaine County Gaming Network.** Backend work on a Node/Express + MySQL platform: a creator
marketplace with a peer-benchmarked pricing engine, a 911 dispatch subsystem I wrote end to
end, and a Discord-facing RAG assistant over internal docs and the server codebase, with
secret scanning at ingest and redacted output.

**Side projects.** [Orbit Chat](https://github.com/orbit-chat) and
[Probis](https://github.com/npyrz/probis) are both active. I'm taking Machine Learning and
Computer Vision this term, which keeps feeding back into the on-device inference work.

### Selected work

**[Orbit Chat](https://github.com/orbit-chat)** is a desktop-first encrypted messaging app.
I'm tech lead on a two-person team and own the server data model and the cryptography layer.
Message content is unreadable to the server: libsodium X25519 sealed conversation keys,
secretbox message and attachment encryption, and key versioning that rekeys whenever
membership changes. It ships signed Windows and macOS builds.
`Electron` `React` `TypeScript` `NestJS` `Prisma` `PostgreSQL` `Socket.IO`

**[Probis](https://github.com/npyrz/probis)** is a local-first Polymarket terminal. It prices
Chicago daily high-temperature markets by building a probability distribution from NWS/NOAA
observations and forecast vintages, fusing that with market-implied probabilities, and ranking
buckets by net edge after execution cost. Nothing is routed without a human click.
`Node` `Express` `React` `PostgreSQL` `WebSockets`

**[Syllab.ai](https://github.com/npyrz/syllab.ai)** is AI class management. It ingests PDFs and
DOCX with timeout guardrails and a strict processing lifecycle, scopes retrieval context to one
class, streams source attribution back with the answer, and enforces per-user quotas so
inference cost stays predictable.
`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Groq`

**[Campus-Connect](https://github.com/npyrz/Campus-Connect)** was my Meta University capstone,
a campus events platform. The interesting part is an 8-signal weighted ranking engine scoring
text similarity to attendance history, mutual-friend and shared-group affinity, host affinity,
day-of-week preference, and calendar conflicts. The weights adapt to how much history a user
actually has.
`React` `Node` `Express` `Prisma` `PostgreSQL`

**[Pixordle](https://github.com/npyrz/Pixordle)** is a daily image-word puzzle. Object detection
turns a photo into guessable words, and solving reveals the image underneath.
`Next.js` `Python`

### Tech

**Languages:** Python · TypeScript · JavaScript · SQL · C++ · C · Java · Go · Lua

**Frameworks:** React · Next.js · Node/Express · NestJS · Flask · Prisma · Socket.IO · Electron · PyTorch · OpenCV · Vitest

**Infrastructure:** PostgreSQL · MySQL · Redis · Ansible · Docker · Linux · systemd · GitHub Actions · AWS S3

<p align="center">
  <img src="https://raw.githubusercontent.com/npyrz/npyrz/output/output/pacman-contribution-graph-dark.svg" alt="contribution graph" />
</p>
