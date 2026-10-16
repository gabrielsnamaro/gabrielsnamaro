<div align="center">
  <img src="profile-circle.png" width="150" alt="Foto de Gabriel Amaro" />
  <h1>Olá! 👋 Sou o Gabriel Amaro</h1>
  <h3>Estudante de Engenharia de Software · Automações, Dados e APIs</h3>
  <p>
    Construo integrações orientadas a eventos entre CRM, e-mail, planilhas e mensageria, e pipelines incrementais e idempotentes para BigQuery e armazenamento compatível com S3.
    Fora do estágio, construo aplicações web e extensões de navegador.
  </p>
  <p>
    <a href="mailto:gabrielsn.amaro@gmail.com"><img src="https://img.shields.io/badge/E--mail-gabrielsn.amaro%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="E-mail" /></a>
    <a href="https://www.linkedin.com/in/gabrielamaro2006/"><img src="https://img.shields.io/badge/LinkedIn-gabrielamaro2006-0A66C2?style=flat" alt="LinkedIn" /></a>
  </p>
</div>

---

### 🚀 Sobre mim

- 🎓 Engenharia de Software na **PUC Minas** (fev/2025 – dez/2028, previsão). Técnico em Informática para Internet (Desenvolvimento de Software) pelo **SENAI** (2024).
- 💼 **Estagiário de Desenvolvimento de Software, Automações e QA** na Smart Leilões Imobiliária desde ago/2025.
- 🔒 Segurança e observabilidade desde o início: JWT, mascaramento de dados em logs e auditoria.
- 🤖 Trabalho com agentes de IA (Antigravity, Claude Code e Codex) apoiados por uma **base de conhecimento no Obsidian, integrada via MCP**, por **skills e subagentes próprios** e por **um hook que roda checagens estáticas antes do deploy**.
- 🌎 Português nativo e inglês avançado, com leitura técnica fluente.

---

### 💼 Trabalho atual

Na Smart Leilões Imobiliária, tenho trabalhado em:

- 🧩 **Plataforma de automações orientada a webhooks** em Google Apps Script, integrada a CRM, e-mail, planilhas e mensageria, com estado por automação (desabilitado, teste ou produção) alterável sem novo deploy; o modo de teste bloqueia antes do primeiro efeito externo.
- ☁️ **Automações serverless no Cloud Run** (Node.js e Docker), com regras de negócio automatizadas em produção.
- 📦 **Pipeline incremental de histórico de conversas** para BigQuery e Cloudflare R2, com carga idempotente e tudo-ou-nada via `MERGE`, auditoria de lacunas e reenvio automático. Identifiquei e corrigi uma perda silenciosa de datas e IDs na carga.
- 🖥️ **Visualizador web multi-fonte, somente leitura** (React, shadcn/ui, Node.js, BigQuery), com busca, renderização segura de HTML de terceiros e controle de acesso por papéis.
- 📊 **API de propostas em planilha e extensão Chrome MV3** de exportação periódica de relatórios, com JWT HS256 implementado sem biblioteca; leitura de planilhas grandes otimizada de ~47 s para menos de 0,1 s no preparo das linhas.
- 🤖 **API de logs para agentes de IA**: somente leitura, JWT por ação, auditoria de toda requisição e uma CLI que assina os tokens sem expor o segredo ao agente.
- 🗺️ **Mapeamento de processos** em Mermaid e documentação técnica para outras equipes e para QA.

> Os repositórios de trabalho são privados; aqui ficam os projetos que posso mostrar.

---

### 📂 Projetos em destaque

#### 📚 [Notion Dynamic Manager](https://github.com/gabrielsnamaro/Personal_Academic_Notion_Automations) · pessoal

- **O que faz:** agenda no meu Notion acadêmico revisões por repetição espaçada (D+1, D+7 e D+30) a partir de um lote de estudo e classifica as tarefas de revisão em ciclos.
- **Como:** Express 5 com login Google verificado no servidor, allowlist de um único e-mail e JWT; troca atômica do bloco de revisões; frontend em React 19, Tailwind v4 e shadcn/ui; 7 testes com `node --test`.
- **Stack:** Node.js, Express 5, JWT, Google OAuth, React 19, Vite, Tailwind CSS v4, shadcn/ui, Vercel

