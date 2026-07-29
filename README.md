<!--
  GitHub Profile README for github.com/dbs-mnnit
  Built around backend engineering, distributed systems, and production AI.
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,45:0f172a,75:0f766e,100:22d3ee&text=Digvijay%20Bahadur%20Singh&fontColor=f8fafc&fontSize=42&fontAlignY=38&desc=Backend%20Software%20Engineer%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20Applied%20AI&descAlignY=59&descSize=17&animation=fadeIn" alt="Digvijay Bahadur Singh" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&multiline=false&repeat=true&width=900&height=45&lines=I+build+backend+systems+that+stay+correct+under+load.;5M%2B+messages%2Fday+%7C+10M%2B+API+requests%2Fday.;Kafka%2C+Redis%2C+distributed+workers%2C+RAG+and+AI+agents." alt="Engineering focus" />
</a>

<br />

<a href="mailto:aksbhabua09@gmail.com"><img src="https://img.shields.io/badge/Email-aksbhabua09%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/digvijay1803"><img src="https://img.shields.io/badge/LinkedIn-Digvijay%20Singh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://leetcode.com/u/dbs_mnnit"><img src="https://img.shields.io/badge/LeetCode-dbs__mnnit-FFA116?style=for-the-badge&logo=leetcode&logoColor=111827" alt="LeetCode" /></a>
<a href="https://github.com/dbs-mnnit"><img src="https://img.shields.io/github/followers/dbs-mnnit?label=Follow&style=for-the-badge&logo=github&color=111827" alt="GitHub followers" /></a>

<br /><br />

<img src="https://komarev.com/ghpvc/?username=dbs-mnnit&label=PROFILE+VIEWS&color=0f766e&style=flat-square" alt="Profile views" />

</div>

---

## Engineering systems that do not panic when traffic does

I am a **Backend Software Engineer** who designs scalable, fault-tolerant platforms for customer engagement, campaign automation, payments, analytics, and AI-powered workflows.

My work sits where systems become difficult: **high throughput, partial failure, duplicate delivery, provider limits, asynchronous execution, database bottlenecks, and unreliable model output**. I turn those constraints into APIs and workflows that are measurable, recoverable, and safe to retry.

```java
public final class EngineeringProfile {
    String role = "Backend Software Engineer";

    List<String> core = List.of(
        "Distributed Systems",
        "Event-Driven Architecture",
        "Backend Scalability",
        "Database Performance",
        "Production AI Workflows"
    );

    String principle =
        "A system is production-ready when failure is expected, observable, and recoverable.";
}
```

---

## Production impact

<table>
<tr>
<td align="center" width="25%">
  <h2>10M+</h2>
  <sub>API requests handled per day</sub>
</td>
<td align="center" width="25%">
  <h2>5M+</h2>
  <sub>SMS, WhatsApp and email messages per day</sub>
</td>
<td align="center" width="25%">
  <h2>10K+</h2>
  <sub>Messages processed per second</sub>
</td>
<td align="center" width="25%">
  <h2>5,000+</h2>
  <sub>Active merchants supported</sub>
</td>
</tr>
<tr>
<td align="center">
  <h2>200K+</h2>
  <sub>Customers supported</sub>
</td>
<td align="center">
  <h2>95%+</h2>
  <sub>Reduction in duplicate notifications</sub>
</td>
<td align="center">
  <h2>70%+</h2>
  <sub>Faster critical MongoDB APIs</sub>
</td>
<td align="center">
  <h2>99%+</h2>
  <sub>Valid structured AI generations</sub>
</td>
</tr>
</table>

---

## What I engineer

<table>
<tr>
<td width="33%" valign="top">

### High-throughput backends

APIs and services designed for sustained traffic, predictable latency, efficient pagination, and clean service boundaries.

**Focus:** REST APIs, Spring Boot, Node.js, MongoDB, PostgreSQL, caching, testing.

</td>
<td width="33%" valign="top">

### Correctness under failure

Asynchronous systems where retries, duplicates, provider failures, and partial completion are handled deliberately.

**Focus:** Kafka, Redis, idempotency, queues, dead-letter flows, rate limiting, distributed locks.

</td>
<td width="33%" valign="top">

### Production AI systems

LLM workflows that retrieve the right context, return validated structures, and recover from model or provider failures.

**Focus:** LangChain, LangGraph, RAG, vector databases, tool calling, caching, structured outputs.

</td>
</tr>
</table>

---

## A system blueprint I work with

```mermaid
flowchart LR
    A[Campaign API] --> B[(Campaign and Recipient State)]
    B --> C[[Kafka]]

    C --> D1[SMS Workers]
    C --> D2[WhatsApp Workers]
    C --> D3[Email Workers]

    D1 --> E[Provider-aware Rate Limiting]
    D2 --> E
    D3 --> E

    E --> F[External Providers]
    F --> G[(Persistent Delivery State)]

    G --> H[Analytics]
    G --> I[Logs, Metrics and Traces]

    D1 -. bounded retry .-> C
    D2 -. bounded retry .-> C
    D3 -. bounded retry .-> C
```

The important part is not the happy path. It is what happens when a consumer restarts, a provider throttles, a request is retried, or the same event appears twice.

**Design concerns I treat as first-class requirements:**

`Idempotency` · `Durable state` · `Bounded retries` · `Dead-letter handling` · `Rate limits` · `Safe reprocessing` · `Observability`

---

## AI workflow architecture

```mermaid
flowchart LR
    A[Merchant or Job Context] --> B[Semantic Retrieval]
    B --> C[(Vector Database)]
    C --> D[LangGraph Workflow]
    D --> E[Gemini or OpenAI Model]
    E --> F[Structured Output Validation]
    F -->|Valid| G[Application Output]
    F -->|Invalid| H[Retry and Recovery]
    H --> D
```

