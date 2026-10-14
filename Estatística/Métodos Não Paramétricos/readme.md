# 📊 Análise Estatística Não Paramétrica com Python 🐍

Este projeto consiste em um estudo prático e detalhado sobre a aplicação e interpretação de **testes estatísticos não paramétricos**. O foco principal é fornecer uma abordagem intuitiva sobre quando e como utilizar cada teste em cenários onde os dados não atendem às suposições necessárias para testes paramétricos tradicionais (como a distribuição normal).

## 🎯 Objetivos

* **Compreender** os critérios teóricos para a escolha de testes não paramétricos.

* **Implementar** testes de hipóteses estatísticas utilizando Python e a biblioteca `scipy.stats`.

* **Analisar** amostras dependentes e independentes com diferentes distribuições e tamanhos.

* **Visualizar** a variação e distribuição dos dados através de gráficos comparativos.

* **Interpretar** estatísticas de teste ($U, H$, etc.) e valores-p ($p\text{-value}$) para tomada de decisão.

## 🛠️ Tecnologias Utilizadas

* **Python 3** 🐍: Linguagem principal do projeto.

* **NumPy** 🔢: Geração e manipulação de arrays/dados simulados.

* **Pandas** 🐼: Estruturação e análise de dados.

* **SciPy (`scipy.stats`)** 🧪: Execução dos testes não paramétricos e de normalidade.

* **Scikit-Posthocs** 🔬: Análises post-hoc após testes não paramétricos.

* **Matplotlib** 📈: Visualização de dados e plotagem de histogramas.

## 🧠 Conceitos Abordados

### 🔍 Quando usar Testes Não Paramétricos?

1. **Distribuição dos Dados**: Quando os dados não seguem uma distribuição normal ou possuem forte assimetria/outliers.

2. **Tamanho da Amostra**: Ideal para amostras pequenas onde a verificação de normalidade é difícil.

3. **Nível de Medida**: Aplicação em dados ordinais ou nominais (categóricos).

4. **Robustez**: Resistência a violações de suposições como a homocedasticidade.

### 🧪 Testes Estatísticos Aplicados

* **Teste de Shapiro-Wilk**: Teste de normalidade utilizado para avaliar se a amostra segue uma distribuição normal.

* **Teste de Wilcoxon**: Alternativa não paramétrica ao *teste t pareado*, utilizado para comparar duas amostras **relacionadas/dependentes**.

* **Teste U de Mann-Whitney**: Alternativa ao *teste t para amostras independentes*, utilizado para comparar duas amostras **independentes**.

* **Teste de Kruskal-Wallis**: Alternativa não paramétrica à *ANOVA*, utilizado para comparar três ou mais grupos **independentes**.

## 