# 📊 Análise de Testes Estatísticos Paramétricos e ANOVA em Python 🐍

Este repositório contém uma análise prática e didática sobre a verificação e aplicação de **testes estatísticos paramétricos** utilizando Python. O foco principal é demonstrar como validar os pressupostos necessários para garantir a precisão de inferências estatísticas ao comparar grupos.

## 🧐 O que é o projeto e o que acontece?

O projeto consiste em um estudo estruturado dentro de um **Jupyter Notebook**, explorando como os testes estatísticos tomam decisões a partir de amostras de dados.

**O que acontece no código:**

* Simulamos cenários reais (ex.: impacto de diferentes tipos de fertilizantes na altura de plantas e o efeito de dietas e exercícios na perda de peso).

* Aplicamos testes para comparar médias de dois ou mais grupos.

* Validamos detalhadamente se os dados atendem às premissas fundamentais (como **normalidade** e **homocedasticidade**) exigidas pelos métodos estatísticos.

## 🎯 Objetivos

* 📌 Demonstrar o uso prático de testes paramétricos em Python.

* 🧪 Ensinar a validar as suposições estatísticas exigidas antes de interpretar os resultados de um teste.

* 💡 Auxiliar no processo de tomada de decisão com base no valor-$p$ ($p$-value) e no nível de significância ($\alpha = 0.05$).

* 🔄 Comparar múltiplos fatores simultaneamente utilizando a ANOVA de Dois Fatores.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido em **Python 3** e utiliza as seguintes bibliotecas da ecossistema de ciência de dados:

* 🧮 **NumPy**: Manipulação de arrays e cálculo de métricas estatísticas básicas.

* 🐼 **Pandas**: Estruturação dos dados em DataFrames para análises fatoriais.

* 📈 **SciPy (`scipy.stats`)**: Aplicação dos testes estatísticos (Shapiro-Wilk, Teste $t$, Levene, Bartlett, ANOVA de um fator).

* 📊 **Statsmodels**: Modelagem estatística via regressão (OLS) e tabelas completas de ANOVA de dois fatores.

## 🔬 Conceitos Abordados

* 📐 **Propriedades dos Testes Paramétricos**: Suposições sobre a distribuição dos dados e o impacto da normalidade na eficiência do teste.

* 🔬 **Teste** $t$ **de Student (Amostras Independentes)**: Comparação entre as médias de dois grupos distintos.

* 📉 **Teste de Normalidade (Shapiro-Wilk)**: Avaliação da suposição de que os dados (ou resíduos) seguem uma distribuição normal.

* 📊 **ANOVA de Um Fator (Teste F)**: Comparação de médias entre três ou mais grupos independentes.

* ⚖️ **Homocedasticidade (Testes de Levene e Bartlett)**: Verificação da igualdade de variâncias entre os grupos comparados.

* 🔀 **ANOVA de Dois Fatores**: Avaliação dos efeitos principais de duas variáveis independentes simultaneamente, além da sua **interação**.

## 