#### 🎧 [AntiDUB](https://github.com/gabrielsnamaro/Extensao_Anti_Dublagem_YT) · pessoal

- **O que faz:** extensão Chrome (Manifest V3) que deixa o áudio original como padrão no YouTube, evitando a dublagem por IA, e restaura os títulos originais.
- **Como:** estratégias em cascata (Strategy) para achar a faixa original, com a API do player e o DOM atrás de Adapters; títulos via oEmbed numa fila de até 3 requisições simultâneas, com deduplicação e cache LRU, para evitar HTTP 429.
- **Stack:** JavaScript, Chrome Manifest V3, `chrome.storage`, oEmbed, IntersectionObserver/MutationObserver

#### ⚙️ [Simulador de escalonamento de CPU](https://github.com/gabrielsnamaro/Scheduling_Algorithms_Simulator_OS) · acadêmico, em dupla

- **O que faz:** simula políticas de escalonamento e calcula tempo de espera médio, turnaround médio e vazão.
- **Como:** em Java, classe abstrata `Escalonador` com quatro implementações (FCFS, SRTF, Round Robin e Multilevel Queue), com prioridades, interrupções de I/O e linha do tempo gravada em arquivo.
- **Stack:** Java

#### 🎓 [Sistema de matrículas](https://github.com/gabrielsnamaro/sistemas-de-matricula-lds2) · acadêmico, em grupo

- **O que faz:** matrícula em até 4 disciplinas obrigatórias e 2 optativas, com perfis de aluno, professor e secretaria e as regras de quórum (mínimo de 3 alunos) e lotação (máximo de 60).
- **Como:** Java 21 e Maven em camadas, persistência atrás de uma interface e testes em JUnit 5; casos de uso, histórias de usuário e diagrama de classes UML no README.
- **Stack:** Java 21, Maven, JUnit 5, UML

Na faculdade, também participei em grupo do **JAM**, gestão de estúdios musicais (Java 21, Spring Boot, Maven, PostgreSQL, React), e de uma plataforma de gestão para um negócio de maquiagem com pagamentos via webhooks (React, Vite, Tailwind CSS, shadcn/ui, TypeScript, PHP, Docker Compose). Esses repositórios são privados.

---

### 💻 Tecnologias

**No dia a dia:**  
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat&logo=javascript&logoColor=F7DF1E)
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat&logo=googleappsscript&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

**Web e extensões:**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=flat&logo=vite&logoColor=FFD62E)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![Chrome MV3](https://img.shields.io/badge/Chrome_MV3-4285F4?style=flat&logo=googlechrome&logoColor=white)

**Java:**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat&logo=junit5&logoColor=white)

**Ferramentas e IA:**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat&logo=obsidian&logoColor=white)
![Mermaid](https://img.shields.io/badge/Mermaid-FF3670?style=flat&logo=mermaid&logoColor=white)

**Acadêmico:**  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat&logo=docker&logoColor=white)

---

<details>
<summary>🇺🇸 English</summary>

<br />

<div align="center">
  <h3>Software Engineering student · Automation, Data and APIs</h3>
  <p>
    I build event-driven integrations between CRM, email, spreadsheets and messaging, and incremental, idempotent pipelines into BigQuery and S3-compatible storage.
    Outside my internship, I build web apps and browser extensions.
  </p>
</div>

#### 🚀 About me

- 🎓 Software Engineering at **PUC Minas** (Feb 2025 – Dec 2028, expected). Technical degree in Internet Computing (Software Development) from **SENAI** (2024).
- 💼 **Software Development, Automation and QA Intern** at Smart Leilões Imobiliária since Aug 2025.
- 🔒 Security and observability from the start: JWT, data masking in logs and auditing.
- 🤖 I work with AI agents (Antigravity, Claude Code and Codex) backed by a **knowledge base in Obsidian, connected through MCP**, by **my own skills and subagents** and by **a hook that runs static checks before deploying**.
- 🌎 Native Portuguese and advanced English, with fluent technical reading.

