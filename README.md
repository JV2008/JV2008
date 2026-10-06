<div align="center">

<!-- HERO BANNER -->
<a href="#-sobre-mim--about-me">
  <img src="assets/hero-banner.svg" alt="João Victor - Software Engineer & Full-Stack Developer Banner" width="100%" />
</a>

<br/>

<!-- ORIGINAL DUAL-LANGUAGE TAGLINE -->
<p align="center">
  <b>🇧🇷 Engenharia de software do core ao deploy: construindo aplicações web escaláveis, APIs robustas e soluções analíticas da modelagem relacional à IA aplicada.</b>
  <br/>
  <sub><b>🇺🇸 Software engineering from core to deploy: building scalable web applications, robust APIs, and data-driven systems from relational modeling to applied AI.</b></sub>
</p>

<!-- QUICK NAVIGATION -->
<p align="center">
  <a href="#-sobre-mim--about-me"><code>Sobre Mim / About</code></a> •
  <a href="#-vitrine-de-projetos--featured-projects"><code>Projetos / Projects</code></a> •
  <a href="#-stack-tecnol%C3%B3gica--tech-stack"><code>Tech Stack</code></a> •
  <a href="#-linha-do-tempo--technical-journey"><code>Evolução / Journey</code></a> •
  <a href="#-estat%C3%ADsticas--github-analytics"><code>Stats</code></a> •
  <a href="#-contato--get-in-touch"><code>Contato / Contact</code></a>
</p>

</div>

---

### 👨‍💻 Sobre Mim / About Me

<table width="100%" border="0">
<tr>
<td width="50%" valign="top">

#### 🇧🇷 Português
Olá! Sou **João Victor**, desenvolvedor de software focado na construção de sistemas web modernos, APIs resilientes e arquiteturas orientadas a dados.

