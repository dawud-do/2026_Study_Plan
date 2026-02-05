# 2026_Study_Plan
Study Plan specific to 2026



# 14-Week Backend Engineering Mastery Plan

## 🎯 Goal
Ready for Senior-level Java/AWS/Postgres/Spring Boot interviews in 3 months. Transitioning from "Java Developer" to "System Architect."

## 📚 Core Resources
- **Books:** 
  - *Designing Data-Intensive Applications (DDIA)* - Martin Kleppmann
  - *Kafka: The Definitive Guide* - Gwen Shapira et al.
  - *Designing Web APIs* - Brenda Jin et al.
- **Video/Hands-on:** 
  - FreeCodeCamp (fCC) YouTube Channel
  - AWS CDK Workshop (TypeScript)
  - Baeldung (Java/Spring Implementation)

---

## 🛠 Context Anchor (Save this for AI chats)
> I am an experienced Java Backend Developer on a 14-week study plan.
> **Goal:** Java/AWS/Postgres/Spring Boot interview ready.
> **Current Stack:** Java 17+, Spring Boot 3, Postgres.
> **Resources:** Kafka: The Definitive Guide, DDIA, Designing Web APIs.
> **Infrastructure:** Using TypeScript with AWS CDK.
> **The Plan:** 
> - Phase 1: Java Reactivation, Design Patterns, API Design. 
> - Phase 2: DDIA (Ch 1-7), TS/AWS CDK, Performance/JVM.
> - Phase 3: Kafka, System Design, Deployment.
> - Phase 4: Mock Interviews/LeetCode.

---

## 🗓 Phase 1: Reactivation & API Excellence (Weeks 1–4)
*Focus: Shaking off the rust and mastering modern Java 17/21.*

### Week 1: Java 17/21 & Concurrency
- **Theory:** Virtual Threads (Project Loom), Records, Sealed Classes.
- **Practice:** Implement a "Thread-Safe Cache" or "Producer-Consumer" using `VirtualThreads`.
- **Resource:** fCC Java Full Course (Review) + Baeldung on Project Loom.

### Week 2: Design Patterns & SOLID in Spring
- **Theory:** Strategy, Factory, Observer, and Decorator patterns.
- **Practice:** Build a "Payment Processing Module" using the **Strategy Pattern** to switch between providers (Stripe/PayPal).
- **Resource:** Baeldung: "Design Patterns in Spring".

### Week 3: Professional API Design
- **Theory:** Book: *Designing Web APIs* (All).
- **Practice:** Refactor the Payment Module to include Idempotency Keys, Cursor Pagination, and Global Exception Handling.
- **Resource:** *Designing Web APIs* (O'Reilly).

### Week 4: Postgres Deep Dive & Spring Data JPA
- **Theory:** Indexing strategies (B-Tree vs GIN), Transaction Isolation levels.
- **Practice:** Connect Spring Boot to Postgres via Docker. Use `EXPLAIN ANALYZE` on complex queries.
- **Resource:** fCC PostgreSQL Course.

---

## 🗓 Phase 2: Data Intensity & Infra-as-Code (Weeks 5–8)
*Focus: Scaling systems and managing AWS via TypeScript.*

### Week 5: DDIA Foundations & Storage
- **Theory:** Book: *DDIA* (Ch 1–3). Understanding LSM-Trees vs. B-Trees.
- **Focus:** Reliability, Scalability, and Maintainability.

### Week 6: TypeScript & AWS CDK
- **Theory:** fCC TypeScript Course (Interfaces, Generics).
- **Practice:** Set up AWS Account. Use **TypeScript CDK** to deploy a VPC, RDS (Postgres), and an S3 Bucket.
- **Resource:** [cdkworkshop.com](https://cdkworkshop.com/).

### Week 7: DDIA Distributed Data
- **Theory:** Book: *DDIA* (Ch 5–7). Replication, Partitioning, and Transactions.
- **Focus:** CAP Theorem vs. PACELC. Why "Eventual Consistency" is a trade-off.

### Week 8: Performance & JVM Tuning
- **Theory:** GC Algorithms (G1GC vs. ZGC), Heap Dump Analysis.
- **Practice:** Load test the Spring app using JMeter/Locust. Use Spring Boot Actuator for metrics.

---

## 🗓 Phase 3: Event-Driven Architecture (Weeks 9–12)
*Focus: High-throughput messaging and System Design.*

### Week 9: Kafka Fundamentals
- **Theory:** Book: *Kafka: The Definitive Guide* (Ch 1–4).
- **Practice:** Set up local Kafka/Zookeeper via Docker Compose. Write a simple Java Producer/Consumer.

### Week 10: Advanced Kafka & Stream Processing
- **Theory:** Book: *Kafka: The Definitive Guide* (Ch 6, 11). Exactly-once delivery.
- **Practice:** Implement "Spring Cloud Stream" to process data from a Kafka topic.

### Week 11: High-Level System Design
- **Theory:** fCC System Design Interview Course.
- **Practice:** Design "Uber" or "Netflix" on a whiteboard (Excalidraw).
- **Resource:** DDIA Ch 10-12 (Batch & Stream Processing).

### Week 12: The "Big Demo" Deployment
- **Practice:** Use **TS CDK** to deploy the full stack to AWS ECS (Fargate). 
- **Stack:** Spring Boot App -> Kafka -> Postgres (RDS).

---

## 🗓 Phase 4: Interview Sprint (Weeks 13–14)
*Focus: Speed, Logic, and Soft Skills.*

### Week 13: Behavioral & System Mocking
- **Task:** Prepare 5 "STAR" method stories.
- **Practice:** Mock System Design sessions focusing on your O'Reilly book knowledge.

### Week 14: LeetCode & Final Review
- **Task:** Top 50 Interview Questions (Arrays, Strings, HashMaps, Trees).
- **Task:** Re-read the "Summary" sections of DDIA and Kafka books.

---

## 🚀 The "Super-Project" Checklist
*Build this incrementally to showcase in interviews:*
- [ ] Spring Boot 3 API with Java 17 Records.
- [ ] PostgreSQL integration with optimized indexing.
- [ ] Kafka Producer/Consumer for async processing.
- [ ] Infrastructure defined entirely in TypeScript (AWS CDK).
- [ ] Dockerized local environment.
- [ ] Unit & Integration tests (JUnit 5/Testcontainers).
