<h1 align="center"> Bem vinda(o) ao Imersão Dados 04 - Alura😊 </h1>

# Imersão Dados 04 

Como realizar predição de preços de imóveis utilizados vários bancos de dados

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Imersão Dados 04**
| :label: Tecnologias | Python, Jupyter Notebook, Geopandas
| :rocket: URL         | https://github.com/KaueAbbe/ImersaoDados
| :fire: Desafio     | https://www.alura.com.br/imersao-dados-4


## Detalhes do projeto

![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=DESENVOLVIMENTO&color=<COLOR>)

<h2 align ="center"> Objetivo da imersão: Predição de Preços de Imóveis em São Paulo🤔</h2>

A Imersão Dados 04 da Alura é um evento de desafio em que os participantes passam uma semana vendo aulas e desenvolvendo um projeto. Os desafiantes dão a aula e passam desafios para os participantes mergulharem no mundo da ciência de dados.

Baseado nos dados de preços de imóveis em São Paulo o objetivo é predizer os valores dos imóveis em São Paulo. 
Para isto quero analisar o dataset e cruzar meu dataset com dados do IBGE para conseguir incrementar o dataset e conseguir fazer uma predição melhor.

O objetivo do modelo é conseguir prever qual seria os valores de um imóvel com determinadas características, como quantidade de banheiro, vaga, localização, tamanho. 
O cruzamento com dados do IBGE vai fornecer valores de rendas e afins relacionados a localização dos imóveis. 

<h2 align ="center"> Quais bibliotecas encontrarei nos notebooks?</h2>
1. Para ler dados: Pandas 🐼|
2. Para ler dados de Geoprocessamento: GeoPandas |
3. Para matemática: Numpy e StatsModels |
4. Para visualização de dados: Seaborn |


<h2 align ="center"> Detalhes do Notebook:</h2>

- [X]  Leitura e tratamento de Dados
- [X]  Visualização de Dados
- [X]  Realização de Desafios dos Instrutores
- [X]  Cruzamento com dados do IBGE
- [X]  Tratamento geográfico do Dataset
- [X]  Criação de Modelo Preditivo

<h2 align ="center">Desenvolvido</h2>

Foi lido o dataset do Kaggle de imóveis de São Paulo e realizou tratamento para alterar tipo de valores que estavam com tipo palavra e foi transformada em número para 
realizar análises, que foram feitas posteriormente com utilização de gráficos do Pandas e do Seaborn.<br>


Posteriormente foi lida dados do IBGE e feito cruzasamento destes dados com o dataset original. Para realizar o cruzamento foi utilizado biblioteca geopandas, shapely
e folium para realizar tratamento geográfico por setor censitário definido pelo IBGE. Utilizei conceito de polígonos e área para determinar qual o setor censitário
pertence o endereço no dataset original. Com os dados do IBGE e do dataset original foi realizado o mapa da cidade de São Paulo analisando a média da renda por setor
censitário.

Por fim foi criado dois modelos de Machine Learning. Um baseado em regressão linear e outro basedo em regressão polinomial. A métrica utilizada para avaliar o modelo foi avaliar o valor do resultado da predição teste e predição treino e obter o valor de R². O melhor modelo foi o basedo em regressão linear.


<h2 align ="center"> Em desenvolvimento:</h2>

1. Atualizar a análise exploratória dos dados e implementar a mudança no modelo
2. Correção o erro de não mostrar o mapa de São Paulo separado por renda dos setores censitários.

<h2 align ="center"> Links e Referências:</h2>

1. <a href=https://medium.com/creditas-tech/dados-georreferenciados-exploração-e-visualização-com-python-edd51e7c53da>Medium - Dados Georreferenciados</a>
2. <a href=https://www.tylervigen.com/spurious-correlations>Exemplos de Correlação</a>


<h2 align ="center">Autor</h2>

<a >
 <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/68445400/167875457-fac973a9-9ff7-44aa-bd3b-d121e2a805d4.jpg" width="150px;" alt=""/>
 <sub><b></b></sub></a> <a>🚀</a>

<h4> Feito com 💙 por Kaue Hermann Abbehausen 👋🏽 
<br/> Formado em Física na Universidade Federal de Uberlândia e estudante de Data Science</h4>
<h4> Entre em contato por</h4>
<div align = "center"> 
   <a href="https://www.linkedin.com/in/kaue-abbehausen-5b1922165/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href="https://www.instagram.com/cienciaeanimacao/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:kaueabbehausen@hotmail.com"><img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" target="_blank"></a>
</div>
