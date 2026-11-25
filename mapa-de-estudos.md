# Mapa de estudos e skills · Study map and skills

**Legenda / Legend:** ✅ concluído / done · 🟡 em andamento / in progress · ⬜ a fazer / to do · 🔒 bloqueado / locked · 🔓 skill desbloqueada / skill unlocked

As skills vêm dos objetivos de aprendizagem, checklists e resumos da própria plataforma. Uma skill é desbloqueada quando a aula que a ensina é concluída. A **badge do módulo** só é liberada quando todas as aulas e o projeto prático do módulo estiverem prontos.
Skills come from the platform's own learning objectives, checklists and summaries.

## Visão geral / Overview

~~~mermaid
flowchart LR
    subgraph DPL[Tera · Digital Product Leadership]
      direction TB
      M1["🟡 01 Fundamentos de PM<br/>9 de 15 aulas"]
      M2["⬜ 02 Métricas"]
      M3["⬜ 03 Product Discovery"]
      M4["⬜ 04 Product Delivery"]
      M5["⬜ 05 Liderança e Negociação"]
      M6["⬜ 06 (a confirmar)"]
      M1 --> M2 --> M3 --> M4 --> M5 --> M6
    end
    subgraph AIPM[Tera · AI Product Manager]
      direction TB
      A1["🔒 01 Eficiência com IA"]
      A2["🔒 02 Discovery & Delivery com IA"]
      A1 --> A2
    end
    M6 --> A1
    subgraph PROJ[Projetos práticos]
      P1["🟡 Projeto 01 · Raio-X de um produto"]
    end
    M1 -.aplica.-> P1
    classDef done fill:#d4edda,stroke:#155724,color:#155724
    classDef doing fill:#fff3cd,stroke:#856404,color:#533f03
    classDef todo fill:#f8f9fa,stroke:#6c757d,color:#343a40
    class M1,P1 doing
    class M3,M4,M5,M6,A1,A2 todo
    class M2 doing
~~~

## DPL · Módulo 01: Fundamentos de Product Management 🟡

~~~mermaid
flowchart TD
    L1["✅ 1 Sua jornada no DPL"] --> L2["✅ 2 O ponto de partida de todo PM"] --> L3["✅ 3 Fundamentos de produto"]
    L3 --> L4["✅ 4 Pessoas de Produto"] --> L5["✅ 5 Q&A: Papéis e Fundamentos"] --> L6["✅ 6 Ciclo de Vida de Produto"]
    L6 --> L7["✅ 7 Product Sense"] --> L8["✅ 8 O que é estratégia de produto"] --> L9["✅ 9 Estratégias claras e ambiciosas"]
    L9 --> L10["✅ 10 Visão de produto"] --> L11["✅ 11 Proposta de valor"] --> L12["✅ 12 Criação de valor"]
    L12 --> L13["✅ 13 Conclusão + teste"] --> L14["✅ 14 Ferramentas para PMs"] --> L15["✅ 15 Desafio: Marketplace"]
    L15 --> B{{"🔒 Badge: Fundamentos de PM"}}
    classDef done fill:#d4edda,stroke:#155724,color:#155724
    classDef todo fill:#f8f9fa,stroke:#6c757d,color:#343a40
    class L1,L2,L3,L4,L5,L6,L7,L8,L9,L10,L11,L12,L13,L14,L15 done
    class B todo
~~~

### Skills do módulo / Module skills

