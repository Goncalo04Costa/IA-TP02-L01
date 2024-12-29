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
### SuperVised

### Unsupervised
os objetivos específicos deste algoritmo são:

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

### Apriori
