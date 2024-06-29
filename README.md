Introdução:

Esse relatório apresenta o trabalho realizado no âmbito de uma atividade extensionista, cujo objetivo foi a coleta, preparação e análise de dados de imunizações no Brasil, no período de 1994 a 2022. O trabalho foi desenvolvido em grupo e disponibilizado de forma aberta no GitHub, conforme as diretrizes do projeto.

Hipóteses de Pesquisa:

As hipóteses de pesquisa formuladas para este trabalho foram:

1: Eventos históricos e políticas de saúde pública têm um impacto significativo no número de imunizações realizadas ao longo do tempo.
2: A introdução de novas vacinas e campanhas de vacinação em massa resultam em aumentos bruscos no número de doses aplicadas.
3: Crises econômicas e pandemias influenciam negativamente o número de imunizações devido a cortes de orçamento e redirecionamento de recursos.

Bases de Dados Escolhidas:

A base de dados utilizada neste trabalho foi obtida do DataSUS, contendo informações detalhadas sobre o número de imunizações realizadas no Brasil de 1994 a 2022. A base de dados do Sistema de Informação do Programa Nacional de Imunizações (SI-PNI/CGPNI/DEIDT/SVS/MS) inclui registros anuais e abrange diversas categorias de vacinas. Baixamos diretamente do DataSUS o arquivo .csv utilizado, selecionando Região como linha, Ano como coluna e a medida Doses_aplicadas. 

Desenvolvimento:

O desenvolvimento do projeto envolveu a criação de um script em Python para realizar a integração, limpeza e transformação dos dados, além da análise e visualização dos resultados. O processo de desenvolvimento pode ser descrito nos seguintes passos:
Carregamento e Inspeção Inicial:
Os dados foram carregados utilizando a biblioteca pandas em Python, com a codificação latin1 e delimitador (;).
Foi realizada uma inspeção inicial para identificar e remover linhas irrelevantes e garantir a correta leitura dos dados.
Renomeação e Reestruturação das Colunas:
As colunas foram renomeadas para refletir os anos de 1994 a 2022, além de uma coluna para o total de imunizações.
Os dados foram transpostos para facilitar a manipulação e análise.
Filtragem e Seleção de Dados Relevantes:
Foi selecionada a linha contendo os totais anuais de imunizações.
Colunas irrelevantes foram removidas, mantendo apenas as colunas necessárias para a análise.
Conversão de Tipos de Dados:
A coluna de anos foi convertida para tipo inteiro para facilitar a manipulação e visualização.
Salvamento dos Dados Limpos:
Os dados limpos foram salvos em um novo arquivo CSV para futuras análises.
Análise e Visualização dos Dados:
Utilizando a biblioteca matplotlib, foi gerado um gráfico que mostra a evolução do número de imunizações ao longo dos anos, destacando eventos históricos significativos que impactaram esses números.
As análises incluíram a identificação de picos e quedas no número de imunizações, correlacionando esses eventos com campanhas de vacinação, introdução de novas vacinas, crises econômicas e a pandemia de COVID-19.


Análises Realizadas e Conclusões Obtidas:

As análises realizadas envolveram a plotagem de gráficos e a identificação de eventos históricos que impactaram o número de imunizações ao longo do tempo. A seguir, são apresentadas as principais conclusões obtidas:

1) Impacto de Eventos Históricos e Políticas de Saúde Pública:

1994: A erradicação da poliomielite nas Américas resultou em campanhas massivas de vacinação, refletindo um aumento significativo nas imunizações.
1997: A campanha nacional de vacinação contra o sarampo contribuiu para um aumento notável no número de doses aplicadas.
2000: A continuidade da expansão do PNI (Programa Nacional de Imunizações), com a introdução de novas vacinas e estratégias de cobertura universal, manteve um crescimento constante no número de imunizações.

2) Introdução de Novas Vacinas e Campanhas de Vacinação:

2002: A introdução da vacina contra hepatite B para crianças menores de 1 ano levou a um aumento nas imunizações.
2003: A implementação da vacina contra Haemophilus influenzae Tipo B (Hib) resultou em um aumento adicional.
2008: A campanha nacional de vacinação contra a rubéola foi uma das maiores do mundo, causando um pico no número de doses aplicadas.
2010: A campanha de vacinação contra H1N1 foi outro evento significativo, seguido por uma queda em 2011 devido à redução na demanda pós-campanha.
2013: A introdução das vacinas HPV, pentavalente e VIP causou um aumento nas imunizações.

3) Influência de Crises Econômicas e Pandemias:
2014-2016: A crise econômica iniciada em 2014 atingindo um ponto crítico em 2016 levou a cortes de orçamento na saúde, refletindo uma queda nas imunizações.
2019-2020: Esforços de vacinação antes da pandemia de COVID-19 resultaram em um aumento em 2019, seguido por uma queda em 2020 devido ao redirecionamento de recursos e impactos da pandemia.

Dashboards:

Os dashboards desenvolvidos para este trabalho foram criados utilizando bibliotecas de visualização de dados em Python, como `matplotlib`. Os gráficos mostram a evolução do número de imunizações ao longo dos anos, destacando eventos históricos significativos que impactaram esses números.


Referências Utilizadas:

DataSUS - Sistema de Informações do Programa Nacional de Imunizações.
Organização Pan-Americana da Saúde (OPAS) - Relatórios sobre a erradicação da poliomielite.
Ministério da Saúde - Relatórios de campanhas de vacinação e introdução de novas vacinas.
Sistema de Informação do Programa Nacional de Imunizações (SI-PNI/CGPNI/DEIDT/SVS/MS)
Conselho Nacional de Saúde - Efeitos da pandemia na vacinação no Brasil

