# ANÁLISE DE VENDAS DE ECOMMERCE

## Introdução

Bem-vindo(a). Esse projeto traz uma análise de vendas de um ecommerce fictício. O objetivo é responder questionamentos que guiem tomadas de decisão por parte da gerência da empresa.

Esse projeto é baseado no desafio proposto pela comunidade "comunidados". A resolução oficial está disponível [nesse vídeo](https://www.youtube.com/live/vF-Ahnnt1mA). Apesar da existência de uma resolução, esse projeto foi realizado de forma independente.

## Dados

A base de dados usada nesse projeto é referente a vendas de um ecommerce. Foi criada usando dados fictícios e disponibilizada pelos organizadores da comunidade. Um dicionário dos dados está disponível [aqui](dicionario.md).

Por ser feita especialmente para esse projeto, a base de dados já foi criada sem erros ou anomalias.

_OBS: Incluir a base de dados em um repositório não é uma prática recomendada. Porém no caso específico desse projeto a base tem apenas 10000 linhas e menos de 1mb. Por isso a base também foi incluída no repositório para possibilitar replicação da análise._

## Desafio

### SQL
As questões a serem respondidas usando SQL são:

1. Qual o faturamento total por produto?
2. Qual o faturamento total por categoria?
3. Qual o ticket médio por cliente?
4. Qual o faturamento total por vendedor?
5. Qual o faturamento por mês?
6. Quais são os 5 produtos mais vendidos?
7. Qual cidade possui maior faturamento?
8. Qual cliente comprou mais em valor?

Além dessas perguntas, há ainda uma atividade para criar uma nova tabela (resumo_vendas) apenas com as colunas produto, categoria, quantidade_total e faturamento_total.

### Python
Já as atividades a serem respondidas usando Python são:

1. Ler o arquivo .csv
2. Criar coluna faturamento (quantidade * preço unitário)
3. Agrupar faturamento por produto
4. Agrupar faturamento por categoria
5. Agrupar faturamento por cliente
6. Criar gráfico de faturamento por categoria
7. Exportar arquivo resumo_vendas.csv

Além dessas questões, o desafio também propõe orientações para _insights_ de negócios. Porém nesse ponto esta análise difere do desafio original, pois serão traçadas estratégias de análise independentes.