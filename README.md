## Mokshith Rao

Backend engineer at Flashback Labs. Karimnagar, India.

I work on backend and infrastructure — Node and Go services, Postgres, and SQS-driven pipelines on AWS. Most of what I build at work is in private repos, so briefly, what it is:

**ImageShield** — likeness-monitoring platform. Node/TypeScript/Fastify and Python/FastAPI over Postgres 16, across 10 containerised services on AWS ECS. Eliminated IDOR across 103 HTTP routes with a build-failing test driven off the live route table. 74 reversible migrations gated in CI by an apply, rollback and diff pipeline.

**Legacy Mode** — the Node/Express backend behind a production AI product, built across 23 phases. Cut voice first-audio latency about 10x after benchmarking four TTS vendors on latency and cost. Cross-process realtime delivery over Postgres LISTEN/NOTIFY rather than adding a pub/sub dependency.

**Media pipeline** — Go and TypeScript ingestion on SQS, DynamoDB and S3. Bounded-concurrency Go workers running ONNX face detection, and a three-tier dedup stage that removed 34.5% of jobs as URL duplicates and another 4.6% as exact content duplicates.

### What's here

[**AutoDev**](https://github.com/5mokshith/AutoDev) — browser-based AI code editor. Runs a full Node runtime in the browser through WebContainers, with agents across Gemini, OpenAI, Anthropic and Groq. Built Jan–Mar 2026; mine apart from six commits from a collaborator.

[**Portfolio**](https://github.com/5mokshith/Portfolio) — source of [mokshith.vercel.app](https://mokshith.vercel.app/).

[**CardioGuard**](https://github.com/5mokshith/CardioGuard) — cardiac arrest detection from real-time ECG signals. Built with a team; won at a hackathon.

[**Qconn**](https://github.com/5mokshith/Qconn) — Q&A platform for campus knowledge sharing.

### Stack

TypeScript, Go, Python, SQL · Node.js, Express, Fastify, FastAPI · PostgreSQL, DynamoDB · AWS (ECS, SQS, S3, IAM, Secrets Manager), Terraform, Docker · React, Next.js

---

[mokshithrao1481@gmail.com](mailto:mokshithrao1481@gmail.com) · [LinkedIn](https://linkedin.com/in/mokshithrao) · [mokshith.vercel.app](https://mokshith.vercel.app/)
