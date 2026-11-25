[← Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais](README.md)

# Aula 6: Teste de Hipóteses / Hypothesis testing

🇧🇷 Com Gustavo Rodrigues Pilatti. A própria aula avisa: o conteúdo é **mais matemático e menos conceitual**, então vale ir com calma. Ela cobre os elementos de um teste de hipótese, o **teste A/B** e outros tipos de teste.

🇺🇸 Null and alternative hypotheses, confidence and significance levels, p-value, A/B testing, and other tests.

**Objetivos de aprendizagem (Tera):**
1. 🇧🇷 Diferenciar tipos de desenho de estudo (observacionais × experimentais).
2. 🇧🇷 Conceituar as etapas e os elementos de um teste de hipótese (H0/H1, alfa, p-valor, significância, intervalo de confiança).
3. 🇧🇷 Compreender a importância e as premissas do teste A/B.
4. 🇧🇷 Realizar um teste A/B: estruturar, conduzir e interpretar os resultados.
5. 🇧🇷 Conhecer outros tipos de teste de hipótese e algumas aplicações.

## Elementos do teste de hipótese / Elements of a hypothesis test

🇧🇷 Quase nunca temos acesso à **população** inteira (todos os clientes, todos os pedidos, um país inteiro). A **estatística inferencial** trabalha com uma **amostra** (um pedaço da população) para chegar a conclusões com algum grau de certeza, sem decidir só pela intuição.

🇧🇷 Uma hipótese é uma afirmação sobre a população, verificada com uma amostra. O **teste de hipótese** quantifica o resultado de um experimento e diz se a hipótese pode ser confirmada ou rejeitada. A **estatística de teste** leva em conta o tamanho da amostra e a distribuição dos valores (normal, t de Student…).

> 🇧🇷 **Exemplo do vídeo:** uma feature aumentou a retenção em 2 pontos percentuais. Isso é muito ou pouco? Só a magnitude não diz; é preciso uma estatística baseada na amostra.

| Hipótese | O que afirma |
|---|---|
| **H1** (alternativa, HA) | **Há** relação entre as variáveis: o efeito que você quer ver. É o foco do teste |
| **H0** (nula) | **Não há** relação; o efeito é só acaso. **O sinal de igualdade vai sempre na H0** |

🇧🇷 H0 e H1 são **mutuamente exclusivas e coletivamente exaustivas**: tudo o que pode acontecer (crescer, reduzir ou manter) está em uma das duas, e uma delas sempre é rejeitada.

| Tipo de hipótese | Exemplo da aula |
|---|---|
| **Direcional** (diz a direção do efeito) | "A nova feature **aumenta** a retenção"; "o novo layout **reduz** os cliques no botão" |
| **Não direcional** (só diz que há relação) | Simplificar uma página pode atrair mais cliques **ou** deixá-la menos atrativa |

**Conceitos importantes:**

| Conceito | O que é (segundo a aula) |
|---|---|
| **Intervalo de confiança** | O intervalo de valores em que acreditamos que está o valor real da população |
| **Nível de confiança** | A % de vezes que se espera reproduzir a estimativa dentro do intervalo. Geralmente **95%**: em 19 de cada 20 amostras, você obtém o valor real |
| **Nível de significância (α, alfa)** | A probabilidade de rejeitar H0. **α = 1 − nível de confiança**, definido pelo pesquisador **antes** do teste. Normalmente **0,05 (5%)** |
| **p-valor** | Calculado pelo software (até o Excel faz). Segundo o texto da aula, é a probabilidade de a hipótese nula ser verdadeira; é ele que se compara com o alfa |

🇧🇷 **Exemplo das bolinhas:** uma população com 90 bolinhas azuis e 10 quadradinhos vermelhos. Tirando 10 de cada vez (e devolvendo), uma amostra sugere 20% vermelhos, outra 30%. Repetindo muitas vezes, as estimativas se aproximam dos 10% reais, sem necessariamente acertar em cheio. Essa faixa em volta do valor real é o **intervalo de confiança**.

~~~mermaid
flowchart LR
  A["Observar a realidade<br/>e achar um problema"] --> B["Criar a hipótese<br/>(o 'chute')"] --> C["Definir H0 e H1"] --> D["Definir α<br/>(geralmente 5%)"] --> E["Executar o teste<br/>e coletar dados"] --> F["Software calcula<br/>o p-valor"] --> G{"p-valor < α?"}
  G -->|"sim"| H["Rejeita H0<br/>(fica com H1)"]
  G -->|"não"| I["Não rejeita H0"]
~~~

> 🇧🇷 **Atenção à linguagem:** num teste de hipótese, **rejeitamos ou não rejeitamos** a hipótese nula. **Nunca "aceitamos"** a hipótese nula.

🇧🇷 **Exemplo do vídeo (público sênior):** você quer lançar um produto para pessoas mais velhas e testa se a sua base tem idade média **maior que 50 anos**.
- **H0:** idade média ≤ 50 (a igualdade fica na nula).
- **H1:** idade média > 50.
- **α = 5%.** O software dá **p-valor = 0,87**, maior que 0,05 → **não rejeitamos H0**: não há evidência de que a média passe de 50.