| Skill | Aula que desbloqueia / Unlocked by | Situação |
|---|---|---|
| Diferenciar **gestão de projeto** de **gestão de produto** (começo, meio e fim × começo, meio, meio...) | 3 Fundamentos de produto | 🔓 |
| Analisar um produto pela **cadeira de três pernas**: experiência, negócios e viabilidade | 3 Fundamentos de produto | 🔓 |
| Comunicar uma visão começando pelo **porquê** (círculo dourado: visão → estratégia → tática) | 3 Fundamentos de produto | 🔓 |
| Explicar o conceito de **dual track agile** (discovery e delivery em trilhas contínuas) | 3 Fundamentos de produto | 🔓 |
| Explicar a diferença entre **PO** (papel do Scrum, foco em desenvolvimento e backlog) e **PM** (função, foco em resultado e estratégia) | 4 Pessoas de Produto | 🔓 |
| Descrever as três camadas: **administração de backlog**, **administração de roadmap** e **product manager** | 4 Pessoas de Produto | 🔓 |
| Mapear as próprias habilidades com o **T-Shaped Product Manager** | 4 Pessoas de Produto | 🔓 |
| Diferenciar **ciclo de desenvolvimento** de **ciclo de vida** | 6 Ciclo de Vida | 🔓 |
| Usar **métricas** (negócio, cliente, produto) para reconhecer a fase do ciclo de vida | 6 Ciclo de Vida | 🔓 |
| Diferenciar o foco e os desafios de PMs em cada fase do ciclo | 6 Ciclo de Vida | 🔓 |
| Explicar por que um **pensamento estruturado** é importante para problemas complexos de negócio | 7 Product Sense | 🔓 |
| Aplicar os componentes do pensamento estruturado: **amar o problema**, pensar em **produto e não em features**, ser **específico e agnóstico** | 7 Product Sense | 🔓 |
| Organizar e comunicar o pensamento com perguntas: **usuário → trabalho a ser feito → objetivos e recursos** | 7 Product Sense | 🔓 |
| Diferenciar **visão, estratégia e tática** | 8 Estratégia de produto | 🔓 |
| Usar os cinco elementos do núcleo da estratégia: **foco, insights, ação, gerenciamento e métricas** | 8 Estratégia de produto | 🔓 |
| Montar uma estratégia com **contexto, foco e sequenciamento** e mantê-la viva com o aprendizado | 8 Estratégia de produto | 🔓 |
| Reconhecer as armadilhas: **feature factory** e mudanças cosméticas | 8 Estratégia de produto | 🔓 |
| Conduzir um **diagnóstico 360°** (cliente, produto, empresa, mercado) com o **Canvas C>P>E>M** | 9 Estratégias claras | 🔓 |
| Usar **jobs to be done** para entender e priorizar problemas | 9 Estratégias claras | 🔓 |
| Escrever um **1-pager** de estratégia (business intent, NSM, público, JTBD, proposta de valor) | 9 Estratégias claras | 🔓 |
| Deixar a **proposta de valor guiar o escopo do MVP** | 9 Estratégias claras | 🔓 |
| Diferenciar **missão e visão** de produto e reconhecer as **7 características** de uma boa visão | 10 Visão de produto | 🔓 |
| Contextualizar a visão pelos **quatro prismas**: contexto (ciclo de vida), empresa, produto (solução, dor, oportunidade) e porquê | 10 Visão de produto | 🔓 |
| Escrever e reescrever a visão com a **frase guiada** e o **canvas de visão** (Roman Pichler) | 10 Visão de produto | 🔓 |
| Contar a visão como **narrativa** (Era uma vez… / storytelling canvas) | 10 Visão de produto | 🔓 |
| Explicar **proposta de valor** e diferenciar **Problem Solution Fit** e **Product Market Fit** | 11 Proposta de valor | 🔓 |
| Validar problema (hipóteses, raiz, intensidade da dor) e solução (**desejável, viável, realizável**) | 11 Proposta de valor | 🔓 |
| Preencher o **Canvas de proposta de valor** começando pelo perfil do cliente | 11 Proposta de valor | 🔓 |
| Dimensionar mercado com **TAM/SAM/SOM**, escolher um **tipo de MVP** e medir o fit (NPS, regra dos 40%, métricas) | 11 Proposta de valor | 🔓 |
| Diferenciar **preço e valor** e explicar por que a criação de valor fideliza (diferencial, receita, sustentabilidade) | 12 Criação de valor | 🔓 |
| Criar valor em passos: **segmento de clientes → persona → problema → solução → cumprir o prometido** | 12 Criação de valor | 🔓 |
| Escolher a ferramenta certa para cada momento: **CSD, mapa de empatia, proto-persona/persona, jornada, stakeholders, BMC** | 14 Ferramentas | 🔓 |
| Priorizar e planejar com **Now/Next/Later, impacto × esforço e MoSCoW**; medir com **canvas de experimento, HEART e OKR** | 14 Ferramentas | 🔓 |
| Mapear suposições e riscos de uma nova iniciativa, achar a **suposição mãe** e começar a mitigação pela **desejabilidade** | 15 Desafio | 🔓 |

