# Week 02 — Basic Metrics and Group Analysis

Esta semana faz parte de uma trilha prática de estudos em **Análise de Dados com Python**, com foco no desenvolvimento do pensamento analítico utilizando **Pandas, NumPy e visualizações simples**.

Enquanto a **Week 01** teve como objetivo compreender a estrutura dos dados e observar padrões iniciais, a **Week 02** avança para a construção de **métricas simples** e **comparações entre grupos**, mantendo um escopo controlado e progressivo.

O foco não está em KPIs corporativos ou análises estatísticas avançadas, mas sim em aprender a **formular perguntas analíticas** e **respondê-las com operações básicas sobre os dados**.

---

## 🎯 Objetivos da Week 02

Ao final desta semana, espera-se desenvolver a capacidade de:

* Criar métricas simples a partir dos dados
* Agrupar informações por variáveis categóricas
* Comparar grupos de forma consciente
* Trabalhar com médias, contagens e proporções
* Transformar tabelas-resumo em visualizações claras
* Interpretar resultados sem tirar conclusões precipitadas

---

## 📊 Dataset

Continuamos utilizando o dataset **Tips**, amplamente empregado para estudos introdutórios em análise de dados.

Características do dataset:

* Cada linha representa uma conta em um restaurante
* Contém variáveis quantitativas e categóricas
* Ideal para análise de métricas simples e comparações entre grupos

O dataset está armazenado localmente na pasta:

```
datasets/raw/
```

---

## 📁 Estrutura do projeto

```
week_02_basic_metrics/
│
├── datasets/
│   ├── raw/
│   └── processed/
│
├── exercises/
│   ├── exercise_01.ipynb
│   ├── exercise_02.ipynb
│   └── exercise_03.ipynb
│
└── README.md
```

---

## 🧪 Exercícios

### Exercise 01 — Métricas simples por grupo

Introdução ao uso de `groupby` e agregações básicas para responder perguntas como:

* Valor médio da conta por dia
* Gorjeta média por período
* Tamanho médio das mesas por grupo

O objetivo é aprender a **resumir dados** sem ainda interpretá-los como indicadores de desempenho.

---

### Exercise 02 — Comparações e proporções

Foco em análises comparativas entre grupos, trabalhando com:

* Contagens relativas
* Proporções
* Distribuição de observações entre categorias

Aqui o objetivo é desenvolver a leitura de tabelas e entender diferenças relativas entre grupos.

---

### Exercise 03 — Métricas e visualização

Aplicação das métricas construídas em visualizações simples, como:

* Gráficos de barras
* Gráficos de linha básicos

O foco é aprender a **traduzir tabelas em gráficos** e descrever visualmente o que os dados mostram.

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## ⚠️ Observação importante

As análises realizadas nesta semana têm caráter **exploratório e descritivo**. Nenhuma conclusão deve ser interpretada como causal ou como tomada de decisão de negócio.

O objetivo é construir uma base sólida para análises mais avançadas nas próximas semanas.