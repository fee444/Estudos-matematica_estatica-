🎬 Sistema de Recomendação de Filmes

Projeto desenvolvido em Python que utiliza técnicas de Processamento de Linguagem Natural (NLP) para recomendar filmes semelhantes com base em características como gênero, palavras-chave, elenco, diretor e descrição.

🚀 Tecnologias Utilizadas
Python
Pandas
Numpy
NLTK
Scikit-Learn
📊 Como Funciona

O projeto segue as seguintes etapas:

Carregamento e união das bases de filmes e elenco.
Limpeza e tratamento dos dados.
Extração de informações relevantes (gêneros, palavras-chave, elenco e diretor).
Criação de uma coluna de tags contendo todas as características do filme.
Aplicação de técnicas de NLP para processamento textual.
Vetorização dos dados utilizando CountVectorizer.
Cálculo da similaridade entre os filmes com Cosine Similarity.
Retorno dos filmes mais parecidos com o título informado pelo usuário.
💡 Exemplo

Ao informar um filme como entrada:

sistema_recomendacao('Avengers: Age of Ultron')

O sistema retorna títulos com características semelhantes.

🎯 Objetivo

Este projeto foi desenvolvido para praticar conceitos de:

Manipulação e tratamento de dados
Processamento de Linguagem Natural (NLP)
Machine Learning aplicado a sistemas de recomendação
Engenharia de atributos (Feature Engineering)