### Badge do módulo / Module badge
🔒 **Fundamentos de PM:** todas as 15 aulas ✅ + Projeto 01 ✅. Teste do módulo feito ✅ (18/11). Falta só o **Projeto 01**.

## Próximos módulos / Next modules
As skills de cada módulo entram aqui quando ele começar, a partir dos objetivos de aprendizagem que a Tera mostrar.

## DPL · Módulo 02: Métricas para Produtos Digitais 🟡

~~~mermaid
flowchart TD
    N1["✅ 1 Depois da base, é hora de medir"] --> N2["✅ 2 Introdução aos Dados"] --> N3["✅ 3 Introdução aos KPIs"]
    N3 --> N4["✅ 4 Definição e Comunicação de KPIs"] --> N5["✅ 5 Métricas para Produtos e Negócios"] --> N6["✅ 6 Teste de Hipóteses"]
    N6 --> N7["✅ 7 Tracking Plan"] --> N8["✅ 8 Cultura de Analytics"] --> N9["✅ 9 SQL para PMs"]
    N9 --> N10["⬜ 10 Conclusão + teste"] --> N11["✅ 11 Desafio: decisão com KPI"]
    N11 --> B2{{"🔒 Badge: Métricas"}}
    classDef done fill:#d4edda,stroke:#155724,color:#155724
    classDef todo fill:#f8f9fa,stroke:#6c757d,color:#343a40
    class N1,N2,N3,N4,N5,N6,N7,N8,N9,N11 done
    class N10,B2 todo
~~~

### Skills do módulo / Module skills

| Skill | Aula que desbloqueia / Unlocked by | Situação |
|---|---|---|
| Explicar por que o produto precisa de **evidência** (métricas), não só de propósito: "percepção não é validação" | 1 Depois da base | 🔓 |
| Explicar o que é **Big Data** (5 Vs) e diferenciar dados **estruturados, não estruturados e semiestruturados** | 2 Introdução aos Dados | 🔓 |
| Reconhecer o **letramento em dados** (ler, coletar e gerenciar, comunicar) e a **maturidade de dados** de uma empresa (de resistente a data-driven) | 2 Introdução aos Dados | 🔓 |
| Evitar **vieses de decisão** (padrão, curto prazo, ganho) e lembrar que **correlação não é causalidade** | 2 Introdução aos Dados | 🔓 |
| Diferenciar **métrica, indicador e KPI** e classificar KPIs em **produtividade, qualidade, capacidade e estratégia** | 3 Introdução aos KPIs | 🔓 |
| Escolher KPIs por **modelo de negócio** (conteúdo, e-commerce, assinatura, vendas, apps) e diferenciar **pipeline de plataforma** | 3 Introdução aos KPIs | 🔓 |
| Escrever objetivos **SMART** e **OKRs** ("Vamos X até Y, medido por Z"), com 2 a 5 KRs e em cascata | 4 Definição e Comunicação de KPIs | 🔓 |
| Construir KPIs com o **framework Karta**, ligados à **jornada do cliente**, e comunicá-los sem distorcer (definições únicas, "você tem o que você mede") | 4 Definição e Comunicação de KPIs | 🔓 |
| Ir do **dado à métrica** (dado → medida → informação → métrica) e evitar **métricas de vaidade** | 5 Métricas para Produtos e Negócios | 🔓 |
| Diferenciar **KPI (monitorar, top-down) e OKR (atingir, bottom-up)** e usar **North Star, boundary metrics e constelação** (input × output) | 5 Métricas para Produtos e Negócios | 🔓 |
| Calcular e interpretar **CAC, DAU/MAU, churn, MRR/ARPU/ARPA, LTV, LTV÷CAC, coeficiente viral, NPS e CSAT** com **AARRR** e **HEART** | 5 Métricas para Produtos e Negócios | 🔓 |
| Analisar métricas por **segmento, teste A/B, multivariada e coorte**, e acompanhar a jornada com o **framework CRESCER** | 5 Métricas para Produtos e Negócios | 🔓 |
| Montar um **teste de hipótese** (H0/H1, α, p-valor) e um **teste A/B** em 4 etapas, interpretando "rejeita / não rejeita H0" | 6 Teste de Hipóteses | 🔓 |
| Montar um **tracking plan**: definir o que medir em colaboração, padronizar nomes de eventos e parâmetros, documentar e validar a coleta (GTM, dataLayer, debuggers) | 7 Tracking Plan | 🔓 |
| Transformar ideias em **hipóteses testáveis** (Test Card, métrica de saúde, critério de sucesso) e conduzir um **processo de experimentação** do objetivo à documentação | 8 Cultura de Analytics | 🔓 |
| Escrever **consultas SQL básicas** (SELECT, WHERE, ORDER BY, LIMIT, IN, BETWEEN, LIKE, IS NULL) a partir de uma pergunta de negócio | 9 SQL para PMs | 🔓 |
| Definir objetivos e KPIs de um negócio novo com **OGSM** e metas **SMART** (caso TeraMove) | 11 Desafio KPI | 🔓 |

