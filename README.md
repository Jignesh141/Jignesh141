<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=650&lines=Jignesh+Patel;Software+Engineer+%7C+Backend+%26+Distributed+Systems;Designing+Systems+That+Scale+to+Millions" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://jignesh-patel141.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://linkedin.com/in/jigneshpatel141"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:jignesh.patel.cs141@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### About

Software Engineer with 2+ years of production experience building and operating distributed systems in FinTech. I design backend services that handle high-volume workloads reliably — and I own them end-to-end from architecture through deployment, observability, and incident response.

Previously at **Cloudoffis Technologies**, where I built Java/Spring Boot microservices processing high-volume financial transactions, reduced API latency by 25%, architected AWS infrastructure that cut costs by 20%, and owned production on-call for critical services.

MS in Computer Science, **California State University, Fullerton** — graduating May 2026.

```
Core: Java · Spring Boot · Python · Apache Kafka · AWS · Kubernetes · Docker · MySQL · MongoDB · Redis · Elasticsearch
```

---

### Projects

> I believe the best way to learn distributed systems is to build them. Each project below solves a real problem with production-grade architecture.

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 [Predictive Autoscaler for Kubernetes](https://github.com/Jignesh141)

Traditional Kubernetes HPA is reactive — it scales *after* things break. I built a system that predicts traffic spikes before they happen.

ML models (LSTM, Prophet) forecast CPU/memory utilization with **91% accuracy** and trigger pod scaling **2–3 minutes before** load arrives. Integrated directly with the Kubernetes API for automated scaling, restarts, and intelligent alerting.

**Result:** 40% faster incident response · 30% less resource waste vs HPA

`Java` `Spring Boot` `Python` `Kubernetes` `Prometheus` `AWS EKS` `TensorFlow` `OpenTelemetry`

</td>
<td width="50%" valign="top">

#### 🔍 [Screenshot Knowledge Engine](https://github.com/Jignesh141)

People screenshot 5–10 things daily — recipes, errors, flights, code — then never find them again. I built a system that fixes this.

A real-time file watcher triggers an async Kafka pipeline that classifies images via CLIP, extracts structured data through OCR + NLP (a recipe becomes ingredients + steps, an error becomes message + stack trace), and indexes everything into Elasticsearch with hybrid full-text + vector search.

**Result:** Natural language search across thousands of screenshots in milliseconds

`Java` `Spring Boot` `Python` `Kafka` `Elasticsearch` `CLIP` `Tesseract` `React` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📄 [NLP Document Intelligence Platform](https://github.com/Jignesh141)

Enterprise document processing at scale — automated text extraction, entity recognition, and semantic search across millions of unstructured documents.

Event-driven ingestion via Kafka + AWS Lambda handles async parsing, chunking, and embedding generation. Hybrid retrieval API combines BM25 keyword matching with vector similarity for search that actually understands context, not just keywords.

**Result:** 92% relevance accuracy · Sub-second query response with auto-completion

`Python` `Java` `Kafka` `AWS Lambda` `Elasticsearch` `sentence-transformers` `Docker` `Kubernetes`

</td>
<td width="50%" valign="top">

#### 💬 [Distributed Real-Time Messaging Platform](https://github.com/Jignesh141)

Designed for the problem most chat systems ignore — what happens when one server isn't enough.

Horizontally scalable architecture using Spring Boot microservices with WebSocket connections and Kafka consumer group partitioning for parallel message processing. MongoDB provides low-latency chat history retrieval. Deployed on Kubernetes with rolling updates for zero-downtime releases.

**Result:** 10K+ concurrent connections · Fault-tolerant ordered delivery · Zero-downtime deploys

`Java` `Spring Boot` `Kafka` `WebSockets` `MongoDB` `JWT` `Docker` `Kubernetes` `AWS`

</td>
</tr>
</table>

---

### Tech Stack

<details>
<summary><b>Languages</b></summary>
<br>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

</details>

<details>
<summary><b>Backend & Frameworks</b></summary>
<br>

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

</details>

<details>
<summary><b>Cloud, Infrastructure & DevOps</b></summary>
<br>

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

</details>

<details>
<summary><b>Databases, Messaging & Search</b></summary>
<br>

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![AWS SQS](https://img.shields.io/badge/AWS_SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)

</details>

<details>
<summary><b>Observability & Monitoring</b></summary>
<br>

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

</details>

<details>
<summary><b>AI / Machine Learning</b></summary>
<br>

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

</details>

---

### Currently

- 🔨 Building **event-driven microservices** and exploring **distributed consensus patterns** (Raft, Paxos)
- 📐 Deep-diving into **large-scale system design** — designing for fault tolerance, consistency tradeoffs, and horizontal scalability
- 🧪 Experimenting with **AI-powered infrastructure automation** — pushing the boundaries of what ML can do for DevOps and platform engineering
- 🎓 Completing MS in Computer Science at **Cal State Fullerton** (May 2026)
- 📬 Open to **Software Engineer / Backend Engineer** opportunities — [let's talk](mailto:jignesh.patel.cs141@gmail.com)

---

<p align="center">
  <i>"Any fool can write code that a computer can understand. Good programmers write code that humans can understand."</i> — Martin Fowler
</p>
