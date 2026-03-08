# 📊 Análise de Evasão de Clientes (Churn) — Telecom X

---

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Visualization-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Viz-brightgreen)

---

## 📌 Descrição do Projeto

Este projeto tem como objetivo analisar a **evasão de clientes (Churn)** em uma empresa de telecomunicações fictícia chamada **Telecom X**.

A análise foi desenvolvida utilizando **Python e bibliotecas de análise de dados**, com o objetivo de identificar **padrões de comportamento que influenciam o cancelamento de clientes**.

A partir dessa análise, é possível compreender melhor os fatores associados ao churn e gerar **insights estratégicos para melhorar a retenção de clientes**.

---

# 🎯 Objetivo

Identificar padrões e fatores que influenciam o **cancelamento de clientes**, respondendo à seguinte pergunta:

> Quais características estão mais associadas à evasão de clientes na Telecom X?

---

# 📊 Indicadores Analisados

Durante a análise foram considerados diferentes aspectos do comportamento dos clientes, incluindo:

* 📅 Tempo de contrato dos clientes
* 💰 Valor da cobrança mensal
* 💳 Método de pagamento
* 🌐 Tipo de serviço de internet
* 🛡️ Serviços adicionais (segurança online, suporte técnico, backup)
* 📺 Serviços de streaming
* 📑 Tipo de contrato

Esses indicadores foram analisados para entender **quais perfis de clientes apresentam maior probabilidade de churn**.

---

# 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* Seaborn
* Matplotlib
* Google Colab

---

# 📈 Etapas da Análise

## 1️⃣ Extração e Tratamento dos Dados

* Importação dos dados a partir de API
* Normalização da estrutura JSON
* Limpeza e padronização das colunas
* Conversão de variáveis categóricas
* Criação de novas variáveis derivadas

---

## 2️⃣ Análise Descritiva

Foi realizada uma análise estatística inicial para entender a distribuição dos dados, incluindo:

* Média
* Mediana
* Desvio padrão
* Valores mínimos e máximos

Essa etapa ajudou a compreender o comportamento geral dos clientes.

---

## 3️⃣ Análise da Distribuição de Churn

Foi analisada a proporção de clientes que:

* Permaneceram no serviço
* Cancelaram o serviço

Essa visualização permite entender o **nível geral de evasão da empresa**.

---

## 4️⃣ Análise por Variáveis Categóricas

Foram utilizados **gráficos de contagem (Countplot)** para analisar como o churn se distribui entre diferentes categorias, como:

* Tipo de contrato
* Método de pagamento
* Serviços adicionais
* Tipo de internet

Essa análise ajuda a identificar **perfis de clientes com maior tendência ao cancelamento**.

---

## 5️⃣ Análise por Variáveis Numéricas

Também foram analisadas variáveis numéricas utilizando:

* 📊 Histogramas
* 📊 Boxplots

Esses gráficos permitiram comparar clientes que **cancelaram e não cancelaram**, identificando possíveis diferenças de comportamento.

---

# 📊 Principais Insights

A análise exploratória revelou alguns padrões importantes:

* Clientes com **contrato mensal apresentam maior taxa de cancelamento**.
* Clientes com **menor tempo de permanência** têm maior probabilidade de churn.
* Clientes que **não utilizam serviços adicionais** apresentam maior tendência ao cancelamento.
* O **valor da cobrança mensal** pode influenciar na decisão de permanência do cliente.

Esses fatores indicam que **retenção de clientes está fortemente ligada ao tempo de contrato e ao nível de engajamento com os serviços oferecidos**.

---

# 🧠 Conclusão

A análise permitiu identificar padrões relevantes que ajudam a compreender os fatores que influenciam o churn na empresa Telecom X.

Os resultados indicam que **clientes com contratos mais curtos e menor utilização de serviços adicionais apresentam maior risco de cancelamento**.

Essas informações podem auxiliar a empresa na criação de **estratégias de retenção e fidelização de clientes**.

---

# 🚀 Possíveis Melhorias Futuras

* Aplicação de **modelos preditivos de churn (Machine Learning)**
* Criação de **dashboard interativo (Power BI / Tableau)**
* Análise de **segmentação de clientes**
* Desenvolvimento de **modelo de previsão de churn**

---

# 📁 Estrutura do Projeto

```
📂 telecom-churn-analysis
 ├── Telecom_X_br_Nathan.ipynb
 ├── README.md
```

---

# 👤 Autor

| [<img src="https://github.com/NathanCarvalho7.png" width=115><br><sub>Nathan Carvalho</sub>](https://github.com/NathanCarvalho7) |
| :------------------------------------------------------------------------------------------------------------------------------: |

Projeto desenvolvido para prática de **Análise de Dados e identificação de padrões de churn utilizando Python**.

---

## 📜 Licença

Este projeto está sob a **MIT License**, permitindo uso, modificação e distribuição.
