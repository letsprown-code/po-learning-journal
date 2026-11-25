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
| 1 | Iniciando seu processo de documentação | 10 | 🟡 |
| 2 | Estruturando sua documentação | 8 | ⬜ |
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

⬜ Exercício da Alura sobre em que fase do DDLC começar a documentação. Fica para a Letícia responder.

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

## Livros e links indicados pela aula / Recommended by the course

- 🔗 [Gitbook](https://www.gitbook.com/) (plataforma do projeto, plano gratuito).
- 📘 [*The Technical Writing Process*](https://www.amazon.com.br/Technical-Writing-Process-five-step-procedures-ebook/dp/B00UA3YX46) (Aula 01).