## Teste A/B / A/B testing

🇧🇷 O **teste A/B** é um caso específico de teste de hipótese com **dois grupos** de observações (usuários, dias, clientes…), divididos **aleatoriamente**: o **grupo controle** fica como está, e o **grupo piloto** (tratamento) recebe a mudança. Se o KPI dos dois for **significativamente diferente**, o tratamento teve efeito. A estrutura é a mesma: hipótese, H0 e H1, experimento, p-valor × alfa.

**As 4 etapas:**

| Passo | O que fazer | Cuidados da aula |
|---|---|---|
| **1. Construa uma boa hipótese** | É o coração do experimento. Converse com pessoas, olhe dados e experimentos do passado | **Defina qual KPI será impactado** |
| **2. Desenhe o tratamento e os grupos** | O que muda (cor do botão, ordem dos elementos, cupom, valor da promoção…); quem é controle e quem é piloto | **Tamanho mínimo de amostra** (calculadoras como a do Evan Miller) e o **alfa** definido antes ("quanto menor o alfa, menos você erra") |
| **3. Execute o experimento** | Aguarde a amostra chegar ao tamanho desejado | Garanta a **aleatoriedade**. **Não encerre antes** por pressão ou ansiedade da liderança: com menos dados, as conclusões podem não ter significância |
| **4. Analise os resultados** | Confira se os dados estão completos; compare a **média do KPI** entre os grupos e a **direção** da diferença | Verifique se a diferença é **estatisticamente significativa** |

**Exemplo completo do vídeo: cupom aumenta a retenção?**

🇧🇷 Você é de Growth num e-commerce e acredita que quem usa cupom vira cliente mais fiel.

1. **Hipótese:** na Black Friday passada, quem usou cupom teve **retenção de 30 dias** de 20%, cerca de **5 pontos percentuais** acima do normal. KPI: retenção em 30 dias. Hipótese: quem usa cupom tem retenção de 30 dias 5 p.p. maior.
2. **Desenho:** a calculadora pede o **baseline** (20%), o **efeito mínimo** a detectar (5 p.p.) e o **alfa** (5%) → amostra mínima de **1.728**. Com orçamento de **R$ 27 mil**, cupons de **R$ 30** para **900 clientes** no piloto e 900 no controle (1.800 > 1.728).
3. **Execução:** enviar os cupons e esperar 30 dias.
4. **Análise:** retenção de **18,9%** no piloto e **13,8%** no controle.
   - **H0:** retenção com cupom ≤ sem cupom. **H1:** com cupom > sem cupom.
   - No Excel: *Dados → Análise de dados → Teste-t: duas amostras presumindo variâncias equivalentes*.
   - **p-valor = 0,002 < 0,05** → rejeitamos H0. Com 95% de confiança, o uso de cupons causa uma retenção maior.

> 🇧🇷 **Cuidado com a comunicação:** não leve para o executivo uma tela cheia de p-valor, alfa, H0 e H1. **Interprete e sintetize**: qual é a ação, o que fazer a partir do resultado.

## Um pouco mais sobre teste de hipótese / More on hypothesis tests

| Método | Como funciona | Quando usar |
|---|---|---|
| **Frequentista** | Faz inferências só a partir dos **dados coletados** no teste; regras claras, ordem lógica, resultado validado | O **padrão**: é o que a aula ensinou |
| **Bayesiano** | Inclui **conhecimento prévio** (e a intuição do pesquisador) por meio de probabilidades; regras mais flexíveis | Só quando a equipe estiver realmente preparada: a chance de resultado errado ou inválido é maior |

**Outros testes citados:**
- 🇧🇷 **Teste t:** verifica se há diferença significativa entre as **médias de dois grupos**; serve até para amostras pequenas (20 ou 30 observações). É o que o Excel rodou no teste A/B.
- 🇧🇷 **ANOVA** (análise de variância): compara as médias de **mais de dois grupos** de uma vez. Fazer vários testes t, de dois em dois, aumenta a chance de **erro do tipo I** (concluir que há efeito quando não há). Limite: a ANOVA diz que **há** diferença em algum grupo, mas **não qual nem em que direção** (H0: todas as médias iguais; H1: alguma é diferente).
- 🇧🇷 Existem muitos outros, com nomes próprios, como o teste de **Levene** (homogeneidade) e o de **Shapiro-Wilk** (normalidade).

> 🇧🇷 O texto da aula compara o teste de hipótese a "aquela blusa básica do armário que combina com tudo": vale do dia a dia corporativo à validação de modelos de machine learning, e ajuda a não cair em gráficos mal construídos.

## Resumo da aula / Lesson takeaways

🇧🇷 No fim, o professor espera que você saiba: definir uma boa hipótese; definir **H0 e H1**; o que é o **p-valor** e o **alfa**, e quando defini-lo; e quais são os valores padrão do dia a dia (**95% de confiança, α = 5%**).

**Checklist da Tera:** são os mesmos cinco objetivos de aprendizagem do início da aula.

**Referência citada na aula:** calculadora de tamanho de amostra para teste A/B de Evan Miller (evanmiller.org).

---

[← Tera · Digital Product Leadership · 02: Métricas para Produtos Digitais](README.md)
