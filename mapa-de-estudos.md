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
    class M2,M3,M4,M5,M6,A1,A2 todo
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
