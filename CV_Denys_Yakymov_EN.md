# Denys Yakymov

**Cybersecurity Engineer | Full-Stack Developer | Security DevOps**

yakden@gmail.com | [github.com/yakden](https://github.com/yakden)

---

## Professional Summary

Security-focused full-stack engineer with deep expertise in offensive and defensive cybersecurity, OSINT, and secure systems architecture. Proven track record building production-grade platforms from scratch — spanning backend microservices, frontend applications, AI/ML pipelines, and hardened infrastructure. Combines hands-on penetration testing and vulnerability research with the ability to architect, develop, and deploy complex distributed systems end-to-end. Fluent in building GDPR/RODO-compliant applications for the European market.

---

## Core Competencies

| Domain | Capabilities |
|--------|-------------|
| **Cybersecurity** | Penetration testing (OWASP), OSINT, vulnerability research, security auditing, threat modeling, fraud detection systems, network protocol analysis |
| **Full-Stack Development** | End-to-end platform development, microservices architecture, multi-tenant SaaS, REST/GraphQL APIs, real-time systems (WebSocket) |
| **AI/ML & Computer Vision** | Object detection (YOLOv8), face recognition, NLP pipelines, document intelligence (OCR, NER, VLM), generative AI integration |
| **Infrastructure & DevOps** | Infrastructure as Code (Terraform, Ansible), container orchestration (Docker), monitoring (Prometheus/Grafana), SSO, WAF, zero-trust security |
| **Telecom & Protocols** | SMPP 3.4/5.0 gateways, SIP/VoIP systems, RTSP video streaming, WebRTC P2P networking, ONVIF device management |

---

## Technical Stack

**Languages:** Go, Python, TypeScript/JavaScript, C++

**Backend:** Django / Django Ninja, FastAPI, Fastify 5, NestJS, Flask, Gin, Express.js, Asterisk PBX

**Frontend:** React 19, Next.js 14-16, Vue 3, React Native/Expo, Three.js, Tailwind CSS, Material-UI

**Databases:** PostgreSQL, MongoDB, Neo4j, Elasticsearch, ClickHouse, Redis, SQLite, Memgraph, Qdrant

**DevOps & Infrastructure:** Docker, Kubernetes, Terraform/OpenTofu, Ansible, ArgoCD, Prometheus, Grafana, OpenTelemetry, Jaeger, CrowdSec, Authentik SSO, Kong API Gateway, Certbot, Nginx, GitHub Actions CI/CD

**AI/ML:** YOLOv8, TensorFlow.js, Google Gemini 2.0, Stable Diffusion, Florence-2, GLiNER, Llama-3, FAISS, Surya OCR, DeepSORT

**Security Tools:** Shodan, OSINT frameworks, Nmap, Cameradar, OWASP methodology, custom exploit development

**Protocols:** SMPP 3.4/5.0, SIP, RTSP, WebRTC, WebSocket, ONVIF, HTTP/2

---

## Key Projects

### WAW365.com — B2B Auto Parts Marketplace
**Go + Django Ninja + Next.js + PostgreSQL + ClickHouse + Manticore Search**
- Architected and built a high-load multi-tenant B2B marketplace connecting auto parts suppliers and buyers
- Implemented async task processing (Celery), real-time WebSocket messenger, and VIN cross-referencing engine
- Conducted comprehensive security audit with 79 remediations across 11 security domains
- Deployed with Docker Compose, Certbot SSL, and production monitoring

### Enterprise SMPP SMS Gateway Platform
**Python + asyncio + Redis + Kafka + PostgreSQL**
- Built SMPP 3.4/5.0 compliant SMS gateway with intelligent routing and load balancing
- Implemented real-time fraud detection engine, billing system, and admin panel
- Designed for high-throughput message processing with async I/O architecture

### AI-Powered IP Camera Surveillance System
**FastAPI + React + YOLOv8 + DeepSORT + WebSocket**
- Developed AI surveillance platform with real-time face detection, recognition, and object tracking
- Integrated YOLOv8 models (6MB-130MB) with deep-sort-realtime for persistent tracking
- Built GDPR/RODO-compliant video analytics with configurable retention policies

### DocPipeline — Multi-Agent Document Intelligence
**FastAPI + Celery + RabbitMQ + PostgreSQL + Memgraph + Qdrant**
- Designed multi-agent pipeline: OCR (Surya) -> VLM (Florence-2) -> NER (GLiNER + Llama-3) -> Entity Resolution (FAISS)
- Optimized for 8GB VRAM GPU constraints with model scheduling and memory management
- Built knowledge graph storage in Memgraph with vector search in Qdrant

### Unified Infrastructure Stack
**Terraform/OpenTofu + Ansible + Docker + Prometheus/Grafana**
- Built three-layer IaC pipeline: provisioning (Hetzner Cloud) -> configuration (Ansible) -> deployment (Docker Compose)
- Integrated Cloudflare DNS, Mailcow email, Authentik SSO, and CrowdSec WAF
- Automated full-stack deployment with monitoring, alerting, and security hardening

### VoIP Server with AI Voice Assistant
**Python + Asterisk + Google Gemini API**
- Built SIP server with AI-powered voice assistant using Gemini for real-time conversational AI
- Integrated calendar management, call recording, ticket system, and audio processing pipeline

### Remote Desktop Access System
**Go + React + WebRTC + WebSocket + DXGI**
- Developed P2P mesh remote access solution with WebRTC for video/audio streaming
- Implemented Windows screen capture via DXGI, TCP tunneling, and JWT authentication
- Built web-based admin panel with user management and session monitoring

### Crypto Signal Trading System
**FastAPI + Next.js 14 + PostgreSQL + Redis Pub/Sub + Binance WebSocket + Prometheus/Grafana**
- Architected 15-microservice event-driven platform aggregating 10+ real-time data sources (Reddit, Telegram, Twitter/X, on-chain analytics, Binance WebSocket, CoinGecko, RSS feeds)
- Built signal engine with 30-second analysis cycles scoring trading opportunities 0-100 across 4 dimensions (mentions, sentiment, volume, token age)
- Implemented safety-first trading with kill switch, paper trading mode, DCA entry, automatic stop-loss/take-profit, and CCXT exchange integration (Binance, ByBit, OKX)
- Developed real-time Next.js dashboard with 3D visualizations (Three.js), P&L tracking, and admin panel with service health monitoring

### EcomPilot PL — Multi-Channel Commerce SaaS
**TypeScript/Fastify 5 + Next.js 14 + React Native/Expo + NATS JetStream + PostgreSQL + ClickHouse + Elasticsearch + Kubernetes**
- Designed enterprise SaaS platform with 17 microservices + 3 frontend apps (web, mobile, admin) in Turborepo monorepo with Drizzle ORM
- Integrated 8 marketplaces (Allegro, Vinted, OLX, Etsy, Amazon, eBay, Empik, Erli) with unified listing, inventory, and order management
- Implemented GDPR Privacy API (data export, deletion, consent management), KSeF Polish tax compliance, and Stripe billing with tiered pricing
- Deployed with Kubernetes, ArgoCD GitOps, Terraform AWS, distroless Docker images, OpenTelemetry tracing, Kong API Gateway, and HashiCorp Vault

### SocialBoost — SMM Reseller SaaS Platform
**Flask + PostgreSQL + Redis + Stripe + Nginx + HAProxy + Prometheus/Grafana + ELK**
- Built enterprise reseller panel with 86+ API endpoints, dynamic tiered pricing engine, and external provider API integration
- Implemented 3-level affiliate referral tree with automatic commission calculation, white-code invite system, and campaign management
- Integrated Stripe PaymentIntent + Coinbase Commerce for fiat and crypto payments with HMAC webhook signature verification
- Deployed with multi-stage Docker, HAProxy load balancing, ELK log aggregation, Prometheus monitoring, and full CI/CD (GitHub Actions with Bandit/Trivy security scanning)

### NumPulse — Phone Number Analytics SaaS
**FastAPI + React + Neo4j + PostgreSQL + ClickHouse**
- Scraped 55+ SMS provider sites with distributed crawlers
- Built 7-stage NLP processing pipeline for message classification and entity extraction
- Constructed relationship graphs in Neo4j with REST/GraphQL API exposure

---

## Security Expertise

- **Penetration Testing:** OWASP methodology, web application security assessment, API security testing
- **OSINT & Reconnaissance:** Shodan-based asset discovery, RTSP camera enumeration (Cameradar), network fingerprinting
- **Vulnerability Research:** IoT/IP camera exploit development (Dahua, D-Link), protocol-level vulnerability analysis (RTSP, SIP, SMPP)
- **Security Auditing:** Comprehensive platform audits (79-fix WAW audit covering authentication, authorization, input validation, cryptography, session management, logging, CORS, rate limiting, dependency scanning, data protection, error handling)
- **Fraud Detection:** Real-time SMPP message fraud detection with pattern analysis and anomaly scoring
- **Network Security:** Protocol emulation for security testing, async network service analysis, port scanning
- **Compliance:** GDPR/RODO implementation, data retention policies, consent management, PII protection

---

## Infrastructure & DevOps

- **IaC:** Terraform/OpenTofu for Hetzner Cloud provisioning, Ansible playbooks for server configuration
- **Containerization:** Docker Compose orchestration for 15+ production services
- **Monitoring:** Prometheus metrics collection, Grafana dashboards, alerting pipelines
- **Security:** CrowdSec intrusion prevention, Authentik SSO, Certbot automated TLS, rate limiting
- **CI/CD:** GitHub Actions workflows, automated testing, deployment automation
- **DNS & CDN:** Cloudflare DNS management, edge caching, DDoS protection

---

## Additional

- **Languages:** Ukrainian (native), Russian (fluent), English (professional), Polish (working proficiency)
- **Certifications & Research:** OSINT methodology, OWASP Top 10, IoT security research
- **Open Source:** Contributor to security tooling, maintainer of cameradar fork for RTSP camera discovery
- **Location:** Poland (EU work authorization)
