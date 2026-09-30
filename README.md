<div align="center">

<img src="./assets/engineering-header.svg" width="100%" alt="Abhay Jaiswal — Backend engineering, applied AI, hands-on frontend and open source" />

**Java & Spring Boot backend engineer · Applied AI builder · Hands-on React developer**

I build APIs, event-driven workflows, and AI features—with attention to what happens when dependencies fail.

[**Portfolio ↗**](https://abhay-portfolioo.netlify.app/) &nbsp; · &nbsp; [**Explore my repositories ↗**](https://github.com/Abhay123abhi?tab=repositories) &nbsp; · &nbsp; [**Open-source contribution ↗**](https://github.com/darrien1998/dsh-ditto/pull/12)

</div>

---

## Selected engineering work

### 01 / Event-Driven Incident Observability
**From an alert to a durable investigation report.**

A local platform that brings metrics, logs, and traces into one incident workflow. An optional AI service retrieves runbooks and past incidents with pgvector, then generates a grounded root-cause hypothesis.

- **Reliability:** transactional outbox, alert deduplication, and consumers that tolerate redelivery.
- **Observability:** Prometheus, Loki, Tempo, and Grafana; partial evidence stays visible when a source fails.
- **Applied AI:** embeddings → vector retrieval → Gemini; hypotheses stored separately from incident truth.

`Java` · `Spring Boot` · `Kafka` · `PostgreSQL / pgvector` · `Docker Compose`

[**Explore the project →**](https://github.com/Abhay123abhi/event-driven-incident-observability) · [RAG implementation](https://github.com/Abhay123abhi/event-driven-incident-observability/blob/main/docs/ai-investigation.md) · [Failure scenarios](https://github.com/Abhay123abhi/event-driven-incident-observability/blob/main/docs/failure-demos.md)

### 02 / AI-Powered News Intelligence
**Multiple publishers. One feed. Answers connected to their sources.**

A Spring Boot + React app combining Guardian and NYT articles with Gemini summaries, Q&A, briefings, and coverage comparison.

- **Backend:** concurrent provider calls, normalized results, deduplication, and Redis caching.
- **AI integration:** structured responses and validated citation IDs, grounded in the supplied articles.
- **Failure handling:** partial provider results, timeouts, retry backoff, and a circuit breaker; core news works with AI disabled.

`Java 21` · `Spring Boot` · `React` · `Redis` · `Gemini`

[**Explore the project →**](https://github.com/Abhay123abhi/ai-powered-news-intelligence)

<details>
<summary><b>More hands-on work — real-time communication & frontend</b></summary>

<br/>

| Project | What I built |
| --- | --- |
| [Room Chat](https://github.com/Abhay123abhi/chat-app) | Spring Boot + React guest chat with MongoDB persistence, STOMP/WebSocket delivery, presence, and missed-message recovery after reconnecting. |
| [Personal Portfolio](https://github.com/Abhay123abhi/personal-portfolio) | React portfolio with project walkthroughs, experience, and a content-driven blog. [Visit the live site ↗](https://abhay-portfolioo.netlify.app/) |

</details>

## Open source

**Merged contribution · [dsh-ditto #12 — Java language adapter](https://github.com/darrien1998/dsh-ditto/pull/12)**

Contributed Java support to a review-first developer tool, making Java source files available through its language-adapter system.

[Browse my contributions →](https://github.com/pulls?q=is%3Apr+author%3AAbhay123abhi+-user%3AAbhay123abhi)

## Where I work across the stack

| Area | Technologies & focus |
| --- | --- |
| **Backend** | Java · Spring Boot · REST APIs · concurrency · event-driven workflows |
| **Applied AI** | Gemini integration · RAG · embeddings · pgvector · structured output · source grounding |
| **Data & messaging** | PostgreSQL · Redis · MongoDB · Kafka · transactional outbox |
| **Frontend** | React · JavaScript · API integration · real-time interfaces |
| **Delivery & observability** | Docker · Docker Compose · Gradle · Maven · Prometheus · Grafana · Loki · Tempo |

## How I approach engineering

**Design for failure.** Make retries, duplicate events, and unavailable dependencies part of the design.

**Keep AI grounded.** Connect generated output to evidence and keep the core workflow independent of AI availability.

**Build the complete flow.** Connect backend behavior to a usable frontend, documented setup, and reproducible failure scenarios.

---

<div align="center">
<sub>Currently exploring distributed systems, retrieval quality, and performance through hands-on projects.</sub>
<br/><br/>
<a href="https://abhay-portfolioo.netlify.app/"><b>Experience, projects & writing — visit my portfolio ↗</b></a>
</div>
