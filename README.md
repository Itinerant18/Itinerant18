<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:03001e,40:7303c0,80:ec38bc,100:fdeff9&height=240&section=header&text=Aniket%20Karmakar&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Junior%20Executive%20Engineer%20—%20R%26D%20%40%20Security%20Engineers%20Pvt.%20Ltd.&descAlignY=60&descAlign=50&descSize=17" width="100%" alt="Aniket Karmakar Header" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&pause=1000&color=EC38BC&center=true&vCenter=true&width=800&height=45&lines=Junior+Executive+Engineer+%E2%80%94+R%26D+%40+SEPLe;Distributed+Systems+%7C+Go+%2B+Kafka+%2B+Redis+Cluster;Designing+Autonomous+AI+Agents+%26+Multi-Agent+Systems;Enterprise+Multilingual+RAG+Pipelines+%2B+RAPTOR;IoT+Platform+Architect+%7C+ThingsBoard+%2B+ESP32;Full-Stack+%7C+Next.js+16+%2B+React+19+%2B+Cloudflare+DO" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/itinerant018)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Itinerant18)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:itinerant018@gmail.com)
[![Location](https://img.shields.io/badge/Kolkata%2C%20India-7303c0?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Kolkata)

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Itinerant18&color=EC38BC&style=flat-square&label=Profile+Views)](https://github.com/Itinerant18)
[![Followers](https://img.shields.io/github/followers/Itinerant18?style=flat-square&color=7303c0&label=Followers&logo=github)](https://github.com/Itinerant18?tab=followers)
[![Active Since](https://img.shields.io/badge/Active%20Since-Nov%202021-EC38BC?style=flat-square)](https://github.com/Itinerant18)
[![Public Repos](https://img.shields.io/badge/Public%20Repos-46-7303c0?style=flat-square&logo=github&logoColor=white)](https://github.com/Itinerant18?tab=repositories)

</div>

---

## 👨‍💻 About Me

<table>
<tr>
<td valign="top" width="58%">

```yaml
name: Aniket Karmakar
role: Junior Executive Engineer — R&D
company: Security Engineers Pvt. Ltd. (SEPLe)
base: Kolkata, India 🇮🇳

focus_areas:
  ▸ High-throughput distributed backends (Go, Kafka, Redis H3)
  ▸ Autonomous multi-agent AI & custom MCP servers
  ▸ Enterprise RAG pipelines (RAPTOR, HyDE, pgvector)
  ▸ Industrial IoT gateways, telemetry & device provisioning
  ▸ Cross-platform full-stack systems (Next.js, Flutter, Cloudflare)

currently_exploring:
  ▸ Multi-Agent orchestration & tool-use workflows
  ▸ Triton ML model serving & graph-based routing
  ▸ Edge computing with Cloudflare Durable Objects
```

</td>
<td valign="top" width="42%" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300" alt="Coding Workspace" />

</td>
</tr>
</table>

---

## 🚀 Featured Engineering Projects

### 1. [Vahnly](https://github.com/Itinerant18/Vahnly) — Real-Time Driver-Dispatch Platform
> **Real-time scheduled & on-demand driver dispatch engine for vehicle owners in Kolkata.**
- **Architecture:** High-throughput Go backend ingesting driver telemetry streams over gRPC, indexing spatial availability in **Redis H3 res-8 spatial cells**, and publishing events to **Kafka (KRaft)**.
- **Optimization:** Hungarian and Greedy order matching with **Triton Inference Server** (XGBoost ETA correction) wrapped in a `sony/gobreaker` circuit breaker with contraction-hierarchy road-graph fallback.
- **Client Surfaces:** Dual Next.js 16 + Capacitor rider and driver applications with WebSocket fan-out and a Vite admin control dashboard.
- **Stack:** `Go 1.25` · `PostgreSQL / PostGIS` · `Redis 7.2 Cluster` · `Kafka` · `Triton` · `Next.js 16` · `Docker` · `K8s / KEDA`

---

### 2. [SEPLE Tender Agent](https://github.com/Itinerant18/Seple-Tender-Agent) — Autonomous Procurement Intelligence
> **Production decision-support system automating discovery, parsing, and semantic matching of government bids.**
- **MCP Tool-Use:** Features a custom **Model Context Protocol (MCP)** server bridge (`tender_mcp/server.py`) exposing the live PostgreSQL tender database directly to AI models as native tools.
- **Semantic Reasoning:** LLM reasoning pipeline matching ambiguous procurement contracts (e.g. mapping "video surveillance" to CCTV portfolios without keyword overlap) with deterministic regex fallbacks (`fallback-regex`).
- **Resilient Pipeline:** Automated scrapers built with Playwright navigating WAF-protected state portals (GeM, CPPP, TenderTiger) with multi-channel Slack/email alert digests.
- **Stack:** `Python` · `FastAPI` · `PostgreSQL` · `OpenAI GPT-4o` · `MCP` · `Playwright` · `React` · `Docker Compose`

---

### 3. [Dexter Tech Support AI](https://github.com/Itinerant18/Swacth360_bot) — Multilingual Enterprise RAG Assistant
> **Industrial IoT & HMS control panel technical support assistant deployed for field engineers and plant operators.**
- **21-Node RAG Pipeline:** Implements recursive **RAPTOR** hierarchical cluster indexing, **HyDE** query expansion, and cross-encoder passage reranking across 31 PostgreSQL migrations.
- **Two-Tier Caching:** Tier-1 exact-match cache via Upstash Redis (<5ms latency) + Tier-2 semantic cache via `pgvector` cosine similarity (threshold ≥ 0.90, <50ms latency).
- **Multilingual & Visual:** Real-time conversational translation (English, Hindi, Bengali) with dynamic on-the-fly **Mermaid.js** wiring diagram generation in chat.
- **Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Flutter` · `Supabase pgvector` · `Pinecone` · `OpenAI GPT-4o` · `Upstash Redis`

---

### 4. [Urban Assist](https://github.com/Itinerant18/Urban-assist) — UK Home Services Marketplace
> **Full-lifecycle service booking marketplace connecting UK homeowners with vetted local professionals.**
- **Monorepo Architecture:** Structured `pnpm` monorepo hosting three independent Next.js 14 applications (`customer`, `provider`, `admin`) sharing typed `@urban-assist/ui`, `db`, and `domain` packages.
- **Reliable State & Payouts:** Supabase PostgreSQL with strict RLS policies, Stripe payment and webhook integration, Upstash Redis rate limiting, and scheduled edge function cascading via `pg_net` and Vault secrets.
- **Stack:** `Next.js 14` · `TypeScript` · `Supabase` · `Stripe` · `Upstash Redis` · `Tailwind CSS` · `pnpm workspaces`

---

### 5. [Bank Telemetry Outage Warning & Diagnostic System](https://github.com/Itinerant18/Data_scrapping_thgingsboard_ml-intern) — Critical Infrastructure Analytics
> **Predictive 24-hour power outage forecasting and diagnostic ticket generation for 135 commercial bank branch gateways.**
- **Deterministic Reliability:** Fail-closed deterministic typed ticket renderer (`ticket-policy-v1`) with Stage C field-level validator achieving 100% acceptance across frozen splits; non-deterministic LLMs disabled for safety.
- **Machine Learning:** Calibrated LightGBM model with Platt scaling achieving **89.66% incident recall** with a **22.6-hour mean lead time** before power loss events.
- **Stack:** `Python` · `LightGBM` · `ThingsBoard IoT` · `Scikit-learn` · `PyTorch` · `Docker` · `AWS EC2/ECS`

---

### 6. [Serendipity](https://github.com/Itinerant18/Serendipity) — Multi-Platform Marketplace Ecosystem
> **Complete e-commerce platform spanning Web and Mobile with dual database architecture.**
- **Dual-Database Pattern:** Segregated Supabase PostgreSQL instances separating customer order flows from multi-tenant seller inventory management.
- **Real-Time FSM:** Finite State Machine managing order lifecycles (`pending → confirmed → shipped → delivered`) broadcasting live status changes over private Socket.IO rooms.
- **Dual Payments:** Dual-integrated Razorpay (UPI / India) and Stripe (Global cards) checkout flows.
- **Stack:** `React 18` · `Expo 54 / React Native` · `Node.js / Express` · `Supabase` · `Redis` · `Socket.IO` · `Tailwind CSS 4`

---

### 7. [TicTac Match](https://github.com/Itinerant18/Tic-tac-toe) — Cloudflare Edge Matchmaking Game
> **Real-time mobile-first social gaming platform built entirely on Cloudflare edge serverless infrastructure.**
- **Actor Model on the Edge:** Orchestrated with Cloudflare **Durable Objects** — `MatchmakerDO` for lobby websocket queues and matchmaking, `RoomDurableObject` for transactional game boards, and `ConnectionDO` for live 1-on-1 chats.
- **Zero-Cold-Start DB:** Persisted with Cloudflare **D1** SQL database and integrated with Firebase Auth and Razorpay subscription plans.
- **Stack:** `Cloudflare Workers` · `Durable Objects` · `Cloudflare D1` · `React 19` · `Tailwind CSS 4` · `Vite`

---

### 8. [SWatch360](https://github.com/Itinerant18/SWatch360) — ThingsBoard Industrial IoT Client
> **Clean Architecture Flutter mobile application replacing desktop interfaces for IoT field engineers.**
- **Hardware Provisioning:** Direct on-site BLE (`flutter_esp_ble_prov`) and SoftAP Wi-Fi provisioning for ESP32 microcontroller hardware.
- **Interactive Dashboards:** Full ThingsBoard IoT dashboard rendering with bidirectional JavaScript-to-Dart bridge, FCM push notifications, and alarm acknowledgement.
- **Stack:** `Flutter` · `Dart` · `ThingsBoard PE Client` · `BLoC` · `Hive` · `Firebase FCM` · `BLE`

---

### 9. [Pookies AI Zone](https://github.com/Itinerant18/pookies-ai-zone) — AI Tools Directory & Comparison
> **Cross-platform mobile directory curating 320+ AI tools with algorithmic side-by-side comparison.**
- **Automated Pipeline:** Daily GitHub Actions cron crawling ProductHunt, Futurepedia, and GitHub repos to enrich and upsert tools into a Convex real-time database.
- **Stack:** `React Native` · `Expo 54` · `TypeScript` · `Convex DB` · `FastAPI` · `Python` · `Clay Neumorphic UI`

---

### 10. [FinanceAI Advisor](https://github.com/Itinerant18/Financial-Advisor) — AI Financial Advisory Platform
> **Full-stack personal finance advisory platform with interactive KPI monitoring.**
- **Structured LLM Controller:** Express backend with custom system prompts generating actionable financial guidance paired with mock metric visualization.
- **Stack:** `React 18` · `TypeScript` · `Vite` · `Tailwind CSS` · `Express.js` · `OpenAI GPT-3.5 Turbo`

---

## 🛠️ Tech Stack

<div align="center">

### 🔤 Languages
[![Skills](https://skillicons.dev/icons?i=ts,js,go,python,dart,postgres,cpp,html,css&perline=9)](https://skillicons.dev)

### 🖥️ Frontend, Mobile & Edge
[![Skills](https://skillicons.dev/icons?i=react,nextjs,tailwind,flutter,vite,cloudflare,redux&perline=7)](https://skillicons.dev)

### ⚙️ Backend & Distributed Systems
[![Skills](https://skillicons.dev/icons?i=nodejs,express,fastapi,kafka,redis,graphql,nginx&perline=7)](https://skillicons.dev)

### 🗄️ Databases & Vector Stores
[![Skills](https://skillicons.dev/icons?i=postgres,supabase,sqlite,mongodb&perline=6)](https://skillicons.dev)
<br/>
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=for-the-badge&logo=timescale&logoColor=black)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare_D1-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

### 🤖 AI · Multi-Agent · RAG
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Model Context Protocol](https://img.shields.io/badge/MCP_Server-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![RAPTOR Indexing](https://img.shields.io/badge/RAPTOR_Hierarchical_RAG-7303c0?style=for-the-badge)
![Triton Server](https://img.shields.io/badge/NVIDIA_Triton-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)

### 📡 Industrial IoT & Hardware
[![Skills](https://skillicons.dev/icons?i=raspberrypi,arduino&perline=6)](https://skillicons.dev)
![ThingsBoard](https://img.shields.io/badge/ThingsBoard_IoT-1E88E5?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT_Protocol-660066?style=for-the-badge)
![ESP32](https://img.shields.io/badge/ESP32_BLE_%26_SoftAP-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

### ☁️ DevOps & Cloud
[![Skills](https://skillicons.dev/icons?i=docker,githubactions,aws,gcp,firebase,netlify,vercel,git&perline=8)](https://skillicons.dev)

</div>

---

## 🏛️ Architecture Mastery

<div align="center">

### ✅ Battle-Tested

![MVC](https://img.shields.io/badge/MVC_Architecture-✅-2ea44f?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API_Design-✅-2ea44f?style=flat-square)
![JWT](https://img.shields.io/badge/JWT_%2F_OAuth2-✅-2ea44f?style=flat-square)
![Spring Security](https://img.shields.io/badge/Spring_Security-✅-2ea44f?style=flat-square)
![RAG Pipelines](https://img.shields.io/badge/RAG_Pipelines-✅-2ea44f?style=flat-square)
![Semantic Search](https://img.shields.io/badge/Semantic_Search-✅-2ea44f?style=flat-square)
![LLM Orchestration](https://img.shields.io/badge/LLM_Orchestration-✅-2ea44f?style=flat-square)
![Docker](https://img.shields.io/badge/Docker_Compose-✅-2ea44f?style=flat-square)
![ThingsBoard IoT](https://img.shields.io/badge/ThingsBoard_IoT-✅-2ea44f?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT_Telemetry-✅-2ea44f?style=flat-square)
![SSR Next.js](https://img.shields.io/badge/SSR_Next.js-✅-2ea44f?style=flat-square)
![Component Architecture](https://img.shields.io/badge/Component_Architecture-✅-2ea44f?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector_%2F_Vector_DB-✅-2ea44f?style=flat-square)
![Redis Caching](https://img.shields.io/badge/Redis_Caching-✅-2ea44f?style=flat-square)
![Go gRPC](https://img.shields.io/badge/Go_gRPC-✅-2ea44f?style=flat-square)
![Kafka Event Bus](https://img.shields.io/badge/Kafka_Event_Bus-✅-2ea44f?style=flat-square)
![Cloudflare DO](https://img.shields.io/badge/Cloudflare_Durable_Objects-✅-2ea44f?style=flat-square)
![Flutter BLoC](https://img.shields.io/badge/Flutter_BLoC-✅-2ea44f?style=flat-square)

### 🔥 Currently Learning

![System Design](https://img.shields.io/badge/System_Design_HLD%2FLLD-75%25-EC38BC?style=flat-square)
![CAP Theorem](https://img.shields.io/badge/CAP_Theorem-55%25-EC38BC?style=flat-square)
![Kafka](https://img.shields.io/badge/Kafka_%2F_Event_Driven-40%25-EC38BC?style=flat-square)
![CQRS](https://img.shields.io/badge/CQRS_Pattern-30%25-7303c0?style=flat-square)
![Event Sourcing](https://img.shields.io/badge/Event_Sourcing-20%25-7303c0?style=flat-square)
![HyDE Retrieval](https://img.shields.io/badge/HyDE_Retrieval-55%25-EC38BC?style=flat-square)
![Multi-Agent AI](https://img.shields.io/badge/Multi--Agent_AI-35%25-7303c0?style=flat-square)
![LLM Fine-tuning](https://img.shields.io/badge/LLM_Fine--Tuning-25%25-7303c0?style=flat-square)
![Kubernetes](https://img.shields.io/badge/Kubernetes-28%25-7303c0?style=flat-square)
![Observability](https://img.shields.io/badge/Observability-35%25-7303c0?style=flat-square)
![Flutter Clean Arch](https://img.shields.io/badge/Flutter_Clean_Arch-48%25-EC38BC?style=flat-square)
![Triton Serving](https://img.shields.io/badge/Triton_Serving-40%25-EC38BC?style=flat-square)

</div>

---

## 📈 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats-tawny-pi-56.vercel.app/api?username=Itinerant18&theme=tokyonight&hide_border=true&show_icons=true&count_private=true&include_all_commits=true&rank_icon=github" alt="GitHub Stats" />
<img height="180" src="https://github-readme-stats-tawny-pi-56.vercel.app/api/top-langs/?username=Itinerant18&theme=tokyonight&hide_border=true&layout=compact&langs_count=8&card_width=340" alt="Top Languages" />

<br/><br/>

<img width="96%" src="https://streak-stats.demolab.com?user=Itinerant18&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&fire=EC38BC&ring=7303c0&sideLabels=EC38BC&currStreakLabel=EC38BC" alt="GitHub Streak" />

<br/>

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=Itinerant18&theme=tokyo-night&hide_border=true&area=true&color=EC38BC&line=7303c0&point=ffffff" alt="Contribution Graph" />

</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Itinerant18/Itinerant18/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Itinerant18/Itinerant18/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Itinerant18/Itinerant18/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

## ⚔️ Dev Character Sheet

<div align="center">

| Attribute | Character Stat |
| :--- | :--- |
| 🏷️ **Name** | Aniket Karmakar |
| ⚔️ **Class** | Systems Architect & Full-Stack Engineer |
| 🏢 **Guild** | Security Engineers Pvt. Ltd. (SEPLe) — R&D |
| 🗺️ **Server** | Kolkata, India 🇮🇳 |
| 🛡️ **Primary Weapons** | TypeScript · Go · Python · SQL · Flutter |
| 🔮 **Magic Specialization** | Multi-Agent AI · MCP Tooling · RAPTOR RAG Pipelines |
| ⚡ **Active Quest** | Autonomous Tender Discovery & Real-Time Telemetry Dispatch |
| 🎯 **Next Boss Fight** | Distributed Consensus · High-Scale K8s Event Sinks |

</div>

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/itinerant018)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Itinerant18)
[![Email](https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:itinerant018@gmail.com)

<br/>

![Quote](https://img.shields.io/badge/💬_%22Architecture_is_decisions_made_early_—_the_rest_is_just_code.%22-EC38BC?style=for-the-badge&labelColor=03001e&color=7303c0)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:fdeff9,40:ec38bc,80:7303c0,100:03001e&height=130&section=footer" width="100%" alt="Footer Wave" />

</div>
