[← Tera · Digital Product Leadership · 01: Fundamentos de Product Management](README.md)

# Aula 14: Ferramentas para Product Managers / PM toolkit

🇧🇷 Material do Time Tera (sem vídeo). Ferramentas, sozinhas, não resolvem problema nenhum, mas ajudam muito a organizar informações e pensamentos, a decidir e a se comunicar com stakeholders. A Tera oferece um **deck de ferramentas** editável (*Guia de Ferramentas*, também em pptx; a cópia está no repositório privado). São telas com "post-its" virtuais para preencher *frameworks*, da descoberta do problema às métricas. Você não vai usar todas, nem todas ao mesmo tempo, e elas ganham contexto ao longo da jornada.

🇺🇸 Tera's toolkit: 15 canvases from discovery to metrics (CSD matrix, Product Vision Board, TAM/SAM/SOM, empathy map, proto-persona, persona, journey map, stakeholder map, Business Model Canvas, roadmap, impact × effort, MoSCoW, experiment canvas, HEART, OKR).

~~~mermaid
flowchart LR
  subgraph D["Entender o problema e o mercado"]
    CSD["Matriz CSD"] --> PVB["Product Vision Board"] --> TAM["TAM/SAM/SOM"] --> BMC["Business Model Canvas"]
  end
  subgraph U["Entender as pessoas"]
    EMP["Mapa de empatia"] --> PP["Proto-persona"] --> PER["Persona"] --> JOR["Mapa da jornada"] --> STK["Mapa de stakeholders"]
  end
  subgraph P["Priorizar e planejar"]
    RM["Roadmap<br/>Now/Next/Later"] --- IE["Impacto × esforço"] --- MOS["MoSCoW"]
  end
  subgraph M["Testar e medir"]
    EXP["Canvas de experimento"] --> HEART["HEART"] --> OKR["OKR"]
  end
  D --> U --> P --> M
~~~

> 🇧🇷 O agrupamento acima é só para organizar o estudo; na plataforma, as ferramentas aparecem em sequência.

## Entender o problema e o mercado

**Matriz CSD (Certezas, Suposições e Dúvidas)**
- 🇧🇷 Abre perspectivas e organiza o conhecimento sobre o problema de negócio. Responde: o que já sei? Quais são as minhas hipóteses? Quais são as minhas dúvidas?
- 🇧🇷 **Certezas:** de preferência fatos com dados (pesquisas, métricas, uso); sem base sólida, a experiência do grupo com produto, mercado e usuários.
- 🇧🇷 **Suposições:** as hipóteses do grupo sobre o projeto ou problema.
- 🇧🇷 **Dúvidas:** perguntas que você gostaria que os usuários respondessem.
- 🇧🇷 Dicas: **uma ideia por post-it**, pouco texto; todos da mesma cor, porque eles **mudam de coluna** conforme suposições viram certezas, dúvidas viram suposições etc.

**Product Vision Board (Roman Pichler)**
- 🇧🇷 Organiza as informações que dão base à visão de produto. No máximo **dois post-its por coluna**: termos genéricos e amplos são melhores para compor a visão.

**TAM / SAM / SOM**
- 🇧🇷 Perguntas direcionadoras: qual o tamanho do mercado? Como as pessoas resolvem o problema hoje? Quais são os concorrentes diretos e potenciais?
- 🇧🇷 **TAM:** tamanho total do mercado · **SAM:** mercado disponível para a sua solução · **SOM:** fatia realista disponível para o negócio.

**Business Model Canvas (BMC)**
- 🇧🇷 Criado em 2009, primeiro para planejamento estratégico e ciclos de desenvolvimento. Serve para criar projetos do zero e melhorar negócios existentes, em reuniões de decisão e até para apresentar a investidores.
- 🇧🇷 Usos citados: *blueprint* da estratégia; histórico de ações tomadas a partir do canvas; **entender concorrentes** (esboçar o modelo de cada um mostra forças, limites e restrições); entender mais a fundo quem consome.
- 🇧🇷 **Todas as áreas preenchidas precisam de validação.** A Tera indica o artigo *14 maneiras de aplicar o Business Model Canvas* e um vídeo da Strategyzer sobre os blocos.

## Entender as pessoas

**Mapa de empatia**
- 🇧🇷 Organiza o exercício de se colocar no lugar das pessoas usuárias, para entender o impacto da proposta de valor e como se comunicar com elas.

| Bloco | Perguntas |
|---|---|
| **O que vê?** | Ambiente, amigos, o que é comum no dia a dia |
| **O que ouve?** | Quem a influencia, marcas favoritas, onde se informa |
| **O que pensa e sente?** | Preocupações, sonhos, como se sente sobre o seu produto |
| **O que fala e faz?** | Hobbies, o que diz sobre o produto, como decide comprar |
| **Dores** | Medos, frustrações, obstáculos |
| **Necessidades** | O que é sucesso para ela, aonde quer chegar |

> 🇧🇷 Dica: diferencie **certezas (dados)**, suposições com alguma evidência e suposições sem evidência.

**Proto-persona → Persona**

