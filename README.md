# ANÁLISE DE VENDAS DE ECOMMERCE

## Introdução

Bem-vindo(a). Esse projeto traz uma análise de vendas de um ecommerce fictício. O objetivo é responder questionamentos que guiem tomadas de decisão por parte da gerência da empresa.

Esse projeto é baseado no desafio proposto pela comunidade "comunidados". A resolução oficial está disponível [nesse vídeo](https://www.youtube.com/live/vF-Ahnnt1mA). Apesar da existência de uma resolução, esse projeto foi realizado de forma independente.

## Dados

A base de dados usada nesse projeto é referente a vendas de um ecommerce. Foi criada usando dados fictícios e disponibilizada pelos organizadores da comunidade. Um dicionário dos dados está disponível [aqui](dicionario.md).

Por ser feita especialmente para esse projeto, a base de dados já foi criada sem erros ou anomalias.

_OBS: Incluir a base de dados em um repositório não é uma prática recomendada. Porém no caso específico desse projeto a base tem apenas 10000 linhas e menos de 1mb. Por isso a base 'resumo_vendas.csv' também foi incluída no repositório, possibilitando a replicação da análise._

## O Desafio
Os seguintes exercícios são parte do desafio original proposto pela comunidade. Todos os passos para a resolução estão [nesse notebook](exercicios_propostos.ipynb).

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
4. Agrupar faturamento por cliente
5. Agrupar faturamento por categoria
6. Criar gráfico de faturamento por categoria
7. Exportar arquivo resumo_vendas.csv


## A Análise

Além desses exercícios, o desafio também propõe orientações para _insights_ de negócios. Porém nesse ponto esta análise difere do desafio original, pois foram traçadas estratégias de análise independentes. O notebook com a parte técnica dessa análise está disponível [nesse link](analise.ipynb) e a apresentação dos resultados está disponível [nesse post](https://medium.com/@mviniciusc93/análise-temporal-de-vendas-de-e-commerce-e5bce38c4557?postPublishedType=repub)

## Ferramentas e tecnologias utilizadas

* Python: Linguagem principal
* Pandas e Matplotlib: Bibliotecas para manipulação de dados e visualização gráfica.
* SQL: Criação e consulta a banco de dados.
* Github: Versionamento e publicação técnica.

## Tratamento e estruturação de dados

Os dados do arquivo .csv original foram estruturados em um banco de dados .db para realização dos exercícios em SQL e posterior consulta para os exercícios em python e análise. Python foi usado para os exercícios da linguagem e para a criação de dataframes específicos de acordo com as necessidades da análise, além da visualização gráfica.

## Conclusões da análise
A principal conclusão da análise temporal é que uma queda no volume de vendas de notebooks em determinados meses do ano puxa para baixo o faturamento da empresa. A partir dessa conclusão pode-se traçar estratégias financeiras e de marketing para que se mitigue a queda de vendas desse produto ou que se reduza o impacto dessa queda no faturamento geral.