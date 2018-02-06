# **Sistema de Recomendação de Filmes**

Os objetivos destes projeto são:

* Explorar o dataset [ml-latest-small](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip).
* Verificar se existe relação entre as categorias dos filmes.
* Verificar se existe relação entre os ratings e as categorias dos filmes.
* Construir um sistema de recomendação tendo como entrada o id do usuário. A saída deve ser um conjunto de filmes recomendados.
* Apresentar detalhadamente o pipeline da solução proposta.

### **Introdução**

Sistemas de recomendação são amplamentes conhecidos e utilizados em diversas aplicações. Estes sistemas tem como objetivo principal indicar produtos/serviços/conteúdos com base em perfis ou características de produtos já conhecidos. Neste sentido, os sistemas de recomendação podem ser divididos em dois tipos:
- filtragem colaborativa;
- filtragem baseada em conteúdo.

A filtragem colaborativa consiste na utilização de informações provenientes de comportamentos, atividades e preferências e, consequentemente, a análise de similaridade com outros usuários. Tendo como base esta análise comportamental são indicados novos produtos e serviços. A base para estas recomendações é que usuários que têm gostos similares tem grande probabilidade de concordar em recomendações futuras. Em outras palavras, os sistemas de recomendação baseados em filtragem colaborativa são construídos com base no comportamento dos usuários e suas similaridades. Um exemplo clássico deste tipo de recomendação é a sugestão de filmes tendo como base o perfil de cada usuário, os filmes já asssistidos e os ratings fornecidos pelos mesmos. 

Os sistemas de recomendação baseados em conteúdo buscam conhecer os produtos e serviços que serão objeto de recomendações. Por exemplo, para recomendação de filmes com base no conteúdo são analisadas as categorias de cada filme, o estilo, os atores e diretores e etc. Neste tipo de recomendação o foco é o conteúdo e suas características. Estes sistemas tem como premissa que o usuário irá gostar de novos produtos e serviços similares ao filmes que receberam altos ratings anteriormente.

Além disso, existem os sistemas híbridos que combinam características das recomendações colaborativas e dos sistemas baseados em conteúdo para obter melhores resultados.

### **Problema**
O problema que será abordado neste projeto é a recomendação de filmes, ou seja, tendo como base um conjunto de características de usuários e/ou filmes recomendar novos itens que ainda não foram assistidos pelos usuários.

Existem duas abordagens principais para a construção de sistemas de recomendação, como descrito na seção anterior. O primeiro tipo, chamado de filtragem colaborativa, demanda o uso de informações provenientes dos usuários. Desta forma, espera-se analisar informações comportamentais dos usuários como os filmes já assistidos, ratings dados pelo usuários e outras informações que permitam analisar similaridade entre os usuários. Já os sistemas de recomendação com base no conteúdo tem como objetivo analisar as caractarísticas dos filmes como, por exemplo, categorias, tags, diretores, elenco, relação entre as categorias e etc. Desta forma, como descrito anteriormente, o foco deste segundo tipo de abordagem está no conhecimento do filme que será recomendado. Uma terceira abordagem pode ainda combinar características das duas abordagens anteriores tendo uma solução mista. 

O sistema de recomendação, como apresentado na imagem abaixo, tem como entrada um identificador único do usuário para o qual serão feitas recomendações de novos filmes. Na segunda etapa é construída a solução de recomendação tendo como base as informações disponíveis no dataset. Estas informações podem ser sobre os filmes e/ou sobre os usuários. A solução pode seguir um dos três tipos de sistema de recomendação: filtragem colaborativa, sistemas baseados em conteúdo ou solução mista.   
![Visão geral do sistema de recomendação](Overview_do_Problema.jpg)

### **Dataset**
O dataset [ml-latest-small](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip) que será utilizado neste projeto foi obtido no site [Grouplens](https://grouplens.org/) mantido pelo Departamento de Ciência da Computação e Engenharia da Universidade de Minnesota, EUA.

Este dataset é composto de informações obtidas no site [Movielens](https://movielens.org/) que tem como objetivo recomendar filmes para os usuários. Existem duas versões do dataset. A primeira delas é destinada a pesquisas acadêmicas e a segunda para desenvolvimento e ensino. Por uma questão de poder computacional, será utilizada a versão reduzida do dataset destinado à ensino. Este é composto de aproximadamente 100 mil ratings, 1300 tags, 9 mil filmes avaliados por 700 usuários.

### **Solução Proposta**




### **Resultados**




### **Conclusões**


