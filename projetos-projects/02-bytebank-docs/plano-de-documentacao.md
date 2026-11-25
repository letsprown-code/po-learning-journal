# Plano de documentação das Caixinhas

> Documento de estudo. A Bytebank e as Caixinhas são fictícias. É o "exercício contrário" da Aula 05: os documentos já existem, e aqui pensamos como teria sido o planejamento deles.

O plano segue os três passos da Aula 05: **mapeamento** (com inventário de conteúdo), **escopo e não escopo** e o **plano** com a tríade escopo, cronograma e ferramentas.

## 1. Mapeamento: inventário de conteúdo

Campos do modelo da aula. As datas são as deste estudo.

| URL | Título | Tipo de documentação | Objetivo da documentação | Responsável | Data de criação | Última atualização |
|---|---|---|---|---|---|---|
| [documentacao-funcional.md](documentacao-funcional.md) | Caixinhas da Bytebank | Documentação funcional | Apresentar as Caixinhas: o que são, para quem são, tipos e conceitos | Letícia (com o Claude) | 25/11/2026 | 25/11/2026 |
| [tutorial.md](tutorial.md) | Tutorial: crie sua primeira Caixinha | Tutorial | Ensinar a criar uma Caixinha com Meta, explicando o porquê de cada passo | Letícia (com o Claude) | 25/11/2026 | 25/11/2026 |
| [guia-how-to.md](guia-how-to.md) | Como resgatar dinheiro de uma Caixinha | Guia how-to | Resgatar dinheiro de uma Caixinha, direto ao ponto | Letícia (com o Claude) | 25/11/2026 | 25/11/2026 |
| [faq.md](faq.md) | Perguntas frequentes sobre as Caixinhas | FAQ | Responder as dúvidas que travam o uso das Caixinhas | Letícia (com o Claude) | 25/11/2026 | 25/11/2026 |

## 2. Escopo e não escopo

**Público:** pessoas com conta na Bytebank que ainda não usam as Caixinhas. Não são técnicas, então o texto evita jargão financeiro e explica os termos.

**Objetivo:** que a pessoa entenda o que são as Caixinhas, crie a primeira, saiba resgatar o dinheiro e encontre respostas para as dúvidas mais comuns sem precisar do atendimento.

| ✅ Escopo (entra) | ⬜ Não escopo (fica de fora) |
|---|---|
| Visão geral das Caixinhas (documentação funcional) | Regras de rendimento e cálculo de impostos (outro público e outro objetivo) |
| Criar a primeira Caixinha (tutorial) | Documentação de API das Caixinhas para devs parceiros |
| Resgatar dinheiro (how-to) | Outros produtos da Bytebank, como cartões e investimentos |
| Dúvidas de quem está começando (FAQ) | Histórico de decisões internas do time de produto |

**Tipos de documento:** um tipo por objetivo, como na Aula 02. Assim cada informação do inventário tem um lugar certo e nenhum documento tenta fazer tudo.

## 3. Plano de documentação

### Escopo (o quê)

Os 4 documentos acima. Num time ágil, eles entrariam na **planning** junto com o desenvolvimento das Caixinhas, um por sprint, para a documentação ser entregue com o recurso e não depois.

### Cronograma (quando)

| Sprint | Entrega | Escrever | Revisar com o time | Publicar |
|---|---|---|---|---|
| 1 | Documentação funcional | 2 dias | 1 dia | junto com o lançamento do recurso |
| 2 | Tutorial | 3 dias | 2 dias (inclui testar os passos no app) | junto com o lançamento do recurso |
| 3 | Guia how-to | 1 dia | 1 dia | na data de release do repositório |
| 4 | FAQ | 2 dias (depois de ler os primeiros tickets de suporte) | 1 dia | na data de release do repositório |

A FAQ fica por último de propósito: as melhores perguntas vêm das dúvidas reais que chegam depois do lançamento.

### Ferramentas de trabalho (como)

- **Onde escrever e publicar:** GitHub, em Markdown, como no projeto do curso. Isso segue a ideia de Docs as Code (Aula 01): versões, revisão por pull request e histórico de mudanças.
- **Se a empresa já tiver uma ferramenta contratada**, adaptar os documentos a ela.
- **Se não tiver uma que atenda**, testar uma ferramenta no período gratuito ou fazer um benchmark com o time antes de contratar.
