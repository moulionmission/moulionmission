# Hi, I'm Chandu 👋

**Software Engineer | Distributed Systems & Core AI Infrastructure**

I design, build, and operate scalable cloud-native microservices, fault-tolerant distributed systems, and enterprise AI retrieval pipelines. With a strong foundation in distributed consensus, asynchronous event-driven streaming, and practical industry experience, I focus on sub-second latency, zero-data-loss resilience, and production-grade software engineering.

---

## 🎯 About Me

- 🎓 **M.S. Computer Science** — University of Florida | GPA: 3.79/4.0
- 💼 **Software Developer** @ University of Florida | Ex-**Software Engineer** @ HCL Technologies
- 📍 Based in Gainesville, FL
- 🔬 Published research on encrypted file systems (ICET 2024)

I am targeting **Software Engineer, Distributed Systems Engineer, and AI Systems / Core AI** roles where I can apply my expertise in high-throughput backends, cloud architectures, and scalable AI infrastructure.

---

## 🚀 Flagship Projects

### 1. ⚡ [Distributed Key-Value Engine (Raft Consensus)](https://github.com/moulionmission/raft-kv-engine)
> **Resilient, fault-tolerant distributed key-value store in Go implementing the Raft consensus protocol across a multi-node cluster.**
- **Consensus & Replication:** Implemented core Raft state machine replication, randomized election timeouts, and safe log commitment across a 5-node cluster.
- **Chaos-Tested Networking:** Designed a custom socket networking layer capable of simulating packet drops, network partitions, and latency under **50+ chaos testing scenarios**.
- **Concurrency & Throughput:** Resolved critical write-concurrency race conditions under high synthetic load, boosting cluster write throughput by **25%**.
- **Tech Stack:** `Go` • `Raft Consensus` • `TCP Sockets` • `Distributed Systems` • `Chaos Testing`

---

### 2. 🧠 [AI-Powered Retrieval & Clinical Data Ingestion Platform](https://github.com/moulionmission/clinical-rag-stream)
> **High-throughput event streaming and RAG retrieval pipeline for unstructured clinical records.**
- **Event-Driven Scale:** Orchestrated distributed streaming pipelines via **Apache Kafka**, processing **15,000+ events/sec** under peak loads.
- **Privacy & AI Governance:** Automated PII/PHI data masking, schema validation, and boundary access rules ensuring strict compliance with AI governance guidelines.
- **Sub-Second RAG Retrieval:** Integrated hybrid vector search (Pinecone) with document storage to serve real-time contextual embeddings to downstream LLMs.
- **Tech Stack:** `Python` • `FastAPI` • `Apache Kafka` • `Pinecone (Vector DB)` • `LangChain` • `Docker`

---

### 3. ☁️ [Azure Cloud-Native Data Sync & Analytics Engine](https://github.com/moulionmission/azure-enterprise-datasync)
> **Asynchronous multi-format enterprise file processing engine on Azure Web Apps and serverless Azure Functions.**
- **Enterprise Throughput:** Architected an asynchronous data synchronization engine in **C#/.NET Core**, reliably processing **500,000+ enterprise files daily**.
- **Zero-Trust Security:** Built token validation and custom claim inspection gateways integrating **Microsoft Entra ID (Azure AD)** and **Azure Key Vault**.
- **Automated CI/CD:** Engineered automated GitHub Actions pipelines running static analysis, unit/integration testing, and vulnerability scans, cutting release cycles by **40%**.
- **Tech Stack:** `C#` • `.NET Core` • `Azure Functions` • `Azure Key Vault` • `Entra ID` • `GitHub Actions`

---

### 4. 📡 [Remote Telemetry & Event Ingestion Platform](https://github.com/moulionmission/remote-telemetry-platform)
> **High-throughput streaming telemetry pipeline over a 3-broker Kafka cluster with strategic Redis caching and PostgreSQL.**
- **Fault-Tolerant Streaming:** Built a streaming telemetry pipeline handling real-time data over a **3-broker Kafka cluster** configured with partition-aware routing, idempotency, and dead-letter queues.
- **40% Latency Reduction:** Cut streaming data access latency by **40% (250ms to 150ms)** by integrating a strategic Redis caching layer and optimizing consumer thread pooling under **10M-event load tests**.
- **Idempotency & Resilience:** Enforced exactly-once processing semantics using atomic Redis locks (SETNX) and automated poison-pill recovery via DLQ routing.
- **Tech Stack:** `Java` • `Spring Boot` • `Apache Kafka (3 Brokers)` • `Redis` • `PostgreSQL` • `Docker`

---

## 💡 Technical Skills

### 💻 Languages
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### ⚙️ Distributed Systems & Backend
![.NET Core](https://img.shields.io/badge/.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square&logoColor=white)

### 🤖 AI, LLM & Retrieval Systems
![LLMs](https://img.shields.io/badge/LLMs-0D96F6?style=flat-square&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20Architecture-FF6B6B?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone%20Vector%20DB-000000?style=flat-square&logoColor=white)
![Autonomous Agents](https://img.shields.io/badge/Autonomous%20Agents-7B2CBF?style=flat-square&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### ☁️ Cloud & Infrastructure
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![AKS](https://img.shields.io/badge/AKS%20(Kubernetes)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Azure Functions](https://img.shields.io/badge/Azure%20Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### 🔒 Security & Governance
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft%20Entra%20ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-2E7D32?style=flat-square&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure%20Key%20Vault-0078D4?style=flat-square&logoColor=white)

### 🗄️ Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Microsoft SQL Server](https://img.shields.io/badge/SQL%20Server-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white)

### 🛠️ DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## 📫 Let's Connect

- **Email:** [chandramoulidasari616@gmail.com](mailto:chandramoulidasari616@gmail.com)
- **LinkedIn:** [linkedin.com/in/chandramoulidasari17](https://www.linkedin.com/in/chandramoulidasari17/)
- **GitHub:** [github.com/moulionmission](https://github.com/moulionmission)

---

<div align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-brightgreen" alt="Status: Open to Opportunities">
</div>
