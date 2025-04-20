# Brahmand: The Universe of Possibilities

**Brahmand** is a distributed microservices-based platform designed to manage complex backend systems efficiently. It consists of several independent services that communicate seamlessly through RESTful APIs and event-driven architecture. Each service is modular, scalable, and can operate independently, making it a robust solution for modern backend systems.

## Core Services:

1. **Vishnu (Central Engine)**: Orchestrates service discovery, load balancing, and inter-service communication.
2. **Narad (Notification Service)**: Sends real-time notifications for @mentions, #tags, and user activities using WebSockets and async queues.
3. **Brahma (User Profile & Tagging Service)**: Handles user metadata, profile configurations, and tagging logic for @mentions and #hashtags.
4. **Chitragupta (Sentiment & Content Analysis)**: Analyzes user-generated content using sentiment detection and content moderation algorithms built in **Python** with **NLP** libraries like **TextBlob** and **Transformers**.
5. **Shakti (Interaction Service)**: Manages user interactions like likes, comments, shares, and reposts, ensuring concurrency and high-traffic performance.
6. **Durga (Ticketing Service)**: Automatically generates support tickets based on negative sentiment and flagged posts.
7. **Shiva (Escalation Service)**: Escalates unresolved tickets and breaches SLA (Service-Level Agreement), triggering priority responses.
8. **Krishna (Security & Privacy Service)**: Ensures secure service communication with encryption, token-based authentication, and API rate-limiting.

## Tech Stack Used:

- **Backend**:  
  - **Java** (Spring Boot) ![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white) for building robust, scalable microservices and backend systems.
  
- **API Communication**:  
  - **RESTful APIs** ![Rest API](https://img.shields.io/badge/REST-00B5E2?logo=swagger&logoColor=white) for communication between services.
  - **WebSockets** ![WebSockets](https://img.shields.io/badge/WebSockets-1D76B5?logo=websocket&logoColor=white) for real-time notifications and bidirectional communication.
  
- **Message Queues**:  
  - **Kafka** ![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white) for event-driven communication and handling asynchronous message queues.
  - **RabbitMQ** ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white) for reliable messaging between services, ensuring fault tolerance and system scalability.

- **Databases**:  
  - **PostgreSQL** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white) for relational database management and transactional operations.
  - **MySQL** ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) for service-specific storage needs.
  - **Redis** ![Redis](https://img.shields.io/badge/Redis-D82C2C?logo=redis&logoColor=white) for in-memory data storage, caching, and high-performance queries.
  
- **Security**:  
  - **OAuth 2.0** ![OAuth](https://img.shields.io/badge/OAuth-2.0-1E1E1E?logo=oauth&logoColor=white) for secure, token-based authentication and authorization.
  - **JWT (JSON Web Tokens)** ![JWT](https://img.shields.io/badge/JWT-000000?logo=jwt&logoColor=white) for secure communication between microservices.
  
- **Python** (For NLP & Sentiment Analysis) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)  
  - Used in **Chitragupta** for sentiment detection, content moderation, and user feedback analysis using **TextBlob**, **Transformers**, and other NLP libraries.

- **Deployment**:  
  - **Docker** ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) for containerization and creating portable, scalable service environments.
  - **Kubernetes** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) for orchestrating and managing the containerized services in a cloud-native environment.
  
- **DevOps**:  
  - **CI/CD** ![CI/CD](https://img.shields.io/badge/CI/CD-F05032?logo=gitlab&logoColor=white) pipelines for automated testing, deployment, and release management using **Jenkins**, **GitHub Actions**, or **GitLab CI**.
  
- **Logging & Monitoring**:  
  - **ELK Stack** (Elasticsearch, Logstash, Kibana) ![ELK Stack](https://img.shields.io/badge/ELK-005B6E?logo=elasticsearch&logoColor=white) for logging and monitoring application performance.
  - **Prometheus** ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white) and **Grafana** ![Grafana](https://img.shields.io/badge/Grafana-FF3333?logo=grafana&logoColor=white) for real-time monitoring and alerts.

## How to Use This Repo

### Cloning the Repo

To clone this repository, including all submodules, run:

```bash
git clone --recursive https://github.com/your-username/brahmand.git
