# Python-SQL-e-Spark
## Consumo de API

O projeto consiste em consumir uma API de previsão do tempo de um estado inteiro e analisar as previsões de chuva de todas as cidades do estado.

Neste projeto, utilizei requisições HTTP para coletar os dados sobre as cidades do estado no formato JSON e usei os nomes de cada uma como chave de entrada para fazer outra requisição ecoletar os dados das previsões de cada cidade dos ultimos 3 dias cidades.

Apos isso, utilizei Pyspark para criar tempviews dos dataframes com comandos SQL através do spark.sql