#### 💼 Current work

At Smart Leilões Imobiliária, I have been working on:

- 🧩 **Webhook-driven automation platform** in Google Apps Script, integrated with CRM, email, spreadsheets and messaging, with a per-automation state (disabled, test or production) that can be switched without a new deploy; test mode blocks before the first external side effect.
- ☁️ **Serverless automations on Cloud Run** (Node.js and Docker), with automated business rules in production.
- 📦 **Incremental conversation-history pipeline** into BigQuery and Cloudflare R2, with idempotent, all-or-nothing loads via `MERGE`, gap auditing and automatic re-upload. I found and fixed a silent loss of dates and IDs in the load.
- 🖥️ **Read-only multi-source web viewer** (React, shadcn/ui, Node.js, BigQuery), with search, safe rendering of third-party HTML and role-based access control.
- 📊 **Spreadsheet-backed proposals API and Chrome MV3 extension** for scheduled report exports, with HS256 JWT implemented without a library; reading large spreadsheets optimized from ~47 s to under 0.1 s in the row-preparation step.
- 🤖 **Log API for AI agents**: read-only, per-action JWT, auditing of every request and a CLI that signs tokens without exposing the secret to the agent.
- 🗺️ **Business process mapping** in Mermaid, plus technical documentation for other teams and for QA.

> Work repositories are private; these are the projects I can show.

#### 📂 Featured projects

##### 📚 [Notion Dynamic Manager](https://github.com/gabrielsnamaro/Personal_Academic_Notion_Automations) · personal

- **What it does:** schedules spaced-repetition reviews (D+1, D+7 and D+30) in my academic Notion page from a study batch and sorts the review tasks into cycles.
- **How:** Express 5 with Google sign-in verified on the server, a single-email allowlist and JWT; atomic replacement of the review block; React 19, Tailwind v4 and shadcn/ui frontend; 7 `node --test` tests.
- **Stack:** Node.js, Express 5, JWT, Google OAuth, React 19, Vite, Tailwind CSS v4, shadcn/ui, Vercel

##### 🎧 [AntiDUB](https://github.com/gabrielsnamaro/Extensao_Anti_Dublagem_YT) · personal

- **What it does:** Chrome extension (Manifest V3) that makes the original audio the default on YouTube, avoiding AI dubbing, and restores the original titles.
- **How:** cascading strategies (Strategy pattern) to find the original track, with the player API and the DOM behind Adapters; titles from oEmbed through a queue capped at 3 concurrent requests, with deduplication and an LRU cache, to avoid HTTP 429.
- **Stack:** JavaScript, Chrome Manifest V3, `chrome.storage`, oEmbed, IntersectionObserver/MutationObserver

##### ⚙️ [CPU scheduling simulator](https://github.com/gabrielsnamaro/Scheduling_Algorithms_Simulator_OS) · academic, two-person team

- **What it does:** simulates scheduling policies and computes average waiting time, average turnaround and throughput.
- **How:** in Java, an abstract `Escalonador` class with four implementations (FCFS, SRTF, Round Robin and a Multilevel Queue), with priorities, I/O interrupts and the execution timeline written to a file.
- **Stack:** Java

##### 🎓 [Course enrollment system](https://github.com/gabrielsnamaro/sistemas-de-matricula-lds2) · academic, group project

- **What it does:** enrollment in up to 4 required and 2 elective courses, with student, professor and registrar roles and the minimum-enrollment (3 students) and capacity (60 at most) rules.
- **How:** Java 21 and Maven in layers, persistence behind an interface and JUnit 5 tests; use cases, user stories and a UML class diagram in the README.
- **Stack:** Java 21, Maven, JUnit 5, UML

At university, I also took part in group projects on **JAM**, a music studio management system (Java 21, Spring Boot, Maven, PostgreSQL, React), and on a management platform for a makeup business with webhook-based payments (React, Vite, Tailwind CSS, shadcn/ui, TypeScript, PHP, Docker Compose). Those repositories are private.

</details>
