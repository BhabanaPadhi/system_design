# system_design

📘 Foundations of System Design
    What is System Design?

    High-level vs. Low-level design

Functional vs. Non-functional requirements

How to Approach a System Design Interview

Clarifying scope

Requirement gathering

Estimations & constraints

🏗️ Scalability Concepts
Vertical vs. Horizontal Scaling

Load Balancing

Round-robin, Least Connections, IP Hashing

Global vs. Local Load Balancers

Caching

Client-side, CDN, Reverse Proxy, Application-side, Database caching

Cache Invalidation, LRU/LFU, Write-through/write-back

Database Design

RDBMS vs NoSQL

Sharding and Partitioning

Indexing, Denormalization

CAP theorem and PACELC theorem

☁️ Distributed Systems
Basics of Distributed Systems

Characteristics: Fault-tolerance, Availability, Consistency

Coordination and Consensus (e.g., Leader Election, Paxos, Raft)

Microservices Architecture

Benefits and Challenges

API Gateway, Service Mesh, Inter-Service Communication

Data Consistency

Strong vs Eventual Consistency

Quorum, Vector Clocks, CRDTs

Messaging & Queuing Systems

Kafka, RabbitMQ, SQS

At-least-once vs At-most-once vs Exactly-once delivery

⚙️ Performance & Reliability
Rate Limiting & Throttling

Circuit Breakers, Bulkheads, Retry Patterns

Monitoring & Observability

Logs, Metrics, Tracing (ELK, Prometheus, Grafana, OpenTelemetry)

📡 Networking & APIs
DNS, HTTP, HTTPS, TLS, TCP/IP

REST vs gRPC vs WebSockets

API Rate Limiting, Pagination, Idempotency

🧰 Key Infrastructure Components
Content Delivery Network (CDN)

Reverse Proxies (Nginx, HAProxy)

Object Storage (S3, Blob Storage)

💾 Storage & File Systems
Blob/File Storage vs Block Storage

Data Lakes, Warehouses

Cold vs Hot Storage

🔐 Security in System Design
Authentication vs Authorization

OAuth, JWT, SSO, API Keys

Data Encryption

In transit and at rest

DDoS Protection, Rate Limiting, WAFs

📊 Scalable System Examples
Design YouTube / Netflix (Video Streaming)

Design WhatsApp / Messenger (Chat Systems)

Design Twitter / Instagram Feed (Timeline Systems)

Design Uber (Real-time Geolocation & Matching)

Design Dropbox / Google Drive (File Storage & Sync)
