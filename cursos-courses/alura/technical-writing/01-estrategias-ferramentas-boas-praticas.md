# Alura · Formação Technical Writing · 01: Aprenda estratégias, ferramentas e boas práticas

| Campo / Field | Valor / Value |
|---|---|
| Escola / School | Alura |
| Curso / Course | Formação Technical Writing (2 cursos, 18 h) / Technical Writing track (2 courses) |
| Módulo / Module | 01 · Technical Writing: aprenda estratégias, ferramentas e boas práticas (10 h, introdutório) |
| Instrutora / Instructor | Mari Moreira (líder de Developer Communications no Mercado Pago) |
| Situação / Status | ✅ Concluído na Alura em 25/11/2026 (100%) · faltam os quizzes comentados das Aulas 04 e 05 e conferir os erros dos quizzes |
| Fonte / Source | [Alura: Technical Writing: aprenda estratégias, ferramentas e boas práticas](https://cursos.alura.com.br/course/technical-writing-estrategias-ferramentas-boas-praticas) (login) |

🇧🇷 Sobre o curso (texto da plataforma): entender o que é Technical Writing e a diferença para UX Writing, conhecer boas práticas e os principais tipos de documentação técnica em TI, aplicar arquitetura da informação, desenvolver documentações como release notes, troubleshooting e tutoriais, e aprender a planejar e analisar documentações.

🇺🇸 About: what Technical Writing is and how it differs from UX Writing, writing best practices, the main types of technical documentation, information architecture, and how to plan and analyze docs.

## Aulas / Lessons

| # | Aula / Lesson | Atividades / Activities | Situação / Status |
|---|---|---|---|
| 1 | O que é Technical Writing? | 12 | ✅ 12/12 na Alura · falta conferir o quiz |
| 2 | Tipos de documentação técnica | 11 | ✅ 11/11 na Alura · falta conferir o quiz |
| 3 | Boas práticas de escrita para documentação | 11 | ✅ 11/11 na Alura · falta conferir o quiz |
| 4 | Outros formatos de conteúdo técnico | 7 | ✅ 7/7 na Alura · falta conferir o quiz |
| 5 | Planejamento e análise de documentações | 9 | ✅ 9/9 na Alura · falta conferir o quiz |

---

## Aula 01 · O que é Technical Writing? / What is Technical Writing?

Objetivos da aula (resumo da própria plataforma, "O que aprendemos?"):
- ✅ Entender a definição de Technical Writing.
- ✅ Diferenciar Technical Writing de UX Writing.
- ✅ Entender como criar um repositório no GitHub.
- ✅ Compreender as habilidades e o perfil de quem é Tech Writer.

### 1. Apresentação / Introduction

🇧🇷 O curso é o primeiro da formação. É voltado a profissionais de tecnologia que lidam com documentação nos projetos e querem melhorar a comunicação técnica, escrevendo documentações que ajudem as pessoas usuárias a atingir seus objetivos. O caminho: definições de TW, tipos de documentação técnica, outros formatos (como o guia do usuário), arquitetura da informação, boas práticas de escrita e, por fim, planejamento e análise de documentações.

🇺🇸 First course of the track, aimed at tech professionals who work with documentation.

### 2. Slides do curso / Course slides

🇧🇷 A plataforma oferece um PDF com os slides (guardado no repositório privado de materiais). Alguns vídeos foram gravados direto na plataforma, mostrando configurações na prática, e por isso não têm slides.

### 3. O que é Technical Writing / What Technical Writing is

**TW está mais perto do dia a dia do que parece.** Todo manual de móvel, de eletrodoméstico ou de produto que você já usou é documentação técnica. Exemplos da aula:
- 🇧🇷 **Manual de montagem de um sofá:** foto do produto (dá contexto e confirma que é o produto certo), informações técnicas (composição, tecido), partes e dimensões e as etapas de montagem. Mesmo um produto simples, bem documentado, fica totalmente compreensível. As informações técnicas também servem para quem presta serviço ou confere o padrão de qualidade, e dão transparência a quem compra.
- 🇧🇷 **Central de ajuda do Zoom:** tutoriais como "How to join a meeting", com passo a passo e vídeo. O que parece óbvio para quem é de tecnologia não é óbvio para quem está começando a usar a ferramenta.

**Definição (Society for Technical Communication, principal órgão da área):**

> 🇧🇷 Technical Writing envolve comunicar informações complexas para quem precisa realizar uma tarefa ou atingir um objetivo.
> 🇺🇸 Technical writing is communicating complex information to those who need it to accomplish a task or goal.

Em outras palavras: **traduzir** informações que parecem complexas e pouco acessíveis em conteúdos **úteis e acessíveis** para o público.

**A imagem do fio embaraçado.** Dev, produto, negócio, UX e outros times geram informações o tempo todo, de forma orgânica e desordenada (as sprints não param). O trabalho de TW é **buscar essas informações nos times e desatar os nós**, para que a pessoa usuária final (técnica ou não, como devs) receba a linha sem nenhum nó.

~~~mermaid
flowchart LR
  D["Desenvolvimento"] --> N(("Informações<br/>embaraçadas"))
  P["Produto"] --> N
  B["Negócio"] --> N
  U["UX"] --> N
  N -->|"Tech Writer busca<br/>e desembaraça"| C["Conteúdo útil<br/>e acessível"]
  C --> F["Pessoa usuária final<br/>(técnica ou não)"]
~~~

### 4. Para saber mais: tipos de entregas em TW / Types of TW deliverables

**Entregas mais comuns:**

| Entrega | O que é | Exemplo citado |
|---|---|---|
| Documentação de produto | Manual que descomplica tarefas, transformando termos técnicos em linguagem amigável (app, dispositivo, software) | Guia de Início Rápido do Slack |
| Manuais técnicos | Traduzem detalhes técnicos em passos simples | Guias do Python, com exemplos e casos de uso |
| Comunicação com devs | TW como ponte entre devs e outras áreas: atualizações, mudanças e melhorias, via release notes, changelogs, e-mails ou Developer Portal (site com tudo que devs precisam saber de um produto) | Changelogs do GitHub |

**Modelos de trabalho** (segundo o livro *The Product is Docs*, que a aula indica como leitura primordial):

| Modelo | Como funciona | Vantagem | Desafio |
|---|---|---|---|
| **Participação direta** | TW integrada a um time de produto, desde o início da esteira de desenvolvimento | Compreensão rápida e profunda do produto | Fica difícil compartilhar aprendizados com outras áreas |
| **Scrum of Writers** | Time dedicado de TWs atuando de forma transversal em vários times de produto | Atua em várias frentes e escala o conhecimento (boas práticas e padrões para a empresa toda) | Envolvimento tardio: pode chegar só na etapa final do desenvolvimento |

A escolha depende das necessidades da empresa e da dinâmica do desenvolvimento de produtos.

### 5. Technical Writing × UX Writing

"São primas dentro das áreas da escrita."

**Semelhanças:**
- 🇧🇷 Texto com foco na **usabilidade e na experiência**: as duas pensam no público e tentam tornar a informação o mais acessível possível.
- 🇧🇷 **Menos é mais:** se dá para dizer em três linhas, não se escreve em cinco.
- 🇧🇷 O texto **orienta uma ação** (fazer login no app; instalar um produto).

**Diferenças:**

| | Technical Writing | UX Writing |
|---|---|---|
| Escrita | Mais técnica e formal (mesmo traduzindo jargões, a essência é técnica) | Mais amigável e conversacional |
| Onde atua | Times de desenvolvimento e TI (squads com devs, QA e especialistas técnicos) | Times de UX e Design |
| Formatos | Documentação técnica, guias do usuário, tutoriais | Microtextos, tom e voz |

**Exemplos da aula:**
- 🇧🇷 **Zoom:** os textos curtos da tela "Entrar em uma reunião" são UX Writing (microtextos); o artigo de ajuda "How to join a meeting", com passo a passo e vídeo, é Technical Writing.
- 🇧🇷 **Jogo de tabuleiro:** os textos no tabuleiro ("perde a vez", "linha de chegada") são UX Writing; o **manual de instruções**, que define quem ganha, quem perde e quantas pessoas jogam, é Technical Writing.

~~~mermaid
flowchart LR
  J["Jogo de tabuleiro"] --> UX["Textos no tabuleiro<br/>= UX Writing"]
  J --> TW["Manual de instruções<br/>= Technical Writing"]
~~~

### 6. Crie seu repositório de documentações / Course project

🇧🇷 O projeto do curso acontece no **GitHub**. O papel: **Tech Writer da Bytebank**, um banco digital fictício. A cada tipo de documentação estudado, cria-se um arquivo Markdown (`.md`) no repositório. Também vale aplicar no contexto da sua própria empresa.

Passo a passo mostrado no vídeo:
1. Criar uma conta gratuita no GitHub ("New to GitHub? Create an account").
2. Criar um repositório em **New**: escolher um título único, definir público ou privado e incluir o **README** (a apresentação padrão do repositório). Clicar em **Create repository**.
3. Para cada documentação: **Add file → Create new file**, dar um nome com extensão `.md`.
4. Escrever em Markdown e conferir o resultado no **Preview** (`#` gera título; `##`, subtítulo).
5. Salvar com **Commit changes** (com mensagem do commit e descrição opcional).

O repositório de exemplo da instrutora se chama `projeto-alura`.

### 7. Para saber mais: Markdown

🇧🇷 Markdown é uma linguagem de marcação simples, que padroniza a formatação de texto sem a complexidade de linguagens mais robustas. É fácil de aprender e muito aceita em plataformas como GitHub, Reddit e ferramentas de blog. A atividade indica o artigo do blog da Alura "Markdown: como trabalhar com essa linguagem de markup?".

### 8. Habilidades e perfil de um Tech Writer / Skills and profile

🇧🇷 O perfil é **dinâmico** e não exige formação específica (no Brasil não há faculdade de TW; a disciplina ainda é nova no mercado).

**Perfil mais comum:**
- 🇧🇷 Formação em comunicação (Jornalismo, Publicidade, Letras) **ou** afinidade com a escrita (engenharia, administração e outras).
- 🇧🇷 **Multidisciplinar** e de fácil relacionamento com outras áreas. Precisa aprender o domínio da empresa (ex.: fintech na Bytebank; edtech se fosse na Alura).
- 🇧🇷 Gosta de aprender e de repassar: **"aprender a aprender e aprender a ensinar"**.
- 🇧🇷 **Visão sistêmica e analítica** para organizar as informações (o fio embaraçado).
- 🇧🇷 **Pesquisa** como forte viés de trabalho: "somos um pouco Sherlock Holmes", investigando onde estão as informações.

**Conhecimentos da área:**
- 🇧🇷 Boas práticas de escrita (Aula 03).
- 🇧🇷 Tipos de documentação (Aula 02) e ferramentas de doc: **GitHub**, **Swagger** (documentação de APIs), **Confluence** (documentação interna), entre outras.
- 🇧🇷 **Arquitetura da Informação**: organização das informações (Aula 03).
- 🇧🇷 **Markdown** ou outras linguagens de marcação (como XML), que usam símbolos para formatar, como o asterisco do negrito no WhatsApp. Muito usadas na abordagem *docs like code*.

### 9. Para saber mais: Docs as Code

🇧🇷 Tratar a documentação **como um projeto de software**: com código-fonte, versões e revisões, no mesmo ecossistema técnico do produto. Exemplo: o **Kubernetes** hospeda a documentação num repositório público no GitHub, e devs contribuem de forma colaborativa.

| Benefício | O que significa |
|---|---|
| Colaboração fácil | Devs e redatores técnicos contribuem como se mexessem em linhas de código |
| Manutenção | Atualizar a doc é como fazer um commit; o histórico fica nos pull requests |
| Controle de versionamento | Cada revisão ganha uma versão: dá para rastrear mudanças e voltar a uma versão anterior |
| Entrega contínua | Uma "esteira" automática roda passos a cada mudança na doc, mantendo-a sincronizada com o produto |

~~~mermaid
flowchart LR
  A["Mudança no produto"] --> B["Commit na<br/>documentação"] --> C["Revisão<br/>(pull request)"] --> D["Nova versão<br/>publicada<br/>automaticamente"]
~~~

### 10. Sobre Technical Writing (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou).

### 11. Faça como eu fiz: organizar o projeto no GitHub

🇧🇷 Criar a conta no GitHub (se não tiver) e iniciar um repositório para a Bytebank, ou com outro tema. Cada tipo de documentação vira um arquivo `.md` (os tipos vêm na Aula 02).

✅ Projeto prático: [Projeto 02 · Documentações da Bytebank](../../../projetos-projects/02-bytebank-docs/README.md).

### Quiz comentado da Aula 01 / Lesson 1 quiz

<details><summary>1. Segundo a Society for Technical Communication, Technical Writing envolve…</summary>

- ✅ **Comunicar informações complexas para quem precisa realizar uma tarefa ou atingir um objetivo.** É a definição apresentada na aula.
- ❌ Escrever textos longos e detalhados: TW segue o princípio "menos é mais".
- ❌ Criar microtextos amigáveis para telas: isso é UX Writing.
- ❌ Escrever código-fonte com comentários: não é a definição de TW. O que se aproxima disso é o Docs as Code, que trata a documentação *como* código.
</details>

<details><summary>2. No exemplo do jogo de tabuleiro, o que é Technical Writing?</summary>

- ✅ **O manual de instruções** que define quem ganha, quem perde e quantas pessoas jogam.
- ❌ "Perde a vez" e a linha de chegada: são textos da interface do tabuleiro, exemplo de UX Writing.
- ❌ O nome do jogo na caixa: não é citado na aula.
</details>

<details><summary>3. Qual é uma SEMELHANÇA entre TW e UX Writing?</summary>

- ✅ **As duas usam o texto para orientar uma ação** (além do foco na experiência e do "menos é mais").
- ❌ Escrita técnica e formal: só vale para TW.
- ❌ Mais perto dos times de UX e Design: só vale para UX Writing.
- ❌ Produzir tom e voz: é formato de UX Writing.
</details>

<details><summary>4. Qual é o principal desafio do modelo Scrum of Writers?</summary>

- ✅ **A TW pode entrar só na etapa final** do ciclo de desenvolvimento, porque atua de forma transversal.
- ❌ Imersão demais num único time: é o desafio da Participação Direta.
- ❌ Não conseguir escalar o conhecimento: é o contrário, escalar é uma vantagem desse modelo.
- ❌ Nunca conversar com os times: não aparece na aula.
</details>

<details><summary>5. Qual benefício do Docs as Code permite rastrear mudanças e voltar a uma versão anterior?</summary>

- ✅ **Controle de versionamento.**
- ❌ Colaboração fácil: é sobre devs e redatores contribuírem juntos.
- ❌ Entrega contínua: é a esteira automática que publica as mudanças.
- ❌ Arquitetura da informação: é um conhecimento da área, não um benefício do Docs as Code.
</details>

**O que eu errei e por quê:** ⬜ a preencher depois que eu fizer o quiz.

---

## Aula 02 · Tipos de documentação técnica / Types of technical documentation

### 1. Preparando o ambiente

🇧🇷 A aula indica o **repositório do projeto do curso** ([alura-cursos/projeto-alura](https://github.com/alura-cursos/projeto-alura)), com todas as documentações da Bytebank criadas nesta aula, para usar como "guia de bolso" e inspiração.

### 2. O que é uma documentação técnica? / What technical documentation is

🇧🇷 O curso foca nas documentações técnicas comuns no **desenvolvimento de software**, que é o que quem começa como Tech Writer encontra no mercado. (Em design ou produto existem outros tipos de documento.)

- 🇧🇷 **Documentação** é um documento que pode reunir vários outros, com informações importantes sobre como usar um produto ou serviço.
- 🇧🇷 **Cada documento precisa de um objetivo claro.** É tentador escrever muitas coisas num só documento, mas separar os assuntos facilita para quem lê.
- 🇧🇷 Ações mais comuns que uma documentação apoia: **configurar, instalar, personalizar, conhecer/entender, adicionar e eliminar** (não é uma lista fechada).

**Fonte única da verdade (Single Source of Truth).** A pessoa usuária pode achar muitas fontes sobre o produto na internet. A documentação cria uma fonte **fiel e confiável**, tanto para o público externo quanto para o time interno e outras áreas.

**Níveis de documentação de software** (desenho do blog Prototypr mostrado na aula):

~~~mermaid
flowchart TD
  S["Documentação de software"] --> P["Documentação de processos<br/>(bastidores: cronograma, estimativas,<br/>como o processo funciona)"]
  S --> R["Documentação de produto<br/>(mergulha no produto: como funciona,<br/>características, como usar)"]
  R --> SIS["Documentação de sistema<br/>(técnica: framework, arquitetura,<br/>como construir a solução)"]
  R --> U["Documentação da pessoa usuária<br/>(para o público do software)"]
  U --> F["Pessoa usuária final<br/>(ex.: quem entra numa reunião no Zoom)"]
  U --> A["Administradores do sistema<br/>(pessoa usuária mais técnica, ex.: devs)"]
~~~

🇧🇷 Exemplo da instrutora: numa empresa onde trabalhou, ela escrevia documentação de produto para administradores do sistema, porque o público eram pessoas desenvolvedoras (produto técnico para público técnico).

🇺🇸 Each document needs one clear goal; documentation builds a single source of truth.

### 3. Documentação funcional / Functional documentation

🇧🇷 Também chamada de **documentação de produto** ou **de visão geral (overview)**. Objetivo: **contextualizar e apresentar** um assunto (produto, serviço, funcionalidade, recurso). Costuma abrir os portais de documentação, porque é por ela que a pessoa se situa.

**Tópicos comuns:**
1. **O que é o produto** (pode se chamar "Visão geral" ou "Overview"), com um breve contexto de uso e a lista dos tópicos que vêm a seguir.
2. **Recursos disponíveis** (ex.: num banco, os serviços oferecidos e a descrição de cada um).
3. **Para que e para quem serve**, o que direciona o público da documentação.
4. **Principais conceitos**: pode ser um glossário em outra página, com link.

**Exemplos:**
- 🇧🇷 GitHub, "Introdução à sua conta do GitHub": é extensa **de propósito**, para dar o máximo de contexto.
- 🇧🇷 Projeto Bytebank: título, breve descrição do banco e um **sumário (table of contents)** com "Serviços disponíveis", "Para quem é a Bytebank?" e "Como criar sua conta". No fim, "Crie sua conta" leva ao tutorial.

**Sumário (table of contents):** lista, no início do documento, todos os assuntos que ele aborda, antecipando para a pessoa o que ela vai encontrar. A aula destaca que é muito valioso numa documentação funcional.

### 4. Tutoriais e guias how-to / Tutorials and how-to guides

🇧🇷 A definição de cada tipo pode variar conforme o **framework de documentação**. A aula usa o **Diátaxis**, criado por **Daniele Procida** (diretor de engenharia, muito conhecido na comunidade de TW), para simplificar a classificação e dar objetivos mais claros a quatro grandes grupos de documentação.

**Semelhança:** os dois são **passo a passo** para a pessoa atingir um objetivo. Perguntas que guiam a escrita: qual ação precisa ser realizada e quais passos levam até ela.

**Diferença** (segundo Procida): o **tutorial serve ao estudo** (a obrigação é uma experiência de aprendizagem bem-sucedida); o **guia how-to serve ao trabalho** (a obrigação é ajudar a realizar uma tarefa). Estudando, temos tempo para detalhes; trabalhando, precisamos ser rápidos.

| Tutorial | Guia how-to |
|---|---|
| Passo a passo **com mais detalhes** | Passo a passo focado **só na tarefa** |
| Dá os **porquês** de cada ação | Não se preocupa em contextualizar as etapas |
| Quando você está **aprendendo** algo em programação | Quando você **já programa** e quer recapitular como fazer algo |
| — | Título costuma começar com "Como…" ou com um verbo direto ("Criar uma conta na Bytebank") |

**Exemplos:**
- 🇧🇷 **Tutorial** da Microsoft, "Criar suas próprias medidas no Power BI Desktop": sumário, contexto do porquê, pré-requisitos dizendo para quem é, textos mais longos e imagens em cada passo.
- 🇧🇷 **Guia how-to** da Microsoft, "Editar modelos de dados no serviço Power BI": direto ao ponto, sem explicar para quem é.
- 🇧🇷 Bytebank: o **tutorial** tem visão geral da criação de conta, contexto, objetivos, pré-requisitos e passos com imagens; o **how-to** "Como criar uma conta na Bytebank" tem só pré-requisitos e passos. É o mesmo assunto, estruturado para objetivos diferentes.

### 5. Para saber mais: a matriz Diátaxis

🇧🇷 O Diátaxis organiza a documentação para facilitar a compreensão, com foco em qualidade, e deriva sua estrutura de **quatro formas de documentação**.

~~~mermaid
flowchart LR
  D["Diátaxis"] --> PR
  D --> E["Explicação<br/>conceitos e princípios"]
  D --> R["Referência<br/>informação detalhada<br/>para consulta"]
  subgraph PR["Eixo dos passos práticos"]
    T["Tutorial<br/>orientado à aprendizagem<br/>(estudo)"]
    H["Guia how-to<br/>orientado à tarefa<br/>(trabalho)"]
  end
~~~

| Forma | Para que serve | Exemplo da atividade |
|---|---|---|
| **Tutorial** | Passos sequenciais para iniciantes, no aprendizado prático | Configurar um editor de fotos novo, do download aos efeitos básicos |
| **Guia prático (how-to)** | Instruções claras e diretas para uma tarefa específica no trabalho | Criar uma planilha dinâmica numa ferramenta de planilhas online |
| **Referência** | Informações detalhadas sobre um sistema, linguagem ou produto, para consulta | Manual de um sistema operacional com configurações avançadas, comandos e requisitos |
| **Explicação** | Visão mais profunda: conceitos, princípios e relações | Material sobre os princípios da inteligência artificial |

**Elementos essenciais da matriz:** objetivo (declaração clara do propósito), público-alvo (adaptar linguagem e conteúdo ao conhecimento do público) e estrutura hierárquica (títulos e subtítulos).

### 6. Troubleshooting (resolução de problemas)

🇧🇷 Documentação que **lista possíveis erros do produto e apresenta as soluções**. Por que não só corrigir no produto? Porque alguns erros acontecem por várias razões, às vezes de causa pouco conhecida ou atípica, mas cuja solução já se sabe. Escrever o troubleshooting **antecipa a dor** da pessoa usuária.

**Estrutura:** **problema** (geralmente o título; ou o título é "Troubleshooting" e cada problema vira um tópico) → **solução** → **links relacionados**. Pode ser uma página por problema ou uma página única com todos, numa seção própria do portal (ou de suporte).

**Onde achar os erros:**

~~~mermaid
flowchart LR
  T["Tickets de suporte<br/>(com o time de atendimento)"] --> TS["Troubleshooting"]
  F["Feedback das pessoas usuárias<br/>(internas ou externas: polegar<br/>para cima/baixo, comentários)"] --> TS
  Q["Testes no produto<br/>(algo que escapou do QA)"] --> TS
~~~

**Exemplos:** Google Cloud ("Chrome Insider: Troubleshooting with Chrome Browser", com perguntas como "funciona numa janela anônima?" levando a extensões ou cache/cookies); StackSpot (seção "Troubleshooting" em que cada problema é um título); Bytebank ("Erro ao acessar sua conta", com soluções e links relacionados).

### 7. Documentação de API / API documentation

🇧🇷 Documento que descreve as **especificações técnicas de uma API** (também chamado de **referência de API**). Quem vai integrar a API precisa entender exatamente como ela funciona. A aula compara a uma **receita de bolo**: quem segue tem que conseguir replicar e o bolo sair igual.

**O que costuma ter:**
- 🇧🇷 **Recursos** disponíveis na API.
- 🇧🇷 **Métodos** de cada recurso: os verbos GET, POST, PUT, DELETE.
- 🇧🇷 **Endpoints**, que executam ações específicas.
- 🇧🇷 **Requisições**, geralmente no formato **cURL**.
- 🇧🇷 **Respostas** de cada chamada.
- 🇧🇷 **Erros possíveis**, cada um com seu código (400, 500…), mensagem e como resolver. O código **200** indica que deu certo.

**Formatos e contexto:**
- 🇧🇷 **API-first company**: empresa cujo negócio principal é criar APIs para outras empresas (ex.: **Adyen** e **Stripe**). Além da referência, têm **guias e casos de uso**, porque querem que a API seja usada de muitas formas.
- 🇧🇷 **REST API** (arquitetura REST, chamadas por HTTP/HTTPS) pode ser documentada com a especificação **OpenAPI**, que permite usar ferramentas como o **Swagger**.
- 🇧🇷 Boa prática: componentes e trechos de código **fáceis de copiar e colar** melhoram a experiência de devs.

**Exemplos:** VTEX Developers ("API do provedor antifraude": filtros por método, índice dos fluxos antifraude e de autenticação OAuth, e cada endpoint com cabeçalho, campos da requisição e exemplos de requisição e resposta). Bytebank: usa uma API pública do Mercado Pago, só como exercício didático, com autenticação e autorização, recurso de pagamentos, lista de endpoints e, em cada um, corpo da chamada, campos (obrigatórios ou não), exemplo de requisição e duas respostas (sucesso e erro).

### 8. Release notes (notas de versão)

🇧🇷 Apresenta as **principais mudanças de uma nova versão (release)** de um produto ou serviço. Exemplo do dia a dia: o texto "o que mudou" ao atualizar o WhatsApp na loja de aplicativos. Feita por Tech Writers, costuma ser mais técnica e detalhada.

**Tipos de release:**
- 🇧🇷 **Major release**: mudança grande, como da versão 1.0 para a 2.0.
- 🇧🇷 **Minor release**: mudança menor, como de 1.0 para 1.1, ou de 1.1 para 1.1.2.

**Estrutura:**

~~~mermaid
flowchart TD
  D["Descrição da nova versão"] --> N["Novas features"] --> M["Melhorias"] --> B["Bug fixes<br/>(correções)"] --> O["Opcional: descontinuado<br/>e known issues"]
~~~

🇧🇷 **Known issues** (problemas conhecidos) são erros já mapeados em versões anteriores e que ainda estão sendo resolvidos.

**Exemplos:** StackSpot (página única por mês, como linha do tempo, separando features, mudanças e **mudanças na documentação**, que avisam conteúdo novo mesmo sem mudança no produto); Bytebank (versão 1.0.1 hipotética, com melhorias no serviço de investimentos e correção de bugs no carregamento do app).

### Resumo da aula: qual documentação usar? / Which doc to use?

| Se o objetivo é… | Use |
|---|---|
| Apresentar e contextualizar um produto ou serviço | Documentação funcional |
| Ensinar alguém que está aprendendo, com os porquês | Tutorial |
| Ajudar a fazer uma tarefa rápido, direto ao ponto | Guia how-to |
| Resolver erros conhecidos | Troubleshooting |
| Descrever as especificações técnicas para integração | Documentação (referência) de API |
| Comunicar o que mudou numa nova versão | Release notes |

### 9. Escolhendo o modelo de documentação ideal (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou: guia how-to, porque o objetivo é realizar uma tarefa específica).

### 10. Faça como eu fiz: monte uma documentação funcional

🇧🇷 Criar uma documentação funcional para o projeto, usando as documentações do repositório do curso como inspiração.

✅ Projeto prático: [documentação funcional das Caixinhas](../../../projetos-projects/02-bytebank-docs/documentacao-funcional.md).

### 11. O que aprendemos? (exercício da plataforma)

✅ Resposta aberta enviada na plataforma (texto aprovado pela Letícia). O retorno da Alura elogiou a diferença entre tutorial (aprendizado) e how-to (tarefa) e o uso da matriz Diátaxis.

### Quiz comentado da Aula 02 / Lesson 2 quiz

<details><summary>1. Qual documentação costuma abrir os portais, porque contextualiza e apresenta o produto?</summary>

- ✅ **Documentação funcional (visão geral).** Situa a pessoa: o que é o produto, os recursos, para quem serve e os conceitos.
- ❌ Troubleshooting: lista erros e soluções, para quando algo dá errado.
- ❌ Release notes: comunicam o que mudou numa versão nova.
- ❌ Referência de API: especificações técnicas para quem vai integrar a API.
</details>

<details><summary>2. Segundo Daniele Procida, qual é a diferença entre tutorial e guia how-to?</summary>

- ✅ **O tutorial serve ao estudo (aprendizagem) e o how-to serve ao trabalho (realizar uma tarefa).**
- ❌ Tutorial para devs e how-to para pessoas usuárias finais: a diferença é o objetivo, não o público.
- ❌ Tutorial sem passo a passo: os dois são passo a passo.
- ❌ Tutorial curto e how-to longo: é o contrário, o tutorial dá os porquês e contextualiza; o how-to é direto.
</details>

<details><summary>3. Quais são as quatro formas da matriz Diátaxis?</summary>

- ✅ **Tutorial, guia prático, referência e explicação.**
- ❌ Tutorial, troubleshooting, release notes e API: são tipos que o curso apresenta, mas não são as formas do Diátaxis.
- ❌ Funcional, processos, sistema e pessoa usuária: mistura a documentação funcional com os níveis do desenho da Prototypr.
- ❌ Major, minor, feature e bug fix: são termos de release notes.
</details>

<details><summary>4. Qual destas NÃO é fonte de erros para um troubleshooting?</summary>

- ✅ **O roadmap de novas features**: não é citado como fonte.
- ❌ Tickets de suporte, feedbacks das pessoas usuárias e testes no produto: são exatamente as três fontes da aula.
</details>

<details><summary>5. Numa documentação de API, o que são GET, POST, PUT e DELETE?</summary>

- ✅ **Métodos**: os verbos que aparecem ao lado da chamada.
- ❌ Endpoints: são os caminhos que executam ações específicas (ex.: /pre-analysis).
- ❌ Códigos de erro: são números como 400 e 500 (o 200 indica sucesso).
- ❌ Formatos de requisição: o cURL é o formato em que as requisições costumam ser escritas.
</details>

<details><summary>6. Passar da versão 1.0 para a 1.1 é um exemplo de…</summary>

- ✅ **Minor release**: mudança menor (1.0 → 1.1, ou 1.1 → 1.1.2).
- ❌ Major release: mudança grande, como 1.0 → 2.0.
- ❌ Known issue: problema já mapeado que ainda está sendo resolvido.
- ❌ Bug fix: correção listada dentro da release note, não um tipo de versão.
</details>

**O que eu errei e por quê:** ⬜ a preencher depois que eu fizer o quiz.

---

## Aula 03 · Boas práticas de escrita para documentação / Writing best practices

### 1. Preparando o ambiente

🇧🇷 De novo o link para o [repositório do projeto do curso](https://github.com/alura-cursos/projeto-alura), agora com as documentações das Aulas 02 e 03.

### 2. Arquitetura da informação (A.I.) para documentação técnica / Information architecture

> 🇧🇷 **Arquitetura da informação** é a arte de organizar e estruturar uma informação de forma que ela se torne **acessível e intuitiva** para quem usa.
> 🇺🇸 The art of organizing and structuring information so it becomes accessible and intuitive.

🇧🇷 **Exemplo visual: globo.com antes e depois.** O site antigo (por volta de 2010–2014) misturava, colados, links de "astral", "brindes", "busca" e "chat" com notícias de TV, viagem, música, um player de vídeo e o GloboChat. Resultado: confusão, sem saber por onde começar nem qual informação é a mais importante, e provavelmente ruim para quem usa leitor de tela. O site atual, mesmo cheio de conteúdo, tem **espaços entre títulos e imagens, colunas bem delimitadas** e **cores por editoria** (ex.: notícia do Botafogo em verde = GE, Globo Esporte).

🇧🇷 **A informação como peças de um quebra-cabeça:** o trabalho de TW é montar as peças para o resultado ficar claro, acessível, útil e intuitivo. A.I. está na escolha das palavras do título e do subtítulo, na forma de organizar o texto, em decidir se vai ter mais de um subtítulo ou dividir em seções, e no uso de recursos além do texto.

**Por que fazer:**
- 🇧🇷 Tornar o texto **fácil de entender**.
- 🇧🇷 Melhorar a **experiência de aprendizagem** do produto ou serviço.
- 🇧🇷 **Agilizar a adoção do produto**, o que também é um diferencial competitivo num mercado com muita concorrência.

🇧🇷 **Exemplo na documentação:** a página inicial da documentação do GitHub agrupa os tópicos **por categorias em colunas** ("Get Started", "Collaborative coding", "CI/CD and DevOps"), em vez de uma lista contínua. Dentro de "Introdução à sua conta do GitHub": título, subtítulo, título da parte 1, texto corrido e tópicos.

### 3. Componentes, estrutura e organização / Components

🇧🇷 Quais recursos usar para facilitar a transmissão da informação. **A escolha depende da informação** e é critério de quem escreve; "não há uma ciência exata para documentar", e tudo bem se a primeira documentação não ficar tão fluida.

| Componente | Quando ajuda | Exemplo da aula |
|---|---|---|
| **Listas** com marcadores (bullets) | Ordenar tópicos relacionados sem ordem obrigatória; mais visual que o texto corrido | GitHub, "Sobre controle de versão e o Git": quais alterações, quem fez, quando e por quê |
| **Listas numeradas** | Passos em sequência (passo 1, 2, 3), muito úteis em tutoriais | — |
| **Tabelas** | Comparar e classificar informações de forma visual | Mercado Pago, Checkout Pro: requisitos (conta de vendedor, credenciais, certificado SSL) com descrição e se é obrigatório |
| **Diagramas** | Mostrar funcionamento técnico; o **diagrama UML** (Unified Modeling Language) mostra como uma API funciona | Mercado Pago: da pessoa no navegador até a API, com as chamadas do checkout |
| **Trechos de código** (code snippets) | Documentações com configuração técnica; a pessoa copia e cola. Muito úteis em how-to | Flutter, "Hello world", com botão **Run** que mostra o resultado |
| **Hiperlinks** | Ligar documentações e facilitar a navegação, no texto e no sumário | Microsoft, "Introdução ao Microsoft Teams para administradores" |

### 4. Para saber mais: tipos de pesquisa que ajudam na A.I.

| Pesquisa | O que faz | Exemplo da atividade |
|---|---|---|
| **Pesquisa com pessoas usuárias** (personas) | Alinha a documentação às necessidades de grupos específicos | Persona dev júnior pede mais detalhes e passo a passo; dev sênior, texto mais conciso e direto |
| **Análise de dados de acesso** | Mostra os pontos mais acessados e os que precisam de ajuste | Mapa de calor de acesso; página pouco acessada ou com pouco tempo de visita precisa melhorar |
| **Monitoramento automático de feedback** | Respostas rápidas e melhoria contínua | Muitos comentários sobre uma seção indicam que ela está confusa ou incompleta |
| **Pesquisa semântica** | Entende o significado do que a pessoa busca (processamento de linguagem natural) | Busca por "erro 404" leva ao que é o erro e como corrigir |
| **Testes A/B na estrutura** | Compara duas versões de uma seção para ver qual funciona melhor | Duas estruturas monitoradas em paralelo |
| **Card sorting** | As próprias pessoas agrupam as informações conforme a lógica delas | Mostra a organização mais intuitiva para o público |

### 5. Boas práticas de escrita para TW / Writing tips

🇧🇷 O foco não é gramática detalhada, e sim práticas objetivas para aplicar já no projeto.

| # | Boa prática | ❌ Evite | ✅ Prefira |
|---|---|---|---|
| 1 | **Ordem direta (voz ativa)**: sem ambiguidade nem duplo sentido | "O programa será iniciado depois de o software ser instalado." | "Instale o software e, em seguida, inicie o programa." |
| 2 | **Informação principal no início** (como o lide do jornalismo: o quê, quando, onde, por quê) | "Para customizar o seu layout, será necessário realizar etapas de configurações obrigatórias para quem usa o software na versão 1.0." | Título "Como customizar o seu layout?" + "Para seguir com esta customização, primeiro faça as configurações obrigatórias da versão 1.0 do software." |
| 3 | **Segunda pessoa (você)**: quem lê está sozinho, então chame a pessoa | "Vamos adicionar este componente na interface." | "Adicione este componente na interface quando for criar a aplicação." |
| 4 | **Evite jargões que o público não conhece** | "O parâmetro string é chamado no momento de realizar a chamada da API." | "Ao chamar uma API, você precisa informar o parâmetro string (para saber mais sobre este parâmetro, consulte o glossário)." |

**Detalhes de cada dica:**
- 🇧🇷 **Ordem direta:** a melhor dica é **ler em voz alta** para ver se está fluido; se preciso, encurte as frases.
- 🇧🇷 **Você × nós:** o "nós" é tentador, mas quem lê está sozinho. O "nós" cabe quando é de fato da empresa: "entre em contato com o **nosso** suporte".
- 🇧🇷 **Jargões:** quando não tiver certeza de que a pessoa conhece um termo, crie um **glossário** separado e aponte para ele no texto.

### 6. Guia de estilo / Style guide

🇧🇷 Documento que **reúne as principais orientações de comunicação e escrita de uma marca**. Funciona como uma **bússola** para escrever para o público. Nele aparecem tom e voz, persona e boas práticas de escrita: tudo o que a Aula 03 mostrou "culmina" no guia de estilo.

🇧🇷 **Por que existe:** como no trabalho em grupo da escola, um texto escrito a várias mãos fica evidente. Uma documentação pode ser escrita por muitas pessoas, mas **para quem lê não pode parecer**. O guia de estilo responde: como escrever em cada situação, como abreviar, como escrever palavras em inglês, como formatar o texto. Ajuda a tirar dúvidas e a **padronizar** a escrita do time todo.

🇧🇷 A aula **não ensina a criar um guia do zero**: é um projeto extenso, feito com várias áreas (UX, escrita, negócios, branding). Para quem está começando, o caminho é **aprender com guias públicos**, como os do **Google** e da **Microsoft**.

**O que a aula mostra em cada guia:**

| Guia | Seções destacadas |
|---|---|
| **Google** | Nomes de produtos (como escrever e abreviar, não usar nome como verbo); princípios gerais, como acessibilidade e **evitar reivindicações excessivas** (adjetivos como "este tutorial é muito difícil", porque o texto deve ser neutro e objetivo); **linguagem inclusiva**, com tabelas do que é e do que não é recomendado; tom e voz; gramática (abreviações, voz ativa, preposições) |
| **Microsoft** | Voz da marca; lista de termos de A a Z; conteúdo para devs (mesmo técnico, o texto pode ser fluido e agradável); formatação de texto e URLs; escolha de palavras |

**Dica de acessibilidade (do guia da Microsoft):** ao criar um hiperlink, **não use "clique aqui" ou "aqui"**. Quem usa leitor de tela não entende o destino. Coloque o link na palavra que diz para onde ele leva (ex.: "credenciais").

🇧🇷 Recado final da aula: escrever **com intenção**, pensando em como cada recurso ajuda quem lê a entender o texto.

### 7. Para saber mais: templates de documentação

- 🇧🇷 **Fim da tela em branco:** o template dá uma estrutura pré-definida e deixa você focar no conteúdo. Ex.: um guia de instalação sempre com introdução → requisitos do sistema → passo a passo → solução de problemas comuns. A consistência deixa a experiência **previsível** e facilita achar as informações.
- 🇧🇷 **Personalizar para o público:** o mesmo template de tutorial pode ter explicações detalhadas e exemplos simples para iniciantes, ou técnicas avançadas e snippets mais complexos para quem já sabe.
- 🇧🇷 **Uso real:** a Microsoft usa templates (ex.: documentação do Microsoft Azure).
- 🇧🇷 **[The Good Docs Project](https://thegooddocsproject.dev/):** comunidade dedicada à qualidade da documentação técnica, que oferece templates.
- 🇧🇷 Benefícios: simplificar a escrita, **padronizar** e **ganhar tempo** em documentos com base parecida.

### 8. Implantando um novo template de documentação (exercício da plataforma)

✅ Respondido pela Letícia na plataforma (acertou: templates específicos por tipo + guia de estilo).

### 9. Para saber mais: modelos de guia de estilo

🇧🇷 O guia de estilo reúne **tom e voz da marca** e as principais **boas práticas de escrita**. O que ele traz, segundo a atividade:
1. 🇧🇷 **Estrutura clara:** ex.: guia de usuário de um app com introdução e depois funcionalidades passo a passo.
2. 🇧🇷 **Consistência:** terminologia e pontuação iguais em todos os manuais de uma empresa de eletrônicos, o que gera confiança.
3. 🇧🇷 **Exemplo real:** os manuais da Apple, impressos ou online, com linguagem consistente.
4. 🇧🇷 **Imagens de antes e depois** de aplicar o guia mostram o impacto da consistência.
5. 🇧🇷 **Tom profissional:** ex.: documentos de uma consultoria, com escolha de palavras e estilo que transmitem confiança.

**Guias públicos indicados pela aula:**
- 🔗 [Google Developer Style Guide](https://developers.google.com/style): clareza e concisão, da escolha de palavras à formatação de código.
- 🔗 [Microsoft Style Guide](https://learn.microsoft.com/en-us/style-guide/welcome/): de princípios a detalhes, para a voz da Microsoft ser uniforme.
- 🔗 [GitLab Documentation Style Guide](https://docs.gitlab.com/ee/development/documentation/styleguide/): da estrutura de documentos à padronização de código.

🇧🇷 Para quem está começando ou trabalha numa empresa sem diretrizes, esses guias são um bom ponto de partida.

### 10. Faça como eu fiz: monte um tutorial e um guia how-to

🇧🇷 Com a arquitetura da informação e os componentes da aula, criar um **tutorial** e um **guia how-to** para o projeto, usando o repositório do curso como inspiração.

✅ Projeto prático: [tutorial](../../../projetos-projects/02-bytebank-docs/tutorial.md) e [guia how-to](../../../projetos-projects/02-bytebank-docs/guia-how-to.md) das Caixinhas.

### 11. O que aprendemos?

- ✅ Usar a arquitetura da informação a favor da redação técnica.
- ✅ Conhecer componentes, estrutura e organização de documentações.
- ✅ Aprofundar boas práticas de escrita para TW.
- ✅ Entender o que é um guia de estilo e quais são os modelos mais conhecidos.

### Quiz comentado da Aula 03 / Lesson 3 quiz

<details><summary>1. Como a aula define arquitetura da informação?</summary>

- ✅ **A arte de organizar e estruturar a informação para que fique acessível e intuitiva** (as peças do quebra-cabeça).
- ❌ Estrutura de pastas de um repositório: a A.I. vale para qualquer documentação ou site.
- ❌ Cores e fontes de uma marca: é identidade visual; as cores por editoria da globo.com são só um recurso de A.I.
- ❌ Diagrama de como uma API funciona: é o diagrama UML, um componente.
</details>

<details><summary>2. Requisitos com descrição e "obrigatório/opcional": qual componente?</summary>

- ✅ **Tabela** (exemplo do Checkout Pro do Mercado Pago).
- ❌ Trecho de código: para código que se copia e cola.
- ❌ Lista numerada: para passos em sequência.
- ❌ Hiperlink: para ligar documentações e navegar.
</details>

<details><summary>3. Qual frase segue as boas práticas?</summary>

- ✅ **"Instale o software e, em seguida, inicie o programa."** Ordem direta e falando com a pessoa.
- ❌ "O programa será iniciado depois de o software ser instalado.": voz passiva, ordem confusa.
- ❌ "Vamos adicionar este componente…": usa "nós", mas quem lê está sozinho.
- ❌ "O parâmetro string é chamado…": jargão sem explicação nem glossário.
</details>

<details><summary>4. Quando o "nós" cabe numa documentação?</summary>

- ✅ **Quando se refere à própria empresa**: "entre em contato com o nosso suporte".
- ❌ Nos passos de um tutorial: aí a aula pede "você".
- ❌ Sempre: a regra geral é a segunda pessoa.
- ❌ Nunca: a aula diz que existem situações em que cabe.
</details>

<details><summary>5. Por que evitar "clique aqui" num hiperlink?</summary>

- ✅ **Quem usa leitor de tela não entende o destino.** Coloque o link na palavra que diz para onde vai.
- ❌ Texto longo demais: "clique aqui" é curto.
- ❌ Links não devem ser usados: a aula recomenda hiperlinks.
- ❌ "Clique" é jargão: o problema é o "aqui", que não diz o destino.
</details>

<details><summary>6. Qual caminho a aula recomenda para quem está começando, em relação ao guia de estilo?</summary>

- ✅ **Aprender com guias públicos** (Google, Microsoft, GitLab).
- ❌ Criar do zero, sozinho: é um projeto extenso, com várias áreas.
- ❌ Não usar guia: ignora o objetivo de padronizar a escrita de várias pessoas.
- ❌ Copiar o tom e voz de outra marca sem adaptar: não aparece na aula; os guias servem de referência e inspiração.
</details>

**O que eu errei e por quê:** ⬜ a preencher depois que eu fizer o quiz.

---

## Aula 04 · Outros formatos de conteúdo técnico / Other technical content formats

🇧🇷 Formatos que nem sempre se chamam "documentação", mas que também fazem parte do trabalho de TW para facilitar o uso e a adoção de um produto.

### 1. Preparando o ambiente

🇧🇷 De novo o link do [repositório do projeto do curso](https://github.com/alura-cursos/projeto-alura), com todas as documentações da Bytebank até aqui.

### 2. Guia de usuário (User Guide)

🇧🇷 Documentação que procura **englobar todos os aspectos do produto**. É como um conjunto das documentações da Aula 02 (funcional, tutorial etc.) reunidas num só lugar. Os tópicos dependem do produto ou serviço.

**Exemplos:**
- 🇧🇷 **Manual do iPhone** (site de suporte da Apple): título e apresentação → "Comece a usar" (pista de tutorial: ligar, primeira configuração) → "Adicione um toque pessoal" (customização, conta em família, widgets). Tem um sumário: apresentação geral, introdução, modelos, configuração, noções básicas e personalização. Serve tanto para quem acabou de comprar quanto para quem esqueceu como usar uma função.
- 🇧🇷 **Suporte do Zoom**: apresentação geral e vários caminhos (introdução, conta e configurações, suporte, áudio e vídeo, central de aprendizagem e comunidade). A central de aprendizagem traz vídeos, ou seja, outro formato além do texto.

🇧🇷 É mais comum para a pessoa usuária final, mas também pode servir a devs (com uma seção que vai dos conceitos básicos às configurações). Pode ser muito vantajoso, dependendo da estratégia da empresa.

### 3. Guia de início rápido (Quick Start Guide)

🇧🇷 Documento que **orienta a pessoa a começar a usar um produto**: o "ponto zero", os primeiros passos. Nas empresas, o processo costuma começar **mapeando a jornada de uso** para achar esse ponto zero.

**Estrutura** (exemplo do Google Cloud, "criar e executar um fluxo de trabalho SQL no Dataform"):

~~~mermaid
flowchart TD
  T["Título"] --> V["Introdução / visão geral<br/>+ sumário com hiperlinks"]
  V --> P["Antes de começar<br/>(pré-requisitos)"]
  P --> I["Instalação<br/>(se o guia for de instalação, o mais comum)"]
  I --> S["Passo a passo<br/>títulos com verbo + listas numeradas"]
  S --> N["Próximos passos<br/>(no Google: &quot;A seguir&quot;)"]
~~~

- 🇧🇷 **Passo a passo:** títulos objetivos, geralmente com **verbo** (indicam a ação), e **listas numeradas** para deixar a ordem evidente. Botões de navegação são opcionais.
- 🇧🇷 **Próximos passos:** dizem o que fazer em seguida e facilitam a adoção. Como o guia não explica o conceito (ex.: o que é o Dataform), ele aponta para conteúdos conceituais.

**Dicas para escrever:**
1. 🇧🇷 Mapeie qual é a **primeira tarefa** que a pessoa precisa fazer com o produto.
2. 🇧🇷 Entenda qual é o **caminho mais fácil e rápido** para ela fazer essa tarefa (se houver vários, escolha o mais simples).
3. 🇧🇷 Se possível, **diga quanto tempo** a tarefa leva (algumas empresas indicam tempo de leitura e de configuração, porque as primeiras configurações, principalmente para devs, podem demorar).

### 4. Perguntas frequentes (FAQ)

🇧🇷 Documento de **perguntas e respostas** com as principais dúvidas de quem usa o produto, no site ou na documentação.

🇧🇷 **Opinião da instrutora (Mari):** há Tech Writers que discutem se a FAQ deve existir. Para ela, é muito relevante **se os tópicos forem bem escolhidos**: a FAQ não pode virar um depósito de conteúdo que não se sabe onde colocar. O propósito é trazer, num lugar de destaque, as **dúvidas que impedem as pessoas de começar a usar o produto**.

**Exemplos:**
- 🇧🇷 **FAQ da Alura** (no fim da página): sucinta, só com os pontos de adoção dos planos: para quem é a Alura, formas de pagamento, se dá para cancelar e o que fazer se ainda tiver dúvidas (link para a central de ajuda).
- 🇧🇷 **FAQ técnica do Mercado Pago Developers** (seção de suporte): para devs que integram as APIs, não para clientes do banco. Seções como aplicativos e credenciais, meios de pagamento, plugins e conta, e **cada dúvida tem uma página própria** com recomendações e links.

**Dica (blog *I'd Rather Be Writing*, de Tom Johnson): troque pergunta/resposta por objetivo/resposta.**

| Pergunta ampla | Pergunta por objetivo |
|---|---|
| Como criar uma conta na Bytebank? | Como criar uma conta na Bytebank **pelo aplicativo**? |

🇧🇷 Se o produto muda conforme o dispositivo, dá para criar uma pergunta para cada caminho (site, aplicativo, tablet). A FAQ fica mais direcionada, mesmo com dúvidas mais nichadas, desde que sejam comuns.

### Resumo da aula: qual formato usar?

| Formato | Objetivo | Para quem costuma ser |
|---|---|---|
| Guia de usuário | Reunir **todos os aspectos** do produto num só lugar | Principalmente a pessoa usuária final (pode ter seção para devs) |
| Guia de início rápido | Levar do **ponto zero** aos primeiros passos, rápido | Quem está começando a usar o produto |
| FAQ | Responder as **dúvidas que travam** a adoção | Quem está avaliando ou começando a usar |

### 5. Documentação mais indicada (exercício da plataforma)

✅ Respondido pela Letícia na plataforma, na segunda tentativa.

- **Pergunta:** quem acabou de entrar num time e precisa de uma **visão geral** das funcionalidades e da navegação básica, como **novo usuário**, deve usar qual documentação?
- ❌ **Primeira escolha: Guia do Usuário.** Errado porque o guia do usuário é mais detalhado e abrangente do que uma introdução rápida precisa; serve para explorar funcionalidades específicas a fundo.
- ✅ **Resposta certa: Guia de Início Rápido**, porque dá uma visão geral rápida do básico para quem está no ponto zero e quer começar.
- 💡 **Lição:** as palavras-chave "novos usuários" e "começar" apontam para o início rápido; "todos os aspectos do produto" apontaria para o guia do usuário.

### 6. Faça como eu fiz: escolha um dos formatos da aula para completar o projeto

🇧🇷 Escolher guia de usuário, guia de início rápido ou FAQ e desenvolver no projeto, usando o repositório do curso como inspiração (ele tem um modelo de guia de início rápido).

✅ Projeto prático: [FAQ das Caixinhas](../../../projetos-projects/02-bytebank-docs/faq.md), usando a dica de objetivo/resposta.

### 7. O que aprendemos?

- ✅ O que é e como criar um guia do usuário.
- ✅ O que é e como criar um guia de início rápido.
- ✅ O que é e como funciona uma FAQ.

### Quiz comentado da Aula 04 / Lesson 4 quiz

⬜ A fazer na nossa conversa sobre a aula.

---

## Aula 05 · Planejamento e análise de documentações / Planning and analyzing docs

🇧🇷 A parte mais conceitual do curso: por onde começar a planejar e analisar as documentações que já existem e as que queremos criar.

~~~mermaid
flowchart LR
  M["1. Mapeamento<br/>(conversas, pesquisas,<br/>outras fontes)"] --> I["Inventário<br/>de conteúdo"] --> E["2. Escopo<br/>e não escopo"] --> P["3. Plano de<br/>documentação"]
~~~

### 1. Preparando o ambiente

🇧🇷 Último link do [repositório do projeto do curso](https://github.com/alura-cursos/projeto-alura), agora com todas as documentações da Bytebank.

### 2. Mapeamento da documentação existente / Mapping existing docs

🇧🇷 **Mapeamento** é o processo de **pesquisar e listar todas as documentações que já existem**. A instrutora compara com um GIF de alguém parado numa estação enquanto todo mundo passa: é normal sentir "paralisia" diante de tanta informação.

**Por que mapear:**
- 🇧🇷 Confirmar quais documentos já existem na empresa (muitas vezes viram insumo).
- 🇧🇷 Avaliar se esses insumos ajudam a nova documentação, nem que seja como links relacionados.

**Como começar:**
1. 🇧🇷 **Defina prioridades** e comece com um **escopo pequeno** (provavelmente há muito conteúdo legado). Ex.: revitalizar um GitHub antigo ou listar as documentações para quem vai entrar no time.
2. 🇧🇷 **Converse com as pessoas do time.** Sem gestão do conhecimento ativa, a história do projeto fica na cabeça de quem está há mais tempo: são **"documentações vivas"**, que também sabem onde estão os documentos espalhados.
3. 🇧🇷 **Crie um inventário de conteúdo**: uma planilha (ou arquivo base) com tudo o que encontrou.

**Campos do inventário de exemplo da aula** (não existe modelo certo ou errado; adicione ou tire campos):

| URL | Título | Tipo de documentação | Objetivo da documentação | Responsável | Data de criação | Última atualização |
|---|---|---|---|---|---|---|
| link do tutorial | Crie uma conta na Bytebank | Tutorial | Apresentar o passo a passo para criar uma conta | (quem escreveu) | (data) | (data) |

### 3. Definição do escopo e "não escopo" / Scope and non-scope

🇧🇷 Depois do mapeamento, é preciso **filtrar**: decidir o que entra e o que fica de fora da documentação. Isso organiza o trabalho de TW e, principalmente, mostra à pessoa usuária **só o que é relevante para ela naquele momento**. É tentador incluir tudo o que foi mapeado, mas é preciso visão sistemática e crítica.

**Como fazer o escopo:**
1. 🇧🇷 **Identifique o público e o objetivo** da documentação. Saber quem lê e o que essa pessoa deve conseguir fazer define o quanto detalhar.
2. 🇧🇷 **Defina os tipos de documento** que vai escrever. Como cada tipo tem um objetivo (Aula 02), fica mais fácil dividir as informações do inventário e saber o que entra e o que fica de fora em cada um.

### 4. Construção/revisão do plano de documentação técnica / Documentation plan

🇧🇷 O plano vale para criar ou revisar documentações. A aula dá **o mínimo necessário** para começar (a formação tem um conteúdo dedicado só a planejamento). A "tríade" do plano:

| | Pergunta | O que considerar |
|---|---|---|
| **Escopo** | **O quê?** O que vamos documentar | Público e informações a documentar (o exercício do vídeo anterior). O público define o nível técnico. Em times ágeis, quebre o escopo nas **sprints** e coloque a documentação na **planning** junto com as outras entregas: isso facilita a entrega contínua e a manutenção |
| **Cronograma** | **Quando?** Os prazos que dá para cumprir | Tempo para **escrever**, para **editar e revisar** (o time revisa e dá feedback) e para **publicar** (plataformas como o GitHub podem ter datas de deploy e release). Vale para documentação interna e externa |
| **Ferramentas de trabalho** | **Como?** Onde a documentação fica | Google Docs, GitHub ou uma ferramenta que a empresa já contrata (veja se atende). Se não houver: comece pelo **teste gratuito (trial)** e, se for estratégica, negocie a contratação; ou faça um **benchmark** das ferramentas com o time |

🇧🇷 **Desafio da aula:** o "exercício contrário". O repositório da Bytebank foi criado como se já houvesse um plano; agora é pensar como teria sido esse planejamento: público, entregáveis e prazos.

### 5. Para saber mais: Desenvolvimento orientado à documentação (Documentation-Driven Development, DDD)

🇧🇷 A documentação **não é uma etapa final**: ela é protagonista desde o início do desenvolvimento.

1. 🇧🇷 **Documentação como arquiteta:** ao criar um novo módulo, a documentação descreve as funcionalidades e também como elas se conectam ao resto do sistema, como a planta de um prédio antes da obra.
2. 🇧🇷 **Histórias que se desdobram:** a cada ciclo, a documentação guia devs enquanto as funcionalidades entram (ex.: a doc de autenticação nasce junto com o recurso).
3. 🇧🇷 **Resultado:** fluxo de trabalho mais fluido, **menos retrabalho** e documentação que não é feita depois, às pressas.
4. 🇧🇷 **Diagramas de fluxo** ajudam a mostrar a documentação evoluindo lado a lado com o código.

~~~mermaid
flowchart LR
  D1["Documentação<br/>(define o que e como)"] --> C1["Código"] --> D2["Documentação<br/>atualizada"] --> C2["Próximo ciclo"]
~~~

🇧🇷 "Não é só uma prática, é uma **mudança de mentalidade**."

### 6. Faça como eu fiz: monte um plano de documentação

🇧🇷 Registrar o **inventário** dos documentos da Bytebank no modelo do curso e definir o **escopo**, para não criar documentações desnecessárias daqui para frente.

✅ Projeto prático: [plano de documentação das Caixinhas](../../../projetos-projects/02-bytebank-docs/plano-de-documentacao.md) (inventário, escopo e não escopo, cronograma e ferramentas).

### 7. Conteúdo complementar

🔗 Artigo da Alura: [A importância da technical writing nas empresas: como aplicar e obter benefícios na gestão do conhecimento](https://www.alura.com.br/empresas/artigos/technical-writing) (o que é escrita técnica, tipos de documentação, boas práticas e diferença para UX writing).

### 8. O que aprendemos?

- ✅ Mapear uma documentação existente.
- ✅ Entender a importância do escopo e do "não escopo".
- ✅ Montar e revisar um plano de documentação técnica.

### 9. Conclusão

🇧🇷 Fechamento do curso: o que é TW, arquitetura da informação, boas práticas de escrita, tipos de documentação, outros formatos (como o guia do usuário) e, ligando tudo, planejamento e análise. A instrutora recomenda o **segundo curso da formação**, que cria e planeja uma documentação do zero com um framework de processo de documentação conhecido no mercado (o DDLC). Também pede a avaliação do curso.

### Quiz comentado da Aula 05 / Lesson 5 quiz

⬜ A fazer na nossa conversa sobre a aula.

---

## Modelos do projeto do curso (Bytebank) / Course project templates

🇧🇷 O repositório do curso ([alura-cursos/projeto-alura](https://github.com/alura-cursos/projeto-alura/)) tem um modelo para cada tipo de documentação. Cada arquivo começa com um **Contexto** (o que é aquele tipo) e depois traz o **Exemplo de documentação** da Bytebank. Resumo da estrutura de cada modelo:

| Modelo | Estrutura do exemplo | Dicas extras que o modelo traz |
|---|---|---|
| [Documentação funcional](https://github.com/alura-cursos/projeto-alura/blob/main/documenta%C3%A7%C3%A3o-funcional.md) | Título "Bytebank" → frase de apresentação → sumário (serviços, para quem é, como criar a conta) → uma seção por tópico → link para o tutorial | — |
| [Tutorial](https://github.com/alura-cursos/projeto-alura/blob/main/tutorial.md) | Título com verbo ("Crie uma conta na Bytebank") → visão geral com o porquê e a lista dos passos → objetivos → "Antes de começar" (documentos necessários) → passos numerados (1.1, 1.2…) com capturas de tela e caixas de **IMPORTANTE** | Duas abordagens possíveis: guiar uma funcionalidade específica ou guiar um pequeno projeto completo (ex.: deploy de uma biblioteca do zero). O tutorial "pega na mão" da pessoa e explica os motivos |
| [Guia how-to](https://github.com/alura-cursos/projeto-alura/blob/main/guia-how-to.md) | "Como criar uma conta na Bytebank" → pré-requisitos → passos numerados curtos com capturas de tela → "Veja também" | Segundo o Diátaxis: descreva uma sequência de ações, resolva um problema, seja flexível com os casos de uso, elimine o que não for necessário e use títulos objetivos |
| [Troubleshooting](https://github.com/alura-cursos/projeto-alura/blob/main/troubleshooting.md) | "Troubleshooting Bytebank" → erro numerado como título ("Erro ao acessar sua conta") → causa → soluções numeradas → o que fazer se persistir (canais de atendimento) → links relacionados | Segundo o guia do The Good Docs Project: teste o produto, identifique todos os cenários de erro, mapeie a solução de cada um e organize em **sintomas/causas** e **soluções** |
| [Documentação de API](https://github.com/alura-cursos/projeto-alura/blob/main/documenta%C3%A7%C3%A3o-api.md) | Frase de uso → informações gerais (registro no portal de devs, token de acesso no header, exemplo em cURL) → recurso Pagamentos → URL base → tabela de endpoints (método, nome, descrição) → cada endpoint com campos e exemplos | Para APIs REST é comum usar a especificação OpenAPI, como no modelo do Swagger |
| [Release notes](https://github.com/alura-cursos/projeto-alura/blob/main/release-notes.md) | "Release Bytebank - Versão 1.0.1" → data → resumo da versão → novas funcionalidades → melhorias → bug fixes → opcional: known issues e funcionalidades descontinuadas (deprecated) | — |
| [Guia de início rápido](https://github.com/alura-cursos/projeto-alura/blob/main/guia-in%C3%ADcio-r%C3%A1pido.md) | "Iniciando seus investimentos na Bytebank" → visão geral (o que o guia vai orientar) → antes de começar (pré-requisitos) → passos com título de verbo ("Acesse a seção Investimentos") → próximos passos | O modelo diferencia o Quick Start de um *Getting Started*: o Quick Start não contextualiza, só mostra objetivamente o que fazer |
| [FAQ](https://github.com/alura-cursos/projeto-alura/blob/main/perguntas-frequentes-faq.md) | "Perguntas Frequentes (FAQ)" → perguntas numeradas como títulos (o que é a Bytebank, se tem custo, como criar a conta pelo celular) → respostas curtas, com link para a documentação | Pode ficar no fim de uma seção ou numa página à parte |

🇧🇷 Uma cópia do repositório está guardada no repositório privado de materiais.

---

## Livros e links indicados pela aula / Recommended by the course

- 📘 *The Product is Docs* (citado como leitura primordial para quem trabalha com TW).
- 🔗 Society for Technical Communication (definição de TW).
- 🔗 Artigo do blog da Alura sobre Markdown.
- 🔗 [Repositório do projeto do curso (projeto-alura)](https://github.com/alura-cursos/projeto-alura).
- 🔗 Diátaxis, de Daniele Procida (framework de documentação citado na Aula 02).
- 🔗 [The Good Docs Project](https://thegooddocsproject.dev/) (templates de documentação, Aula 03).
- 🔗 Guias de estilo: [Google](https://developers.google.com/style), [Microsoft](https://learn.microsoft.com/en-us/style-guide/welcome/) e [GitLab](https://docs.gitlab.com/ee/development/documentation/styleguide/) (Aula 03).
- 🔗 Blog *I'd Rather Be Writing*, de Tom Johnson (dica de FAQ por objetivo, Aula 04).
- 🔗 [Artigo da Alura sobre technical writing nas empresas](https://www.alura.com.br/empresas/artigos/technical-writing) (Aula 05).
