📊 Análise Exploratória de Dados: Expectativa de Vida

1. 💡 O que é o projeto e o que acontece

Este projeto consiste em uma Análise Exploratória de Dados (EDA) aplicada a um conjunto de dados global sobre saúde pública e fatores socioeconômicos (dataset.csv). O script em Python realiza o carregamento, a inspeção inicial, a filtragem e a renomeação de variáveis de interesse — como expectativa de vida, mortalidade adulta, PIB, gastos com saúde e escolaridade. Em seguida, o projeto explora estatísticas descritivas e gera visualizações gráficas (histogramas e matrizes de dispersão) para entender como esses fatores se relacionam e influenciam a longevidade da população mundial.

2. 🎯 Objetivos

🧹 Estruturar e Limpar: Isolar as principais variáveis de impacto social e sanitário a partir de um dataset bruto.

📈 Compreensão Estatística: Mapear o comportamento estatístico (média, desvio padrão, distribuição) da variável alvo (life_expectancy) e das variáveis preditoras.

🔍 Identificação de Padrões: Visualizar correlações preliminares entre o desenvolvimento econômico/educacional de um país e a expectativa de vida de seus habitantes através de gráficos analíticos.

3. 🛠️ Tecnologias

As seguintes bibliotecas e ferramentas do ecossistema Python foram utilizadas no desenvolvimento:

🐍 Linguagem: Python 3.x

📓 Ambiente de Desenvolvimento: Jupyter Notebook

🐼 Manipulação e Análise de Dados: pandas, numpy

🎨 Visualização Gráfica: matplotlib, seaborn

🤖 Modelagem e Estatística: statsmodels, scikit-learn

4. 🧠 Conceitos Abordados

🔎 Análise Exploratória de Dados (EDA): Técnicas iniciais para examinar características, distribuições e resumos estatísticos de um conjunto de dados.

⚙️ Tratamento de Dados: Seleção de atributos, renomeação de colunas e criação de dicionários de metadados para melhor legibilidade.

📊 Visualização Multivariada: Uso de gráficos de dispersão emparelhados (pairplot) para examinar simultaneamente múltiplas relações numéricas.

🌍 Saúde Global e Economia: Estudo de variáveis de desenvolvimento humano (PIB per capita, anos de escolaridade e gastos governamentais com saúde) em relação à longevidade.

5. 🔄 Fluxo do Algoritmo

O script executa a seguinte sequência lógica:

📦 Importação: Carregamento das bibliotecas de manipulação (pandas, numpy) e visualização (seaborn, matplotlib).

📂 Carregamento dos Dados: Leitura do arquivo dataset.csv para um DataFrame inicial.

👁️ Inspeção Inicial: Verificação da dimensionalidade (shape), tipos de dados (dtypes) e amostragem das primeiras linhas.

✂️ Limpeza e Seleção: Filtragem das colunas estritamente necessárias e padronização de seus nomes para facilitar a referência no código.

📖 Dicionário Descritivo: Mapeamento conceitual das variáveis escolhidas para documentar o significado de cada coluna.

📉 Análise Descritiva e Visual:

Geração de estatísticas descritivas básicas (describe).

Construção de histogramas da expectativa de vida.

Criação de gráficos de pares (pairplot) para correlacionar o comportamento da variável alvo com indicadores populacionais, de saúde e econômicos.
