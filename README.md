# Atividades de Introdução à ciência de dados e inteligência artificial

- Professor: Bruno Faiçal
- Data de início: 10/06/2026
- Linguagem e ferramentas utilizadas: python, jupyter notebook
- Bibliotecas: Pandas, Numpy e Matplotlib

## 1️⃣ Atividade 1NN

A atividade consiste em três etapas:
1. Ler um conjunto de dados _base_ e outro _classificar_ e, a partir de um algoritmo _1NN_, classificar os registros da conjunto _classificar_.
2. Elaborar um algoritmo _KNN_, que aceite um _K_ arbitrário e realize a mesma classificação com bases nas mesmas duas bases de dados.
3. Identificar qual o _K_ que produz o melhor resultado.
A atividade utiliza conjuntos de dados no formato _.csv_ e, por meio de manipulação de dados utilizando a biblioteca pandas, consegue classificar plantas em 3 categorias: _Iris-virginia, Iris-setosa e Iris-versicolor_. Os conjuntos dispõe de quatro características: _tamanho e largura da sépala e tamanho e largura da pétala_. Esse conjunto de dados está disponível publicamente e pode ser encontrado neste <a href="https://archive.ics.uci.edu/dataset/53/iris">link</a>.

## 2️⃣ Atividade KNN

A atividade consistem em 5 etapas:
1. Elaborar uma função que receba um conjunto de dados e uma porcentagem de registros que irão compor o conjunto de teste, e que retorne o conjunto de testes sem rotulo, o conjunto para treino e rotulos dos registros do conjunto de testes. A seleção dos elementos do conjunto de testes deve ser aleatória e serem retirados do conjunto de treino.
2. Utilizar a função descrita acima com um algoritmo KNN, realizando varios testes e considerando uma porcentagem de 20% para registros de treino.
O conjunto de dados utilizado é o mesmo da atividade 1.