# Desafio Lighthouse — Programa de Formação em Dados da Indicium
### Área: Ciência de Dados

## Cenário
Um time da **[Indicium](https://indicium.tech)** está trabalhando junto a um cliente no desenvolvimento de uma **Plataforma de Aluguéis Temporários** na cidade de Nova York. 
Para elaborar a **Estratégia de Precificação**, o cliente solicitou a realização de uma **Análise Exploratória** dos dados de seu principal concorrente, assim como testar a validade de um **Modelo Preditivo**. 

## Objetivo
Desenvolver um **Modelo Preditivo de Preços** (com base no _[dataset](dataset/teste_indicium_precificacao.csv)_)  e avaliá-lo por meio de métricas relevantes ao problema.  

## Perguntas de Negócio

1. Supondo que uma pessoa esteja pensando em alugar um apartamento usando a plataforma, qual localização seria a mais indicada?

2. O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?

3. Existe algum padrão no texto do nome da localização para lugares de mais alto valor?

4. Como você faria a previsão do **preço** a partir dos dados?
   4.1. Quais variáveis e/ou transformações foram usadas/realizadas? Por que?
   4.2. Qual tipo de problema a ser revolvido? (Regressão, Classificação)
   4.3. Qual modelo melhor se aproxima dos dados? Quais as vantagens e desvantagens?
   4.4. Qual medida de performance do modelo foi escolhida? Por que? 

5. Supondo um apartamento com as seguintes características:

```sh
{'id': 2595,
 'nome': 'Skylit Midtown Castle',
 'host_id': 2845,
 'host_name': 'Jennifer',
 'bairro_group': 'Manhattan',
 'bairro': 'Midtown',
 'latitude': 40.75362,
 'longitude': -73.98377,
 'room_type': 'Entire home/apt',
 'price': 225,
 'minimo_noites': 1,
 'numero_de_reviews': 45,
 'ultima_review': '2019-05-21',
 'reviews_por_mes': 0.38,
 'calculado_host_listings_count': 2,
 'disponibilidade_365': 355}
```

Qual preço seria sugerido?
A
A
Qual seria sugerido?

## Execução do Projeto

1 - Clone o repositório:

2 - Instale os requisitos/dependências do projeto: 

```sh
pip install -r requisitos.txt
```

3 - Instale o Jupyter Notebook via pip:

```sh
pip install jupyter
```

4 - Vá até o diretório "eda" e execute o arquivo "analise_exploratoria_dados.ipynb":

```sh
jupyter notebook
```
