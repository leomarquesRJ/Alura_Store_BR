# 📊 Análise de Vendas - Desafio Alura Data Science

Este projeto foi desenvolvido com o objetivo de praticar análise de dados em Python com `pandas` e `matplotlib`, utilizando um conjunto de dados de vendas de quatro lojas.

Ferramenta utilizada: Jupyter Notebook

## 🧾 Dados Utilizados
- Produto
- Preço
- Categoria
- Tipo de pagamento
- Loja
- Data da compra
- Frete
- Avaliação

## 📦 Bibliotecas Utilizadas

```python
import pandas as pd
import matplotlib.pyplot as plt
```

## 📌 Etapas da Análise

### 1. Carregamento dos Dados

Foram carregados 4 arquivos `.csv`, um para cada loja, utilizando o `pandas.read_csv()`.

```python
loja1 = pd.read_csv(url1)
loja2 = pd.read_csv(url2)
loja3 = pd.read_csv(url3)
loja4 = pd.read_csv(url4)
```



### 2. Padronização das Colunas

Padronizamos os nomes das colunas para facilitar o manuseio:

- Todas as letras em minúsculas
- Espaços substituídos por `_`
- Acentos removidos

### 3. Criação de Novas Colunas

faturamento: como cada linha representa uma venda, faturamento foi igual ao preço.
ano_mes: colunas para facilitar agrupamentos por período.

## 📈 Análises Realizadas

🔹 Faturamento Total
🔹 Faturamento Mensal
🔹 Faturamento por Categoria (gráfico de barras)
🔹 Tipo de Pagamento (gráfico de pizza)
🔹 Média de Avaliação por Loja (gráfico de barras) e Melhor e Pior loja
🔹 Produtos Mais e Menos Vendidos
🔹 Vendas por Produto (gráfico de pizza)
🔹 Média do Frete por Loja (gráfico de barras)

## 📌 Conclusões

- Identificamos o faturamento total no periodo e ao longo dos meses.
- Avaliamos os produtos mais rentáveis.
- Comparações entre lojas por frete, avaliação e desempenho de vendas.