## DPL · Módulo 03: Introdução a Product Discovery 🟡

~~~mermaid
flowchart TD
    D1["✅ 1 Os dados levantam perguntas"] --> D2["✅ 2 Customer Development"] --> D3["✅ 3 Product-Market Fit"] --> D4["✅ 4 MVP"]
    D4 --> D5["✅ 5 Hipóteses e leitura de dados"] --> D6["✅ 6 Métodos de pesquisa"] --> D7["⬜ 7 Consolidação de pesquisa"]
    D7 --> D8["⬜ 8 Personas"] --> D9["⬜ 9 Mapa da jornada"] --> D10["⬜ 10 Q&A Persona"] --> D11["⬜ 11 Q&A Jornada"]
    D11 --> D12["⬜ 12 Cultura de experimentação"] --> D13["⬜ 13 Design de experimentos"] --> D14["⬜ 14 Q&A Experimentação"]
    D14 --> D15["⬜ 15 Prototipagem rápida"] --> D16["⬜ 16 Arquitetura da informação"] --> D17["⬜ 17 Mitigação de riscos"]
    D17 --> D18["⬜ 18 Continuous Discovery"] --> D19["⬜ 19 Q&A Prototipagem"] --> D20["⬜ 20 Conclusão + teste"] --> D21["⬜ 21 Desafio do mercado"]
    D21 --> B3{{"🔒 Badge: Product Discovery"}}
    classDef done fill:#d4edda,stroke:#155724,color:#155724
    classDef todo fill:#f8f9fa,stroke:#6c757d,color:#343a40
    class D1,D2,D3,D4,D5,D6 done
    class D7,D8,D9,D10,D11,D12,D13,D14,D15,D16,D17,D18,D19,D20,D21,B3 todo
~~~

### Skills do módulo / Module skills

