## Hi, I'm Noah

CS undergrad at UIC, graduating May 2027. Previously a software engineering intern at Meta.

I like infrastructure and the tooling that keeps it honest — fleet automation, access control,
retrieval systems, and models small enough to run on the device that collected the data.

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

### What I'm working on

Undergraduate research on edge computing — provisioning and access control for a 15-node
NVIDIA Jetson AGX Thor cluster. A Flask API over idempotent Ansible playbooks turned a
15-step manual re-flash into one audited action, and an OAuth-backed SSH certificate
authority replaced shared credentials with short-lived, roster-scoped certificates so each
student reaches only their assigned nodes. That code lives in a private lab repo.

Also currently taking Machine Learning and Computer Vision, which keeps feeding back into
the on-device inference work.

### Tech

**Languages** — Python · TypeScript · JavaScript · SQL · C++ · C · Java · Go · Lua

**Frameworks** — React · Next.js · Node/Express · NestJS · Flask · Prisma · Socket.IO · Electron · PyTorch · OpenCV · Vitest

**Infrastructure** — PostgreSQL · MySQL · Redis · Ansible · Docker · Linux · systemd · GitHub Actions · AWS S3

<p align="center">
  <img src="https://raw.githubusercontent.com/npyrz/npyrz/output/output/pacman-contribution-graph-dark.svg" alt="contribution graph" />
</p>
