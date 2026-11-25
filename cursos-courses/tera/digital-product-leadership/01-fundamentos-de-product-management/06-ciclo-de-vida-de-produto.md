[← Tera · Digital Product Leadership · 01: Fundamentos de Product Management](README.md)

# Aula 6: Ciclo de vida de produto / Product life cycle

## Dois ciclos diferentes / Two different cycles
🇧🇷 O **ciclo de desenvolvimento** tem os *building blocks* do processo: definição do problema → definição do produto → planejamento do desenvolvimento → monitoramento → lançamento → compreensão dos resultados. O **ciclo de vida** (curva S, PLC, *Product Life Cycle*) mostra as vendas ou aquisição ao longo do tempo: introdução, crescimento, maturidade e declínio. **Acontece com todos os produtos.** O ciclo de desenvolvimento se repete **muitas vezes**, em cada fase do ciclo de vida.

~~~mermaid
flowchart LR
    subgraph CV[Ciclo de vida / Life cycle]
      direction LR
      I[Introdução<br/>busca de PMF] --> C[Crescimento<br/>growth] --> M[Maturidade<br/>vaca leiteira] --> D[Declínio<br/>inovação/disrupção]
    end
    CD((Ciclo de desenvolvimento<br/>problema → produto → plano →<br/>monitoramento → lançamento → resultados))
    CD -.repete em.-> I
    CD -.repete em.-> C
    CD -.repete em.-> M
    CD -.repete em.-> D
~~~

🇧🇷 **Simples → complicado:** à esquerda da curva, o produto é simples e resolve uma coisa só. Para crescer, ganha funcionalidades e, em algum ponto, fica complicado. Aí as pessoas migram para produtos mais simples, que é justamente o ponto de partida. Perguntas para localizar o seu produto: ainda é simples? Já está ganhando funcionalidades? Já ficou complicado? Está perdendo usuários para outro produto?

## Atravessar o abismo / Crossing the chasm (Geoffrey Moore)
🇧🇷 De um lado, as pessoas que querem coisas novas (**early adopters**); do outro, o **mercado mainstream**, onde está a maior parte da população e onde o produto precisa chegar para monetizar e crescer. Entre eles há um **abismo**, que só se cruza com uma **proposta de valor bem ajustada** ao grande público. Sem isso, o produto fica preso num nicho, com teto bem menor.

🇧🇷 **Exemplos do professor:** a Sherpay (antecipação salarial) ainda tentava descobrir, com poucas pessoas usando, os benefícios que levariam ao mercado grande; o C6 estava **no meio do abismo**, validando em alto crescimento se a proposta de valor fazia sentido; o PicPay, com quase 60 milhões de clientes, já estava no mainstream. Os erros possíveis numa startup pequena são mais "livres" do que numa empresa grande.

| Dica para cruzar / Tip | 🇧🇷 Detalhe do vídeo |
|---|---|
| 1. Entenda o ciclo de adoção | o que faz as pessoas adotarem a sua tecnologia |
| 2. Segmente | entenda o que cada segmento precisa e construa soluções específicas para ele |
| 3. Forneça um produto completo | MVPs são interessantes, mas precisam entregar valor; ao longo do ciclo, entregue um produto cada vez mais completo |
| 4. Conheça a concorrência | se as pessoas já têm soluções iguais, você só compete por **preço**; ajuste a proposta de valor ao que a concorrência oferece |

🇧🇷 Resumo das quatro dicas: **atingir o *product-market fit*** é uma das responsabilidades mais importantes.

![Curva S: vendas ou aquisição ao longo do tempo. A curva sobe devagar na introdução (foco em retenção, early adopters), passa pelo abismo, sobe rápido no crescimento (foco em mais usuários), estabiliza na maturidade (foco em vazamentos do funil, mercado mainstream) e cai no declínio (foco na causa da queda).](imagens/curva-s-ciclo-de-vida.png)

## Onde está o meu produto? Métricas / Where is my product? Metrics
📏 🇧🇷 "O que não é metrificável é ingerenciável." As métricas seguem as três pernas da cadeira: **negócio**, **cliente** (experiência) e **produto** (tecnologia). Exemplo: aquisição baixa e custo alto = começo do ciclo; custo começa a baixar = meio; volta a subir de forma recorrente = talvez declínio.

| Fase / Stage | 🇧🇷 Como estão as métricas | 🇧🇷 Foco | 🇧🇷 Desafios da pessoa de produto | 🇧🇷 Pergunta-chave |
|---|---|---|---|---|
| **Introdução** | poucas; ainda não se sabe o motivo das variações | **retenção**: poucas pessoas usando muito (dá mais controle para entender o porquê) | entender como as pessoas interagem com o produto (**qualitativo**, porque há poucos usuários); entender os benefícios que elas tiram, para reforçá-los de forma escalável | Como resolver as dores dos usuários da melhor maneira possível? |
| **Crescimento** | aparecem correlações e causalidades; ainda é difícil ligar uso a resultado de negócio | com a retenção comprovada, entender **o que traz mais usuários** e replicar | separar **correlação de causalidade**; trabalho focado em **testes** e novas hipóteses; sustentar o crescimento do que está dando certo | Quais são as principais iniciativas para alavancar o uso do produto, pelo topo do funil (aquisição)? |
| **Maturidade** | estáveis; variáveis entendidas | **vazamentos em todo o funil** ("vedar o balde": quem entra, fica) | visão analítica profunda; gerar e testar hipóteses de melhoria; **começar a simplificar** | Como simplificar o produto para a proposta de valor continuar relevante? |
| **Declínio** | queda constante; impacto no negócio (custo de aquisição sobe, receita cai, NPS piora); grande furo no funil | entender **a causa** da queda de uso | descobrir o que tornou o produto irrelevante (onde a proposta de valor furou); identificar oportunidades-chave para reverter; **testar, testar, testar** | Como mitigar os riscos em novas apostas? |

🇧🇷 A fase de declínio é a mais importante para a **disrupção**, mas há inovação em todas as fases (o fim da curva se parece com o começo).

---

[← Tera · Digital Product Leadership · 01: Fundamentos de Product Management](README.md)
