analise-faturamento-lojas
Análise Estratégica de Desempenho – Alura Store Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio de Data Science com o objetivo de analisar o desempenho das quatro lojas da rede Alura Store e recomendar qual unidade deve ser vendida para viabilizar um novo empreendimento.

A análise foi conduzida com base em dados reais disponibilizados pela Alura, considerando indicadores financeiros e operacionais relevantes para a tomada de decisão estratégica.

Objetivo

Identificar a loja com menor eficiência operacional e financeira, utilizando análise de dados para apoiar a decisão do gestor.

Estutura dos Dados

O dataset contém as seguintes informações:

Produto e Categoria

Preço

Frete

Data da Compra

Local da Venda

Avaliação da Compra

Tipo de Pagamento

Parcelas

Coordenadas Geográficas

🛠 Tecnologias Utilizadas

Python

Pandas

Matplotlib

Google Colab

   Análises Realizadas
✔ 1. Faturamento Total por Loja

Cálculo da soma da coluna Preço para identificar a capacidade de geração de receita de cada unidade.

✔ 2. Vendas por Categoria

Agrupamento por categoria para identificar os segmentos mais populares.

✔ 3. Média de Avaliação dos Clientes

Cálculo da média das avaliações para medir a satisfação dos consumidores.

✔ 4. Produtos Mais e Menos Vendidos

Análise da frequência de vendas por produto.

✔ 5. Frete Médio por Loja

Cálculo do custo médio logístico para avaliar impacto operacional.

     Visualizações
Foram gerados gráficos utilizando Matplotlib, incluindo:

Gráfico de barras – Faturamento por loja

Gráfico de barras – Média de avaliações

Gráfico de barras – Frete médio

Análise visual das categorias mais vendidas

As visualizações foram utilizadas para facilitar a interpretação dos dados e apoiar a recomendação final.

                             Principais Resultados
Após a análise dos indicadores:

A Loja 4 apresentou o menor faturamento (R$ 1.384.497,58)

A Loja 4 apresentou a menor média de avaliação (3,99)

A Loja 1 apresentou o maior frete médio (34,69)

A integração dos dados demonstrou que a Loja 4 possui o desempenho geral mais baixo entre as quatro unidades.

Recomendação Final

Com base na análise financeira e operacional, recomenda-se a venda da Loja 4, pois apresenta:

Menor geração de receita

Menor nível de satisfação dos clientes

Menor competitividade relativa

A decisão é orientada por dados e fundamentada em indicadores estratégicos, reduzindo riscos e permitindo realocação eficiente de recursos.

                                 Como Executar o Projeto
Clone o repositório:

git clone https://github.com/DalilaReis650/alura-store-data-science.git

Instale as dependências:

pip install pandas matplotlib

Execute o notebook no Google Colab ou Jupyter.

                                      Autora
Projeto desenvolvido por Dalila Vieira
