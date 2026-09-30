<div align="center">

[![pt-BR](https://img.shields.io/badge/🇧🇷_Português-009739?style=for-the-badge)](./README.md)
[![en](https://img.shields.io/badge/🇺🇸_English-3C3B6E?style=for-the-badge)](./README_EN.md)

</div>

<div align="center">
  <h1>E aí, eu sou o Luis! 👋</h1>
  <p>Engenheiro de Software | Entusiasta de Modelos de IA | Inovador em Tecnologia</p>
  <p>📧 <a href="mailto:luismaiasombra@gmail.com">luismaiasombra@gmail.com</a></p>
</div>

---

## 🧑‍💻 Sobre Mim

Minha personalidade é uma mistura de mente aberta com alguém que valoriza profundamente alcançar a excelência como profissional e como indivíduo.

Sou movido por adquirir profundidade técnica nas áreas em que atuo — como **engenharia de software** e **modelos de IA**. Fora das telas, estou sempre evoluindo nos esportes (especialmente futebol ⚽) e cultivando experiências positivas com meus amigos e colegas.

Atualmente, estou a **dois semestres de concluir minha graduação em Engenharia de Software na Universidade Federal do Ceará (UFC)**.

> [!TIP]
> ### 🧠 Curiosidades
> 1. Este README foi gerado com base em um repositório privado **"second-brain"** meu, onde descrevo meu conhecimento, valores e perfil de forma altamente modular!
> 2. Você sabia que é possível hospedar seu próprio Bitwarden legítimo de graça?

> [!NOTE]
> ### Meus Valores Fundamentais
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
