# 📊 Probabilidade e Estatística com Python: Funções de Densidade e Integrais

> Um repositório prático para explorar os fundamentos matemáticos e computacionais de variáveis aleatórias contínuas, integrais e distribuições estatísticas utilizando Python. 🚀

## 🧐 O que é o Projeto e o que Acontece?

Este projeto demonstra, através de código em Python e visualizações gráficas interativas, como a teoria da probabilidade se conecta com o cálculo integral.
O script aborda a **Função de Densidade de Probabilidade (FDP)** para variáveis contínuas, explicando como calcular a probabilidade de um evento cair em um determinado intervalo utilizando a área sob a curva (integrais definidas). 📉📈

## 🎯 Objetivos

* **Desmistificar FDPs:** Explicar o papel das Funções de Densidade de Probabilidade no estudo de variáveis contínuas. 🧩

* **Aplicações de Integrais:** Demonstrar o uso prático de integrais definidas para o cálculo de áreas e probabilidades. 📐

* **Visualização de Dados:** Utilizar bibliotecas científicas para plotar e analisar diferentes distribuições estatísticas. 📊

* **Apoio a Ciência de Dados e Machine Learning:** Fornecer uma base sólida sobre distribuições que fundamentam algoritmos estatísticos. 🤖

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes bibliotecas do ecossistema Python:

* **Python 3.x** - Linguagem principal de programação.

* **NumPy** - Manipulação eficiente de arrays numéricos e operações matemáticas.

* **SciPy** (`scipy.stats`, `scipy.integrate`) - Funções estatísticas, distribuições contínuas e cálculo de integrais.

* **Matplotlib** - Criação de gráficos estáticos e visuais para análise de probabilidade.

## 🧠 Conceitos Abordados

1. **Função de Densidade de Probabilidade (FDP):** Descrição de como as probabilidades são distribuídas ao longo de intervalos contínuos. 📋

2. **Cálculo Integral:**

   * *Integral Indefinida:* Antiderivadas e o conceito inverso da diferenciação. 🔄

   * *Integral Definida:* Cálculo da área sob a curva de uma função entre limites específicos. 📏

3. **Distribuição Normal (Gaussiana):** A clássica "curva em sino" aplicada a fenômenos naturais, com exemplos práticos de cálculo de intervalos (ex: regra empírica de 68%). 🔔

4. **Distribuição Uniforme Contínua:** Modelagem onde todos os valores de um intervalo possuem exatamente a mesma probabilidade de ocorrência. ⏹️

5. **Distribuição Exponencial e Processo de Poisson:** Modelagem do tempo entre eventos independentes com taxa constante (ex: tempo de resposta em chamados de TI). ⏱️

## 🔄 Fluxo do Algoritmo

O script executa o seguinte pipeline lógico:

1. **Importação de Bibliotecas:** Carregamento de módulos essenciais de matemática, estatística e plotagem (`numpy`, `scipy`, `matplotlib`). 📦

2. **Definição de Parâmetros:** Configuração de parâmetros estatísticos (como média $\mu$, desvio padrão $\sigma$, ou taxa $\lambda$). ⚙️

3. **Cálculo Numérico:**

   * Definição do intervalo de interesse ($[a, b]$).

   * Cálculo da densidade de probabilidade teórica.

   * Aplicação de integração numérica (ex: `scipy.integrate.quad`) para mensurar a área sob a curva. 🧮

4. **Geração de Gráficos:**

   * Plotagem das curvas de densidade.

   * Destaque visual (preenchimento de áreas correspondentes às probabilidades calculadas).

   * Exibição de anotações com os valores numéricos obtidos. 🎨