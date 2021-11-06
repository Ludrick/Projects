# Desafio Data Science - Creditas

## O problema

Precisamos entender como podemos priorizar os clientes de maneira que os clientes que tenham a maior probabilidade de serem enviados para a análise de crédito sejam atendidos primeiro.

### Contexto sobre o fluxo do cliente

Após preencher os dados no site, solicitando um empréstimo com garantia de automóvel, o cliente passa por um conjunto de regras automáticas para saber se ele será pré-aprovado. Em caso positivo esse cliente pode prosseguir no fluxo e preencher uma quantidade maior de dados (ficha cadastral), o que irá agilizar o seu processo de atendimento. Em caso negativo, esse cliente fica impedido de fazer uma solicitação de empréstimo. Independente de preencher a ficha cadastral, o cliente pode ser atendido e um consultor de negócios fará a avaliação se a pessoa deve ou não ser enviada para análise.

### Objetivo

O objetivo é construir um modelo de classificação que retorne a probabilidade que um cliente tem de ser enviado para análise de crédito dado que ele foi pré-aprovado para o empréstimo com garantia de automóvel.

## Os dados
- Todos os dados necessários para modelagem estão no arquivo `dataset.csv`. A descrição dos dados está no arquivo `description.csv`.
- Nesta base estão todos os clientes que entraram no site, mesmo aqueles que não foram pré-aprovados, sendo necessário filtrar os clientes válidos.