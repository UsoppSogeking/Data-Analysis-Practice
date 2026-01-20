# Week 03 — Covariance and Correlation (Descriptive Analysis)

Esta semana faz parte de uma trilha prática de estudos em **Análise de Dados com Python**, com foco no desenvolvimento do pensamento analítico por meio de **métricas descritivas** e **visualizações exploratórias**.

Após a **Week 01**, dedicada à leitura visual e compreensão da distribuição dos dados, e a **Week 02**, voltada à construção de métricas simples e comparações entre grupos, a **Week 03** introduz o estudo de **covariância e correlação** como ferramentas para descrever **como variáveis numéricas variam juntas**.

O foco permanece no entendimento conceitual, na leitura crítica dos resultados e na comunicação clara dos achados, evitando deliberadamente modelos estatísticos, regressões ou qualquer forma de inferência causal.

---

## 🎯 Objetivos da Week 03

Ao final desta semana, espera-se desenvolver a capacidade de:

* Compreender o conceito de covariância como medida de variação conjunta
* Interpretar o sinal e as limitações da covariância
* Entender a correlação como uma versão padronizada da covariância
* Ler e interpretar coeficientes de correlação de forma consciente
* Relacionar métricas numéricas com padrões visuais
* Descrever relações entre variáveis sem assumir causalidade

---

## 📊 Dataset

Nesta semana, continuamos utilizando o dataset **Tips**, amplamente empregado em estudos introdutórios de análise de dados.

Características do dataset:

* Cada linha representa uma conta em um restaurante
* Contém variáveis quantitativas e categóricas
* Ideal para análise de métricas simples e comparações entre grupos

O dataset está armazenado localmente na pasta:

```
datasets/raw/
datasets/processed/
```

---

## 📁 Estrutura do projeto

```
week_03_correlation_covariance/
│
├── datasets/
│   ├── raw/
│   │   └── tips.csv
│   └── processed/
│       └── tips_clean.csv
│
├── exercises/
│   ├── exercise_01_covariance.ipynb
│   ├── exercise_02_correlation.ipynb
│   └── exercise_03_visual_relationships.ipynb
│
└── README.md
```

---

## 🧪 Exercícios

### Exercise 01 — Covariância e variação conjunta

Introdução ao conceito de `covariância`, explorando como duas variáveis numéricas variam juntas.

Os exercícios abordam:

* Cálculo da covariância entre pares de variáveis
* Interpretação do sinal (positivo e negativo)
* Discussão sobre a influência da escala nas magnitudes
* Limitações da covariância como métrica interpretável isoladamente

O objetivo é entender a covariância como uma ferramenta descritiva, não comparável entre diferentes pares de variáveis.

---

### Exercise 02 — Correlação como métrica padronizada

Introdução à `correlação` como uma forma padronizada de medir a relação entre variáveis numéricas.

O foco está em:

* Cálculo de coeficientes de correlação
* Leitura de matrizes de correlação
* Interpretação da magnitude e do sinal dos coeficientes
* Comparação consciente entre diferentes pares de variáveis

A correlação é tratada como uma métrica de associação, sem qualquer interpretação causal.

---

### Exercise 03 — Relações numéricas e visualização

Conexão entre métricas numéricas e representações visuais.

Os exercícios envolvem:

* Gráficos de dispersão (scatter plots)
* Observação de padrões visuais e dispersão dos pontos
* Comparação entre leitura visual e coeficientes de correlação
* Uso de visualizações como apoio à interpretação descritiva

O objetivo é reforçar a importância de combinar números e gráficos na análise exploratória.

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

As análises realizadas nesta semana têm caráter **estritamente exploratório e descritivo**.

Não são realizados testes estatísticos, regressões ou inferências causais.
Os resultados devem ser interpretados apenas como descrições de padrões observados nos dados.

Esta abordagem visa construir uma base conceitual sólida para análises mais avançadas nas próximas semanas.