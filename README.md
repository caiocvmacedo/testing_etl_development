# testing_etl_development
Exemplo de desenvolvimento de ETL para dados CSV.

### Desafio Técnico 
#### Objetivo 
#### Esse teste consiste em implementar um pipeline de dados que faça: 

•	Importação de um arquivo CSV para processamento 

•	Limpeza dos dados importados 

•	Criação de uma tabela-resultado que: 

o	Liste em ordem decrescente as “location_region” por média de “risk score” 

•	Criação de uma tabela-resultado que: 

o	Considerando somente a transação mais recente ("timestamp") com 
"transaction_type" igual a "sale" de cada "receiving address", liste os 3 "receiving address" com maior "amount" dentre estas transações (apresente o "receiving address", o "amount" e o "timestamp"). 

### Requerimentos 
#### Orquestração: 	
Gostaríamos de avaliar sua sugestão de solução para orquestração automatizada dessa pipeline de dados. 

#### Data Quality Automatizado:
Esta solução deverá monitorar através de indicadores e métricas de qualidade dos dados, como a quantidade de registros, a quantidade de erros, o percentual de conformidade (qtd. erros/ qtd. registros), entre outros, além de reportar os problemas e as anomalias de qualidade dos dados, como os valores faltantes, os valores inconsistentes, os valores incorretos, entre outros. 

#### Simplificar:
Quantidade total de registros

Quantidade de registros inseridos
 
Quantidade de registros com erro
