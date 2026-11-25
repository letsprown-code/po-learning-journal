# Alura · Formação Technical Writing · 02: Crie uma documentação do zero com DDLC

| Campo / Field | Valor / Value |
|---|---|
| Escola / School | Alura |
| Curso / Course | Formação Technical Writing (2 cursos, 18 h) / Technical Writing track |
| Módulo / Module | 02 · Technical Writing: crie uma documentação do zero com DDLC (8 h, intermediário) |
| Instrutora / Instructor | Mari Moreira (líder de Developer Communications no Mercado Pago) |
| Situação / Status | ✅ Concluído na Alura em 25/11/2026 (100%) · quiz do curso: 10 de 10 ✅ |
| Fonte / Source | [Alura: Technical Writing: crie uma documentação do zero com DDLC](https://cursos.alura.com.br/course/technical-writing-crie-documentacao-zero-ddlc) (login) |
| Pré-requisito / Prerequisite | [Curso 01: estratégias, ferramentas e boas práticas](01-estrategias-ferramentas-boas-praticas.md) ✅ |

🇧🇷 Sobre o curso (texto da plataforma): criar uma documentação técnica com o framework DDLC, criar um plano de comunicação para divulgar a documentação, entender a importância da comunicação eficaz na divulgação e planejar indicadores de sucesso.

🇺🇸 About: build technical documentation with the DDLC framework, plan how to announce it, and define success metrics.

## Aulas / Lessons

| # | Aula / Lesson | Atividades / Activities | Situação / Status |
|---|---|---|---|
| 1 | Iniciando seu processo de documentação | 10 | ✅ 10/10 na Alura · quiz ✅ |
| 2 | Estruturando sua documentação | 8 | ✅ 8/8 na Alura · quiz ✅ |
| 3 | Escrita e revisão | 9 | ✅ 9/9 na Alura · quiz ✅ |
| 4 | Publicação | 7 | ✅ 7/7 na Alura · quiz ✅ |
| 5 | Medindo a eficácia da sua documentação | 9 | ✅ 9/9 na Alura · quiz ✅ |

---

## Aula 01 · Iniciando seu processo de documentação / Starting your documentation process

### 1. Apresentação

🇧🇷 O curso aprofunda o Technical Writing com um **processo de documentação do zero**, usando o framework **DDLC**. Cada fase do DDLC é aplicada ao projeto: criar uma documentação desde o início numa plataforma de documentação, o **Gitbook** (gratuito). É para quem trabalha com tecnologia e tem contato com documentação técnica e quer trabalhá-la "de uma ponta a outra".

### 2. Apresentação do projeto do curso

🇧🇷 Diferente do Curso 01 (repositório no GitHub), agora a entrega é uma **documentação com aparência de site** no Gitbook. O papel continua o mesmo: **Tech Writer da Bytebank**, mas seguindo o processo completo: planejamento → criação → revisão → publicação.

- 🇧🇷 O exemplo mostra logo da Bytebank, campo de busca, modo claro e escuro e menus com submenus, como num site.
- 🇧🇷 **Criar conta no [Gitbook](https://www.gitbook.com/):** "Start for free" → entrar com GitHub (o Gitbook integra com várias ferramentas, inclusive o GitHub), com Gmail ou com e-mail → criar uma **organização** (explicado mais adiante no curso). A versão gratuita basta.

### 3. Para saber mais: slides do curso

🇧🇷 PDF com os slides (guardado no repositório privado de materiais). Alguns vídeos foram gravados direto na plataforma e não têm slides.

### 4. O que é o Ciclo de Vida de Desenvolvimento da Documentação (DDLC)?

🇧🇷 **DDLC** (Documentation Development Life Cycle) é um framework de processo de documentação com abordagem parecida com a do **Ciclo de Vida de Desenvolvimento de Software** (SDLC). Duas características, seja qual for a adaptação feita na empresa:
- 🇧🇷 o processo é **sistemático**;
- 🇧🇷 o processo é **cíclico**.

🇧🇷 O objetivo é dar **protagonismo à documentação** nos processos de trabalho, para que ela seja criada e atualizada o tempo todo.

**As 6 etapas:**

~~~mermaid
flowchart LR
  A["1. Análise e<br/>planejamento"] --> B["2. Design /<br/>estruturação"] --> C["3. Desenvolvimento<br/>do conteúdo (escrita)"] --> D["4. Edição e revisão<br/>(proofreading)"] --> E["5. Publicação"] --> F["6. Manutenção"]
  F -->|"ciclo"| A
~~~

| Etapa | O que acontece |
|---|---|
| 1. Análise e planejamento | Começar a planejar a documentação ou o conjunto de documentações |
| 2. Design ou estruturação | Definir a estrutura da documentação |
| 3. Desenvolvimento do conteúdo | Escrever |
| 4. Edição e revisão (*proofreading*) | Ler e validar se o texto atende ao que foi planejado |
| 5. Publicação | Publicar |
| 6. Manutenção | Garantir que a documentação seja mantida e escalável; reforça o caráter **cíclico** |

### 5. Quiz de alternativas para fixar conhecimentos (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou: B e C).

- ✅ **C. Integrar a documentação desde a fase de Design:** alinha as informações com a arquitetura do software desde o início e faz a documentação ser parte do desenvolvimento.
- ✅ **B. Começar na fase de testes:** os recursos estão mais estáveis, o que dá uma visão mais completa e precisa do produto.
- ❌ A e D: a plataforma não trouxe explicação para as alternativas erradas.

### 6. Planejamento da documentação (etapa 1 do DDLC: análise e planejamento)

🇧🇷 É o ponto de partida: **levantar tudo** o que será necessário para construir a documentação.

**O que fazer nessa etapa:**
- 🇧🇷 **Testar o software** para entender como o produto funciona e quais são os fluxos.
- 🇧🇷 **Pedir demos** ao time de desenvolvimento (quando uma pessoa dev apresenta tecnicamente a solução) e **gravar**, para ter material de consulta.
- 🇧🇷 **Analisar a audiência**: quem é o público, o que precisa saber e qual a **bagagem técnica** dele, para definir o nível de detalhe.
- 🇧🇷 **Mapear as ferramentas** necessárias.
- 🇧🇷 **Coletar informações com os SMEs** (*Subject Matter Experts*, pessoas especialistas no assunto), para ter contexto do projeto e das especificações do produto.

**Modelo de documento de planejamento do projeto (Bytebank):**

| Tópico | No projeto do curso |
|---|---|
| 1. Contexto do projeto | A Bytebank passou por um **rebranding** da marca e do app; os materiais de apoio ficaram desatualizados, então é preciso criar novas documentações |
| 2. Público | Pessoas físicas clientes da Bytebank, **sem conhecimento técnico avançado**; pode ser preciso contextualizar conceitos do mercado financeiro |
| 3. Conhecimento técnico | Conhecimento básico de finanças |
| 4. Necessidades apontadas pelos SMEs | Contextualizar todos os serviços da Bytebank, principalmente o de **investimentos**, que acabou de ser lançado |
| 5. Ferramentas necessárias | Para capturas de tela, diagramas, tradução, publicação e criação de vídeos (no projeto, a publicação é no Gitbook) |

- 🇧🇷 **Ferramentas também envolvem pessoas:** se UX ou design ajudam com diagramas e imagens, é preciso alinhar com essas áreas quem entrega o quê, por causa dos prazos.
- 🇧🇷 **Tradução:** o projeto é só em português, mas algumas empresas documentam em mais de um idioma.
- 🇧🇷 O planejamento mapeia necessidades **operacionais** (o que viabiliza a documentação) e de **informação** (o conjunto de materiais reunidos com SMEs e pesquisas).

### 7. Para saber mais: planejamento de documentação em 2 cenários

| Cenário | Como começar | Exemplo da atividade |
|---|---|---|
| **Criar do zero** ("tela em branco") | Defina os objetivos e quem são as pessoas usuárias e suas necessidades (personas ajudam); estruture de forma intuitiva, com índice claro, guias passo a passo e exemplos práticos | Documentação do **Django** (framework web em Python), que vai do básico ao avançado e atende iniciantes e experientes |
| **Atualizar uma documentação existente** ("reforma de casa antiga") | Faça uma **auditoria**: o que está desatualizado, o que simplificar ou expandir (o feedback de usuários e colegas ajuda); use práticas ágeis (quebrar em tarefas menores) e **versionamento** para rastrear mudanças | **Guia de estilo da Microsoft**, atualizado com regularidade |

### 8. Para saber mais: framework Technical Writing Process

🇧🇷 Outro framework de processo de documentação, com **cinco etapas**: planejar, estruturar, escrever, revisar e publicar.

| Etapa | O que envolve |
|---|---|
| **Planejar** | Escopo do projeto, cronograma e processo; perguntas sobre público, revisores, informações existentes, guias de estilo e modelos |
| **Estruturar** | Ordem lógica do documento (estrutura narrativa, por processo, biblioteca ou sistema), com especialistas no assunto |
| **Escrever** | Transformar esboços em rascunhos com técnicas como **KISS**, **Plain English** e **voz ativa**, incorporando a experiência dos especialistas |
| **Revisar** | O "polimento": revisões formais, testes e edição para garantir precisão e usabilidade |
| **Publicar** | Lançar o documento, considerando design gráfico, tradução e produção |

📘 Livro indicado: [*The Technical Writing Process*](https://www.amazon.com.br/Technical-Writing-Process-five-step-procedures-ebook/dp/B00UA3YX46), com modelos prontos.

### 9. Faça como eu fiz: crie seu planejamento de documentação

🇧🇷 Criar o documento de planejamento e levantar tudo o que é necessário para a documentação da Bytebank, com base no modelo do curso ("Curso TW - Modelo de planejamento Bytebank", guardado no repositório privado de materiais).

✅ Projeto prático: [planejamento da documentação da Bytebank no Gitbook](../../../projetos-projects/03-bytebank-gitbook/01-planejamento.md).

### 10. O que aprendemos?

- ✅ O que é o Ciclo de Vida de Desenvolvimento da Documentação (DDLC).
- ✅ Quais são as etapas do DDLC.
- ✅ Como estruturar o planejamento da documentação.

### Quiz comentado da Aula 01 / Lesson 1 quiz

<details><summary>1. Quais são as duas características do DDLC?</summary>

- ✅ **Sistemático e cíclico**: dá protagonismo à documentação e a mantém atualizada.
- ❌ Rápido e barato: não aparece na aula.
- ❌ Linear e com fim definido: contradiz a manutenção, que faz o ciclo recomeçar.
- ❌ Feito só pelo time de desenvolvimento: o trabalho envolve SMEs, stakeholders e outras áreas.
</details>

<details><summary>2. O que são SMEs?</summary>

- ✅ **Pessoas especialistas no assunto** (Subject Matter Experts), que dão contexto e informações.
- ❌ Ferramentas de captura de tela: são um item da lista de ferramentas.
- ❌ Usuários finais: são o público, analisado à parte.
- ❌ Templates do The Good Docs Project: são modelos de documentação.
</details>

**O que eu errei e por quê:** ✅ nada: acertei as 10 perguntas do quiz do curso (25/11/2026).

---

## Aula 02 · Estruturando sua documentação / Structuring your documentation

### 1. Refinamento e alinhamento com as áreas responsáveis

🇧🇷 O alinhamento **não tem número no DDLC**: é um momento de **transição entre as etapas**. Acontece em todas as fases, mas é essencial agora, porque retoma o que veio do planejamento e ajuda na estruturação.

🇧🇷 **Como funciona:** conversas com **stakeholders** (pessoas interessadas no projeto de documentação), **SMEs** e os times que vão trabalhar junto. O trabalho de Tech Writer é colaborativo; é aqui que se fecham acordos sobre o que será feito e como.

**O que alinhar:**

| Ponto | Por quê |
|---|---|
| **Expectativas com o projeto** | Quem pede a documentação costuma achar que ela leva menos tempo e é menos complexa do que é (a instrutora conta que isso acontece até no Mercado Pago). Alinhar evita problemas futuros |
| **Dinâmica com as áreas parceiras** (devs e design) | Há dependências: imagens do design, trechos de código e arquivos técnicos dos devs. Se as agendas não batem, dá para **negociar entrega por fases** com os stakeholders ("entregamos assim agora e complementamos na próxima sprint") |
| **Definição de pronto (DoD, *definition of done*)** | Conceito do Scrum: quando a entrega é considerada pronta. Ajuda a acertar expectativas e, se questionarem a entrega, a resgatar os acordos e argumentar |

🇧🇷 **Documentação é um trabalho contínuo, não tem fim:** não é só uma entrega pontual quando sai uma funcionalidade ou versão nova; sempre há novas entregas ou atualizações.

### 2. Construindo uma cultura de documentação

🇧🇷 **Cultura de documentação** é fazer a documentação ganhar protagonismo nos projetos e ser vista como importante por todos, não só pelo time de Tech Writers. Sem isso, há resistência das equipes e falta de parceria para conseguir informações, imagens e código.

🇧🇷 A instrutora conta que muitas ideias do curso vêm do livro **"Dominando a Redação Técnica: guia essencial para profissionais de tecnologia", de Ellen Baldin**, que tem uma seção sobre cultura de documentação.

**Iniciativas (adaptar ao contexto de cada empresa):**

1. 🇧🇷 **Documentação como critério de aceite das tarefas:** a funcionalidade não é lançada se a documentação não estiver atualizada. No começo haverá resistência ("fica para a próxima sprint"); seja firme e garanta pelo menos a parte inicial.
2. 🇧🇷 **Templates de documentação** para otimizar o trabalho, como os do [The Good Docs Project](https://thegooddocsproject.dev/) (open source).
3. 🇧🇷 **Buscar aliados**, principalmente **lideranças**, que influenciam as áreas.
4. 🇧🇷 **Testes e feedbacks constantes**, internos e externos (ex.: times de UX Research), para garantir que a documentação esteja correta e útil.
5. 🇧🇷 **Capacitar outras pessoas a documentar**, espalhando as boas práticas até virarem parte da cultura da empresa.

### 3. Definindo estrutura e componentes visuais (etapa 2 do DDLC: design)

🇧🇷 No design, pense em:
- 🇧🇷 **Estrutura do menu** da documentação.
- 🇧🇷 **Elementos visuais**: logo, identidade visual, cores e fonte. Trazer a identidade da empresa e do produto gera **coesão e consistência** para a pessoa usuária.
- 🇧🇷 **Recursos visuais** levantados no planejamento (imagens, diagramas): se já existem, é hora de recebê-los e decidir como usá-los.

🇧🇷 **Perguntas do modelo de planejamento para o design:** vai ter as telas do aplicativo? Preciso de mais algum recurso visual? Como quero organizar a documentação na plataforma?

🇧🇷 **No projeto:** o time de design preparou um **Figma** (ferramenta de prototipagem) com as telas do novo app (menu com transferências, investimentos e outros serviços; tela inicial verde com saldo e extrato), o que ajuda a organizar a documentação.

**Assuntos mapeados com stakeholders e SMEs:**

| Assunto | Por que entra |
|---|---|
| Serviço de Investimentos | Recurso novo; dar visibilidade |
| Serviços de Transferências e de Extrato | Algumas informações mudaram com o novo app; aproveitar para atualizar o que já existe |
| Como criar uma conta | É a "porta de entrada" para atrair novas pessoas depois da mudança |
| Glossário ou principais conceitos | O público não tem muito conhecimento técnico de finanças |
| Visão geral do aplicativo | O app é novo; explicar como navegar |
| Histórico de mudanças | Pedido nas reuniões: ter as **release notes** numa linha do tempo, porque o app seguirá em melhoria contínua |

**Organizando a arquitetura da informação no [Octopus](https://octopus.do/)** (ferramenta de visualização de estrutura):
1. 🇧🇷 Agrupe assuntos do mesmo "guarda-chuva": investimentos, transferências e extrato viram subseções de uma seção de serviços.
2. 🇧🇷 **O nome da seção depende do guia de estilo / tom de voz da marca:** mais informal, "Nossos Serviços"; mais formal, "Serviços da Bytebank". O curso escolheu "Nossos Serviços" para ficar mais próximo da pessoa usuária.
3. 🇧🇷 Subseções facilitam a **manutenção**: serviços novos entram ali depois.
4. 🇧🇷 Liste os tópicos de cada página (ex.: PIX, DOC e TED dentro de Transferências, sem uma página para cada, a menos que tenham muito conteúdo).
5. 🇧🇷 "Criar conta" fica no **primeiro nível do menu**, ao lado de "Nossos Serviços", porque não faz sentido dentro de serviços.

~~~mermaid
flowchart TD
  D["Documentação Bytebank"] --> V["Visão geral"]
  D --> S["Nossos Serviços"]
  S --> T["Transferências<br/>(PIX, DOC, TED)"]
  S --> E["Extrato"]
  S --> I["Investimentos"]
  D --> C["Como criar uma conta"]
~~~

🇧🇷 Fazer esse desenho antes ajuda a ter ideia do **tamanho** da documentação e de como será a **navegação**.

### 4. Como formatar sua documentação do projeto (Gitbook)

🇧🇷 Vídeo gravado na plataforma, mostrando o Gitbook (registro do conteúdo; no nosso projeto ficamos no GitHub):

- 🇧🇷 **Organização** = o projeto no Gitbook; uma conta pode ter várias. A versão **gratuita basta** (a instrutora usa a paga por causa dos recursos de métricas da Aula 05).
- 🇧🇷 **Estrutura:** renomear "Untitled" para o nome da documentação ("Bytebank"); a primeira página ("Page") vira "Visão Geral"; **Add new page → New document page** para cada seção (ex.: "Nossos serviços", com a descrição "Conheça os serviços disponíveis da Bytebank"); o **+** cria subpáginas (transferências, extrato, investimentos); arrastar para mudar a ordem.
- 🇧🇷 **Customize:** prévia da página; tema padrão branco no plano gratuito (boa prática de acessibilidade, documentação "clean"; dá para escolher outra cor sólida); **light/dark mode** com botão para a pessoa escolher e modo padrão definido por você; **paginação** (anterior e próxima página); **compartilhamento** com imagem para redes sociais; idioma do conteúdo; exportar em **PDF**; **Page Rating** (avaliação da página com emojis, "altamente recomendada").
- 🇧🇷 **Publicar:** Share → Published Web → "Publish this space to the web", que gera o link. Para alterar páginas, entrar em **Edit**.

### 5. Quiz de alternativas para fixar conhecimentos (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou: B e D). Explicações da plataforma:

- ✅ **D. Valorizar a formatação visual:** é crucial para comunicar bem, principalmente em saúde; uma apresentação organizada ajuda a compreensão e a adesão, e ignorá-la prejudica a documentação e a experiência da pessoa usuária.
- ✅ **B. Envolver especialistas em saúde desde o início:** escolha da Letícia, aceita pela plataforma.
- ❌ **C. Estruturar só pelas características técnicas:** desconsiderar a experiência da pessoa usuária e os benefícios para a saúde pode deixar a informação inacessível ou menos motivadora; a abordagem deve ser holística. *(Esta alternativa foi marcada por engano do Claude ao clicar, não pela Letícia.)*

### 6. Para saber mais: dicas para criar e editar imagens, diagramas e vídeos

| Recurso | Dicas da atividade | Ferramentas citadas |
|---|---|---|
| **Imagens** | Escolher a ferramenta conforme o projeto; manter **coerência visual** (paleta e estilo alinhados à identidade da documentação; consultar o manual da marca ou o time de UX); nas **capturas de tela**, focar nas informações importantes | [Canva](https://www.canva.com/) e [Snappa](https://snappa.com/) (iniciantes), [Photoshop](https://www.adobe.com/br/products/photoshop) (avançado); Snipping Tool no Windows, Command + Shift + 4 ou 5 no Mac |
| **Diagramas** | Usar ferramentas especializadas; **sequência lógica**, sem informação desnecessária; **ícones universalmente reconhecidos**; personalizar cores e estilos conforme a identidade visual | [Draw.io](https://app.diagrams.net/), [Lucidchart](https://www.lucidchart.com/) |
| **Vídeos** | **Roteiros** estruturados e concisos, divididos em seções; **demonstração prática** passo a passo; edição profissional (com apoio de especialistas); **legendas e traduções** para acessibilidade; acompanhar visualizações, comentários e sugestões | [Adobe Premiere](https://www.adobe.com/br/products/premiere), [Wondershare Filmora](https://www.wondershare.net/) |

### 7. Faça como eu fiz: liste as ferramentas e desenvolva um rascunho na plataforma de doc

🇧🇷 Com stakeholders, SMEs e equipes alinhados e a cultura de documentação em mente, criar a estrutura da documentação e definir os componentes visuais (o curso indica o Gitbook).

✅ Projeto prático: [estrutura e ferramentas da documentação da Bytebank](../../../projetos-projects/03-bytebank-gitbook/02-estrutura.md) (no GitHub, por decisão do projeto).

### 8. O que aprendemos?

- ✅ Refinar o projeto.
- ✅ Construir uma cultura de documentação.
- ✅ Alinhar com as áreas parceiras (devs e designers).
- ✅ Criar uma estrutura de documentação.
- ✅ Definir quais componentes serão usados na documentação.

### Quiz comentado da Aula 02 / Lesson 2 quiz

<details><summary>1. Qual iniciativa ajuda a construir uma cultura de documentação?</summary>

- ✅ **Documentação como critério de aceite** das tarefas.
- ❌ Deixar para a próxima sprint: é a resistência que a aula pede para enfrentar.
- ❌ Manter o conhecimento só com Tech Writers: contradiz capacitar outras pessoas.
- ❌ Evitar as lideranças: contradiz buscar aliados.
</details>

<details><summary>2. Por que "Como criar uma conta" fica no primeiro nível do menu?</summary>

- ✅ **Não faz sentido dentro de serviços e é a porta de entrada** para novas pessoas.
- ❌ Por ser a página mais longa: não é citado.
- ❌ Porque o Gitbook não permite subpáginas: falso, o vídeo cria subpáginas pelo +.
- ❌ Porque o guia de estilo proíbe: não aparece; o guia de estilo entra no nome "Nossos Serviços".
</details>

**O que eu errei e por quê:** ✅ nada: acertei as 10 perguntas do quiz do curso (25/11/2026).

---

## Aula 03 · Escrita e revisão / Writing and review

### 1. Começando a escrever sua documentação (etapa 3 do DDLC: desenvolvimento do conteúdo)

🇧🇷 Agora se escreve, com base no planejamento, no mapeamento e na estrutura. O vídeo mostra a escrita da página de **Investimentos** no Gitbook (partindo do texto do documento de planejamento) e o raciocínio por trás dela.

**Dicas de escrita da aula:**
- 🇧🇷 **Escreva uma primeira versão**, mesmo pouco estruturada, e **leia em voz alta** para sentir se está fluida, se falta uma seção explicativa, se a ordem faz sentido e se as frases podem ser reescritas. Se travar, escreva tudo o que imaginou e depois decida o que fica.
- 🇧🇷 **Comece dizendo o que a pessoa vai encontrar na página** (um subtítulo que antecipa o conteúdo). No Gitbook, isso vai na **Page description**: "Nesta seção, você encontra as principais informações sobre o serviço de Investimentos do aplicativo da Bytebank".
- 🇧🇷 Como nem todo mundo conhece investimentos, a página começa com uma seção de **Contexto**.
- 🇧🇷 **Hierarquia de títulos** (heading 1, 2, 3) define a estrutura que aparece na página. Na primeira tentativa, "Contexto" e "Comece a investir" ficaram como nível 2 e os passos como nível 3; depois de ver na **pré-visualização (Preview)**, a instrutora subiu "Contexto" e "Comece a investir" para nível 1 e os passos para nível 2, e o texto ficou mais fluido e destacado.
- 🇧🇷 **A escrita é tentativa e erro:** a primeira versão não precisa ser perfeita; vá refinando.

**Estrutura final da página de Investimentos:**

~~~mermaid
flowchart TD
  T["Investimentos (título)<br/>+ descrição da página"] --> C["Contexto"]
  T --> CI["Comece a investir"]
  CI --> P1["Passo 1: Acesse a seção Investimentos"]
  CI --> P2["Passo 2: Selecione o investimento"]
  CI --> P3["Passo 3: Preencha as informações"]
  T --> N["Próximos passos"]
~~~

🇧🇷 Dicas do Gitbook: ocultar a barra lateral (**Hide Sidebar**) para ver melhor o texto; os ícones ao lado do texto (atalho "^ + /") mudam o tipo de bloco (parágrafo, heading 1, 2, 3).

### 2. Utilizando Inteligência Artificial (I.A.)

🇧🇷 O uso de IA gera debate no mercado, mas a aula convida a vê-la como **aliada**: para destravar bloqueios na escrita e, principalmente, **acelerar a revisão**, refinando o texto antes de mandá-lo para a revisão formal e evitando refações.

🇧🇷 **Exemplo com a [Clarice.ai](https://app.clarice.ai/sign-in)** (IA focada em produção de textos; tem versão paga e teste gratuito):
- 🇧🇷 **Score do texto** com critérios como correção, clareza, concisão, força e originalidade, além de verificar plágio.
- 🇧🇷 Sugestões que apareceram no texto de Investimentos: **pontuação final em falta**, **erro de crase** e **"substantivos rastejantes"** (muitos substantivos seguidos deixam o texto confuso; a dica é transformar substantivos e adjetivos em verbos, parecido com o que a autora Dad Squarisi chama de "fileirinha de dês").
- 🇧🇷 Ao selecionar um trecho, dá para pedir: **simplificar, encurtar, melhorar ou mudar o tom**. Ex.: a frase de contexto virou "No campo de investimentos, você pode gerenciar e aplicar seu dinheiro de acordo com seu perfil de investidor e seus objetivos."
- 🇧🇷 A Clarice não é feita especificamente para Tech Writers, mas reforça o trabalho.

### 3. Definindo as etapas de revisão (etapa 4 do DDLC: edição e revisão)

🇧🇷 **Revisão** é o momento de **validar os documentos antes de publicar**. Pontos importantes:

1. 🇧🇷 **Confirmar quem valida** a documentação (ex.: SMEs). A conversa começou no planejamento; agora, com o conteúdo pronto, é preciso confirmar de novo.
2. 🇧🇷 **Estipular prazos** para receber todos os feedbacks até a publicação. As pessoas têm dificuldade com prazos de revisão, então seja **assertiva**: se há 4 dias para o feedback, deixe claro, porque depois ainda é preciso tempo para os ajustes.
3. 🇧🇷 **Se possível, usar ferramentas como IA** na primeira revisão, para achar erros de gramática, pontuação e outros detalhes.

🇧🇷 Depois de consolidar o texto, compartilhe com quem avalia: SMEs, stakeholders, colegas ou outros Tech Writers. Alguns feedbacks entram já; outros ficam para uma próxima entrega. Faça uma revisão cuidadosa antes de enviar e **estimule os feedbacks**: quem escreve se acostuma com o texto e deixa passar detalhes, e tudo bem.

### 4. Validação com stakeholders e ajustes finais

**Como funciona:**
- 🇧🇷 **Lembrar o escopo** definido no planejamento (alinhar expectativas). No mercado, é comum receber feedbacks **pouco palpáveis**, sem ação clara; é preciso analisar o que de fato é válido.
- 🇧🇷 **Avaliar os feedbacks** recebidos: o que manter, o que é pertinente e o que não é.
- 🇧🇷 **Manter histórico de comentários e alterações** (no Gitbook, o botão **Merge** salva o que foi escrito; no Google Docs, há recursos para ver o texto anterior e as mudanças). Isso preserva o histórico e ajuda a entender **o motivo** de cada sugestão.

🇧🇷 O tempo entre revisão, ajustes e publicação costuma ser curto, então é preciso **parcimônia** para decidir o que entra.

**Planilha de feedbacks do curso** (modelo disponível para baixar; guardado no repositório privado de materiais):

| Nome | Página | Feedback | Responsável | Situação | Acionável | Cabe nessa sprint? | Prazo |
|---|---|---|---|---|---|---|---|
| Ricardo | Principais conceitos | "Senti falta de alguma coisa, acho que está muito vazia" | Stakeholder | Em análise | Não fica claro o que ele precisa | Não | A definir |
| Diego | Como criar sua conta na Bytebank | Usou a CNH e o texto não dizia que ela não podia estar vencida | Usuário | Em análise | Adicionar uma observação para checar a validade dos documentos | Sim | 12/12/2023 |

- 🇧🇷 **Ricardo (vago):** não dá para saber o que falta; precisaria de mais tempo para conversar e entender, e talvez nem caiba no prazo. Fica para depois.
- 🇧🇷 **Diego (concreto):** um ajuste rápido que evita que outras pessoas tenham a mesma dúvida. Entra agora.

### 5. Desenvolvendo o conteúdo (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou). Pergunta: qual prática é recomendada na fase de revisão do DDLC?

- ✅ **Envolver pessoas da equipe sem conhecimento técnico**, para ter uma perspectiva mais ampla. Explicação da plataforma: quem não é especialista técnico traz uma visão valiosa sobre a clareza e a compreensão da documentação para um público mais amplo.
- ❌ Revisar só os trechos de código; ignorar a revisão porque o DDLC "garante" a precisão; achar que ferramentas automáticas de gramática bastam: a plataforma não mostrou explicação para as alternativas erradas.

### 6. Para saber mais: lista de ferramentas de IA para escrita

| Ferramenta | Para quê (segundo a atividade) | Versão gratuita? |
|---|---|---|
| [ChatGPT](https://chat.openai.com/) | Gerar textos técnicos; plugins de tradução, formatação, imagens na versão paga | Sim (com limitações) |
| [Smodin](https://smodin.io/) | Artigos técnicos originais, sem plágio; escolhe tópico, idioma e tom | Sim, limitada |
| [Sudowrite](https://www.sudowrite.com/) | Melhorar estilo, gramática e clareza; destravar bloqueio criativo | Só teste |
| [Rytr](https://rytr.me/) | Assistência rápida na escrita técnica do dia a dia | Sim |
| [Chibi AI](https://chibi.ai/) | Explorar novas perspectivas e estilos no texto técnico | Teste de 2.000 palavras |
| [Surfer](https://surferseo.com/ai/) | Otimizar conteúdo para SEO, concorrência e palavras-chave | Não |
| [Copy.AI](https://www.copy.ai/) | Gerar conteúdo técnico com rapidez e consistência | Sim |
| [Jasper](https://www.jasper.ai/) | Conteúdo técnico original e sem plágio | Teste de 7 dias |
| [Copymatic](https://copymatic.ai/) | Criação de textos técnicos | 10 créditos de teste |
| [Trinka](https://www.trinka.ai/) | Escrita técnica acadêmica | Sim |

### 7. Para saber mais: templates de documentação

🇧🇷 O **[The Good Docs Project](https://thegooddocsproject.dev/)** ensina e capacita a criar documentação de qualidade para software de código aberto e áreas relacionadas, com **templates, recursos, boas práticas e ferramentas**. Baseia-se em tipos de documento, modelos de maturidade, estratégias de conteúdo e diretrizes de escrita, e orienta como personalizar os templates. É feito para devs, Tech Writers e donos de projeto; é colaborativo, com grupos no GitLab. "Os templates são como bússolas."

### 8. Faça como eu fiz: escreva uma documentação e faça a revisão

🇧🇷 Escrever a documentação do projeto e revisá-la, usando a IA como aliada (pode ser a versão gratuita do ChatGPT, com prompts claros e objetivos). A instrutora deixa a [página da Bytebank no Gitbook](https://bytebank-documentation.gitbook.io/bytebank/) como inspiração. Na opinião do instrutor: compartilhar com stakeholders (ou colegas, se o tema for do trabalho) para viver a experiência de revisão.

✅ Projeto prático: [escrita e revisão](../../../projetos-projects/03-bytebank-gitbook/03-escrita-e-revisao.md), com a página de [Investimentos](../../../projetos-projects/03-bytebank-gitbook/docs/investimentos.md).

### 9. O que aprendemos? (exercício da plataforma)

✅ Resposta aberta enviada na plataforma (texto aprovado pela Letícia). O retorno da Alura elogiou a ligação entre contextualização, hierarquia dos títulos e escrita, e lembrou que manter o histórico de alterações garante a rastreabilidade das decisões.

### Quiz comentado da Aula 03 / Lesson 3 quiz

<details><summary>1. Qual dica de escrita a aula dá para quando você trava?</summary>

- ✅ **Escrever uma primeira versão e ler em voz alta**; a escrita é tentativa e erro.
- ❌ Esperar a revisão antes de escrever: inverte a ordem do DDLC.
- ❌ Copiar a documentação de outra empresa e pular para a publicação: não aparecem na aula.
</details>

<details><summary>2. O que fazer com o feedback vago do Ricardo?</summary>

- ✅ **Deixar em análise, sem prazo**, porque não é acionável e não cabe na sprint.
- ❌ Aplicar na hora por vir de stakeholder: não dá para agir sem entender o que falta.
- ❌ Descartar para sempre: feedbacks adiados voltam na manutenção.
- ❌ Publicar o feedback na documentação: não aparece na aula.
</details>

**O que eu errei e por quê:** ✅ nada: acertei as 10 perguntas do quiz do curso (25/11/2026).

---

## Aula 04 · Publicação / Publishing

### 1. Definindo locais de publicação (etapa 5 do DDLC: publicação)

🇧🇷 O processo de publicação **depende da ferramenta**:

| Onde | Como publica (segundo a aula) |
|---|---|
| **GitHub** | O **pull request** é validado por outras pessoas desenvolvedoras (configurado no workflow do GitHub); depois da aprovação e do **merge**, o conteúdo fica disponível no repositório ou num site |
| Repositório + gerador de site | A documentação fica no repositório, e a parte visual é gerada por um gerador de site |
| Ferramenta ou servidor próprio | Ex.: no Mercado Pago, usam o GitHub com um servidor dedicado para o deploy e a publicação |
| **Gitbook** | **Share → Publish to the web → "Publish this space to the web"**; depois, "Visit site" ou "Copy link" para compartilhar |


**Fluxo de publicação no GitHub, passo a passo** (juntando o que os dois cursos ensinam; cada etapa indica a aula de onde veio):

~~~mermaid
flowchart TD
  A["1. Criar o repositório<br/>(New → título único, público ou privado, README → Create repository)<br/><i>Curso 01 · Aula 01</i>"]
  B["2. Criar o arquivo da documentação<br/>(Add file → Create new file → nome.md)<br/><i>Curso 01 · Aula 01</i>"]
  C["3. Escrever em Markdown e conferir no Preview<br/>(# título, ## subtítulo)<br/><i>Curso 01 · Aula 01</i>"]
  D["4. Salvar com commit<br/>(Commit changes + mensagem)<br/><i>Curso 01 · Aula 01 e Docs as Code</i>"]
  E["5. Abrir um pull request com a mudança<br/><i>Curso 01 · Docs as Code; Curso 02 · Aula 04</i>"]
  F["6. Revisão do pull request por outras pessoas<br/>(validação configurada no workflow do GitHub)<br/><i>Curso 02 · Aula 04</i>"]
  G{"Aprovado?"}
  H["7. Merge<br/>(histórico fica nos pull requests: versionamento)<br/><i>Curso 01 · Docs as Code; Curso 02 · Aula 04</i>"]
  I["8. Conteúdo disponível"]
  J["No próprio repositório"]
  K["Num site, com gerador de site<br/>(ex.: Jekyll, motor do GitHub Pages)<br/><i>Curso 02 · Aulas 04 e 05</i>"]
  L["Num servidor próprio de deploy<br/>(ex.: Mercado Pago)<br/><i>Curso 02 · Aula 04</i>"]
  M["9. Divulgar (plano de comunicação)<br/><i>Curso 02 · Aula 04</i>"]
  A --> B --> C --> D --> E --> F --> G
  G -->|"não: ajustar"| C
  G -->|"sim"| H --> I
  I --> J
  I --> K
  I --> L
  J --> M
  K --> M
  L --> M
~~~

🇧🇷 No Docs as Code (Curso 01), essa esteira pode ser automatizada (**entrega contínua**): a cada mudança aprovada na documentação, alguns passos acontecem sozinhos, e a documentação fica sincronizada com o produto.

🇧🇷 A publicação **não é o fim**: é preciso divulgar.

### 2. Formas de comunicar a publicação: plano de comunicação

🇧🇷 Primeiro, identifique o **público**: interno ou externo.

| Público | Canais sugeridos na aula |
|---|---|
| **Interno** (pessoas da empresa) | **Canal oficial de releases** na rede social da empresa (Slack, Discord, Workplace etc.), marcando as pessoas interessadas; e-mail; **compartilhar direto com os stakeholders** (lideranças e áreas parceiras que acompanharam desde o planejamento) |
| **Externo** | Notícia no **site da documentação** (últimas notícias, banner) ou **dentro do aplicativo** (notificação); **newsletter** por e-mail; para público técnico (devs), **release notes**; para o usuário final, **parceria com o time de comunicação/marketing** |

🇧🇷 A instrutora conta que, na prática, usa o **Slack** com um canal de releases: toda sexta-feira, quando há versão nova, posta a mensagem e notifica o canal.

🇧🇷 **Exemplo do Nubank (conta PJ):** os Tech Writers documentam a configuração para o público **interno** (outros times de desenvolvimento). Para o público **externo**, o time pode acionar comunicação e marketing, que escreve um texto mais conversacional no [blog do Nubank](https://blog.nubank.com.br/conta-pj-nubank-novidades/) ("A Conta PJ Nubank: acompanhe as novidades"). A estrutura do post lembra uma documentação técnica: o que é, para quem é, funções disponíveis, situação atual e linha do tempo das mudanças.

### 3. Próximos passos com a sua documentação (etapa 6 do DDLC: manutenção)

🇧🇷 O DDLC é **cíclico**: depois de publicar e divulgar, é preciso planejar o futuro e manter a documentação atualizada. Fontes para a manutenção:

~~~mermaid
flowchart LR
  F1["Feedbacks de SMEs e stakeholders<br/>que não couberam na entrega"] --> M["Manutenção<br/>(volta ao planejamento)"]
  F2["Análise de desempenho<br/>(métricas)"] --> M
  F3["Feedbacks ativos do público<br/>(fóruns, suporte, seção de<br/>feedback na doc, newsletters)"] --> M
  F4["Backlog do produto"] --> M
  M --> P["1. Análise e planejamento"]
~~~

- 🇧🇷 **Feedbacks adiados:** os que ficaram para depois na revisão; agora é hora de ver quais priorizar.
- 🇧🇷 **Métricas:** depende da ferramenta e das integrações; os números mostram o que melhorar (assunto da Aula 05).
- 🇧🇷 **Feedbacks externos:** agora que a documentação está no ar, chegam de fóruns, comunidades, canais, newsletters e e-mails.
- 🇧🇷 **Backlog do produto:** as oportunidades do produto viram mudanças na documentação; as reuniões de planejamento do backlog são o momento de pegar essas atualizações.

### 4. Para saber mais: próximas etapas logo após a publicação

| Etapa | O que fazer | Exemplo da atividade |
|---|---|---|
| **Monitorar o feedback** | Comentários na documentação, pesquisas de satisfação, análises de uso | Microsoft: sistema de comentários na documentação online |
| **Atualizações regulares** | Revisar e atualizar para refletir as versões mais recentes | Documentação do Python, atualizada a cada versão |
| **Melhoria contínua** | Reescrever seções confusas, adicionar exemplos mais claros, reorganizar a estrutura | — |
| **Integração com outros recursos** | Complementar com outros formatos, como tutoriais em vídeo | Adobe Photoshop, com muitos tutoriais em vídeo |
| **Avaliação regular** | Testes de usabilidade, feedback de especialistas, comparação com as melhores práticas do setor | — |

🇧🇷 "A escrita técnica é uma jornada, não um destino."

### 5. Implantando um plano de comunicação eficaz (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou: E). Explicação da plataforma: um **plano de comunicação abrangente** (e-mails, reuniões, postagens em fóruns relevantes, com detalhes sobre a documentação e como usá-la) é crucial para informar todos os stakeholders, dar os detalhes relevantes e garantir a adoção. A plataforma não mostrou explicação para as alternativas erradas.

### 6. Faça como eu fiz: crie uma comunicação para divulgar a documentação (público interno e externo)

🇧🇷 Criar um plano de comunicação: locais de publicação, abordagem etc.

✅ Projeto prático: [publicação, comunicação e manutenção](../../../projetos-projects/03-bytebank-gitbook/04-publicacao-e-comunicacao.md).

### 7. O que aprendemos?

- ✅ Criar um plano de comunicação para a documentação.
- ✅ Planejar a manutenção da documentação.

### Quiz comentado da Aula 04 / Lesson 4 quiz

<details><summary>1. Como se publica uma documentação no GitHub?</summary>

- ✅ **Pull request revisado e aprovado, depois merge.**
- ❌ "Publish this space to the web": é o caminho do Gitbook.
- ❌ Mandar por e-mail: não é forma de publicar citada.
- ❌ Não dá para publicar no GitHub: falso; a aula cita o exemplo do Mercado Pago.
</details>

<details><summary>2. Como comunicar a documentação a usuários finais (pessoas físicas)?</summary>

- ✅ **Parceria com comunicação ou marketing** (como o post do Nubank).
- ❌ Release notes: para público técnico (devs).
- ❌ Só o canal interno de releases: é para o público interno.
- ❌ Não comunicar: vai contra o plano de comunicação.
</details>

**O que eu errei e por quê:** ✅ nada: acertei as 10 perguntas do quiz do curso (25/11/2026).

---

## Aula 05 · Medindo a eficácia da sua documentação / Measuring effectiveness

### 1. Definição dos indicadores de sucesso

🇧🇷 Dois pontos sobre métricas de documentação:
1. 🇧🇷 *"You can't manage what you can't measure"* ("você não pode gerenciar aquilo que não consegue medir"): sem métricas, não sabemos o impacto da documentação nem como reverter números ruins.
2. 🇧🇷 As métricas muitas vezes **vão além da própria documentação**. Ex.: numa empresa com suporte, o sucesso da documentação pode aparecer nos números do suporte.

**Caminho com duas perguntas:**

~~~mermaid
flowchart LR
  R["1. Qual resultado espero<br/>com a documentação?"] --> D["2. Quais dados mostram<br/>se estou chegando lá?"]
~~~

| Resultado esperado | Possíveis dados |
|---|---|
| **Aumentar a adoção do produto** (mais pessoas criando conta e usando os serviços da Bytebank) | Número de pessoas que usam o produto (cruzando com as datas de publicação das documentações); percentual de satisfação; taxa de retenção (quem entra e permanece) |
| **Diminuir casos de suporte** | Número de tickets abertos; número de acessos à documentação; percentual de satisfação |

- 🇧🇷 A métrica da documentação costuma ser **indireta**: vem do **cruzamento** com outros dados, não só do número de acessos.
- 🇧🇷 Documentação é **subjetiva**: até uma nota de satisfação pode ter vários motivos por trás. Tudo bem **recalcular a rota** da forma de medir.
- 🇧🇷 Com os dados, planeja-se a rota: atualizar documentações existentes, fazer testes de usabilidade etc.

### 2. Métricas relacionadas aos usuários e à documentação

🇧🇷 Métricas dependem do contexto: empresa, ferramentas e se há times de **BI ou dados** para ajudar.

**Dois grandes grupos:**

| Grupo | Exemplos |
|---|---|
| **Métricas da documentação em si** | Número de acessos; páginas mais e menos visitadas; percentual de satisfação ("Gostei"/"Não gostei"; no Gitbook, emojis de rosto feliz, neutro e triste) |
| **Métricas da pessoa usuária** (mais indiretas) | Feedback com **campo de comentário** além do botão (ex.: Mercado Pago, comentário opcional que traz muito insumo); **pesquisas** (ex.: VTEX, link para um formulário do Google); **testes com pessoas usuárias** (testes de usabilidade com o time de pesquisa e UX, que trazem métricas subjetivas) |

**Fontes de dados:**
- 🇧🇷 Formulários de feedback.
- 🇧🇷 **Ferramentas de métricas**: o Gitbook tem uma área de insights; ele e boa parte dos sites se integram ao **Google Analytics** (acessos, usuários únicos, visitas).
- 🇧🇷 **Entrevistas com pessoas usuárias** (com o time de UX) e dinâmicas internas no time.
- 🇧🇷 Se houver time de dados ou BI, converse: são especialistas e podem trazer outras fontes.

### 3. Simulando métricas no projeto do curso

🇧🇷 No projeto, duas fontes: os **feedbacks** (da revisão e depois dela) e os dados do **Gitbook** (o que vale para outra ferramenta é investigar os recursos e as integrações dela).

- 🇧🇷 **Insights → Content scores:** pontuação gerada pelo **Page rating**; mostra um ranking de páginas com sentimento **positivo** e outro com sentimento **negativo**. Uma seção com score negativo pode ser priorizada para melhoria, conforme o feedback.
- 🇧🇷 **Search analytics:** mostra a possibilidade de integrar com ferramentas como o Google Analytics para **cruzar dados**. Ex.: 100 mil acessos com poucos feedbacks pode indicar pouco engajamento, e aí se cria uma estratégia para reverter.

🇧🇷 Objetivo da aula: desenvolver um **olhar sistemático e analítico** sobre as documentações.

### 4. Para saber mais: ferramentas de documentação do mercado

| Ferramenta | O que é (segundo a atividade) |
|---|---|
| [Docusaurus](https://docusaurus.io/) | Código aberto, para construir, implantar e manter documentação; tem versões, blogs e páginas personalizadas (o Facebook já usou) |
| [Sphinx](https://www.sphinx-doc.org/en/master/) | Criado para a documentação do Python; usa [reStructuredText](https://docutils.sourceforge.io/rst.html) e extensões (vários formatos de saída, inclusão de código-fonte) |
| [MkDocs](https://www.mkdocs.org/) | Alternativa rápida e simples ao Sphinx, usando **Markdown** |
| [Jekyll](https://jekyllrb.com/) | Gerador de sites estáticos; é a engine do **[GitHub Pages](https://pages.github.com/)**, então dá para hospedar a documentação direto do repositório no GitHub |

### 5. Para saber mais: métricas da documentação

| O que as métricas mostram | Exemplo da atividade |
|---|---|
| **Conteúdos mais populares e eficazes** | Guia de app de culinária: visualizações das receitas e tempo na seção de dicas |
| **Engajamento e onde melhorar ou expandir** | Manual de software: tempo médio de leitura e taxa de cliques; muito tempo na solução de problemas indica interesse em resolver problemas específicos |
| **Pontos de confusão** | Fórum com avaliações: a quantidade de feedback por página mostra o que gera mais discussão |
| **Otimização da documentação** | Google: analisa a interação com os guias e ajusta a estrutura |
| **Visualização do engajamento** | Gráfico de linha com os downloads de um manual ao longo do tempo |

### 6. Quiz sobre os assuntos abordados ao longo das aulas (exercício da plataforma)

✅ Respondido na plataforma. Pergunta: quais são bons indicativos de sucesso da documentação no contexto do DDLC? (3 alternativas)

Marcadas: B, C e E. Explicações da plataforma:
- ✅ **B. Taxa de rejeição no site:** pode indicar a relevância inicial da documentação, **mas atenção**: sozinha não diz nada sobre a compreensão ou a utilidade do conteúdo.
- ✅ **E. Número de downloads:** é um grande indicativo da demanda e do interesse pela documentação.
- ❌ **C. Tempo médio de resposta do suporte:** pode ser influenciado por vários fatores, não só pela documentação; é um indicador indireto e não específico.
- ⬜ **A. Frequência de atualizações** e **D. Número total de palavras:** não foram marcadas, e a plataforma não mostrou explicação para elas.

### 7. Faça como eu fiz: defina as métricas de sucesso e as formas de obtê-las

✅ Projeto prático: [métricas de sucesso da documentação da Bytebank](../../../projetos-projects/03-bytebank-gitbook/05-metricas.md).

### 8. O que aprendemos?

- ✅ Definir os indicadores de sucesso da documentação.
- ✅ Formas de obter as métricas da documentação.

### 9. Conclusão

🇧🇷 Recapitulação do DDLC: análise e planejamento → design → desenvolvimento do conteúdo → edição e revisão → publicação → manutenção, sempre **cíclico**. Próximos passos sugeridos: conhecer **outros frameworks de processo de documentação** e, principalmente, **praticar** e implementar o processo no trabalho.

### Quiz comentado da Aula 05 / Lesson 5 quiz

<details><summary>1. Quais são as duas perguntas para definir métricas?</summary>

- ✅ **Qual resultado espero? Quais dados mostram se estou chegando lá?**
- ❌ Páginas e palavras; quem escreveu e quando; ferramenta mais barata ou bonita: não são as perguntas da aula.
</details>

<details><summary>2. Por que a métrica da documentação costuma ser indireta?</summary>

- ✅ **O impacto aparece no cruzamento com outros dados** (produto, suporte).
- ❌ Documentação não pode ser medida: contradiz "you can't manage what you can't measure".
- ❌ Só o time de BI vê os números: ele ajuda, mas não é o único caminho.
- ❌ O Gitbook não mostra métricas: falso, tem Insights e Content scores.
</details>

**O que eu errei e por quê:** ✅ nada: acertei as 10 perguntas do quiz do curso (25/11/2026).

---

## Livros e links indicados pela aula / Recommended by the course

- 🔗 [Gitbook](https://www.gitbook.com/) (plataforma do projeto, plano gratuito).
- 📘 [*The Technical Writing Process*](https://www.amazon.com.br/Technical-Writing-Process-five-step-procedures-ebook/dp/B00UA3YX46) (Aula 01).
- 📘 *Dominando a Redação Técnica: guia essencial para profissionais de tecnologia*, de Ellen Baldin (Aula 02).
- 🔗 [The Good Docs Project](https://thegooddocsproject.dev/) (templates, Aula 02).
- 🔗 [Octopus](https://octopus.do/) (estrutura visual da documentação, Aula 02).
- 🔗 [Clarice.ai](https://app.clarice.ai/sign-in) (IA para textos, Aula 03).
- 🔗 [Página da Bytebank no Gitbook, feita pela instrutora](https://bytebank-documentation.gitbook.io/bytebank/) (Aula 03).
- 🔗 [Post do Nubank sobre a conta PJ](https://blog.nubank.com.br/conta-pj-nubank-novidades/) (exemplo de comunicação, Aula 04).
- 🔗 Ferramentas de documentação: [Docusaurus](https://docusaurus.io/), [Sphinx](https://www.sphinx-doc.org/en/master/), [MkDocs](https://www.mkdocs.org/), [Jekyll](https://jekyllrb.com/) / [GitHub Pages](https://pages.github.com/) (Aula 05).
