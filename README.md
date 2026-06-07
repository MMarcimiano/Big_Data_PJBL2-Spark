# Big_Data_PJBL2-Spark
Repository for PJBL 2 of the Big Data discipline at PUCPR.

# PJBL 2 - Apache Spark com Python

## Descrição

Projeto desenvolvido para a disciplina de Big Data utilizando Apache Spark (PySpark) no Google Colab.

O objetivo do trabalho foi realizar consultas e análises sobre um conjunto de dados de operações comerciais internacionais utilizando os conceitos de:

- RDD
- PairRDD
- Transformações
- Ações
- Filtragem
- Ordenação
- Agregação de dados

---

## Dataset

O conjunto de dados utilizado contém aproximadamente:

- 8 milhões de registros
- 1,1 GB de tamanho
- Arquivo CSV separado por ";"

Estrutura das colunas:

| Coluna | Descrição |
|----------|----------|
| country_or_area | País |
| year | Ano |
| comm_code | Código da mercadoria |
| commodity | Descrição da mercadoria |
| flow | Tipo de fluxo comercial |
| trade_usd | Valor da transação em dólares |
| weight_kg | Peso em quilogramas |
| quantity_name | Unidade de medida |
| quantity | Quantidade |
| category | Categoria |

---

## Tratamento dos Dados

Antes da execução dos exercícios foi realizada uma etapa de preparação dos dados contendo:

- Remoção do cabeçalho
- Separação dos campos utilizando ";"
- Tratamento de valores faltantes
- Remoção de registros inválidos quando necessário
- Conversão de tipos numéricos para cálculos estatísticos

---

## Exercícios Desenvolvidos

### Exercício 1
Número de transações envolvendo o Brasil utilizando RDD.

### Exercício 2
Número de transações envolvendo o Brasil utilizando PairRDD.

### Exercício 3
Número de transações envolvendo o Brasil durante 2016 utilizando RDD.

### Exercício 4
Número de transações envolvendo o Brasil durante 2016 utilizando PairRDD.

### Exercício 5
Número de transações por Flow e por Ano a partir de 2010.

### Exercício 6
Média da coluna Price para o ano de 2016 utilizando RDD.

### Exercício 7
Média da coluna Price para o ano de 2016 utilizando PairRDD.

### Exercício 8
Preço máximo e mínimo por categoria e por ano.

### Exercício 9
País com o maior valor de exportação.

### Exercício 10
Preço mínimo por país e por ano.

### Exercício 11
Transação com maior preço por quilograma do tipo Export.

---

## Estrutura do Repositório

```

PJBL2/
│
├── PJBL2.ipynb
├── README.md
│
└── resultados/
├── exercicio1.txt
├── exercicio2.txt
├── exercicio3.txt
├── exercicio4.txt
├── exercicio5.txt
├── exercicio6.txt
├── exercicio7.txt
├── exercicio8.txt
├── exercicio9.txt
├── exercicio10.txt
└── exercicio11.txt

```

---

## Observação

O dataset original não foi incluído neste repositório devido ao seu tamanho aproximado de 1,1 GB, excedendo o limite recomendado para armazenamento no GitHub.

Para execução do notebook é necessário disponibilizar o arquivo CSV no Google Drive e ajustar o caminho de leitura conforme utilizado no código.

---

## Tecnologias Utilizadas

- Python 3
- Apache Spark (PySpark)
- Google Colab
- Google Drive
- GitHub

---

Disciplina de Big Data
