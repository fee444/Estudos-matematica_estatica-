# 📊 Distribuições de Probabilidade como Ferramentas de Análise

## 📌 O que é o projeto e o que acontece?
Este repositório contém uma análise prática e computacional de **distribuições de probabilidade de variáveis aleatórias discretas** utilizando Python. O projeto demonstra como quantificar a incerteza em processos e experimentos contáveis, abordando desde simulações de eventos clássicos até a modelagem matemática de probabilidades.

---

## 🎯 Objetivos
- 📝 **Descrever distribuições** de resultados possíveis em experimentos ou processos.
- 🧮 **Calcular probabilidades** exatas de eventos específicos ou intervalos.
- 📉 **Medir tendência central e dispersão** (média, variância e desvio padrão).
- 🔍 **Realizar inferências estatísticas** fundamentadas para a tomada de decisões.
- 💻 **Modelar e simular** fenômenos reais através de computação científica.

---

## 🛠️ Tecnologias
As seguintes bibliotecas e ferramentas foram utilizadas neste projeto:
- ![Python](https://img.shields.io/badge/Python-3.x-blue.svg?logo=python&logoColor=white)
- ![NumPy](https://img.shields.io/badge/NumPy-Data_Analysis-013243.svg?logo=numpy&logoColor=white)
- ![SciPy](https://img.shields.io/badge/SciPy-Statistical_Tools-8CAAE6.svg?logo=scipy&logoColor=white)
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Visualization-11557c.svg)

---

## 🧠 Conceitos Abordados
- **Variáveis Aleatórias Discretas**: Conceitos fundamentais e quantificação de incerteza.
- **Distribuição Uniforme Discreta**: Igualdade de probabilidade entre resultados finitos (ex: lançamento de um dado).
- **Distribuição Binomial**: Contagem de sucessos em ensaios independentes de Bernoulli (ex: lançamentos de moeda).
- **Outras Distribuições**: Introdução estrutural a Poisson, Geométrica, Binomial Negativa e Hipergeométrica.

---

## ⚙️ Fluxo do Algoritmo
1. **Importação de Bibliotecas**: Carregamento dos pacotes estatísticos (`scipy.stats`), de manipulação numérica (`numpy`) e visualização (`matplotlib.pyplot`).
2. **Definição de Parâmetros**: Configuração de variáveis como número de ensaios ($n$) e probabilidade de sucesso ($p$).
3. **Simulação Computacional**: Geração de amostras aleatórias (`np.random.randint`) ou cálculo direto de funções de massa de probabilidade (`binom.pmf`).
4. **Análise de Frequência**: Iteração para calcular contagens absolutas e percentuais das ocorrências simuladas.
5. **Visualização de Dados**: Construção de gráficos de barras (`plt.bar`) para exibir visualmente o comportamento das distribuições de probabilidade.