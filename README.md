<div align="center">
  <h1>Hi there, I'm Luis! 👋</h1>
  <p>Software Engineer | AI Models Enthusiast | Tech Innovator</p>
</div>

---

## 🧑‍💻 About Me

My personality is a mix of being an open-minded person and someone who deeply values achieving excellence as a professional and as an individual. 

I am driven by acquiring technical depth in the fields I work in—such as **software engineering** and **AI models**. Beyond the screen, I am always progressing in sports (especially soccer ⚽) and cultivating positive life experiences with my friends and colleagues.

Currently, I am **two semesters away from completing my Software Engineering degree at the Federal University of Ceará (UFC)**.

> [!TIP]
> 🧠 **Fun Fact:** This very README was generated based on a private **"second-brain"** repository of mine, where I describe my knowledge, values, and profile in depth in a highly modular manner!

> [!NOTE]
> ### My Core Values
> - 🎨 **Creativity**: Approaching problems with an open mind and innovative solutions.
> - ⭐ **Excellence**: Delivering high-quality, robust, and reliable systems.
> - ⚖️ **Ethics**: Building trust, transparency, and doing the right thing.

---

## 🚀 Featured Projects (Financial Ecosystem)

I have been building a comprehensive financial data ecosystem. Here are the core components highlighting some advanced patterns and architectural decisions:

### ⚙️ Architecture & Core Practices
Across the ecosystem, I employ modern backend and system design practices:
- **Containerization**: Extensive **Docker** usage for isolated, reproducible, and scalable environments.
- **Routing & Gateway**: **Traefik** acts as a central reverse proxy, handling TLS termination and dynamic service routing.
- **Security & Infrastructure**: Robust **Authentication** flows, leveraging **Supabase** for user management and non-domain tasks, keeping the core domain logic clean and focused.
- **Software Design**: Extensive use of **Dependency Injection** to build decoupled, testable, and highly maintainable services.

### 📊 `FinHubLTI` (Dashboard)
A modern, high-performance frontend dashboard for real-time financial data visualization.
- **Tech**: Angular 18, Tailwind CSS, Lightweight Charts.
- **Features**: Consumes live data via **gRPC-Web** (Server Streaming) for instantaneous chart updates, with a smart fallback to HTTPS polling.

### ⚡ `QuantWin API` (qData_service)
A robust real-time and historical market data platform serving ticks and OHLC bars.
- **Tech**: Python, FastAPI, gRPC, Envoy, Docker, Traefik.
- **Features**: Dual-interface providing a **REST API** for historical data and **native gRPC** for live streaming. Fully secured with JWT authentication and Traefik TLS. Employs strict dependency injection to separate business logic from protocol handling.

### 🗄️ `TimescaleDB Storage` (db)
A highly optimized time-series database architecture tailored for financial tick and OHLC data.
- **Tech**: PostgreSQL 16, TimescaleDB, Docker Compose.
- **Features**: Uses TimescaleDB hypertables with automatic chunk partitioning and compression policies (7-day intervals) for lightning-fast queries.

### 🌉 `mt5-websocket-bridge`
*Status: Planned some technical outlines.*
Designed to be the connecting bridge for MetaTrader 5, utilizing WebSocket protocols to feed real-time market data directly into the ecosystem.

---

<div align="center">
  <i>Building with <b>creativity</b>, focused on <b>excellence</b>, and guided by <b>ethics</b>.</i>
</div>
