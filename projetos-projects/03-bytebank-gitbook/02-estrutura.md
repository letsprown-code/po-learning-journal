# Etapa 2 do DDLC · Design / estruturação

> Documento de estudo. A Bytebank é fictícia. Segue o vídeo "Definindo estrutura e componentes visuais da sua documentação".

## 1. Perguntas de design (do modelo de planejamento)

| Pergunta | Resposta no projeto |
|---|---|
| Vai ter as telas do aplicativo? | Sim: o time de design preparou um Figma com as telas do novo app |
| Preciso de mais algum recurso visual? | Logo e identidade visual da nova marca (rebranding), para dar coesão à documentação |
| Como quero organizar a documentação? | Em seções e subseções, conforme o desenho abaixo |

## 2. Assuntos mapeados com stakeholders e SMEs

- Serviço de Investimentos
- Serviços de Transferências e de Extrato
- Como criar uma conta
- Glossário ou principais conceitos
- Visão geral do aplicativo
- Histórico de mudanças (release notes)

## 3. Estrutura do menu (arquitetura da informação)

No curso, esse desenho é feito no Octopus. Aqui ele fica em Mermaid, que o GitHub mostra direto.

~~~mermaid
flowchart TD
  D["Documentação Bytebank"] --> V["Visão geral do aplicativo"]
  D --> S["Nossos Serviços"]
  S --> T["Transferências<br/>(PIX, DOC e TED na mesma página)"]
  S --> E["Extrato"]
  S --> I["Investimentos"]
  D --> C["Como criar uma conta"]
  D --> G["Glossário / principais conceitos"]
  D --> H["Histórico de mudanças"]
~~~

| Decisão | Motivo (segundo a aula) |
|---|---|
| Investimentos, Transferências e Extrato dentro de **Nossos Serviços** | Estão sob o mesmo "guarda-chuva"; serviços novos entram ali depois, o que facilita a manutenção |
| Nome "Nossos Serviços" (e não "Serviços da Bytebank") | Tom de voz mais próximo da pessoa usuária |
| PIX, DOC e TED na página de Transferências | Não têm conteúdo suficiente para uma página cada |
| **Como criar uma conta** no primeiro nível do menu | Não faz sentido dentro de serviços; é a porta de entrada para novas pessoas |

## 4. Ferramentas que vou usar

| Para quê | Ferramenta | Origem |
|---|---|---|
| Publicação | GitHub (Markdown) | Decisão do projeto (o curso sugere o Gitbook) |
| Estrutura / diagramas | Mermaid no GitHub | Decisão do projeto (o curso usa o Octopus; a aula de dicas cita Draw.io e Lucidchart) |
| Capturas de tela | Ferramenta nativa do sistema (Ferramenta de Captura no Windows; Command + Shift + 4 ou 5 no Mac) | Aula "dicas para criar e editar imagens, diagramas e vídeos" |
| Imagens | Canva (iniciantes) | Aula "dicas para criar e editar imagens, diagramas e vídeos" |
