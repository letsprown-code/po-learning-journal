# Alura · Formação Technical Writing · 02: Crie uma documentação do zero com DDLC

| Campo / Field | Valor / Value |
|---|---|
| Escola / School | Alura |
| Curso / Course | Formação Technical Writing (2 cursos, 18 h) / Technical Writing track |
| Módulo / Module | 02 · Technical Writing: crie uma documentação do zero com DDLC (8 h, intermediário) |
| Instrutora / Instructor | Mari Moreira (líder de Developer Communications no Mercado Pago) |
| Situação / Status | 🟡 Em andamento / In progress |
| Fonte / Source | [Alura: Technical Writing: crie uma documentação do zero com DDLC](https://cursos.alura.com.br/course/technical-writing-crie-documentacao-zero-ddlc) (login) |
| Pré-requisito / Prerequisite | [Curso 01: estratégias, ferramentas e boas práticas](01-estrategias-ferramentas-boas-praticas.md) ✅ |

🇧🇷 Sobre o curso (texto da plataforma): criar uma documentação técnica com o framework DDLC, criar um plano de comunicação para divulgar a documentação, entender a importância da comunicação eficaz na divulgação e planejar indicadores de sucesso.

🇺🇸 About: build technical documentation with the DDLC framework, plan how to announce it, and define success metrics.

## Aulas / Lessons

| # | Aula / Lesson | Atividades / Activities | Situação / Status |
|---|---|---|---|
| 1 | Iniciando seu processo de documentação | 10 | ✅ 10/10 na Alura · falta quiz |
| 2 | Estruturando sua documentação | 8 | 🟡 Lida, falta exercício + quiz |
| 3 | Escrita e revisão | 9 | ⬜ |
| 4 | Publicação | 7 | ⬜ |
| 5 | Medindo a eficácia da sua documentação | 9 | ⬜ |

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

⬜ A fazer na nossa conversa sobre a aula.

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

⬜ Exercício da Alura (documentação de um app de saúde e bem-estar). Fica para a Letícia responder.

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

⬜ A fazer na nossa conversa sobre a aula.

---

## Livros e links indicados pela aula / Recommended by the course

- 🔗 [Gitbook](https://www.gitbook.com/) (plataforma do projeto, plano gratuito).
- 📘 [*The Technical Writing Process*](https://www.amazon.com.br/Technical-Writing-Process-five-step-procedures-ebook/dp/B00UA3YX46) (Aula 01).
- 📘 *Dominando a Redação Técnica: guia essencial para profissionais de tecnologia*, de Ellen Baldin (Aula 02).
- 🔗 [The Good Docs Project](https://thegooddocsproject.dev/) (templates, Aula 02).
- 🔗 [Octopus](https://octopus.do/) (estrutura visual da documentação, Aula 02).