* 🎯 **Foco de Atuação**: Desenvolvimento Full-Stack com **Next.js**, **TypeScript**, ecossistema **.NET (C#)** e **Java**, integrando bancos relacionais e nuvem.
* 🏗️ **Arquitetura & Qualidade**: Modelagem relacional estrita (3FN), separação limpa de camadas (Service & Repository pattern), autenticação segura (JWT, NextAuth, BCrypt) e rate limiting.
* 📊 **Dados & Nuvem**: Experiência prática com **GCP** (BigQuery, Dataflow, Dataform), **Neon Database Serverless**, **PostgreSQL** e deploys contínuos via **Vercel** e **Render**.
* 🤖 **Inovação Contínua**: Exploração ativa de orquestração de **agentes autônomos de IA** e consumo analítico de telemetria.

</td>
<td width="50%" valign="top">

#### 🇺🇸 English
Hello! I am **João Victor**, a software engineer dedicated to crafting performant web applications, resilient backend APIs, and data-driven architectures.

* 🎯 **Core Focus**: Full-Stack engineering leveraging **Next.js**, **TypeScript**, **.NET (C#)**, and **Java**, bridged with cloud data pipelines.
* 🏗️ **Architecture & Integrity**: Rigorous relational modeling (3NF), decoupled business logic (Service/Repository layers), secure auth (JWT, NextAuth, BCrypt), and API rate limiting.
* 📊 **Cloud & Data**: Hands-on workflow with **Google Cloud Platform** (BigQuery, Dataflow, Dataform), **Neon Serverless PostgreSQL**, and automated CI/CD across **Vercel** & **Render**.
* 🤖 **Continuous Growth**: Building modular **AI agent orchestration** APIs and high-volume transactional fraud analytics.

</td>
</tr>
</table>

---

### 🚀 Vitrine de Projetos / Featured Projects

Projetos reais, com código auditável, arquitetura deliberada e deploys públicos em produção.

<br/>

#### 1. 💰 App de Finanças Pessoais — *Full-Stack SaaS Platform*
> **Substituição de planilhas financeiras por uma plataforma web completa em produção com modelagem 3FN.**

<div align="center">
  <a href="https://github.com/JV2008/app-financa-pessoal">
    <img src="assets/project-financas.svg" alt="App Finanças Pessoais Preview" width="100%" />
  </a>
</div>

* **🇧🇷 Problema & Solução**: Sistema criado para substituir controles manuais via Excel por um painel analítico com autenticação, gestão multi-contas, transações em tempo real e gráficos de evolução orçamentária.
* **🇺🇸 Architecture Highlights**:
  * **Core Stack**: `Next.js 15 (App Router)` · `React 18` · `TypeScript` · `Tailwind CSS` · `Recharts`
  * **Database & Integrity**: **PostgreSQL** via **Neon Database Serverless** com schema normalizado em **3FN** — saldo derivado matematicamente do histórico imutável de transações (sem inconsistência de cache).
  * **Security & Performance**: Rate limiting distribuído com **Upstash Redis** (`@upstash/ratelimit`), autenticação via **NextAuth** com hash **BCrypt**.
* **Status**: 🟢 Em produção ativa com dual-deploy.
* **Links**: [📂 Repositório GitHub](https://github.com/JV2008/app-financa-pessoal) • [🌐 Live Demo (Vercel)](https://app-financa-pessoal-eight.vercel.app) • [⚙️ API Service (Render)](https://app-financa-pessoal.onrender.com)

---

#### 2. 🛡️ Sentinela Analytics — *Dashboard Antifraude & Telemetria*
> **Painel transacional para monitoramento de risco e cibersegurança com visualização analítica interativa.**

<div align="center">
  <a href="https://github.com/JV2008/frontend-developer-portfolio">
    <img src="assets/project-sentinela.svg" alt="Sentinela Analytics Dashboard Preview" width="100%" />
  </a>
</div>

* **🇧🇷 Problema & Solução**: Interface analítica desenhada para equipes de prevenção a fraudes em pagamentos. Processa KPIs de volume transacionado, score de risco e distribuição temporal de incidentes.
* **🇺🇸 Architecture Highlights**:
  * **Core Stack**: `JavaScript (ES6+ Vanilla)` · `Chart.js` · `CSS Tokens` · `Pub/Sub State Management`
  * **Arquitetura Desacoplada**: Implementação estrita do padrão de serviço (`dataService.js`). A interface consome contratos padronizados (`/dashboard`), permitindo migração imediata de mock sintético determinístico para queries de Data Warehouses analíticos (**Google BigQuery** / Snowflake).
  * **Interatividade Avançada**: Seleção de período por *brushing* no gráfico temporal (arrastar de mouse), rankings paginados por MCC, Estabelecimento e Emissor.
* **Status**: 🟢 Protótipo Arquitetural Funcional (Zero-build / Clean Vanilla ES6)
* **Links**: [📂 Repositório GitHub](https://github.com/JV2008/frontend-developer-portfolio) • [🖼️ Visualizar Screenshot do Dashboard](https://github.com/JV2008/frontend-developer-portfolio/blob/main/Sentinela%20Analytics%20Dashboard%20Antifraude%20-%20Cyberseguran%C3%A7a%20%26%20Dados.png)

---

<table width="100%" border="0">
<tr>
<td width="50%" valign="top">

#### 3. 🤖 API Agents — *AI Agents Orchestration*
API RESTful modular voltada para criação, teste e orquestração de agentes autônomos inteligentes integrados a LLMs.

* **Stack**: `Python` · `Flask` · `REST API` · `Agentic Workflows`
* **Diferenciais**:
  * Isolamento modular de agentes especialistas (`agent-math`)
  * Endpoint REST `/chat` com suporte a execução determinística
  * Arquitetura extensível para acoplamento de novos agentes e ferramentas
* **Status**: 🛠️ Ativo & Experimental
* **Acesso**: [📂 Explorar Código no GitHub](https://github.com/JV2008/API_Agents)

</td>
<td width="50%" valign="top">

#### 4. ⚡ CadastroDotNet Web API — *.NET 10 Core*
API corporativa construída com .NET de última geração e persistência em banco relacional PostgreSQL.

* **Stack**: `C#` · `.NET 10` · `Entity Framework Core` · `PostgreSQL (Npgsql)`
* **Diferenciais**:
  * Autenticação e autorização via `JwtBearer`
  * Criptografia e segurança de credenciais com `BCrypt.Net`
  * Documentação interativa integrada com `Swagger / OpenAPI`
  * Mapeamento objeto-relacional robusto com EF Core Migrations
* **Status**: 🟢 Concluído
* **Acesso**: [📂 Explorar Código no GitHub](https://github.com/JV2008/cadastroDotNet)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 5. 📦 SENAI Notes REST API & Backend
Microsserviço de gestão de dados com integração frontend e pipeline de entrega automatizada.

* **Stack**: `Node.js` · `Express.js` · `CORS` · `Render CI/CD`
* **Diferenciais**:
  * Operações CRUD completas com tratamento de erros
  * Documentação formal de contratos no Postman (`docs_Postman`)
  * Deploy contínuo automatizado no Render
* **Status**: 🟢 Deploy Ativo
* **Acesso**: [📂 Repositório](https://github.com/JV2008/senai-frameworks-frontend-api-backend) • [🚀 Live API (Render)](https://senai-frameworks-frontend-api-backend.onrender.com/api/notes)

</td>
<td width="50%" valign="top">

#### 6. 🎨 Digital Atelier — *Mobile-First Landing Page*
Projeto de curadoria e experiência visual premium desenvolvido sob metodologia Mobile First.

* **Stack**: `HTML5 Semântico` · `CSS3 Flexbox/Grid` · `Design System`
* **Diferenciais**:
  * Responsividade pixel-perfect sem dependência de frameworks pesados
  * Foco em branding refinado, microinterações e hierarquia tipográfica
  * Carregamento ultrarrápido com zero tempo de compilação
* **Status**: 🟢 Concluído
* **Acesso**: [📂 Explorar Código no GitHub](https://github.com/JV2008/DigitalAtilier)

</td>
</tr>
</table>

---

### 🛠️ Stack Tecnológica / Tech Stack

Tecnologias comprovadas no histórico de repositórios e projetos ativos.

<div align="center">

#### Frontend & UI Engineering
<p>
  <img src="https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

#### Backend & APIs
<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</p>

#### Bancos de Dados & Cache
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Neon_Serverless-00E599?style=for-the-badge&logo=neon&logoColor=black" alt="Neon Database" />
  <img src="https://img.shields.io/badge/Redis_Upstash-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Entity_Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="EF Core" />
</p>

#### Cloud, Data & Infraestrutura
<p>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP" />
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white" alt="BigQuery" />
  <img src="https://img.shields.io/badge/Dataflow-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Dataflow" />
  <img src="https://img.shields.io/badge/Dataform-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Dataform" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render" />
</p>

#### Ferramentas & Engenharia
<p>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Antigravity-8B5CF6?style=for-the-badge&logo=google&logoColor=white" alt="Antigravity" />
</p>

</div>

---

### 📈 Linha do Tempo & Evolução Técnica / Technical Journey

Visualização animada e verificada dos marcos de desenvolvimento registrados no GitHub de 2024 até o presente.

<div align="center">
  <img src="assets/commit-timeline.svg" alt="Animated Technical Evolution Timeline (2024-2026)" width="100%" />
</div>

<br/>

<details>
<summary><b>🔍 Detalhamento das Fases de Evolução (Clique para expandir)</b></summary>
<br/>

* **Fase 1 (Fev/2024 – Jun/2024) — Fundamentos & Lógica**: Domínio de estruturas condicionais, vetores, matrizes, coleções e lógica computacional em Java (`primeiro-projeto-git`, `Estruturas-Condicionais`, `Matriz`, `Arraylist`).
* **Fase 2 (Jul/2024 – Dez/2024) — POO Avançada & Modelagem Relacional**: Aplicação de herança, polimorfismo, interfaces e abstrações em Java (`Arena_dos_Herois`, `POO-encapsulamento`), aliada à modelagem de tabelas e queries SQL relacionais.
* **Fase 3 (Jan/2025 – Jun/2025) — Persistência Corporativa & Mobile**: Mapeamento objeto-relacional com JPA / Hibernate em bancos MySQL (`JPAAluno`, `JPAProduto`, `carrojpa`) e introdução ao desenvolvimento mobile com Dart/Flutter (`PDMaula1`).
* **Fase 4 (Jul/2025 – Mar/2026) — Ecossistema Web Moderno & APIs C# .NET**: Criação de APIs robustas com ASP.NET Core e Entity Framework no .NET 10 (`cadastroDotNet`), aliadas ao frontend reativo com Next.js, React e Tailwind CSS.
* **Fase 5 (2026 – Presente) — Produção em Nuvem, IA Aplicada & Analytics**: Lançamento de aplicações completas com banco serverless Neon 3FN, rate limiting via Redis, telemetria analítica com contratos para Data Warehouses (`Sentinela Analytics`), deploys em Vercel e Render e orquestração de agentes de IA (`API_Agents`).

</details>

---

### 🐍 Radar de Contribuições / Contribution Activity

<div align="center">
  <img src="assets/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake Dark Animation" width="100%" />
  <p><sub><i>Atualizado automaticamente via GitHub Actions com pipeline agendado diário.</i></sub></p>
</div>

---

### 📊 Estatísticas / GitHub Analytics

<div align="center">

<table border="0">
<tr>
<td align="center" valign="middle">
  <a href="https://github.com/JV2008">
    <img src="https://github-readme-stats.vercel.app/api?username=JV2008&show_icons=true&bg_color=0d1117&text_color=94a3b8&title_color=38bdf8&icon_color=a855f7&border_color=30363d&border_radius=10" alt="João Victor's GitHub Stats" />
  </a>
</td>
<td align="center" valign="middle">
  <a href="https://github.com/JV2008">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JV2008&layout=compact&bg_color=0d1117&text_color=94a3b8&title_color=38bdf8&border_color=30363d&border_radius=10&hide=css,html" alt="Top Languages" />
  </a>
</td>
</tr>
<tr>
<td colspan="2" align="center">
  <a href="https://github.com/JV2008">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=JV2008&background=0D1117&border=30363D&stroke=6366F1&ring=A855F7&fire=38BDF8&currStreakNum=E2E8F0&sideNums=E2E8F0&currStreakLabel=38BDF8&sideLabels=94A3B8&dates=64748B" alt="GitHub Streak" />
  </a>
</td>
</tr>
</table>

</div>

---

### 📬 Contato & Conecte-se / Get In Touch

Estou aberto a oportunidades profissionais, desafios de engenharia e trocas sobre tecnologia. Vamos conversar!

<div align="center">

<p>
  <a href="https://www.linkedin.com/in/jo%C3%A3o-victor-leite-5624613b9/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn João Victor" />
  </a>
  &nbsp;
  <a href="mailto:joaovictor25032@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email João Victor" />
  </a>
  &nbsp;
  <a href="https://github.com/JV2008">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub JV2008" />
  </a>
</p>

<p>
  <sub>⚡ <i>"Autenticidade técnica e código construído com propósito."</i> • <b>João Victor (JV2008)</b></sub>
</p>

</div>
