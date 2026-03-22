# Денис Якимов

**Инженер по кибербезопасности | Full-Stack разработчик | Security DevOps**

yakden@gmail.com | [github.com/yakden](https://github.com/yakden)

---

## Профессиональное резюме

Инженер с глубокой экспертизой в наступательной и оборонительной кибербезопасности, OSINT и архитектуре защищённых систем. Подтверждённый опыт создания production-ready платформ с нуля — от серверных микросервисов и фронтенд-приложений до AI/ML-конвейеров и защищённой инфраструктуры. Совмещаю практическое тестирование на проникновение и исследование уязвимостей с умением проектировать, разрабатывать и развёртывать сложные распределённые системы. Опыт создания GDPR/RODO-совместимых приложений для европейского рынка.

---

## Ключевые компетенции

| Область | Возможности |
|---------|------------|
| **Кибербезопасность** | Тестирование на проникновение (OWASP), OSINT, исследование уязвимостей, аудит безопасности, моделирование угроз, системы обнаружения мошенничества, анализ сетевых протоколов |
| **Full-Stack разработка** | Разработка платформ end-to-end, микросервисная архитектура, мультитенантный SaaS, REST/GraphQL API, системы реального времени (WebSocket) |
| **AI/ML и компьютерное зрение** | Детекция объектов (YOLOv8), распознавание лиц, NLP-конвейеры, интеллектуальная обработка документов (OCR, NER, VLM), интеграция генеративного AI |
| **Инфраструктура и DevOps** | Infrastructure as Code (Terraform, Ansible), оркестрация контейнеров (Docker), мониторинг (Prometheus/Grafana), SSO, WAF, zero-trust |
| **Телеком и протоколы** | SMPP 3.4/5.0 шлюзы, SIP/VoIP-системы, RTSP видеостриминг, WebRTC P2P, управление ONVIF-устройствами |

---

## Технологический стек

**Языки:** Go, Python, TypeScript/JavaScript, C++

**Backend:** Django / Django Ninja, FastAPI, Fastify 5, NestJS, Flask, Gin, Express.js, Asterisk PBX

**Frontend:** React 19, Next.js 14-16, Vue 3, React Native/Expo, Three.js, Tailwind CSS, Material-UI

**Базы данных:** PostgreSQL, MongoDB, Neo4j, Elasticsearch, ClickHouse, Redis, SQLite, Memgraph, Qdrant

**DevOps и инфраструктура:** Docker, Kubernetes, Terraform/OpenTofu, Ansible, ArgoCD, Prometheus, Grafana, OpenTelemetry, Jaeger, CrowdSec, Authentik SSO, Kong API Gateway, Certbot, Nginx, GitHub Actions CI/CD

**AI/ML:** YOLOv8, TensorFlow.js, Google Gemini 2.0, Stable Diffusion, Florence-2, GLiNER, Llama-3, FAISS, Surya OCR, DeepSORT

**Инструменты безопасности:** Shodan, фреймворки OSINT, Nmap, Cameradar, методология OWASP, разработка эксплойтов

**Протоколы:** SMPP 3.4/5.0, SIP, RTSP, WebRTC, WebSocket, ONVIF, HTTP/2

---

## Ключевые проекты

### WAW365.com — B2B маркетплейс автозапчастей
**Go + Django Ninja + Next.js + PostgreSQL + ClickHouse + Manticore Search**
- Спроектировал и разработал высоконагруженный мультитенантный B2B маркетплейс для поставщиков и покупателей автозапчастей
- Реализовал асинхронную обработку задач (Celery), WebSocket-мессенджер в реальном времени, движок кросс-референсов по VIN
- Провёл комплексный аудит безопасности с 79 исправлениями в 11 доменах безопасности
- Развернул с Docker Compose, Certbot SSL и production-мониторингом

### Enterprise SMPP SMS Gateway Platform
**Python + asyncio + Redis + Kafka + PostgreSQL**
- Разработал SMPP 3.4/5.0-совместимый SMS-шлюз с интеллектуальной маршрутизацией и балансировкой нагрузки
- Реализовал систему обнаружения мошенничества в реальном времени, биллинг и панель администратора
- Спроектировал для высокопропускной обработки сообщений с async I/O архитектурой

### AI-система видеонаблюдения на базе IP-камер
**FastAPI + React + YOLOv8 + DeepSORT + WebSocket**
- Разработал AI-платформу видеонаблюдения с детекцией лиц, распознаванием и трекингом объектов в реальном времени
- Интегрировал модели YOLOv8 (6-130 МБ) с deep-sort-realtime для устойчивого отслеживания
- Реализовал GDPR/RODO-совместимую видеоаналитику с настраиваемыми политиками хранения данных

### DocPipeline — мультиагентная обработка документов
**FastAPI + Celery + RabbitMQ + PostgreSQL + Memgraph + Qdrant**
- Спроектировал мультиагентный конвейер: OCR (Surya) -> VLM (Florence-2) -> NER (GLiNER + Llama-3) -> Entity Resolution (FAISS)
- Оптимизировал для GPU с 8 ГБ VRAM — планирование моделей и управление памятью
- Построил граф знаний в Memgraph с векторным поиском в Qdrant

### Unified Infrastructure Stack
**Terraform/OpenTofu + Ansible + Docker + Prometheus/Grafana**
- Создал трёхуровневый IaC-конвейер: провиженинг (Hetzner Cloud) -> конфигурация (Ansible) -> деплой (Docker Compose)
- Интегрировал Cloudflare DNS, Mailcow почту, Authentik SSO и CrowdSec WAF
- Автоматизировал полный деплой с мониторингом, алертингом и харденингом безопасности

### VoIP-сервер с AI голосовым ассистентом
**Python + Asterisk + Google Gemini API**
- Разработал SIP-сервер с AI-голосовым ассистентом на базе Gemini для диалогового AI в реальном времени
- Интегрировал управление календарём, запись звонков, систему тикетов и конвейер обработки аудио

### Система удалённого доступа
**Go + React + WebRTC + WebSocket + DXGI**
- Разработал P2P mesh-решение для удалённого доступа с WebRTC для видео/аудио стриминга
- Реализовал захват экрана Windows через DXGI, TCP-туннелирование и JWT-аутентификацию
- Создал веб-панель управления с контролем пользователей и мониторингом сессий

### Crypto Signal Trading System
**FastAPI + Next.js 14 + PostgreSQL + Redis Pub/Sub + Binance WebSocket + Prometheus/Grafana**
- Спроектировал event-driven платформу из 15 микросервисов, агрегирующую 10+ источников данных в реальном времени (Reddit, Telegram, Twitter/X, on-chain аналитика, Binance WebSocket, CoinGecko, RSS)
- Разработал signal engine с 30-секундными циклами анализа, скоринг торговых возможностей 0-100 по 4 измерениям (упоминания, сентимент, объём, возраст токена)
- Реализовал safety-first трейдинг: kill switch, paper trading, DCA-вход, автоматический stop-loss/take-profit, интеграция с биржами через CCXT (Binance, ByBit, OKX)
- Создал real-time дашборд на Next.js с 3D-визуализациями (Three.js), отслеживанием P&L и admin-панелью мониторинга сервисов

### EcomPilot PL — мультиканальный коммерческий SaaS
**TypeScript/Fastify 5 + Next.js 14 + React Native/Expo + NATS JetStream + PostgreSQL + ClickHouse + Elasticsearch + Kubernetes**
- Спроектировал enterprise SaaS-платформу: 17 микросервисов + 3 фронтенд-приложения (web, mobile, admin) в Turborepo монорепо с Drizzle ORM
- Интегрировал 8 маркетплейсов (Allegro, Vinted, OLX, Etsy, Amazon, eBay, Empik, Erli) с единым управлением листингами, инвентарём и заказами
- Реализовал GDPR Privacy API (экспорт данных, удаление, управление согласиями), KSeF налоговый комплаенс Польши, Stripe-биллинг с тарифными планами
- Развернул на Kubernetes с ArgoCD GitOps, Terraform AWS, distroless Docker-образами, OpenTelemetry трейсингом, Kong API Gateway и HashiCorp Vault

### SocialBoost — SaaS-платформа для SMM-реселлеров
**Flask + PostgreSQL + Redis + Stripe + Nginx + HAProxy + Prometheus/Grafana + ELK**
- Разработал enterprise reseller-панель с 86+ API endpoints, движком динамического тиранного ценообразования и интеграцией с внешним провайдером
- Реализовал 3-уровневую реферальную систему с автоматическим расчётом комиссий, системой white-code инвайтов и управлением кампаниями
- Интегрировал Stripe PaymentIntent + Coinbase Commerce для фиатных и крипто-платежей с HMAC-верификацией webhook-подписей
- Развернул с multi-stage Docker, HAProxy балансировкой, ELK-логированием, Prometheus-мониторингом и полным CI/CD (GitHub Actions с Bandit/Trivy security scanning)

### NumPulse — SaaS-аналитика телефонных номеров
**FastAPI + React + Neo4j + PostgreSQL + ClickHouse**
- Разработал скрейпинг 55+ сайтов SMS-провайдеров с распределёнными краулерами
- Построил 7-этапный NLP-конвейер для классификации сообщений и извлечения сущностей
- Создал графы связей в Neo4j с REST/GraphQL API

---

## Экспертиза в кибербезопасности

- **Тестирование на проникновение:** методология OWASP, оценка безопасности веб-приложений, тестирование безопасности API
- **OSINT и разведка:** обнаружение активов через Shodan, перечисление RTSP-камер (Cameradar), сетевой фингерпринтинг
- **Исследование уязвимостей:** разработка эксплойтов для IoT/IP-камер (Dahua, D-Link), анализ уязвимостей на уровне протоколов (RTSP, SIP, SMPP)
- **Аудит безопасности:** комплексные аудиты платформ (аудит WAW на 79 исправлений: аутентификация, авторизация, валидация ввода, криптография, управление сессиями, логирование, CORS, rate limiting, сканирование зависимостей, защита данных, обработка ошибок)
- **Обнаружение мошенничества:** детекция фрода в SMPP-сообщениях в реальном времени с анализом паттернов и скорингом аномалий
- **Сетевая безопасность:** эмуляция протоколов для тестирования безопасности, анализ асинхронных сетевых сервисов, сканирование портов
- **Комплаенс:** внедрение GDPR/RODO, политики хранения данных, управление согласиями, защита PII

---

## Инфраструктура и DevOps

- **IaC:** Terraform/OpenTofu для провиженинга Hetzner Cloud, Ansible playbooks для конфигурации серверов
- **Контейнеризация:** Docker Compose оркестрация 15+ production-сервисов
- **Мониторинг:** сбор метрик Prometheus, дашборды Grafana, конвейеры алертинга
- **Безопасность:** CrowdSec IPS, Authentik SSO, автоматизированный TLS Certbot, rate limiting
- **CI/CD:** GitHub Actions, автоматизированное тестирование, автоматизация деплоя
- **DNS и CDN:** управление DNS Cloudflare, edge-кеширование, DDoS-защита

---

## Дополнительно

- **Языки:** украинский (родной), русский (свободно), английский (профессиональный), польский (рабочий)
- **Сертификации и исследования:** методология OSINT, OWASP Top 10, исследования безопасности IoT
- **Open Source:** контрибьютор инструментов безопасности, мейнтейнер форка cameradar для обнаружения RTSP-камер
- **Локация:** Польша (разрешение на работу в ЕС)
