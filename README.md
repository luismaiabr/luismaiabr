<div align="center">
  <h1>👋 Luis Maia</h1>
  <p>📧 <a href="mailto:luismaiasombra@gmail.com">luismaiasombra@gmail.com</a></p>
  <p><i>Clique no idioma para expandir / Click a language to expand</i></p>
</div>

<details open>
<summary><img src="https://flagcdn.com/24x18/br.png" alt="Brasil" width="20" height="15" /> <b>Português</b></summary>

<br>

<div align="center">
  <h1>E aí, eu sou o Luis! 👋</h1>
  <p>Engenheiro de Software | Entusiasta de Modelos de IA | Inovador em Tecnologia</p>
</div>

---

## 🧑‍💻 Sobre Mim

Minha personalidade é uma mistura de mente aberta com alguém que valoriza profundamente alcançar a excelência como profissional e como indivíduo.

Sou movido por adquirir profundidade técnica nas áreas em que atuo — como **engenharia de software** e **modelos de IA**. Fora das telas, estou sempre evoluindo nos esportes (especialmente futebol ⚽) e cultivando experiências positivas com meus amigos e colegas.

Atualmente, estou a **dois semestres de concluir minha graduação em Engenharia de Software na Universidade Federal do Ceará (UFC)**.

> ### 🧠 Curiosidades
> 1. Este README foi gerado com base em um repositório privado **"second-brain"** meu, onde descrevo meu conhecimento, valores e perfil de forma manual e altamente modular!
> 2. Você sabia que é possível hospedar seu próprio Bitwarden legítimo de graça?

> ### 🧭 Meus Valores Fundamentais
> - 🎨 **Criatividade**: Abordar problemas com mente aberta e soluções inovadoras.
> - ⭐ **Excelência**: Entregar sistemas de alta qualidade, robustos e confiáveis.
> - ⚖️ **Ética**: Construir confiança, transparência e fazer a coisa certa.

---

## 🚀 Projetos em Destaque (Ecossistema Financeiro)

Tenho construído um ecossistema abrangente de dados financeiros. Aqui estão os componentes principais, destacando padrões avançados e decisões arquiteturais:

### ⚙️ Arquitetura & Práticas Centrais
Em todo o ecossistema, emprego práticas modernas de backend e design de sistemas:
- **Conteinerização**: Uso extensivo de **Docker** para ambientes isolados, reproduzíveis e escaláveis.
- **Roteamento & Gateway**: **Traefik** atua como proxy reverso central, gerenciando terminação TLS e roteamento dinâmico de serviços.
- **Segurança & Infraestrutura**: Fluxos robustos de **Autenticação**, utilizando **Supabase** para gerenciamento de usuários e tarefas fora do domínio, mantendo a lógica de domínio principal limpa e focada.
- **Design de Software**: Uso extensivo de **Injeção de Dependências** para construir serviços desacoplados, testáveis e altamente manuteníveis.

### 📊 `FinHubLTI` (Dashboard)
Um dashboard frontend moderno e de alto desempenho para visualização de dados financeiros em tempo real.
- **Tech**: Angular 18, Tailwind CSS, Lightweight Charts.
- **Funcionalidades**: Consome dados ao vivo via **gRPC-Web** (Server Streaming) para atualizações instantâneas nos gráficos, com fallback inteligente para polling HTTPS.

### ⚡ `QuantWin API` (qData_service)
Uma plataforma robusta de dados de mercado em tempo real e históricos, servindo ticks e barras OHLC.
- **Tech**: Python, FastAPI, gRPC, Envoy, Docker, Traefik.
- **Funcionalidades**: Interface dupla fornecendo uma **API REST** para dados históricos e **gRPC nativo** para streaming ao vivo. Totalmente protegida com autenticação JWT e TLS via Traefik. Utiliza injeção de dependências estrita para separar lógica de negócio do tratamento de protocolos.

### 🗄️ `TimescaleDB Storage` (db)
Uma arquitetura de banco de dados de séries temporais altamente otimizada para dados financeiros de ticks e OHLC.
- **Tech**: PostgreSQL 16, TimescaleDB, Docker Compose.
- **Funcionalidades**: Usa hypertables do TimescaleDB com particionamento automático de chunks e políticas de compressão (intervalos de 7 dias) para consultas ultrarrápidas.

### 🌉 `mt5-websocket-bridge`
*Status: Delineamento técnico planejado.*
Projetado para ser a ponte de conexão para o MetaTrader 5, utilizando protocolos WebSocket para alimentar dados de mercado em tempo real diretamente no ecossistema. Minha equipe e eu estamos rodando o MT5 em modo headless em um VPS Linux.

---

<div align="center">
  <i>Construindo com <b>criatividade</b>, focado em <b>excelência</b>, e guiado pela <b>ética</b>.</i>
</div>

</details>

<details>
<summary><img src="https://flagcdn.com/24x18/us.png" alt="USA" width="20" height="15" /> <b>English</b></summary>

<br>

<div align="center">
  <h1>Hi there, I'm Luis! 👋</h1>
  <p>Software Engineer | AI Models Enthusiast | Tech Innovator</p>
</div>

---

## 🧑‍💻 About Me

My personality is a mix of being an open-minded person and someone who deeply values achieving excellence as a professional and as an individual.

I am driven by acquiring technical depth in the fields I work in—such as **software engineering** and **AI models**. Beyond the screen, I am always progressing in sports (especially soccer ⚽) and cultivating positive life experiences with my friends and colleagues.

Currently, I am **two semesters away from completing my Software Engineering degree at the Federal University of Ceará (UFC)**.

> ### 🧠 Fun Facts
> 1. This very README was generated based on a private **"second-brain"** repository of mine, where I describe my knowledge, values, and profile in depth in a highly modular manner!
> 2. Did you know you can host your own, legitimate Bitwarden for free?

> ### 🧭 My Core Values
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
Designed to be the connecting bridge for MetaTrader 5, utilizing WebSocket protocols to feed real-time market data directly into the ecosystem. My team and I are running MT5 in headless mode in a Linux VPS.

---

<div align="center">
  <i>Building with <b>creativity</b>, focused on <b>excellence</b>, and guided by <b>ethics</b>.</i>
</div>

</details>
