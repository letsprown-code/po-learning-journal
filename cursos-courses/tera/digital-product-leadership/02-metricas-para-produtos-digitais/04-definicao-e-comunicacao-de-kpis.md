[← Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais](README.md)

# Aula 4: Definição e Comunicação de KPIs / Defining and communicating KPIs

🇧🇷 Com Henrique Santana e Bruno, da Tera. A aula mostra como **definir objetivos** (SMART e OKR), como **construir KPIs** (quantos, ligados à jornada do cliente, com o framework Karta) e como **comunicá-los** sem confundir nem enganar ninguém.

🇺🇸 Defining goals (SMART, OKR), building KPIs (5–9, customer journey, Karta framework) and communicating them (shared definitions, engagement, honest data storytelling).

## Definição dos objetivos: SMART / Setting goals

🇧🇷 Primeiro, diferencie **objetivo de sonho**. O **SMART** ajuda: um objetivo precisa ser

| Letra | Significado |
|---|---|
| **S** | Específico (*specific*) |
| **M** | Mensurável (*measurable*) |
| **A** | Atingível (*achievable*) |
| **R** | Relevante (*relevant*) |
| **T** | Temporal (*time-bound*) |

🇧🇷 **Exemplo do vídeo (a corrida do Bruno):** "melhorar na corrida" é sonho. "Chegar a um ritmo de **4min20 por km**" é específico e mensurável. É atingível (há pessoas que chegam lá, um *benchmark*), é relevante (ele poderia competir) e precisa de prazo. Com o ritmo atual em torno de 5min/km, "seis a oito meses" parecia sonho; os dois chegam a **três meses**, "pegando firme".

## OKR: objetivos e resultados-chave / OKRs

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

## Construção de KPIs / Building KPIs

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

## Comunicação de KPIs / Communicating KPIs

**1. Alinhe os conceitos.** 🇧🇷 Marketing acha que venda é o clique em "comprar"; logística, que é quando o produto sai; financeiro, quando o dinheiro cai. Vira a **Torre de Babel**. Se cada um mede de um jeito, o KPI não é confiável. Ao definir o OKR, deixe claro no KR **como** a métrica é medida, numa definição única que todos os times aceitam.

**2. Engaje o time, medindo a coisa certa.** 🇧🇷 **Case dos poços na União Soviética:** perfuradores eram recompensados por **metro perfurado**, para achar petróleo. Os primeiros mil metros são fáceis; depois, cada metro demora mais. Resultado: em vez de ir mais fundo, faziam **vários buracos rasos** e ganhavam a recompensa máxima. O sucesso era achar petróleo, mas a medida era metros. A solução seria um indicador que combine os metros com o objetivo final, com uma **linha de base** (a partir de mil metros, nos lugares mais prováveis), já que só "achou ou não achou petróleo" também não funcionaria.

> 🇧🇷 **"Você sempre vai ter o que você mede."** Saber comunicar o que está medindo e qual é o objetivo é tão importante quanto definir e medir.

**3. Conte a história com dados (*storytelling*), com honestidade.**
- 🇧🇷 Um gráfico precisa ser **acionável**: o exemplo de pizza confusa da aula não permite tirar nada dele.
- 🇧🇷 Livro citado: ***Como Mentir com Estatística***. Vendas de 100 mil, 101 mil e 103 mil num gráfico que **começa no 100 mil, e não no zero**, parecem um salto enorme. É um **erro de proporção**. Passe a informação correta para não enganar a audiência.

## Resumo da aula / Lesson takeaways

**Lembre-se (Henrique Santana):**
1. 🇧🇷 **Alinhar os conceitos** que fundamentam um KPI entre as pessoas do time é essencial para construí-lo e medi-lo ("senão a gente vai perfurar metros adoidado").
2. 🇧🇷 **Ter poucos objetivos** ajuda o time a focar.
3. 🇧🇷 **OKR e outras metodologias são só ferramentas** e podem ser substituídas; o mais importante são **as pessoas**, que precisam entender e se engajar.

**Checklist da Tera — você deve sair desta aula entendendo:**
1. 🇧🇷 Como definir KPIs de forma eficiente a partir de ferramentas e padrões do mercado.
2. 🇧🇷 Como planejar a comunicação e o monitoramento dos KPIs, mantendo o time engajado.

**Referência citada na aula:** livro *Como Mentir com Estatística*.

---

[← Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais](README.md)
