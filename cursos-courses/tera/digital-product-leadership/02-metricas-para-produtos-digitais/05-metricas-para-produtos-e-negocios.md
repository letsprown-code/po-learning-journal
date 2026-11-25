[← Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais](README.md)

# Aula 5: Métricas para Produtos e Negócios / Metrics for products and business

🇧🇷 Com Igor Torres (Head of Product, Neon), em conversa com o Holmes, da Tera. "Se não dá para medir, fica difícil decidir." A aula vai da **cultura de métricas** a um **framework criado pelo próprio professor** para escolher as métricas certas.

🇺🇸 Why metrics, the data → measure → information → metric ladder, vanity metrics, what makes a good metric, and where metrics sit among research methods.

## Cultura de métricas: por que usar métricas? / Why metrics?

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

## Métricas como ferramenta: como elas ajudam a decidir? / Metrics as a tool

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

## Frameworks de métricas: quais métricas usar? / Metrics frameworks

🇧🇷 Para saber se o negócio vai bem, dá para olhar de dois jeitos: o **crescimento do negócio** (a relação inteira: a pessoa conhece a cafeteria, toma o café, paga, volta) ou a **performance do produto** (o operador dá conta? o cardápio está claro? a pessoa consegue pagar?). Para cada visão, um framework:

![Dois frameworks de métricas: AARRR, as métricas piratas (aquisição, ativação, retenção, indicação e receita), com visão de crescimento do negócio, usado por growth e marketing; e HEART (adoção, engajamento, sucesso da tarefa, retenção e satisfação), com visão de performance do produto, usado por design. Nos dois, as etapas são relações, não um funil rígido.](imagens/aarrr-e-heart.png)

| | **AARRR (métricas piratas)** | **HEART** |
|---|---|---|
| **Visão** | Crescimento do negócio (*growth*) | Performance do produto, jornada do cliente |
| **Quem usa mais** | Growth e marketing | Design |
| **Formato** | Costuma ser visto como funil (o professor prefere ver como **relações**) | Não é funil: relação entre métricas |
| **Origem** | Dave McClure (500 Startups) | Google |

> 🇧🇷 **Usuário é quem usa; cliente é quem paga.** Nem sempre as métricas são as mesmas. No B2B2C (ex.: vender café para empresas), quem bebe é o usuário, mas quem compra é a empresa, e o usuário influencia o cliente ("horrível esse café").

### AARRR, etapa por etapa

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

### HEART, etapa por etapa

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

## Aplicando métricas no dia a dia / Applying metrics day to day

**Quatro tipos de análise** (do livro *Lean Analytics*):

| Análise | O que é | Exemplo da aula |
|---|---|---|
| **Segmentada** | Dividir a base por um critério e comparar | iOS × Android; faixas de idade. "Quem tem iOS compra duas vezes mais?" |
| **Teste A/B** | Mudar **uma** coisa e medir o resultado, com um **grupo controle** | Botão verde × vermelho. **Cuidado:** precisa de estatística (a amostra representa a população?) e de atenção à sazonalidade (testar um e-commerce na Black Friday distorce tudo) |
| **Multivariada** | Mudar **várias** coisas e ver a correlação | Botão verde × vermelho **e** iOS × Android: quem clica em qual? Mais complexa |
| **Coorte (safra)** | Comparar grupos parecidos ao longo do tempo | **Tera Gym** (abaixo) |

🇧🇷 **Case Tera Gym (análise de coorte):** a academia abre em janeiro só com aparelhos (o MVP). Em fevereiro, libera a **piscina**; em maio, o **crossfit**. Quem entrou em janeiro veio pelos aparelhos; quem entrou em maio veio pelo crossfit, com desejos diferentes. Comparando a retenção do **mês 1** de cada safra (ex.: 20% da safra de janeiro × 50% da de abril), dá para ver se as novas features fizeram as pessoas ficarem. O professor mostra um caso real do produto dele: a retenção no mês 1 passou de 10% (safra de março de 2020) para 19% (safra de dezembro de 2020).

### O framework CRESCER (Igor Torres, 2021)

🇧🇷 Criado pelo professor juntando **HEART + AARRR + constelação de métricas**, com "gostinho brasileiro". A ideia: **produto e negócio são uma coisa só** (a relação entre cliente e empresa), e a jornada do cliente pode ser acompanhada por **sete grandes indicadores**, cujas iniciais formam **CRESCER**:

![O framework CRESCER, do professor Igor Torres: sete grandes indicadores na jornada do cliente: entrada, engajamento, conversão, retenção, receita, satisfação e compartilhamento. Cada um com o equivalente no HEART e nas métricas piratas, e com o motor de crescimento ligado a ele: entrada e receita ao motor pago, retenção ao motor de aderência e compartilhamento ao motor viral.](imagens/framework-crescer.png)

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

## Perguntas e respostas (com Gabriel Holmes) / Q&A

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

## Resumo da aula / Lesson takeaways

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

---

[← Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais](README.md)
