# Alura · Formação Technical Writing · 01: Aprenda estratégias, ferramentas e boas práticas

| Campo / Field | Valor / Value |
|---|---|
| Escola / School | Alura |
| Curso / Course | Formação Technical Writing (2 cursos, 18 h) / Technical Writing track (2 courses) |
| Módulo / Module | 01 · Technical Writing: aprenda estratégias, ferramentas e boas práticas (10 h, introdutório) |
| Instrutora / Instructor | Mari Moreira (líder de Developer Communications no Mercado Pago) |
| Situação / Status | 🟡 Em andamento · Aula 01 de 5 lida, aguardando conversa e quiz / In progress · lesson 1 of 5 read |
| Fonte / Source | [Alura: Technical Writing: aprenda estratégias, ferramentas e boas práticas](https://cursos.alura.com.br/course/technical-writing-estrategias-ferramentas-boas-praticas) (login) |

🇧🇷 Sobre o curso (texto da plataforma): entender o que é Technical Writing e a diferença para UX Writing, conhecer boas práticas e os principais tipos de documentação técnica em TI, aplicar arquitetura da informação, desenvolver documentações como release notes, troubleshooting e tutoriais, e aprender a planejar e analisar documentações.

🇺🇸 About: what Technical Writing is and how it differs from UX Writing, writing best practices, the main types of technical documentation, information architecture, and how to plan and analyze docs.

## Aulas / Lessons

| # | Aula / Lesson | Atividades / Activities | Situação / Status |
|---|---|---|---|
| 1 | O que é Technical Writing? | 12 | 🟡 Lida, falta conversa + quiz |
| 2 | Tipos de documentação técnica | 11 | ⬜ |
| 3 | Boas práticas de escrita para documentação | 11 | ⬜ |
| 4 | Outros formatos de conteúdo técnico | 7 | ⬜ |
| 5 | Planejamento e análise de documentações | 9 | ⬜ |

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

⬜ Exercício de múltipla escolha da Alura. Fica para a Letícia responder na plataforma.

### 11. Faça como eu fiz: organizar o projeto no GitHub

🇧🇷 Criar a conta no GitHub (se não tiver) e iniciar um repositório para a Bytebank, ou com outro tema. Cada tipo de documentação vira um arquivo `.md` (os tipos vêm na Aula 02).

⬜ Projeto prático: a fazer em `projetos-projects/`.

### Quiz comentado da Aula 01 / Lesson 1 quiz

⬜ A fazer na nossa conversa sobre a aula.

---

## Livros e links indicados pela aula / Recommended by the course

- 📘 *The Product is Docs* (citado como leitura primordial para quem trabalha com TW).
- 🔗 Society for Technical Communication (definição de TW).
- 🔗 Artigo do blog da Alura sobre Markdown.