I have built AI workflows with semantic retrieval, metadata filtering, async execution, caching, retries, and structured outputs—reducing campaign creation from hours to **under five minutes** and improving content relevance by **35%+**.

---

## Technology constellation

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=java,cpp,go,ts&theme=dark" alt="Java, C++, Go and TypeScript" />

### Backend, data and messaging
<img src="https://skillicons.dev/icons?i=spring,nodejs,mongodb,postgres,redis,kafka&theme=dark" alt="Spring Boot, Node.js, MongoDB, PostgreSQL, Redis and Kafka" />

### Cloud, delivery and observability
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,jenkins,githubactions,git,grafana&theme=dark" alt="AWS, Docker, Kubernetes, Jenkins, GitHub Actions, Git and Grafana" />

<br /><br />

<img src="https://img.shields.io/badge/LangChain-Production%20LLM%20Apps-1C3C3C?style=flat-square" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-Agentic%20Workflows-0f766e?style=flat-square" alt="LangGraph" />
<img src="https://img.shields.io/badge/RAG-Semantic%20Retrieval-7C3AED?style=flat-square" alt="RAG" />
<img src="https://img.shields.io/badge/Gemini-Generative%20AI-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/OpenAI-API-111827?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API" />
<img src="https://img.shields.io/badge/Datadog-Observability-632CA6?style=flat-square&logo=datadog&logoColor=white" alt="Datadog" />

</div>

---

## Experience snapshot

<details open>
<summary><strong>Backend Software Engineer · SmartOrbit</strong> &nbsp; <code>May 2024 — Present</code></summary>
<br />

Working on **Loyaltty**, a customer engagement and loyalty platform serving thousands of merchants and hundreds of thousands of customers.

- Built backend services across loyalty, campaigns, billing, analytics, and AI-powered campaign creation.
- Designed a Kafka-based multi-channel messaging system processing **5M+ messages/day** at **10K+ messages/second**.
- Reduced duplicate notifications by **95%+** with Redis-backed idempotency, persistent delivery states, and controlled retries.
- Improved critical MongoDB response times by **70%+** through compound indexing, aggregation optimization, query-plan analysis, and efficient pagination.
- Built fault-tolerant workflows with bounded retries, dead-letter queues, provider tracking, and safe reprocessing.
- Reduced production debugging time by **50%+** with structured logging and end-to-end tracing.
- Built LangGraph and RAG pipelines for campaign planning, generation, retrieval, validation, and recovery.

</details>

---

## Featured build — FastFill

### AI resume, cover-letter and job-autofill extension

FastFill retrieves relevant candidate context for a job description, generates tailored application material, and uses Chrome Extension APIs to automate form completion.

```mermaid
flowchart LR
    A[Job Description] --> B[Requirement Parser]
    B --> C[Candidate Context Retrieval]
    C --> D[(Vector Database)]
    D --> E[Agentic Generation Workflow]
    E --> F1[Tailored Resume]
    E --> F2[Cover Letter]
    E --> F3[Screening Answers]
    F1 --> G[Chrome Extension Autofill]
    F2 --> G
    F3 --> G
```

**Engineering behind it:** LangChain · RAG · VectorDB · LLMs · structured generation · agentic workflows · browser automation

---

## Competitive programming

<table>
<tr>
<td width="55%" valign="middle">

- Solved **1,000+** Data Structures and Algorithms problems.
- Achieved **Expert** rating on Codeforces.
- Secured **Global Rank < 500** in a CodeChef contest.
- Participated in **Google Kick Start** and **Meta Hacker Cup**.

</td>
<td width="45%" align="center">

<a href="https://leetcode.com/u/dbs_mnnit">
  <img width="100%" src="https://leetcard.jacoblin.cool/dbs_mnnit?theme=dark&font=JetBrains%20Mono&ext=contest" alt="Digvijay's LeetCode statistics" />
</a>

</td>
</tr>
</table>

---

## Engineering principles

<table>
<tr>
<td align="center" width="25%"><strong>Correctness before cleverness</strong></td>
<td align="center" width="25%"><strong>Retries must be safe</strong></td>
<td align="center" width="25%"><strong>Observability is a feature</strong></td>
<td align="center" width="25%"><strong>Failure is part of the design</strong></td>
</tr>
</table>

> I do not just ask, “Will this work?” I ask, “What happens when it runs twice, fails halfway, or receives 100× the expected traffic?”

---

## GitHub activity

<div align="center">

<img width="49%" src="https://streak-stats.demolab.com?user=dbs-mnnit&theme=tokyonight&hide_border=true&background=0D1117&ring=22D3EE&fire=14B8A6&currStreakLabel=22D3EE" alt="GitHub contribution streak" />

<br /><br />

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=dbs-mnnit&bg_color=0d1117&color=cbd5e1&line=22d3ee&point=14b8a6&area=true&hide_border=true" alt="GitHub contribution activity graph" />

</div>

---

## Let us talk engineering

<div align="center">

I enjoy discussing backend architecture, distributed systems, database performance, production AI, and difficult system-design trade-offs.

<br />

<a href="mailto:aksbhabua09@gmail.com"><img src="https://img.shields.io/badge/Start%20a%20Conversation-Email%20Me-0f766e?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Digvijay" /></a>
<a href="https://www.linkedin.com/in/digvijay1803"><img src="https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>

<br /><br />

### Build for the happy path. Engineer for everything after it.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:020617,45:0f172a,75:0f766e,100:22d3ee" alt="Footer" />

</div>