| Skill | Aula que desbloqueia / Unlocked by | Situação |
|---|---|---|
| Passar de "o que está acontecendo" (métricas) para "por quê" (discovery), com perguntas e escuta ativa | 1 Os dados levantam perguntas | 🔓 |
| Montar uma **visão inicial do problema** com fatos e evidências (matriz CSD, visão empírica × validada × plausível, Answer First × Last) | 2 Customer Development | 🔓 |
| Aplicar as 4 etapas do **Customer Development**, declarar problema e **hipóteses** testáveis e escrever um **job to be done** | 2 Customer Development | 🔓 |
| Diferenciar **problem-solution fit, product-market fit e escala**; medir o PMF com AARRR, unit economics, NPS e o teste dos 40%; mapear os riscos de produto, cliente e mercado | 3 Product-Market Fit | 🔓 |
| Escolher o **tipo de MVP** (landing page, pré-venda, vídeo, piecemeal, SaaS/PaaS, manual/Mágico de Oz) conforme a incerteza a reduzir | 4 MVP | 🔓 |
| Fazer o **framing do problema** (5 porquês), estruturar hipóteses com **árvore de oportunidades** e **matriz CSD** e validá-las lendo dados (coleta, segmentação, regras de negócio, visualização) | 5 Hipóteses e leitura de dados | 🔓 |
| Escolher o **método de pesquisa** (atitudinal × comportamental, quali × quanti, contexto) e planejar desk research, **teste de usabilidade**, entrevista, survey e grupo focal sem vieses | 6 Métodos de pesquisa | 🔓 |

## Alura · Formação Technical Writing 🟡

~~~mermaid
flowchart LR
    C1["✅ 01 Estratégias, ferramentas e boas práticas<br/>concluído em 25/11/2026"] --> C2["🟡 02 Documentação do zero com DDLC<br/>Aulas 01 e 02 de 5"]
~~~

### Curso 01: Aprenda estratégias, ferramentas e boas práticas ✅

~~~mermaid
flowchart TD
    A1["✅ 1 O que é Technical Writing?"] --> A2["✅ 2 Tipos de documentação técnica"] --> A3["✅ 3 Boas práticas de escrita"]
    A3 --> A4["✅ 4 Outros formatos de conteúdo técnico"] --> A5["✅ 5 Planejamento e análise"]
    A5 --> B{{"🔓 Badge: Curso 01 de Technical Writing"}}
~~~

| Skill | Aula que desbloqueia / Unlocked by | Situação |
|---|---|---|
| Definir Technical Writing e o objetivo de TW nas empresas | Aula 01 | 🔓 |
| Diferenciar Technical Writing de UX Writing | Aula 01 | 🔓 |
| Criar um repositório de documentações no GitHub | Aula 01 | 🔓 |
| Reconhecer as habilidades e o perfil de um Tech Writer | Aula 01 | 🔓 |
| Conhecer os principais tipos de documentação técnica em TI | Aula 02 | 🔓 |
| Aplicar arquitetura da informação e boas práticas de escrita | Aula 03 | 🔓 |
| Desenvolver release notes, troubleshooting, tutoriais e mais | Aulas 02 a 04 | 🔓 (projeto: funcional, tutorial, how-to e FAQ; faltam troubleshooting e release notes, opcionais) |
| Planejar e analisar documentações | Aula 05 | 🔓 |

### Curso 02: Crie uma documentação do zero com DDLC 🟡

~~~mermaid
flowchart TD
    D1["✅ 1 Iniciando seu processo de documentação"] --> D2["✅ 2 Estruturando sua documentação"] --> D3["⬜ 3 Escrita e revisão"]
    D3 --> D4["⬜ 4 Publicação"] --> D5["⬜ 5 Medindo a eficácia"]
    D5 --> B2{{"🔒 Badge: Curso 02 de Technical Writing"}}
~~~

| Skill | Aula que desbloqueia / Unlocked by | Situação |
|---|---|---|
| Explicar o DDLC e suas 6 etapas | Aula 01 | 🔓 |
| Planejar uma documentação (público, SMEs, ferramentas) | Aula 01 | 🔓 |
| Criar uma documentação técnica com o framework DDLC | Aulas 02 a 04 | 🟡 Aula 02 lida |
| Criar um plano de comunicação para divulgar a documentação | Aula 04 | 🔒 |
| Planejar indicadores de sucesso da documentação | Aula 05 | 🔒 |