| Proto-persona | Persona |
|---|---|
| Feita a partir de **hipóteses ou vivências** das pessoas do projeto; não precisa de pesquisa | Representação fictícia construída a partir de **etnografia de pessoas reais**, com características psicológicas, representando um grupo parecido |
| Um "protótipo": dá clareza rápida sobre os usuários | Criada com base em **pesquisa com usuários** |
| Deve ser **atualizada e evoluir para persona**, validando ou invalidando as hipóteses com usuários reais | Usada em **Design** (necessidades, comportamentos, objetivos) e **Marketing** (canais, assuntos, melhores momentos para ofertar) |

- 🇧🇷 Para a persona, **comece simples**: converse com 2 ou 3 pessoas (WhatsApp, videochamada), com um roteiro de perguntas sobre o dia a dia, necessidades, o que não tem sido bom, o caminho antes e depois de comprar ou usar.
- 🇧🇷 **Nome, foto e citação** tangibilizam a persona. **Objetivos e dores são o core** da ferramenta.

**Mapa da jornada (experiência do usuário)**
- 🇧🇷 Identifica todos os **pontos de contato** entre a pessoa e o produto; mostra barreiras e oportunidades antes, durante e depois de uma atividade.
- 🇧🇷 **Passo 1:** escolha um momento essencial e divida em **antes, durante e depois** (ex.: pré-compra, compra, pós-compra), quebrando em etapas.
- 🇧🇷 **Passo 2:** em cada etapa, as **ações** da persona, os **pontos de contato** e as **emoções** (feliz, satisfeito, chateada).
- 🇧🇷 **Passo 3:** identifique **oportunidades**: o que torna cada etapa melhor para a pessoa? O que é relevante para o negócio?
- 🇧🇷 Perguntas de apoio: o que a pessoa espera em cada momento? Do que precisa? As habilidades dela combinam com o desafio? O próximo passo está claro?

**Mapa de stakeholders**
- 🇧🇷 Stakeholders podem ser pessoas ou organizações, **internas** (dentro da empresa) ou **externas**, interessadas no sucesso do projeto. O mapa ajuda a priorizar **quem** recebe **o quê** em cada contexto.
- 🇧🇷 Passos: liste todos; entenda o interesse de cada um; identifique como cada um atua ou influencia; separe em **primárias** (diretamente envolvidas), **secundárias** (influentes, afetam indiretamente) e **terciárias** (são afetadas, apesar de não atuarem no produto).

## Priorizar e planejar

**Roadmap de produto (Now / Next / Later)**
- 🇧🇷 Depois de priorizar, organize os esforços num mapa para todos saberem o que priorizar e o que ficou decidido. Comece por: onde estamos? Aonde queremos chegar? Como chegaremos lá?
- 🇧🇷 **Now:** oportunidades endereçadas agora, ativamente · **Next:** oportunidades a refinar e aprofundar antes de executar · **Later:** oportunidades do backlog para aprofundar no futuro.
- 🇧🇷 Serve como ferramenta de **comunicação** com o time e **guia** dos próximos passos.

**Matriz de impacto × esforço**

| | Baixo esforço | Alto esforço |
|---|---|---|
| **Alto impacto** | Bons resultados sem demandar muita energia do time | Resultados expressivos, mas levam mais tempo e recursos |
| **Baixo impacto** | Pouco esforço e pouco resultado: verifique se a ação é mesmo necessária | Muito tempo e baixo impacto: **evitar sempre que possível** |

- 🇧🇷 Primeiro, liste todas as ações necessárias; depois classifique cada uma. Ajuda a **justificar decisões** e redirecionar as próximas ações.

**MoSCoW**
- 🇧🇷 Comunica a stakeholders a importância das iniciativas num **release específico** e ajuda a decidir quanto esforço vai para cada categoria.

| Categoria | Significado |
|---|---|
| **Must have** (obrigatório) | Não negociável: não dá para lançar sem |
| **Should have** (deveria ter) | Importante, mas não vital: sem ela a solução funciona; com ela, agrega muito valor |
| **Could have** (poderia ter) | Não é necessária para a função principal; impacto bem menor se ficar de fora |
| **Won't have (this time)** (não terá agora) | Ajuda a **evitar aumento de escopo**; algumas virão no futuro, outras talvez nunca |

## Testar e medir

**Canvas de experimento**
- 🇧🇷 Desenha o experimento com clareza e segurança: escreva **hipóteses objetivas e testáveis**, defina **métricas de sucesso** e padrões do teste, execute e analise pelos critérios definidos no início.

**HEART**
- 🇧🇷 Modelo de planejamento de métricas para o produto todo ou uma funcionalidade: **H**appiness (satisfação), **E**ngagement (engajamento), **A**doption (adoção), **R**etention (retenção) e **T**ask success (sucesso da tarefa).
- 🇧🇷 Em cada linha: **objetivos** (*goals*), **sinais** (*signals*) e **métricas** (*metrics*). Muito usado por times de Design; dá uma visão de performance ao longo da jornada.

**OKR (Objectives and Key Results)**
- 🇧🇷 Metodologia de gestão para os objetivos principais. O **objetivo** deixa claro o que buscar e engaja (ex.: "tornar-se autoridade no mercado", "oferecer um suporte melhor"). Os **key results** medem o quão perto se está (ex.: "alcançar 10 mil inscritos na newsletter", "formar 5 parcerias de co-marketing").

---

[← Tera · Digital Product Leadership · 01: Fundamentos de Product Management](README.md)
