# [Detecção de fraude em transações de cartões de crédito utilizando modelos classificatórios de Machine Learning](https://github.com/grmirand4/sc2023-deteccao-fraude-machine-learning)

**Projeto - Machine Learning I**

Instrutor: [Carlos Stefano](https://www.linkedin.com/in/carlos-stefano/)

**Equipe: [Gabriel Miranda](https://www.linkedin.com/in/grmiranda/), [Marcus Thadeu](https://www.linkedin.com/in/marcus-thadeu/), [Ruann Campos](https://www.linkedin.com/in/ruann-campos/) e [Thiago Caveglion](https://www.linkedin.com/in/thiago-caveglion/)**

## 🎯 Objetivo geral
Prever transações fraudulentas em cartões de crédito através da construção de modelos classificatórios de machine learning (KNN, Decision Tree, Random Forest e Gradient Boosting)

## 📝 Objetivos específicos
No desenvolvimento de nossa análise, buscamos responder às seguintes perguntas:
* É possível prever quais das transações realizadas entre 06/2020 e 12/2020 contidas em `fraudTest.parquet` são fraudulentas?
* Quais dos modelos classificatórios construídos apresentaram melhor performance?

## 📊 Sobre o data set
Os data sets `fraudTrain.parquet` e `fraudTest.parquet` utilizados em nossa análise apresentam informações fictícias retiradas [dessa base de dados do Kaggle](https://www.kaggle.com/datasets/kartik2112/fraud-detection). É um data set simulado de transações de cartões de crédito ocorridas entre as datas de 01/01/2019 a 31/12/2020; refere-se aos cartões de 1000 clientes diferentes realizando transações a 800 comerciantes distintos. As colunas dos arquivos incluem:
* `trans_date_trans_time`: data e hora da transação
* `cc_num`: número do cartão de crédito
* `merchant`: nome do comerciante
* `category`: categoria de compra
* `amt`: valor da transação
* `first`: primeiro nome da pessoa
* `last`: último nome da pessoa
* `gender`: gênero da pessoa que realizou a transação
* `dob`: data de nascimento da pessoa que realizou a transação
* `job`: profissão da pessoa que realizou a transação
* `street`, `state`, `zip`: endereço da pessoa que realizou a transação
* `city`: cidade da pessoa que realizou a transação
* `city_pop`: população da cidade da pessoa que realizou a transação
* `lat`: latitude da pessoa que realizou a transação
* `long`: longitude da pessoa que realizou a transação
* `merch_lat`: latitude do comerciante
* `merch_long`: longitude do comerciante
* `trans_num`, `unix_time`: dados da transação
* `is_fraud`: 1 para transações fraudulentas, 0 caso contrário
