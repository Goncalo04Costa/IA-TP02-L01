# Estrutura do Notebook

## Introdução
Realizado por:

- Gonçalo Costa (26024)

- Daniela Pereira (25988)

- Fábio Miranda (26003)

## Conjunto(s) de dados
Foram selecionados dois dataset´s para os diferentes algoritmos utilizados neste projeto.

Para os algoritmos Supervised e Apriori foi usado o mesmo dataset **"Housing Price Prediction Data"**.

No **Supervised**, o objetivo é prever a classe de preço das propriedades com base em características como o número de quartos, banheiros, área útil e vizinhança. Isso visa otimizar a avaliação de casas, proporcionando uma maneira mais precisa e eficiente de estimar o valor de mercado de uma propriedade, auxiliando compradores, vendedores e investidores no processo de decisão.

Já no **Apriori**, o objetivo de negócio é identificar padrões de associação entre as características das propriedades, como número de quartos, casas de banho, localização, e a categoria de preço. Isso visa melhorar a compreensão das relações entre essas variáveis, otimizando a previsão do preço das casas e auxiliando na tomada de decisões para compradores, vendedores e investidores no mercado imobiliário.

Para o algoritmo **Unsupervised** foi usado o dataset **"New York Housing Market"**, onde visamos entender o comportamento do mercado imobiliário em Nova Iorque, utilizando técnicas de análise de dados e aprendizado de máquina, como o KMeans para agrupamento de dados.
O objetivo é criar um modelo que permita à empresa entender melhor as características dos imóveis e identificar padrões no mercado, segmentando os imóveis em clusters que podem ser analisados de forma mais detalhada para tomada de decisão.


## Algoritmos desenvolvidos

### Apriori
Objetivos específicos:

1. **Identificação de Regras de Associação no Mercado Imobiliário:**
   - **Meta:** Utilizar o algoritmo Apriori para encontrar padrões e associações frequentes entre as características dos imóveis, como número de quartos, banheiros, localização, e a categoria de preço.
   - **Objetivo:** Melhorar a compreensão das relações entre essas variáveis, otimizando a previsão de preços e auxiliando compradores, vendedores e investidores na tomada de decisões.

2. **Exploração de Relações Frequentes:**
   - **Meta:** Analisar as combinações de características que frequentemente aparecem juntas no mercado imobiliário, como localização e número de quartos.
   - **Objetivo:** Identificar combinações de atributos que atraem maior valor de mercado ou atendem a perfis específicos de consumidores.

3. **Visualização de Padrões para Estratégias de Mercado:**
   - **Meta:** Criar gráficos e tabelas que demonstrem as regras de associação e os padrões frequentes descobertos pelo algoritmo.
   - **Objetivo:** Oferecer insights claros e visualmente intuitivos para estratégias de marketing e personalização de ofertas no mercado imobiliário.

4. **Validação e Refinamento das Regras Descobertas:**
   - **Meta:** Avaliar a qualidade e a relevância das regras geradas, utilizando métricas como suporte, confiança, e lift.
   - **Objetivo:** Garantir que os padrões identificados sejam úteis e aplicáveis em cenários reais do mercado imobiliário.

### SuperVised
Objetivos específicos:

1. Classificação das Propriedades:
   - **Meta:** Utilizar algoritmos de aprendizado supervisionado para prever a classe de preço de propriedades com base em atributos como número de quartos, banheiros, área útil e vizinhança.
   - **Objetivo:** Facilitar a categorização de propriedades por faixa de preço, ajudando no planejamento e posicionamento de mercado.

2. Identificação de Fatores Determinantes:
   - **Meta:** Analisar a importância das variáveis no modelo de previsão, identificando os fatores que mais influenciam a classe de preço.
   - **Objetivo:** Oferecer insights valiosos para desenvolvedores e investidores sobre quais características tornam uma propriedade mais valiosa.

3. Otimização do Processo de Avaliação:
   - **Meta:** Automatizar a previsão de classes de preço com alta precisão, utilizando modelos treinados em dados históricos de imóveis.
   - **Objetivo:** Reduzir o tempo e esforço necessários para avaliar propriedades, melhorando a eficiência e confiabilidade do processo.

4. Visualização de Resultados:
   - **Meta:** Criar gráficos e relatórios que apresentem a distribuição das classes de preço e o impacto das variáveis analisadas.
   - **Objetivo:** Facilitar o entendimento dos resultados por stakeholders, promovendo a utilização prática dos insights obtidos.

### Unsupervised
Objetivos específicos:

1. **Segmentação de Imóveis:**
   - **Meta:** Utilizar a técnica de **KMeans** para agrupar os imóveis em clusters com base em suas características, como preço, número de quartos, área do imóvel, localização, etc.
   - **Objetivo:** Identificar grupos de imóveis com características semelhantes, permitindo uma melhor análise e segmentação do mercado imobiliário, e facilitando a personalização de ofertas para diferentes grupos de consumidores.

2. **Identificação de Padrões no Mercado:**
   - **Meta:** Analisar a correlação entre as características dos imóveis e seus preços, e identificar quais variáveis mais impactam o preço final de venda.
   - **Objetivo:** Oferecer insights sobre os fatores que mais influenciam o preço dos imóveis, ajudando no desenvolvimento de estratégias de preços, bem como oferecendo recomendações sobre quais características valorizar em novos desenvolvimentos imobiliários.

3. **Melhoria da Precisão na Avaliação de Imóveis:**
   - **Meta:** Melhorar a precisão da avaliação de imóveis usando dados históricos de vendas, características dos imóveis e a segmentação obtida pelos clusters.
   - **Objetivo:** Oferecer uma ferramenta mais precisa para corretores de imóveis e investidores ao avaliar novos imóveis, ajudando-os a determinar um preço de venda mais adequado e competitivo com base nas características e no mercado local.

4. **Visualização dos Resultados para Tomada de Decisão:**
   - **Meta:** Criar visualizações interativas e gráficos que permitam aos stakeholders (gestores, investidores, etc.) analisar os dados de forma intuitiva.
   - **Objetivo:** Facilitar a comunicação de resultados e insights para equipes não técnicas, permitindo que tomadores de decisão compreendam rapidamente as tendências do mercado e façam escolhas informadas baseadas nos dados.
