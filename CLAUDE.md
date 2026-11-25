# Como estudamos neste repositório

Diário de estudos de Product Owner da Letícia. Escrevemos em português (Brasil), com resumo em inglês nas notas, no mesmo formato do repositório irmão `letsprown-code/qa-learning-journal`.

## Regras de conteúdo
- **Só o que está na plataforma.** As notas registram o conteúdo do curso com nossas palavras. Não acrescentar, inventar nem alterar nada.
- **Fontes da aula:** usar sempre os textos da página (resumos, "Lembre-se", "Aprofunde") **e as legendas dos vídeos**, mesmo quando ela não for assistir. O vídeo traz contexto e exemplos que o texto não tem.
- **Sugestões externas:** só com fonte confiável e citada (ex.: Scrum Guide oficial). Primeiro mostrar a sugestão para a Letícia avaliar; só entra na nota depois da aprovação, numa seção separada e marcada como "Complemento (fonte externa)".
- Livros e links listados nas notas são só os que a própria aula indica.

## Ritmo
- Uma aula por vez. Antes de cada aula, perguntar se ela vai assistir ao vídeo.
- Depois da aula: conversar sobre o conteúdo e fazer perguntas ou quiz comentado, no estilo do diário de QA. Só então atualizar a nota.
- No quiz, a explicação de cada pergunta diz por que a certa está certa **e por que cada opção errada está errada**. Quando ela contar o que errou, explicar por que a opção que ela escolheu está errada e registrar isso no quiz comentado da nota.
- Para ler as seções da aula é preciso clicar em "Avançar", o que marca progresso na conta dela. Avisar quando isso acontecer. Nunca responder avaliações, quizzes ou desafios da plataforma no lugar dela.

## Visual e progresso
- Usar fluxos e diagramas (Mermaid; C4 quando o assunto for arquitetura de sistemas) sempre que ajudarem a entender a aula. Diagramas também seguem a regra de conteúdo: só o que a aula diz.
- Imagens: redesenhar os conceitos das aulas no nosso estilo (SVG em `imagens-images/<curso>-<módulo>/`, exportado em PNG com `rsvg-convert -w 1400`), conferir a renderização antes de publicar e embutir o PNG na nota. Nunca copiar slides ou prints da Tera de forma idêntica (o repositório é público e o material é pago); ela aprovou esse formato.
- **Estilo das imagens: Design System da Let's Code, Opção C** (artefato "Let's Code — Design System v1.0 · Opção C"): fonte Inter (títulos 900 com espaçamento negativo, corpo 400); fundo #FFFFFF, texto #0D0D0D, apoio #5E5E5E, bordas finas (#0D0D0D ou #E0E0E0), sem sombras; o único destaque é o chartreuse #DFFF00 como **marca-texto** atrás de 1 a 4 palavras, sempre com texto preto em cima (nunca chartreuse como cor de texto no fundo claro); traço fino #A0B300 no claro; um destaque por título. Quando for preciso diferenciar mais coisas (ex.: várias categorias num mesmo diagrama), ela autorizou usar outras cores que combinem com a paleta, mantendo o contraste de texto ≥ 4,5:1 e sem depender só da cor.
- Toda imagem com texto alternativo; nunca passar informação só por cor (usar também ✅ 🟡 ⬜ 🔒 🔓).
- `mapa-de-estudos.md`: mapa do que foi visto e estudado, com as **skills** que cada aula desbloqueia e a **badge** de cada módulo (todas as aulas + projeto prático). Skills vêm dos objetivos de aprendizagem e checklists da plataforma. Atualizar a cada aula.

## Materiais baixados
- Slides, planilhas, PDFs e prints de tela da plataforma vão **só** para o repositório **privado** `letsprown-code/po-learning-materiais` (só ela usa). Nunca neste repositório público.
- Baixar o material de cada aula junto com a aula.

## Projetos
- Cada módulo concluído ganha um projeto prático em `projetos-projects/<número>-<nome>/`, aplicando só ferramentas e conceitos das aulas. As análises e opiniões dela ficam ali, nunca nas notas de curso.

## Estrutura
- Notas: organizadas como na plataforma, `cursos-courses/<escola>/<curso>/<número>-<módulo>/<número>-<aula>.md`, minúsculas com hífen. O curso tem um `README.md` com a lista de módulos; cada módulo tem um `README.md` com tabela de cabeçalho (escola, curso, módulo, situação, fonte) e a lista de aulas com links.
- Glossário: só termos que apareceram nas aulas, com a aula de origem.
- Atualizar a tabela de progresso do README a cada aula.
- Nunca publicar material pago na íntegra, nomes de colegas ou dados de empresas reais.

## Tera
- Plataforma: https://plataforma.somostera.com (login dela, no navegador do app Claude).
- Ordem de estudo: Digital Product Leadership (módulos 01 a 06) → AI Product Manager (módulos 01 e 02) → trilha "Crie protótipos e produtos digitais com IA" (opcional).
- As legendas ficam nos vídeos (Mux): depois de carregar o player, cada `<video>` tem `<track srclang="pt-BR">` apontando para um `.m3u8` com os trechos em `.vtt`.
