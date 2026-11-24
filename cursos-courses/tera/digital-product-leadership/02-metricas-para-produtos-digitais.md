# Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais

| Campo / Field | Valor / Value |
|---|---|
| Escola / School | Tera |
| Curso / Course | Digital Product Leadership (DPL), formação com 6 módulos / 6-module program |
| Módulo / Module | 02 · Métricas para Produtos Digitais |
| Situação / Status | 🟡 Em andamento · 5 de 11 aulas / In progress · 5 of 11 lessons |
| Fonte / Source | [Tera: Digital Product Leadership](https://plataforma.somostera.com/formations/digital-product-leadership) (login) |

🇧🇷 Sobre o módulo (texto da plataforma): entender a função das métricas no ciclo de desenvolvimento, aprender a definir indicadores e aprofundar os conhecimentos em análise de dados.

🇺🇸 About: the role of metrics in the development cycle, how to define indicators, and data analysis.

## Aulas / Lessons

| # | Aula / Lesson | Professor(a) / Instructor | Situação / Status |
|---|---|---|---|
| 1 | Depois da base, é hora de medir (opcional) | Time Tera | ✅ |
| 2 | Introdução aos Dados em Produtos Digitais | Juliana Reksua (iFood) | ✅ |
| 3 | Introdução aos KPIs | Henrique Santana | ✅ |
| 4 | Definição e Comunicação de KPIs | Henrique Santana | ✅ |
| 5 | Métricas para Produtos e Negócios | Igor Torres (Neon) | ✅ |
| 6 | Teste de Hipóteses | Gustavo Rodrigues Pilatti | ⬜ |
| 7 | Planejamento e Implementação de Tracking (Tracking Plan) | Huxley Dias | ⬜ |
| 8 | Cultura de Analytics e Planejamento de Testes | Huxley Dias | ⬜ |
| 9 | SQL para PMs: comandos básicos para consultas rápidas | | ⬜ |
| 10 | Conclusão: Métricas para Produtos Digitais (recap + teste) | Tera | ⬜ |
| 11 | Desafio: tomada de decisão com KPI | | ⬜ |

---

## 1. Depois da base, é hora de medir / After the basics, it's time to measure

🇧🇷 Vídeo curto (cerca de 1 min e meio) que faz a ponte entre o Módulo 01 e o 02. Com a base estabelecida, surge a pergunta: **como provar que o produto cumpre o seu papel?** Não basta ter propósito: é preciso **evidência**.

🇺🇸 Bridge video: purpose is not enough, you need evidence. Without metrics, even your best argument is just an opinion.

~~~mermaid
flowchart LR
  A["Propósito<br/>(Módulo 01)"] -->|"métricas"| B["Evidência"] --> C["Decisões mais<br/>seguras e consistentes"]
~~~

**Ideias principais do vídeo:**
- 🇧🇷 **"Sem métrica, até o seu melhor argumento vira opinião."**
- 🇧🇷 Boas intenções não bastam, e **percepção não é validação**: um produto pode parecer promissor, mas só os dados mostram se ele realmente gera valor.
- 🇧🇷 A pergunta muda: **o que exatamente estamos medindo? E por quê?**
- 🇧🇷 O módulo promete ajudar a sair da abstração para a objetividade: **medir o que importa, traduzir resultado em argumento e usar métricas para guiar decisões** com mais segurança.
- 🇧🇷 **Não** se trata de decorar KPIs "de prateleira" ou repetir fórmulas prontas, e sim de usar dados **com intenção**, em produtos vivos, com times reais e sob pressão.
- 🇧🇷 Fortalecer o raciocínio de PM: alinhar **visão e execução com base em evidência, não em achismos**, e usar **a métrica certa no momento certo**, mesmo quando não há consenso.

> 🇧🇷 "Bora tirar os números da gaveta e colocar as decisões na mesa?"

---

## 2. Introdução aos Dados em Produtos Digitais / Intro to data in digital products

🇧🇷 Com Juliana Reksua (Advanced Data Analyst, iFood), economista, com passagem por estatística, ciência de dados e estratégia de negócio; a conversa é mediada pela Gil, da Tera. A aula mostra **de onde vêm os dados**, o que é **Big Data** e por que os dados se tornaram centrais na tomada de decisão.

🇺🇸 Where data comes from (a short history), Big Data and its 5 Vs, and the three types of data (structured, unstructured, semi-structured).

### De onde vêm os dados? / Where does data come from?

🇧🇷 Usar dados para decidir **não é novidade**: o resumo da aula cita o primeiro experimento estatístico registrado no século XVII e o termo *Business Intelligence* em 1865. A partir dos anos 1920, com o primeiro método de armazenamento (fitas magnéticas), o mundo dos dados passa a crescer de forma **exponencial**.

**Alguns marcos da linha do tempo da aula:**

| Ano | Marco |
|---|---|
| 1865 | Surge a ideia de *Business Intelligence* (inteligência para decisões de negócio) |
| ~1928 | Primeiro método de guardar informações: fitas magnéticas |
| 1946 | ENIAC, o primeiro computador eletrônico |
| 1970 | Surge o **SQL**, linguagem de coleta e tratamento de dados |
| 1974 | Pesquisa de texto (como digitar algo no Google) |
| ~1990 | Primeiras menções ao termo *Big Data*; surge o **Python** |
| 1991 | Internet |
| 1997 | Google |
| 2004 | Facebook |
| 2006 | Hadoop: processamento distribuído para grandes volumes de acesso |
| 2007 | scikit-learn, biblioteca de Python para modelagem ("três linhas de código, você tem um modelo") |
| 2013 | Amazon Redshift: armazenamento em nuvem |
| 2017 | Tecidos e redes de dados (cruzar bases de forma mais fluida) |
| 2019 | Python vira a linguagem mais usada do mundo |
| 2020 | AutoML e plataformas de Data Science (máquinas criando modelos) |

🇧🇷 Dois aspectos marcam a virada a partir da metade do século XX: a **velocidade** das mudanças e as inovações em **comunicação** (carta, rádio, TV, internet, celular). Somados a ferramentas que permitem **visualizar** os dados, eles explicam a curva exponencial.

> 🇧🇷 **Python é só para quem trabalha com dados?** Não. Com bases muito grandes (mais de ~500 mil linhas) o Excel deixa de funcionar, e SQL e Python facilitam. Mas, segundo a professora, **dominar essas ferramentas não é o que define um bom profissional de dados**.

### Big Data e os 5 Vs / Big Data and the 5 Vs

![Os 5 Vs do Big Data: volume, velocidade, variedade, veracidade e valor, cada um com um exemplo da aula. Abaixo: analisar muitos dados não faz um bom analista; entender o que os dados contam, com ética, e levar isso para a decisão, sim.](../../../imagens-images/dpl-02/cinco-vs-big-data.png)

🇧🇷 *Big Data* é um grande conjunto de dados vindo de muitas fontes, com características e estruturas diferentes. A professora comenta que já viu os "Vs" como 3 e como 7; ela usa **5**:

| V | O que significa (resumo da aula) | Exemplo do vídeo |
|---|---|---|
| **Volume** | A quantidade de dados produzida e armazenada é enorme, sem precedentes | Estudo citado (2020): em 6 minutos, mais de 9 mil terabytes, como 2 milhões de stories no Instagram e 250 milhões de mensagens no WhatsApp |
| **Velocidade** | Os dados precisam ser lidos e processados em tempo hábil; sem essa velocidade, o volume nem existiria | A cada minuto: 500 horas de vídeo no YouTube, 404 mil horas assistidas na Netflix |
| **Variedade** | Textos, imagens, áudios, vídeos, cliques, passos, compras… "hoje, dado é tudo" | Até a posição do mouse na tela é dado para alguém |
| **Veracidade** | Extrair informação de forma **confiável**: robustez e consistência | Antes da análise, confira a veracidade dos dados que a geraram; dados errados (ou mal interpretados de propósito) podem até direcionar público eleitoral |
| **Valor** | Que valor dá para extrair, de acordo com o propósito do negócio | Para uma empresa, segmentar usuários; para um médico, otimizar exames e ter histórico dos pacientes |

> 🇧🇷 **Analisar muito dado faz de alguém um bom analista?** Não. Segundo a professora, você pode analisar pouquíssimos dados e ser excelente. O que conta é entender **o que os dados estão contando**, trabalhar com eles com **ética** e levar um **direcionamento estratégico** ao time (negócio, produto…).

🇧🇷 No fim, o objetivo é **tomar decisões estratégicas orientadas a dados**. Alinhar com stakeholders e fazer as decisões da análise serem **compartilhadas e validadas** pelos times melhora muito o resultado.

### Tipos de dados / Types of data

| Tipo | O que é | Exemplo |
|---|---|---|
| **Estruturado** | Armazenado, acessado e processado num **formato fixo**; exige menos processos | Uma planilha tratada: linhas e colunas. No Big Data, **não passam de ~20%** dos dados |
| **Não estruturado** | Forma e estrutura **desconhecidas**; o **maior volume** de dados; precisa de tratamento para análise | Fotos, posts, buscas no Google, músicas ouvidas |
| **Semiestruturado** | Mistura dos dois: o conteúdo é não estruturado, mas ganha "etiquetas" | A mesma foto enviada por e-mail ou salva numa pasta: agora se sabe quem enviou, para quem e onde está |

### Para que e para quem são os dados / What data is for, and for whom

🇧🇷 **Big Data não é só negócio.** Dados servem em qualquer situação onde (1) há necessidade de melhoria e (2) nós, humanos, não conseguimos captar sozinhos. Exemplo do vídeo: um time de vôlei que media batimentos, risco de contusão, tempo de resposta à bola e posição na quadra para estudar cada adversário. A gente já vive imerso em dados (e gera muitos sem perceber), então dá para ter **menos medo** de trabalhar com eles.

🇧🇷 A tecnologia fez surgir um novo tipo de empresa, que decide com base em dados para medir **efeito, impacto e risco** das decisões. A professora mostra que as marcas mais valiosas de 2020 são empresas que consomem e também geram muitos dados ("dados como o novo petróleo").

🇧🇷 **Quem trabalha com dados?** Não só cientistas e engenheiros de dados: uma **pessoa de produto** que roda um teste para escolher a melhor melhoria também gera dados e decide com base neles. A demanda por esses profissionais cresce ano a ano (gráfico citado, da Austrália).

**Uma pessoa letrada em dados (*data literacy*) precisa de três blocos:**

| Bloco | O que é (segundo a aula) |
|---|---|
| **Ler dados** | Não é só ler gráfico: dado o contexto do negócio (ou produto), **qual análise faz sentido?** Pode ser mínimo, máximo e média, ou um modelo robusto |
| **Coletar e gerenciar dados** | Não é sobre ferramenta (SQL, Python): é receber uma planilha e tratá-la com **olhar crítico**. Ex.: numa pesquisa com 200 usuários, saber o que fazer com 3 respostas "teste" ou vazias e o quanto isso afeta a amostra |
| **Comunicar-se com dados** | Relatórios, dashboards e apresentações claros. Se o stakeholder não entende o gráfico, "nada vale": o produto de dados é feito para outras pessoas consumirem |

🇧🇷 **Competências, do básico ao avançado** (o mapa da aula):
1. **Conhecimento de dados:** o que é um dado, estruturado ou não, de onde vem.
2. **Decisões com dados:** análises básicas (mínimo, média, mediana), visualizações simples, usar dados para fortalecer o argumento de produto ou negócio.
3. **Coleta de dados:** depende do contexto. Uma pesquisa de produto com 500 ou 5 mil usuários cabe no Excel; a base de pedidos do iFood (mais de 2 milhões por dia, analisando 3 meses) não cabe.
4. **Gerenciamento de dados:** organização, preservação e curadoria. Ex.: o pedido no app gera um dado **bruto** (zona *raw*), que é tratado e limpo para analistas e cientistas usarem; em grandes empresas, há **governança** de acessos.
5. **Aplicação:** quem dá direcionamento estratégico precisa garantir antes que o dado **faz sentido** (é consistente? não tem linha duplicada?).

> 🇧🇷 Os itens 1 a 3 são o que, segundo a professora, toda pessoa que quer decidir com dados (ou promover uma cultura *data-driven* no time) deve ter em mente. Ninguém precisa saber tudo: o mapa de skills da Cappra para profissionais de dados chegou a **mais de 200 skills**.

**"Habilidades técnicas são importantes, mas não são suficientes."** (Juliana Reksua)
- 🇧🇷 "De nada adianta programar em 30 linguagens se você não sabe o que fazer com aquilo", e às vezes o problema se resolve **com uma média**. A ferramenta precisa responder ao **problema de negócio**.
- 🇧🇷 **Ética:** em algum momento há um humano por trás do modelo; vieses pessoais se replicam nos modelos (a aula cita casos de modelos racistas, misóginos, machistas).
- 🇧🇷 Uma pesquisa da IBM com cerca de 5.800 executivos (comentada por Josh Bersin) apontou a necessidade de recapacitar cerca de **120 milhões de profissionais** em skills **não técnicas**; entre 2016 e 2018, as soft skills passaram à frente das hard skills no ranking.
- 🇧🇷 **Validade das habilidades técnicas:** até a segunda metade do século XX, uma habilidade técnica "durava" uns 15 anos (ex.: datilografia); hoje, cerca de 5 anos; em dados, **2 a 3 anos**. Por isso, "skill zero" é **saber aprender e se adaptar**, com flexibilidade, resiliência e abertura.

### Cultura *data-driven* / Data-driven culture

🇧🇷 É a cultura em que **toda decisão** é orientada por dados, da mais micro ("água em garrafa ou em lata na geladeira da startup?") à mais macro (comprar outra empresa). **Tecnologia de ponta não basta**: é preciso romper barreiras culturais e organizacionais e ter um novo modelo de liderança. Empresas tradicionais têm processos mais engessados; empresas mais jovens tendem a se adaptar mais rápido.

**Maturidade de dados de uma organização** (exemplo da aula: um salão de beleza):

~~~mermaid
flowchart LR
  A["1. Resistente<br/>não usa dados"] --> B["2. Curiosa<br/>vê valor, mas não<br/>coleta de forma inteligente"] --> C["3. Tática<br/>analisa o passado"] --> D["4. Estratégica<br/>entende o porquê e<br/>antecipa o próximo período"] --> E["5. Data-driven<br/>dados em todas as etapas<br/>e todos os níveis"]
~~~

| Estágio | Como é |
|---|---|
| **Resistente** | Não tem dados e não se importa; pode até ver valor, mas não faz nada para coletar |
| **Curiosa** | Atribui valor aos dados, mas não sabe quais KPIs importam nem como aplicar (ex. do vídeo: papelada no setor público) |
| **Tática** | Analisa comportamentos **passados** (o salão viu um pico às sextas no mês passado), mas não usa para prever nem reorganizar |
| **Estratégica** | Entende a **razão** dos comportamentos e antecipa o que esperar da clientela no próximo período |
| **Data-driven** | Dados coletados e enriquecidos de forma sistemática, usados do planejamento à conclusão; a cultura é absorvida **em todos os níveis**, e todos "falam a mesma língua" |

> 🇧🇷 Nenhum estágio é "errado", mas quem não usa dados perde eficiência e decide com mais risco. Lembrete da professora: **correlação não é causalidade** (o tema volta mais à frente).

**Dois exercícios propostos no vídeo:**
1. 🇧🇷 Preencher o mapa de skills de dados da Cappra agora e de novo no fim do curso, para ver a evolução.
2. 🇧🇷 Pensar em usos de dados no seu dia a dia (saúde, bem-estar, trabalho).

**Aprofunde (indicações da aula):** artigo *The Skills Of The Future Are Now Clear: And Despite What You Think, They're Not Technical* (Josh Bersin); relatório *The enterprise guide to closing the skills gap* (IBM Institute for Business Value); estudo *Trilhas de Conhecimento Organizado por Área* (Cappra Institute for Data Science).

### Usabilidade dos dados: três cases / Data in practice

| Case | O que fazem com dados | Resultado |
|---|---|---|
| **Grupo Pão de Açúcar (Clube Extra)** | Programa de recompensas: produtos mais comprados, ticket médio, marcas preferidas → **clusterizar** os clientes e estudar o comportamento | Promoções com mais conversão (ex.: quem compra muito item de bebê recebe desconto nisso). "Você paga o desconto com seus dados" |
| **Monsanto (hoje Bayer)** | Estatística e testes para recomendar plantio de sementes aos agricultores | Menos risco, mais rendimento, menos uso de terra; testar várias hipóteses ao mesmo tempo aumenta a chance de aprender |
| **iFood** | IA para (1) montar a **lista de restaurantes** de cada pessoa (mesmo morando na mesma casa, as listas diferem) e (2) **prever pedidos e entregadores** por dia e turno (e se chover? feriado?) | Direciona o consumo e organiza a logística |

### Processos de decisão com base em dados / Data-driven decision making

🇧🇷 Ao levar uma análise para o stakeholder, é preciso **comunicar com clareza** e evitar **vieses**. A aula destaca três:

| Viés | O que é | Exemplo da aula |
|---|---|---|
| **De padrão** | O cérebro procura padrões e quer replicá-los | Achar um "padrão" nos números sorteados da loteria. **Correlação não é causalidade**: o consumo de queijo muçarela e o número de doutores em engenharia civil sobem juntos, mas um não causa o outro (site citado: *Spurious Correlations*) |
| **De curto prazo** | Ganhos rápidos dão de 3 a 4 vezes mais dopamina do que ganhos de longo prazo, então tendemos a priorizar o curto prazo | Case do NPS dos restaurantes (abaixo) |
| **De ganhar** | Preferimos a opção apresentada como **ganho** à apresentada como **perda**, mesmo quando são iguais | Jogo de aposta (abaixo) |

**🍕 Case: NPS baixo dos restaurantes no iFood**

🇧🇷 Pesquisas mostram que a maior dor dos restaurantes é ter **poucos pedidos**. Três ações possíveis para aumentar o volume:
1. Enviar **cupons** sem custo para o restaurante se autopromover.
2. Dar **destaque na listagem** para restaurantes com poucos pedidos.
3. **Ajudar o restaurante a melhorar a operação** (estudar ineficiências, acompanhar KPIs, levantar hipóteses).

🇧🇷 A Gil escolheu o cupom ("todo mundo chuta cupom"). Mas 1 e 2 são decisões **curto-prazistas**: quando o cupom ou o destaque acabam, o restaurante não aprendeu a vender mais. A opção 3 é trabalhosa (talvez um ciclo de seis meses, clusterizando perfis e levantando hipóteses), mas resolve a dor **sem criar dependência**. Pergunta-chave: **estou resolvendo a dor ou só mascarando?**

**🎲 Jogo da aposta (enquadramento)**
- 🇧🇷 **Opção 1:** você recebe R$ 1.000 e pode **ganhar mais R$ 500** (ou apostar para ganhar mais R$ 1.000).
- 🇧🇷 **Opção 2:** você recebe R$ 2.000 e pode **perder R$ 500** (ou apostar entre não perder nada e perder R$ 1.000).
- 🇧🇷 As opções seguras levam ao **mesmo saldo (R$ 1.500)**, mas a gente prefere a que fala em "ganhar". **A forma como a informação é transmitida influencia a decisão.**

> 🇧🇷 **A forma de comunicar o trabalho é tão importante quanto o trabalho.** Se você testou 30 hipóteses e conta como se fossem 2, a mensagem fica simplista e diz pouco do seu trabalho. A professora brinca: quem trabalha com dados é "influencer", porque o trabalho é **influenciar decisões**, com base em dados, de forma ética.

### Resumo da aula / Lesson takeaways

**Lembre-se (Juliana Reksua):**
1. 🇧🇷 **Habilidades técnicas são importantes, mas não sozinhas.** É preciso saber usá-las além do técnico: entender o problema, a dor e como gerar valor.
2. 🇧🇷 **As pessoas nem sempre pensam igual a você, e as hipóteses que você escolher as influenciarão.** Decisões grandes (de empresas, de governos) podem depender de como você apresenta os dados.
3. 🇧🇷 **Ferramentas são instrumentos de análise, mas quem toma e direciona decisões é você.** Conhecer contexto social, econômico e financeiro, e ter ética, também faz um bom profissional.

**Checklist da Tera — você deve sair desta aula entendendo:**
1. 🇧🇷 De onde os dados vieram e como vêm sendo usados no mercado nos últimos anos, com o crescimento das áreas de dados.
2. 🇧🇷 Como o uso de dados se tornou estratégico e decisivo na tomada de decisão de negócios.
3. 🇧🇷 Como é trabalhar com dados, discutindo ferramentas comuns nas áreas de dados.

---

## 3. Introdução aos KPIs / Intro to KPIs

🇧🇷 Com Henrique Santana (Head of Data and Machine Learning na CloudHumans; na plataforma, Principal ML Engineer na Dell), em conversa com o Bruno, da Tera. A aula apresenta o conceito de KPI, os quatro tipos, os KPIs mais comuns por modelo de negócio e a diferença entre **pipeline** e **plataforma**.

🇺🇸 What a KPI is, four KPI types, common KPIs by business model, and pipeline vs platform businesses.

### Conceito e tipos de KPIs / Concept and types

🇧🇷 Um **KPI** (*Key Performance Indicator*) é um indicador-chave para a empresa, normalmente associado a um conjunto de **objetivos**. Um **indicador** pode ser uma única métrica ou um cálculo entre métricas; quando ele é ligado a um **objetivo de negócio** e a empresa toda passa a focar nele, ele é "promovido" a KPI.

~~~mermaid
flowchart LR
  M["Métrica<br/>algo que se mede"] --> I["Indicador<br/>métrica ou cálculo<br/>entre métricas"] --> K["KPI<br/>indicador ligado a um<br/>objetivo de negócio"]
~~~

**Como é um bom KPI (segundo a aula):**
- 🇧🇷 **Mensurável:** toda métrica tem uma medida por trás.
- 🇧🇷 **Relevante para o negócio:** não adianta um KPI que nada tem a ver com o negócio.
- 🇧🇷 **Dá uma direção clara:** de onde vem, para onde vai, mínimo, máximo, o que se espera, qual é a meta.
- 🇧🇷 **Traz o propósito** da empresa embutido nos números.

> 🇧🇷 Sem isso, a empresa fica com vários indicadores perdidos, que ninguém sabe o que significam nem consegue comunicar. "Se a gente não torna ele relevante, as pessoas vão esquecer e ninguém vai bater essa meta."

![Os quatro tipos de KPI: produtividade (CAC e ROI), qualidade (tickets e SLA), capacidade (requisições por minuto e entregas por dia) e estratégia (market share e NPS).](../../../imagens-images/dpl-02/tipos-de-kpis.png)

| Tipo | Objetivo | Exemplos da aula |
|---|---|---|
| **Produtividade** | Otimizar a produção (maximizando ou minimizando) e acompanhar se cresce | **CAC**, custo de aquisição de cliente (quanto menor, melhor); **ROI**, retorno sobre investimento |
| **Qualidade** | Ver se o produto atende às necessidades e vontades dos clientes | Número de **tickets** ou reclamações; **SLA** (*Service Level Agreement*), o tempo para atender |
| **Capacidade** | Fazer "mais com menos" com a estrutura atual | **Requisições por minuto** (aguentar a Black Friday no e-commerce); **entregas por dia** |
| **Estratégia** | Analisar o desempenho das estratégias | **Market share** (fatia do mercado); **NPS** |

**Exemplos do vídeo:**
- 🇧🇷 **CAC:** depende do time de vendas, mas também da retenção, porque trazer um cliente custa muito mais do que mantê-lo. Logo no primeiro exemplo já aparece a importância de **vários times acompanharem os KPIs**.
- 🇧🇷 **Entregas por dia no iFood:** com a mesma quantidade de entregadores, otimizar a rota para fazer três ou quatro entregas na mesma rua sem voltar ao estabelecimento. Os KPIs influenciam como você melhora o produto e a logística.
- 🇧🇷 **NPS é controverso:** tenta medir algo subjetivo com um número (% de promotores − % de detratores). **40 promotores e 60 neutros** dão NPS 40; **60 promotores, 20 neutros e 20 detratores** também dão 40. Situações bem diferentes, mesmo valor. Todo KPI depende de **interpretação**.

### KPIs por tipo de negócio / KPIs by business model

| Negócio | KPIs citados | O que medem |
|---|---|---|
| **Conteúdo com publicidade** (ex.: ge.globo) | **Tempo no site**; **profundidade de rolagem** (*scroll depth*) | Quanto mais tempo e mais rolagem, mais chance de mostrar anúncios e sinal de que o conteúdo agrada |
| **E-commerce** | **Produtos adicionados ao carrinho**; **abandono de carrinho**; **valor médio do pedido** | Intenção de compra; potenciais clientes perdidos (ex.: o livro importado ficou caro com o dólar); quanto cada compra traz |
| **Assinatura** (ex.: Medium, Netflix, Spotify) | **Taxa de conversão** (visitante → assinante); **valor do cliente no longo prazo** / *upsell*; **churn** (taxa de evasão) | Virar assinante; gerar mais valor (plano família, 4K); quem deixa de assinar quando o conteúdo deixa de ser relevante |
| **Geração de leads e vendas** (ex.: HubSpot, SAP, Salesforce, Zendesk) | **Conversão** em etapas (lead → **lead qualificado**); **taxa de fechamento** | Se o comercial não fecha com quem já viu a demo, desperdiça recurso e perde cliente |
| **Aplicativos móveis** (texto da aula) | **Taxa de instalação**; **taxa de ativação** (usou depois de baixar?); **taxa de retenção** (continuou usando?) | O caminho do download ao uso contínuo |

**Pontos de atenção do vídeo:**
- 🇧🇷 **A mesma métrica muda de sentido com o negócio:** no site de conteúdo, mais tempo é bom; num site de vendas, muito tempo pode indicar dúvida.
- 🇧🇷 **Um KPI pode prejudicar outro:** jogar o cliente direto para o carrinho com um único item reduz o **abandono**, mas piora o **valor médio do pedido**. É uma decisão de negócio; por isso é preciso saber qual é o **objetivo principal** para definir qual KPI pesa mais.
- 🇧🇷 **Netflix e churn:** para não depender das produtoras, que podem tirar conteúdo da plataforma (e fazer o assinante sair), a Netflix passou a produzir conteúdo próprio, uma decisão de negócio baseada no KPI de churn.
- 🇧🇷 Vender licenças para empresas (SAP, Salesforce) pede contato mais personalizado, porque o retorno de cada conversão é alto. E quem acompanha os dados precisa estar perto do negócio e dos times que fazem o processo.

### Pipeline × plataforma / Pipeline vs platform

| Pipeline | Plataforma |
|---|---|
| Um **fluxo** que vai da matéria-prima ao produto final; a compra final faz o fluxo continuar | Um modelo que cria valor ao **facilitar trocas** entre dois ou mais grupos interdependentes (produtores e consumidores) |
| Ex.: o tênis da Adidas: matéria-prima → fábrica → armazém → logística → loja → você | Ex.: Uber (sem carros), Airbnb (sem quartos), iFood, a loja de apps do Google |
| KPI típico: vender mais tênis | Ex. do shopping: o que importa não é a venda de um tênis específico, e sim se as lojas são relevantes e se o cliente passa por várias delas |

🇧🇷 **Case Loft (exemplo de plataforma):** a pessoa **compradora** (*buyer*) procura imóveis na vitrine; a **vendedora** (*seller*) anuncia o imóvel; na transação, o pagamento vai para a plataforma, que repassa à vendedora **menos a taxa** (é assim que ela ganha dinheiro). Como tem os dois lados, a plataforma pode oferecer **mais serviços** para ficar ainda mais relevante para as duas pontas.

~~~mermaid
flowchart LR
  B["Buyer<br/>quer comprar"] -->|"busca e paga"| P["Plataforma<br/>(owner)"]
  S["Seller<br/>quer vender"] -->|"anuncia"| P
  P -->|"repassa o valor<br/>menos a taxa"| S
~~~

### Resumo da aula / Lesson takeaways

**Lembre-se (Henrique Santana):**
1. 🇧🇷 **As empresas não são iguais**, então não faz sentido usar as mesmas métricas. Tudo o que se fala de dados precisa estar ligado ao **negócio** e ao seu objetivo.
2. 🇧🇷 **Nem todo indicador vai ser um KPI.** Só os que são chave para o objetivo da empresa são "promovidos", e isso depende de contexto e interpretação.

**Checklist da Tera — você deve sair desta aula entendendo:**
1. 🇧🇷 O conceito de KPIs e suas principais categorias.
2. 🇧🇷 KPIs comumente usados em diferentes tipos de negócios.
3. 🇧🇷 A diferença entre pipeline e plataforma.

---

## 4. Definição e Comunicação de KPIs / Defining and communicating KPIs

🇧🇷 Com Henrique Santana e Bruno, da Tera. A aula mostra como **definir objetivos** (SMART e OKR), como **construir KPIs** (quantos, ligados à jornada do cliente, com o framework Karta) e como **comunicá-los** sem confundir nem enganar ninguém.

🇺🇸 Defining goals (SMART, OKR), building KPIs (5–9, customer journey, Karta framework) and communicating them (shared definitions, engagement, honest data storytelling).

### Definição dos objetivos: SMART / Setting goals

🇧🇷 Primeiro, diferencie **objetivo de sonho**. O **SMART** ajuda: um objetivo precisa ser

| Letra | Significado |
|---|---|
| **S** | Específico (*specific*) |
| **M** | Mensurável (*measurable*) |
| **A** | Atingível (*achievable*) |
| **R** | Relevante (*relevant*) |
| **T** | Temporal (*time-bound*) |

🇧🇷 **Exemplo do vídeo (a corrida do Bruno):** "melhorar na corrida" é sonho. "Chegar a um ritmo de **4min20 por km**" é específico e mensurável. É atingível (há pessoas que chegam lá, um *benchmark*), é relevante (ele poderia competir) e precisa de prazo. Com o ritmo atual em torno de 5min/km, "seis a oito meses" parecia sonho; os dois chegam a **três meses**, "pegando firme".

### OKR: objetivos e resultados-chave / OKRs

🇧🇷 O **OKR** (*Objectives and Key Results*), metodologia criada por Andrew Grove (ex-CEO da Intel) e popularizada pelo Google, conecta objetivos e KPIs: o **objetivo** é definido com SMART e os **resultados-chave** (*key results*) são os **KPIs**. Em vez de metas anuais ou de dois anos, os ciclos ficam mais curtos.

> 🇧🇷 **Fórmula:** "Vamos **(objetivo)** até **(prazo)**, medido por **(esse conjunto de key results)**."

🇧🇷 **Exemplo da aula:** "Vamos **aumentar as vendas do PlayStation 5 em 30% até o fim do semestre**", medido por:
- **% de vendas**, mês contra mês;
- **consoles fabricados** por mês (sem produto, não há venda).

🇧🇷 Os dois KRs se equilibram: fabricar muito sem vender só incha o estoque; vender muito rápido sem fabricar acaba com o estoque (como faltou PS5 no mercado).

**Dicas para definir OKRs:**
1. 🇧🇷 **Prepare as pessoas:** o time todo precisa entender o conceito; não adianta só uma área medir assim.
2. 🇧🇷 **Curto prazo:** no máximo **3 meses** (1 mês costuma ser curto para ter ciclo de iteração e feedback).
3. 🇧🇷 **Curto, simples e fácil de memorizar.** "Se eu leio um OKR, respiro e penso, provavelmente ele foi definido errado."
4. 🇧🇷 **De 2 a 5 key results por objetivo:** mais que isso, você se perde.
5. 🇧🇷 **Com números:** nada de subjetividade na medição.

**OKRs em cascata:** não existe um OKR só. O da empresa se desdobra pelos departamentos (logística entrega, marketing traz compradores, fábrica garante a produção) e chega até cada pessoa (ex.: quem faz controle de qualidade mede defeitos e itens aprovados).

~~~mermaid
flowchart TD
  E["Empresa<br/>vender +30% de PS5 até o fim do semestre"] --> L["Logística<br/>entregar os consoles"]
  E --> MK["Marketing<br/>trazer compradores"]
  E --> F["Fábrica<br/>fabricar o suficiente"]
  F --> Q["Controle de qualidade<br/>defeitos e itens aprovados"]
~~~

> 🇧🇷 "Se a empresa quer conquistar o mundo, o departamento pode conquistar um país, e você, pelo menos um estado."

### Construção de KPIs / Building KPIs

🇧🇷 **Quantos KPIs acompanhar?** Nossa memória de curto prazo dá conta de **7 ± 2 itens**, então **5 a 9 KPIs** é um bom número. Muitos KPIs tiram o foco; um só não captura a complexidade. Mas depende do negócio: um piloto de avião que só olhasse altitude, velocidade e combustível deixaria qualquer passageiro desesperado. E existem **indicadores complementares**: vender mais PS5 não faz sentido se o custo dos eletrônicos passar do valor de venda.

**Alinhe os KPIs à jornada do cliente:**

~~~mermaid
flowchart LR
  A["Conhecimento"] --> B["Consideração"] --> C["Compra"] --> D["Serviço"] --> E["Lealdade"]
~~~

🇧🇷 **Exemplo do Starbucks no vídeo:** a pessoa conhece e entra na loja → compra → é chamada pelo nome, gosta do ambiente e da música → faz um cadastro e recebe novidades dos produtos de que mais gosta (lealdade). Dá para ter indicadores em cada etapa.

**Framework Karta KPI** (do objetivo ao KPI):

~~~mermaid
flowchart TD
  O["1. Metas e objetivos"] --> F["2. Fatores críticos de sucesso<br/>ex.: aumentar vendas em X% até tal data"]
  F --> M["3. Métricas<br/>o que acompanhar (conversão, downloads...)"]
  M --> ME["4. Medidas<br/>a unidade por trás de cada métrica"]
  ME --> K["5. Algumas métricas viram indicadores,<br/>e alguns indicadores são promovidos a KPI"]
~~~

🇧🇷 Nem toda métrica é promovida: no exemplo da aula, "download de PDF" é medida, mas não vira indicador. Para virar KPI, precisa ter um **objetivo**, ser **bem mensurável e acompanhável** e ser **relevante** para o negócio.

🇧🇷 **Um indicador para a Tera (exemplo do vídeo):** juntar as respostas de perguntas feitas ao fim dos cursos (como a empresa usa dados, o momento de inovação…) num **índice único de 0 a 100** de maturidade digital das empresas impactadas, divulgado ao mercado. Outras empresas fazem isso, como a Tabela FIPE e o índice da Loft, às vezes em parceria com jornais ou universidades.

### Comunicação de KPIs / Communicating KPIs

**1. Alinhe os conceitos.** 🇧🇷 Marketing acha que venda é o clique em "comprar"; logística, que é quando o produto sai; financeiro, quando o dinheiro cai. Vira a **Torre de Babel**. Se cada um mede de um jeito, o KPI não é confiável. Ao definir o OKR, deixe claro no KR **como** a métrica é medida, numa definição única que todos os times aceitam.

**2. Engaje o time, medindo a coisa certa.** 🇧🇷 **Case dos poços na União Soviética:** perfuradores eram recompensados por **metro perfurado**, para achar petróleo. Os primeiros mil metros são fáceis; depois, cada metro demora mais. Resultado: em vez de ir mais fundo, faziam **vários buracos rasos** e ganhavam a recompensa máxima. O sucesso era achar petróleo, mas a medida era metros. A solução seria um indicador que combine os metros com o objetivo final, com uma **linha de base** (a partir de mil metros, nos lugares mais prováveis), já que só "achou ou não achou petróleo" também não funcionaria.

> 🇧🇷 **"Você sempre vai ter o que você mede."** Saber comunicar o que está medindo e qual é o objetivo é tão importante quanto definir e medir.

**3. Conte a história com dados (*storytelling*), com honestidade.**
- 🇧🇷 Um gráfico precisa ser **acionável**: o exemplo de pizza confusa da aula não permite tirar nada dele.
- 🇧🇷 Livro citado: ***Como Mentir com Estatística***. Vendas de 100 mil, 101 mil e 103 mil num gráfico que **começa no 100 mil, e não no zero**, parecem um salto enorme. É um **erro de proporção**. Passe a informação correta para não enganar a audiência.

### Resumo da aula / Lesson takeaways

**Lembre-se (Henrique Santana):**
1. 🇧🇷 **Alinhar os conceitos** que fundamentam um KPI entre as pessoas do time é essencial para construí-lo e medi-lo ("senão a gente vai perfurar metros adoidado").
2. 🇧🇷 **Ter poucos objetivos** ajuda o time a focar.
3. 🇧🇷 **OKR e outras metodologias são só ferramentas** e podem ser substituídas; o mais importante são **as pessoas**, que precisam entender e se engajar.

**Checklist da Tera — você deve sair desta aula entendendo:**
1. 🇧🇷 Como definir KPIs de forma eficiente a partir de ferramentas e padrões do mercado.
2. 🇧🇷 Como planejar a comunicação e o monitoramento dos KPIs, mantendo o time engajado.

**Referência citada na aula:** livro *Como Mentir com Estatística*.

---

## 5. Métricas para Produtos e Negócios / Metrics for products and business

🇧🇷 Com Igor Torres (Head of Product, Neon), em conversa com o Holmes, da Tera. "Se não dá para medir, fica difícil decidir." A aula vai da **cultura de métricas** a um **framework criado pelo próprio professor** para escolher as métricas certas.

🇺🇸 Why metrics, the data → measure → information → metric ladder, vanity metrics, what makes a good metric, and where metrics sit among research methods.

### Cultura de métricas: por que usar métricas? / Why metrics?

🇧🇷 O trabalho de produto, resumido: olhar para o **cliente** e para o **negócio** e cuidar da troca de valor entre eles, ou seja, **tomar boas decisões que geram valor para os dois lados**. Métricas são uma ferramenta para decidir melhor. E toda decisão começa pela **percepção**.

| Só empatia ou só persona… | …leva a | Com dados |
|---|---|---|
| **Empatia** sem dados vira quase passiva: achamos que sabemos o que o outro pensa | **Viés cognitivo**: julgar com base nas nossas próprias experiências | Um olhar **sem viés** e **dinâmico** |
| **Persona** que não é atualizada vira **"persona de museu"**: fica bonita na parede e é usada só quando convém | Um mundo **fixo e rígido**, com opiniões imutáveis e ultrapassadas | Como um "filme interativo" (ou *reality show*) do cliente, **em tempo real** |

🇧🇷 Produto e cliente mudam o tempo todo (o digital de dois ou cinco anos atrás era outro), então é preciso **observação constante**.

**Do dado à métrica (exemplo do NPS na aula):** tudo começa por uma **pergunta-raiz**, como "o quão satisfeitos nossos clientes estão?".

~~~mermaid
flowchart LR
  P["Pergunta-raiz<br/>o quão satisfeitos estão?"] --> D["Dado<br/>notas de 0 a 10<br/>(20 respostas)"] --> M["Medida<br/>agrupar: 9–10 promotores,<br/>7–8 passivos, ≤6 detratores<br/>(3, 4 e 13)"] --> I["Informação<br/>15% promotores, 20% passivos,<br/>65% detratores"] --> ME["Métrica<br/>NPS = 15% − 65% = −50<br/>(negativo é ruim: subir!)"]
~~~

| Nível | O que é (resumo da aula) |
|---|---|
| **Dado** | A forma mais simples de informação, geralmente um número ou valor |
| **Medida** | Dá clareza ao grupo de dados, agrupando por relação e com um pouco de contexto |
| **Informação** | Dá contexto em forma de significado, deixa a medida entendível |
| **Métrica** | Conta a história completa, **respondendo à pergunta-raiz** |

> 🇧🇷 **Métrica de vaidade** é parar na informação: **número absoluto sem contexto**, sem parâmetro de bom ou ruim, sem objetivo. Ex.: "meu app tem 100 mil downloads", "tenho 100 mil seguidores" (de onde vieram? quantos interagem?). Não ajuda a decidir.

🇧🇷 **Os dados a gente não escolhe**, eles existem por aí e precisamos colhê-los. **As métricas a gente escolhe**: é quando damos sentido aos dados. Uma cultura de dados é condição para uma cultura de métricas.

**O que é uma boa métrica:**
- 🇧🇷 Segundo o livro ***Lean Analytics***: é **comparativa**, **fácil de entender** e é uma **razão** (ex.: "100 km" não diz nada; "100 km **por hora**" você entende na hora).
- 🇧🇷 Segundo ***Planning and Designing Effective Metrics***: **conta uma história** usando dados, medidas e informações.

**Onde as métricas ficam entre os métodos de pesquisa** (gráfico do Nielsen Norman Group citado na aula):

| | Atitudinal (o que as pessoas **dizem**) | Comportamental (o que as pessoas **fazem**) |
|---|---|---|
| **Qualitativo** (por quê?) | **Entrevistas:** por que pensam o que pensam; ricas, boas para explorar, mais difíceis de interpretar | **Testes de usabilidade:** "compre um produto" e perguntar por que clicou ali |
| **Quantitativo** (quanto?) | **Questionários online:** % que prefere a opção 1 ou 2; rápido | **Métricas:** quanto as pessoas fazem o que fazem **dentro do próprio produto** |

🇧🇷 **A brincadeira da banana e da maçã:** perguntar "banana ou maçã?" é rápido e dá uma porcentagem (quantitativo). Perguntar "qual fruta você mais gosta?" abre todas as opções, demora e precisa de interpretação (qualitativo), mas é mais rico. (O Holmes escolheu banana… e depois abacaxi.)

🇧🇷 **Vantagens das métricas:** escalabilidade e agilidade na interpretação. **Limite:** olham do **presente para o passado**; para entender o futuro e as intenções, é preciso pesquisar (atitudinal).

> 🇧🇷 **Antes de falar de métricas: qual pergunta você quer responder?** A métrica é uma ferramenta para responder a ela.

**Aprofunde (indicações da aula):** *Planning and Designing Effective Metrics* (Martin Klubeck); *Lean Analytics: Use Data to Build a Better Startup Faster* (Alistair Croll).

### Métricas como ferramenta: como elas ajudam a decidir? / Metrics as a tool

🇧🇷 **O roadmap em três partes** (o professor usa o *GO Product Roadmap* como síntese: período, nome, e as três partes que importam):

| Parte | Pergunta | Na analogia do golfe |
|---|---|---|
| **Objetivo** (*goal*) | **Onde** queremos ir? (é abstrato, como dirigir numa estrada escura só com o farol) | Ganhar o troféu (o **resultado**, *outcome*) |
| **Features** | **O que** vamos fazer para chegar lá? | As tacadas (a **entrega**, *output*) |
| **Métricas** | **Como** vamos saber que chegamos? | Os sinais de que estamos perto (em 13º lugar? mais à frente?) |

> 🇧🇷 "Empoderamento significa criar um ambiente onde as pessoas são donas dos **resultados**, e não das **tarefas**. Isso não significa menos gerenciamento, significa um gerenciamento melhor." (Marty Cagan, *Empowered*, citado na aula) No produto, a gente aprende as regras do jogo enquanto joga.

**KPI × OKR**

| | KPI (indicador-chave de performance) | OKR (objetivos e resultados-chave) |
|---|---|---|
| **De onde vem** | ***Top-down***: diretoria, C-level, acionistas | Na teoria, ***bottom-up***: dos times que estão perto do produto e do cliente |
| **Para quê** | **Monitorar** a sustentabilidade do negócio, com nível mínimo e máximo de variação | **Atingir**: ultrapassar uma barreira, evoluir algo |

🇧🇷 **KPIs e OKRs podem coexistir** e ajudam o negócio a materializar a visão.

**As seis perspectivas de KPI** (do livro *Key Performance Indicators*, de Bernard Marr, que lista 75 KPIs): **financeira** (a mais comum), **clientes**, **marketing e vendas**, **operacional**, **responsabilidade social e corporativa** e **colaboradores internos**. Produto costuma ficar mais na de **clientes**, com um pouco de financeiro e de marketing e vendas (*growth*), mas a pessoa de produto precisa olhar para tudo, com foco.

> 🇧🇷 **Dica valiosa do professor:** com diretoria, C-level e acionistas, a conversa quase sempre é sobre cinco coisas: **aumentar a receita, diminuir custos, aumentar o market share, aumentar a receita dos clientes existentes (*lifetime value*) e aumentar o valor do acionista**. "No fim do dia, tudo é *business*."

**OKR na prática**
- 🇧🇷 **Objetivo:** a parte **inspiracional**, ligada à visão (ex.: "ter o melhor aplicativo do Brasil").
- 🇧🇷 **Resultados-chave:** a parte **tangível**, que mostra o que é atingir o objetivo (ex.: 5 estrelas na loja de apps, retenção acima de 90%, menos reclamações).
- 🇧🇷 **Quantos:** por grupo de trabalho (squad, tribo, área), uns **3 objetivos**, cada um com **3 a 5 resultados-chave**. Com um só KR dá para desbalancear: a nota na loja chega a 5, mas o app não vende nada.

~~~mermaid
flowchart TD
  V["Visão da empresa<br/>(KPIs já rodando)"] --> O["Objetivos<br/>longo prazo na diretoria;<br/>trimestre ou ano em produto"] --> KR["Resultados-chave<br/>3 a 5 por objetivo"] --> IN["Iniciativas / temas<br/>grupos de épicos e testes"] --> T["Épicos e tarefas"]
~~~

🇧🇷 **A ordem importa:** primeiro entender para onde ir e o que significa sucesso; **só depois** pensar nas iniciativas. Não é preciso ter certeza de que a iniciativa funciona: fazem-se testes para ver se ela mexe no indicador e então evolui-se o produto.

> 🇧🇷 "Muitos bons produtos já foram lançados sem OKR, KPI ou qualquer métrica. Mas é muito difícil ter certeza de que vamos lançar sempre um bom produto sem usar." O importante é saber o **onde, o como e o quê**.

**Métricas de produto × métricas de negócio** (exemplo da cafeteria)

| Métricas de produto | Métricas de negócio |
|---|---|
| O que acontece **do ponto A ao ponto B**: a pessoa entrou querendo café e saiu com o café na mão (tempo para moer, para preparar, se recebeu) | A **relação inteira**: como ela descobriu a cafeteria, se o preço faz sentido, se conseguiu comprar, se voltou e indicou para outras pessoas |
| Muito usadas para design, performance e usabilidade | Antes, durante e depois da visita |

🇧🇷 Uma não vive sem a outra.

**North Star Metric, *boundary metrics* e constelação de métricas**
- 🇧🇷 A **North Star Metric** (métrica estrela-guia) é a métrica de foco, e "sempre vai cair para a receita". O problema é usá-la para **bloquear todas as outras**.
- 🇧🇷 **Boundary metrics** (métricas de limite) vigiam se a busca pela North Star não está prejudicando outra coisa: não dá para aumentar a receita à custa do engajamento.
- 🇧🇷 **Constelação de métricas:** olhar a relação entre as grandes métricas. Uma **métrica de saída** (*output*: engajamento, retenção, receita) é puxada por **métricas de entrada** (*input*: CAC, performance do cadastro…). Ações levam a resultados.

~~~mermaid
flowchart LR
  I1["Input<br/>CAC"] --> O["Output<br/>receita, engajamento,<br/>retenção"]
  I2["Input<br/>performance<br/>do cadastro"] --> O
  I3["Input<br/>..."] --> O
~~~

🇧🇷 **Exemplo do LinkedIn:** colocar um anúncio a cada post aumentaria a receita no curto prazo, mas as pessoas deixariam de engajar e abandonariam o produto. Métricas **sempre se relacionam** (mais engajamento mexe na retenção, que mexe na receita), por isso é preciso conhecer a **jornada** do cliente para escolher quais usar.

**Reflita (da aula):** quais são os objetivos do seu negócio? E quais métricas mostram se você está chegando lá?

**Aprofunde (indicações da aula):** artigo *Não confunda mais: usando OKR e KPI do jeito certo* (Cauê Machado); livro *Key Performance Indicators: The 75 Measures Every Manager Needs to Know* (Bernard Marr); livro *Avalie o que importa* (John Doerr); artigo *Don't Let Your North Star Metric Deceive You* (Brian Balfour, Shaun Clowes e Casey Winters).

### Frameworks de métricas: quais métricas usar? / Metrics frameworks

🇧🇷 Para saber se o negócio vai bem, dá para olhar de dois jeitos: o **crescimento do negócio** (a relação inteira: a pessoa conhece a cafeteria, toma o café, paga, volta) ou a **performance do produto** (o operador dá conta? o cardápio está claro? a pessoa consegue pagar?). Para cada visão, um framework:

![Dois frameworks de métricas: AARRR, as métricas piratas (aquisição, ativação, retenção, indicação e receita), com visão de crescimento do negócio, usado por growth e marketing; e HEART (adoção, engajamento, sucesso da tarefa, retenção e satisfação), com visão de performance do produto, usado por design. Nos dois, as etapas são relações, não um funil rígido.](../../../imagens-images/dpl-02/aarrr-e-heart.png)

| | **AARRR (métricas piratas)** | **HEART** |
|---|---|---|
| **Visão** | Crescimento do negócio (*growth*) | Performance do produto, jornada do cliente |
| **Quem usa mais** | Growth e marketing | Design |
| **Formato** | Costuma ser visto como funil (o professor prefere ver como **relações**) | Não é funil: relação entre métricas |
| **Origem** | Dave McClure (500 Startups) | Google |

> 🇧🇷 **Usuário é quem usa; cliente é quem paga.** Nem sempre as métricas são as mesmas. No B2B2C (ex.: vender café para empresas), quem bebe é o usuário, mas quem compra é a empresa, e o usuário influencia o cliente ("horrível esse café").

#### AARRR, etapa por etapa

**Aquisição** — 🇧🇷 visitantes, conversões, custo por lead: como as pessoas chegam e conhecem o produto.

**Ativação e o CAC** — 🇧🇷 não adianta virar lead se não vira cliente.
- **CAC = custo de vendas e marketing ÷ número de novos clientes.** Ex.: R$ 1.000 num anúncio que trouxe 100 clientes = CAC de R$ 10.
- Entram só os custos **para trazer cada pessoa** (anúncios, num B2B também propaganda física e vendedor); **não** entram custos fixos como desenvolvedores e designers.
- **Para produto, o CAC é moeda de comparação:** testando anúncios com propostas de valor diferentes ("cafeteria fantástica", "melhor café do mundo", "só café orgânico"), o que tiver **menor CAC** mostra qual proposta funciona, e o produto pode se transformar a partir disso. Também cria um vocabulário comum com marketing.

**Retenção, usuários ativos e churn** — 🇧🇷 a pessoa volta?
- **DAU / WAU / MAU** (usuários ativos por dia, semana ou mês) **= ativos no período ÷ total de usuários × 100**. Ex.: 100 de 1.000 entraram no mês = MAU de 10%. Dá para comparar safras: quem entrou no mês 1 voltou no mês 2?
- **A periodicidade depende do produto:** WhatsApp é diário; banco, talvez mensal; delivery, semanal. Exemplo citado: o Facebook tinha uns 66% da base usando todo dia.
- **Recompra** é a retenção vista pelo negócio. **Case do suplemento:** um produto de consumo mensal queria crescer, mas tinha **9% de recompra**. O professor mandou dar um passo para trás: crescer assim só faria o CAC subir sem segurar ninguém.
- **Churn = quem cancelou no período ÷ total no início do período.** É a taxa de cancelamento (às vezes de abandono). **Netflix em 2010:** um churn de cerca de 70% ao ano foi um dos sinais para a virada da locação de vídeo para o streaming. No e-commerce de produtos comprados a cada três anos, "churn" precisa ser reinterpretado.

> 🇧🇷 **O momento do negócio muda a métrica principal:** no começo (antes do Product Market Fit), o essencial é **retenção** ("a pessoa está voltando?"); depois, conseguir trazer pessoas que usam e voltam; na **escala**, fazer a troca de valor funcionar com **receita**.

**Receita** — 🇧🇷
- **MRR** (*Monthly Recurring Revenue*, receita recorrente mensal), no total, por conta (**ARPA**, *Average Revenue Per Account*: uma conta com vários usuários, como Netflix e muitos B2B) ou por usuário (**ARPU**, *Average Revenue Per User*: o usuário é quem paga, como em muitos SaaS).
- **Margem bruta (GM):** quão rentável é o produto (fórmula como está na aula: receita ÷ lucro × 100).
- **LTV (*lifetime value*) = ARPA × período × GM ÷ churn**: quanto cada cliente gera de receita no período. Divide-se pelo churn porque o que interessa é **quem ficou**. Muda de empresa para empresa (um e-commerce que vende de tudo × um que vende só eletrônicos).
- **LTV ÷ CAC:** a Netflix de 2010 tinha um LTV de cerca de US$ 78 e um CAC de uns US$ 10 a 17, ou seja, LTV de **4,3 vezes** o CAC. Olhando só isso, "estava tudo bem"; o churn mostrava o contrário. **Nunca olhe uma métrica só.**

**Indicação (*referral*)** — 🇧🇷 o boca a boca funciona?
- **Coeficiente viral = novos usuários via convite ÷ total de usuários.** Ex.: 100 usuários recebem 10 convites cada; vêm 300 novos → coeficiente 3. Para Product Market Fit, a referência citada é **0,7**.
- **Escolhendo o valor do cupom (exemplo do quadro):** cupons de R$ 25, 50 e 100 trazem coeficientes de 0,5, 0,7 e 0,8. O de **R$ 50** é o melhor equilíbrio: o de 100 custa o dobro para quase o mesmo efeito. (O professor avisa que os números são ilustrativos.)
- **NPS = % promotores (9–10) − % detratores (0–6)**, de −100 a 100. É uma métrica de **recomendação** (atitudinal quantitativa), muitas vezes usada para satisfação. Também existe o **eNPS**, dos colaboradores.
- **CSAT** (*Customer Satisfaction*): a nota de cada tarefa (como as estrelas depois de uma corrida de Uber); é **comportamental**. Dá para amar o Uber e avaliar mal uma corrida, mas uma sequência de CSATs ruins pode derrubar o NPS.

**Os três motores de crescimento** (*A Startup Enxuta*, de Eric Ries; ligados às métricas piratas no livro *Scaling Lean*):

| Motor | O que olhar | Sinal de Product Market Fit citado |
|---|---|---|
| **Pago** | **LTV × CAC** | LTV **3 vezes** maior que o CAC: 1 para 1 é linear; 3 começa a ser exponencial |
| **Aderência** (*stickiness*) | **Churn × taxa de crescimento** | Churn menor que a taxa de crescimento |
| **Viral** | **Coeficiente viral** | A partir de **0,7** (o Nubank é citado como marca que quase não gasta com aquisição) |

🇧🇷 **Case "Café Igor & Holmes":** ao lançar o café frutado, **não** olhar primeiro para o custo de trazer gente, e sim para a **recompra** (a pessoa voltou?). Se volta, há produto. Depois, para **escalar**, entram os motores: anúncios (LTV × CAC, sem perder a retenção) e viralização ("compartilhe com um amigo e ganhe um cupom").

#### HEART, etapa por etapa

| Letra | Pergunta | Métricas citadas |
|---|---|---|
| **Adoção** (*adoption*) | O produto (ou a **feature** nova) está recebendo pessoas? | Downloads e visitas (em relação a algo), leads, cadastros |
| **Engajamento** (*engagement*) | A pessoa interage? | Usuários ativos, visitas no mês, % de interação com as opções do *job to be done* |
| **Sucesso da tarefa** (*task success*) | Ela conclui o *job to be done*? | Conversão (ex.: quem abriu um curso e chegou ao fim; a Tera mede isso agora com você!) |
| **Retenção** (*retention*) | Ela volta a usar? | Recompra, churn, usuários ativos |
| **Satisfação** (*happiness*) | Ela está satisfeita? | Ex.: quem compra e volta pode trocar de café se um concorrente mostrar o status do pedido e entregar no mesmo dia |

> 🇧🇷 **Engajamento é como o usuário interage. Retenção é se ele continua interagindo.** (No WhatsApp: engajamento é tudo o que acontece no dia; retenção é voltar no dia seguinte.)

🇧🇷 O HEART pode ficar **dentro** das métricas piratas e serve tanto numa visão geral quanto em cada etapa (ex.: a **busca** de um e-commerce: as pessoas adotam, engajam, voltam, convertem?). O professor mostra um quadro real em que as iniciativas eram organizadas por esses pilares (dores a aliviar e ganhos a criar), e até os **squads** eram montados por indicador. O HEART vale **em qualquer momento** do negócio.

**Reflita (da aula):** quais conjuntos de métricas (*input*) ajudam a definir a grande métrica (*output*) do seu produto ou negócio?

**Aprofunde (indicação da aula):** *A Startup Enxuta* (Eric Ries).

### Aplicando métricas no dia a dia / Applying metrics day to day

**Quatro tipos de análise** (do livro *Lean Analytics*):

| Análise | O que é | Exemplo da aula |
|---|---|---|
| **Segmentada** | Dividir a base por um critério e comparar | iOS × Android; faixas de idade. "Quem tem iOS compra duas vezes mais?" |
| **Teste A/B** | Mudar **uma** coisa e medir o resultado, com um **grupo controle** | Botão verde × vermelho. **Cuidado:** precisa de estatística (a amostra representa a população?) e de atenção à sazonalidade (testar um e-commerce na Black Friday distorce tudo) |
| **Multivariada** | Mudar **várias** coisas e ver a correlação | Botão verde × vermelho **e** iOS × Android: quem clica em qual? Mais complexa |
| **Coorte (safra)** | Comparar grupos parecidos ao longo do tempo | **Tera Gym** (abaixo) |

🇧🇷 **Case Tera Gym (análise de coorte):** a academia abre em janeiro só com aparelhos (o MVP). Em fevereiro, libera a **piscina**; em maio, o **crossfit**. Quem entrou em janeiro veio pelos aparelhos; quem entrou em maio veio pelo crossfit, com desejos diferentes. Comparando a retenção do **mês 1** de cada safra (ex.: 20% da safra de janeiro × 50% da de abril), dá para ver se as novas features fizeram as pessoas ficarem. O professor mostra um caso real do produto dele: a retenção no mês 1 passou de 10% (safra de março de 2020) para 19% (safra de dezembro de 2020).

#### O framework CRESCER (Igor Torres, 2021)

🇧🇷 Criado pelo professor juntando **HEART + AARRR + constelação de métricas**, com "gostinho brasileiro". A ideia: **produto e negócio são uma coisa só** (a relação entre cliente e empresa), e a jornada do cliente pode ser acompanhada por **sete grandes indicadores**, cujas iniciais formam **CRESCER**:

![O framework CRESCER, do professor Igor Torres: sete grandes indicadores na jornada do cliente: entrada, engajamento, conversão, retenção, receita, satisfação e compartilhamento. Cada um com o equivalente no HEART e nas métricas piratas, e com o motor de crescimento ligado a ele: entrada e receita ao motor pago, retenção ao motor de aderência e compartilhamento ao motor viral.](../../../imagens-images/dpl-02/framework-crescer.png)

| Indicador | Pergunta | Equivalente citado |
|---|---|---|
| **Entrada** | Como as pessoas estão chegando? | Aquisição (AARRR), adoção (HEART) |
| **Engajamento** | Como estão interagindo? | Engajamento (HEART); "interesse", topo do funil para marketing |
| **Conversão** | Estão concluindo as tarefas propostas? | Sucesso da tarefa (HEART), *job to be done*, ativação (AARRR), fim do funil |
| **Retenção** | Estão voltando a interagir? | Retenção (HEART e AARRR) |
| **Receita** | Tudo isso gera receita? | Receita (AARRR): a linguagem dos executivos |
| **Satisfação** | Estão satisfeitas? Pode ser o grande diferencial frente à concorrência | Felicidade (HEART), NPS |
| **Compartilhamento** | Estão indicando? Ligado à satisfação, mas separado fica mais fácil de potencializar | Indicação (AARRR) |

🇧🇷 Engajamento + conversão = o **uso** do produto; a retenção amarra o uso; tudo termina na receita. Os indicadores também conversam com os **motores de crescimento**: potencializar **compartilhamento** é o motor viral; **receita e entrada**, o motor pago; **retenção**, o motor de aderência. E ajudam a falar com cada área: engajamento, conversão e retenção servem mais a design; receita e entrada, mais a marketing.

**Como usar no dia a dia (os quatro passos do professor):**
1. 🇧🇷 **Entenda como a jornada se aplica** ao seu produto ou negócio.
2. 🇧🇷 **Para cada etapa, mapeie pontos de dor e oportunidades de ganho** e crie iniciativas. Ex.: na entrada, a dor é "não consegue completar o cadastro"; o ganho esperado é "entrar só com o CPF". A métrica: % de quem começa o cadastro e termina.
3. 🇧🇷 **Defina as métricas como sinais do fluxo**, como semáforos numa rua: um sinal vermelho mostra a etapa com "trânsito pesado". Para cada grande indicador (*output*), algumas métricas de entrada (*input*) (ex.: receita → LTV, MRR, ARPU; retenção → usuários ativos, churn). Não precisa usar todas. O OKR pode ser expresso nessa jornada.
4. 🇧🇷 **Analise constantemente e tome decisões.**

> 🇧🇷 **"Métricas são uma ferramenta para a sua tomada de decisão. São um meio, não um fim."**

### Perguntas e respostas (com Gabriel Holmes) / Q&A

- 🇧🇷 **Como chegar na pergunta certa?** Comece pelo mais simples: para onde o negócio está indo? O que o cliente faz com o produto? Quais são os maiores indicadores? Depois quebre até o que falta responder.
- 🇧🇷 **Quais dados explorar?** O processo é **inverso**: não "abra todos os dados"; volte à pergunta e à decisão que precisa tomar, e busque os dados mais ligados a ela, ao cliente e ao negócio.
- 🇧🇷 **Métrica de produto × de negócio?** Para o professor, "no fim do dia, tudo é business": métricas de usabilidade estão dentro do produto, que está dentro do negócio. Ele prefere **não separar**.
- 🇧🇷 **Como não transformar métricas em metas (ruins)?** Atrelar bônus a uma meta só financeira leva ao ***sandbagging*** ("saco de areia"): as pessoas propõem metas mais baixas para bater. Melhor ligar as metas à **evolução do negócio como um todo** (quanto mais alto na hierarquia, mais a meta é o negócio). "Se o negócio não evolui mas você bate suas metas, tem algo errado."
- 🇧🇷 ***Storytelling* para quem decide:** conte a **jornada** do cliente com a empresa (entrar, cadastrar, engajar, comprar, voltar) e use os grandes indicadores para sintetizar. Falar "entrada de pessoas" é mais fácil do que "CAC" para quem não é de marketing.
- 🇧🇷 **Alinhar stakeholders:** o professor só usa métricas para isso. "**O óbvio é individual**" (frase da esposa dele): cada área interpreta "o cliente falou X" de um jeito; a visão quantitativa cria um **vocabulário em comum**.
- 🇧🇷 **Quais métricas acompanhar?** Evite a **paralisia de análise**: comece pelo **OKR** (é por ele que você será cobrado), depois olhe as métricas ligadas a ele para equilibrar, e vá criando um **dicionário** de métricas da empresa. É um trabalho cultural.
- 🇧🇷 **CEO quer uma coisa, cliente outra:** fale a **língua do CEO** (os cinco indicadores de receita, custo, market share, valor dos clientes e valor ao acionista), mas trazendo a visão do cliente: "se o usuário tiver isso e fizer aquilo, mexe aqui". O CEO é quem toma mais risco e precisa estar convencido. Testes e experimentos ajudam a ligar indicadores à receita.
- 🇧🇷 **Janela de comparação:** a análise de **safra**, de acordo com a periodicidade natural do produto (semanal, mensal).
- 🇧🇷 **Taxa ou acumulado?** Prefira **taxa** (é comparativa). Números acumulados tendem à vaidade ("100 mil downloads no ano"); "os downloads cresceram 30%" já tem referência. Receita às vezes aparece acumulada. "Tudo depende."
- 🇧🇷 **Uma métrica que mudou tudo (case B2W, 2014):** a conversão era **vendas ÷ sessões**. O app parecia converter menos que a web, mas no celular a pessoa abre o app muitas vezes antes de comprar (umas 9 sessões por venda, contra 2 na web). Trocando o denominador por **pessoas** que entraram, o app vendia **o dobro** da web. A empresa só adotou dois anos depois. Lição: **olhe como a métrica é formulada.**
- 🇧🇷 **Imprevistos:** com a jornada quebrada em etapas e sinais em cada uma, o imprevisto aparece. Aí entram testes, experimentos e também pesquisa qualitativa ("perguntar ao motorista por que está parado").
- 🇧🇷 **Convencer que uma métrica perdeu o sentido:** com cultura de métricas, mostre que ela não influencia mais o indicador financeiro. Sem cultura, é um trabalho de **destilar**: entender por que a pessoa está presa àquele indicador (valorização? satisfação? crescimento viral?) e ligá-lo a uma métrica que faça sentido.
- 🇧🇷 **CRESCER e stakeholders:** cria vocabulário comum e mostra conexões entre áreas (ex.: mostrar a marketing como a entrada se liga ao engajamento).
- 🇧🇷 **Quando a métrica cai:** quebre a etapa em **microconversões** (baixar o app, abrir, cadastrar, telefone, e-mail…) para achar o erro. Se a mudança for de comportamento externo (ex.: a pandemia no delivery), dê foco a outra métrica que você consegue influenciar.

### Resumo da aula / Lesson takeaways

**Lembre-se (Igor Torres):**
1. 🇧🇷 **Não tenha (só) empatia pelo seu usuário. Tenha métricas.** Uma cultura de métricas e dados dá uma visão dinâmica e sem viés do cliente.
2. 🇧🇷 **Saiba para onde quer ir, o que vai fazer para chegar lá e como vai saber que chegou.** Não importa se é com OKR ou outra coisa.
3. 🇧🇷 **Produto ou negócio? Como quiser chamar:** é o que oferece a troca de valor entre empresa e cliente.
4. 🇧🇷 **Simplificar a visão de métricas associando-a à jornada do cliente** facilita o dia a dia e a decisão.
5. 🇧🇷 **Métricas são uma ferramenta: um meio, não o fim.**

> 🇧🇷 Fechamento do professor, citando Steve Blank: mais do que métrica por métrica, a gente quer saber se **"a pupila do cliente dilata"**. "Coloque seu coração, entenda seu produto, entenda seu cliente."

**Checklist da Tera — você deve sair desta aula entendendo:**
1. 🇧🇷 A importância de definir e acompanhar métricas para avaliar com os stakeholders a evolução do produto digital.
2. 🇧🇷 A relação entre as métricas e o roadmap de produto.
3. 🇧🇷 O que são e como funcionam KPIs e OKRs.
4. 🇧🇷 Quais métricas são mais relevantes para PMs, considerando o ciclo de vida e a estratégia de negócios.

**Aprofunde (indicações da aula):** livro *Product Analytics* (Joanne Rodrigues); framework CRESCER + guia de uso (baixado no repositório privado); artigo *Correlação estatística e causalidade em métricas de produto* (Pablo Silva); *Measure What Matters / Avalie o que importa* (John Doerr).
