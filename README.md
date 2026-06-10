# Hi, I'm Igor 👋

**Full-Stack Developer — TypeScript · Node.js · React** · Minsk (UTC+3) · open to remote

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/igor-roslik-ab5519205)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/igorroslik)
[![Email](https://img.shields.io/badge/Email-roslik2014%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:roslik2014@gmail.com)

Full-stack engineer with 4 years of experience building multi-tenant B2B SaaS end to end.
Recent focus — production AI/LLM engineering: inference cost control, reliability, semantic search.
Most of my work lives in private company orgs, so the green squares don't tell the whole story — highlights below.

---

## 🤖 AI sales-call analysis platform · 2025 → now

Multi-tenant B2B SaaS that scores sales calls with LLMs and turns them into coaching recommendations and manager training.

- Cut the cost of repeated LLM calls by ~10–15% with **Vertex AI context caching** — TTL management, cached-token accounting
- Built the **LLM-response robustness layer**: malformed-JSON recovery, provider fallbacks, circuit breakers, failure-metadata logging
- Developed the **call-scoring pipeline** and designed its second-generation subsystems: prompt versioning & overrides, scoring calibration cycle, re-analysis tooling
- Reworked the real-time **voice-training module** on the OpenAI Realtime API
- Hardened **BullMQ/Redis background jobs**: idempotency, retries, duplicate protection; extended CRM integrations (calls/deals/managers sync)

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Redis` `BullMQ` `Vertex AI / Gemini / OpenAI`

## 🛒 E-commerce dropshipping platform & marketplace · 2023 → now

Multi-tenant platform connecting thousands of retailers and suppliers; automates product import, inventory, orders, fulfillment, and payments across Shopify and WooCommerce.

- Built **semantic product search** over a ~500k-item catalog: all-MiniLM embeddings (384-dim), OpenSearch `knn_vector` index, hybrid neural query with fuzzy fallback
- Led **subscription billing** (Chargebee — plans, commissions, refunds, invoice reconciliation); built the **automated supplier-payouts** system
- Led **order processing & fulfillment**: routing line items to suppliers, fulfillment events, order timeline, tracking propagation
- Co-led the **Shopify** integration and developed the **WooCommerce** integration; near-real-time **inventory sync** with Redis-debounced webhook processing
- Built the **test infrastructure**: factories, MSW mocking, in-memory MongoDB/Redis/RabbitMQ containers

`Node.js` `Express` `TypeScript` `MongoDB` `RabbitMQ` `Redis` `OpenSearch` `React` `Vite`

---

## 🧰 Tech

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)

## 📄 Background

- **Sunmait Tech** — Full-Stack Developer, Jul 2022 → now: both projects above, plus an HR / personnel-management platform (Express, PostgreSQL, Socket.IO, React) in 2022–2023
- **Belarusian State University** — Information Security, Faculty of Radiophysics and Computer Technologies, 2017–2022
- **Languages:** English — B2 · Russian — native · Belarusian — native
