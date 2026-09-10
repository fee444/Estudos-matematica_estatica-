Regressão Linear com Scikit-Learn

Projeto desenvolvido durante meus estudos de Machine Learning, com foco na construção, avaliação e interpretação de um modelo de Regressão Linear utilizando Python e Scikit-Learn.

Sobre o projeto

O projeto utiliza um dataset com 400 registros e 7 variáveis relacionadas a vendas e entregas.

O objetivo é utilizar as informações disponíveis para construir um modelo capaz de prever o custo_entrega e, posteriormente, analisar a influência das variáveis preditoras sobre essa variável alvo.

Tecnologias utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
Etapas desenvolvidas
1. Carregamento e exploração dos dados

O dataset foi carregado utilizando Pandas e inicialmente foram analisadas sua estrutura, dimensões, tipos das variáveis e primeiras observações.

O conjunto possui:

400 registros
7 variáveis
Variáveis numéricas e categóricas
Nenhum valor nulo identificado na estrutura apresentada
2. Análise exploratória

Foi realizada uma análise exploratória considerando os diferentes tipos de variáveis, buscando compreender a estrutura dos dados antes da construção do modelo.

3. Preparação das variáveis

As variáveis foram separadas em:

Variáveis numéricas
Variáveis categóricas nominais
Variáveis categóricas ordinais

Para o pré-processamento foram utilizados:

StandardScaler para variáveis numéricas
OneHotEncoder para variáveis categóricas nominais
OrdinalEncoder para a variável categórica ordinal
4. Construção do Pipeline

Foi utilizado o ColumnTransformer para aplicar diferentes transformações às variáveis e, posteriormente, o Pipeline para integrar o pré-processamento ao modelo de Regressão Linear.

Essa abordagem permite manter o processo de transformação e modelagem organizado em um único fluxo.

5. Comparação de estratégias

Foram testadas duas estratégias de tratamento das variáveis categóricas.

Estratégia 1

As variáveis categóricas foram transformadas utilizando OneHotEncoder.

Resultado:

RMSE: 5,099
R²: 0,4218

Estratégia 2

As variáveis foram classificadas entre nominais e ordinais:

area_urbana e cliente_local → OneHotEncoder
status_entrega → OrdinalEncoder

Resultado:

RMSE: 5,124
R²: 0,4162

Nesse conjunto de dados, a primeira estratégia apresentou desempenho ligeiramente superior.

Interpretação dos coeficientes

Além da capacidade preditiva, o projeto também explorou os coeficientes da Regressão Linear para entender a relação entre as variáveis preditoras e o custo_entrega.

Entre os principais resultados:

Variável	Coeficiente
cliente_local_Sim	9,0489
status_entrega_Ruim	1,7012
valor_venda_unitario	1,5760
status_entrega_Medio	1,3328
area_urbana_Sim	-0,3692
idade_vendedor	0,3688
valor_venda_total	-0,1750

O maior coeficiente em magnitude foi o de cliente_local_Sim, indicando a maior associação estimada com o custo de entrega dentro do modelo.

É importante interpretar esses coeficientes considerando as demais variáveis constantes e lembrando que associação no modelo não significa necessariamente causalidade.

Principais aprendizados

Durante o desenvolvimento, foram praticados conceitos importantes de Machine Learning:

Análise exploratória de dados
Separação entre variáveis numéricas e categóricas
Codificação de variáveis categóricas
Padronização de dados
ColumnTransformer
Pipeline
Regressão Linear
Separação entre treino e teste
Predição
RMSE
R²
Interpretação de coeficientes
Comparação de diferentes estratégias de pré-processamento
Conclusão

O projeto reforçou que a construção de um modelo de Machine Learning não envolve apenas escolher um algoritmo.

O tratamento adequado das variáveis, a criação de um pipeline consistente, a avaliação dos resultados e principalmente a interpretação do modelo são etapas fundamentais para transformar dados em informações úteis.

Este projeto faz parte da minha jornada de estudos em Data Science e Machine Learning.
