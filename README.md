# projeto_aplicado_1
Projeto de Análise Exploratória de Dados 🎓🏡📊
Estudos de Oportunidades Baseadas no Airbnb Open Data RJ
Universidade Presbiteriana Mackenzie 🏫✨
Faculdade de Computação e Informática 💻🔍
Autores:

André Dalle Vedove Canassa – 10415817 ✉️
Kaymmi Antunes Costa Silva – 10415640 ✉️
Matheus Gomes – 10408179 ✉️
Valdo Alvim da Rocha Junior – 10414936 ✉️
Docente:

Prof. Felipe Albino dos Santos 👨‍🏫
SÃO PAULO 2024 🗓️

Resumo 📝
O projeto realizado pela equipe da Universidade Presbiteriana Mackenzie, Faculdade de Computação e Informática, tem como objetivo explorar e analisar os dados relacionados às locações via Airbnb na cidade do Rio de Janeiro e elaborar um modelo de avaliação de preços de aluguel. Utilizamos dados de locações de agosto de 2018 a maio de 2020, obtidos do site Kaggle. A análise exploratória inclui técnicas de visualização e um modelo analítico usando Python e bibliotecas como pandas, numpy, seaborn, matplotlib, plotly.express e sklearn. O projeto visa auxiliar pessoas na precificação de aluguéis com base nas características dos imóveis, fornecendo insights valiosos para proprietários, turistas e stakeholders.

Sumário 📚
Contexto do Estudo
Descrição da Origem
Descrição do Dataset
Objetivos e Metas
Definições de Modelo Analítico
5.1 Definição da Linguagem de Programação
5.2 Análise Exploratória da Base de Dados
5.3 Tratamento da Base de Dados
5.4 Bases Teóricas dos Métodos
5.5 Cálculo da Acurácia
Resultados
6.1 Modelagem Preditiva
6.2 Resultados dos Modelos
6.3 Insights Extraídos das Análises
6.4 Soluções
Conclusão
Cronograma
Referências
Contato dos Componentes do Grupo
Contexto do Estudo 🌍
Atualmente, a economia compartilhada tem se destacado como uma força transformadora em diversas áreas, e a indústria de hospedagem não é exceção. Plataformas como o Airbnb têm revolucionado a forma como as pessoas viajam, oferecendo uma ampla gama de opções de hospedagem em destinos ao redor do mundo. No contexto específico da cidade do Rio de Janeiro, um dos principais destinos turísticos do Brasil, o Airbnb desempenha um papel significativo no mercado de locações.

Descrição da Origem 📈
Os dados utilizados neste projeto foram obtidos a partir do conjunto de dados disponível na plataforma Kaggle, especificamente do conjunto intitulado "Airbnb Rio de Janeiro". Este conjunto de dados é acessível através do link.

Descrição do Dataset 📊
Este conjunto de dados é composto pela união de todos os arquivos "listings.csv.gz" provenientes dessa fonte específica, abrangendo informações detalhadas sobre as propriedades disponíveis para locação no Rio de Janeiro durante o período de agosto de 2018 a maio de 2020. Composto por 96 colunas, esse conjunto de dados oferece uma ampla variedade de informações sobre as listagens de propriedades, incluindo características físicas, preços de locação, disponibilidade de datas, comodidades oferecidas e avaliações dos hóspedes.

Objetivos e Metas 🎯
O projeto tem como objetivo coletar, limpar e analisar dados disponíveis publicamente do Airbnb utilizando técnicas de ciência de dados e visualização de dados para extrair insights significativos. Aplicaremos técnicas de aprendizagem de máquina e modelos estatísticos preditivos para elaborar um modelo que auxiliará na precificação dos valores cobrados de aluguel.

Definições de Modelo Analítico 🔍
Definição da Linguagem de Programação 🐍
A linguagem de programação escolhida para este projeto é Python, utilizando bibliotecas como pandas, pathlib, numpy, seaborn, matplotlib, plotly.express e sklearn.

Análise Exploratória da Base de Dados 📈
Utilizamos técnicas de visualização, como histogramas, gráficos de barras, heatmap de correlação e boxplots, para entender a distribuição dos dados, identificar padrões, relações entre variáveis e outliers.

Tratamento da Base de Dados 🛠️
As etapas de tratamento incluíram a correção do tipo de dado, identificação e remoção de dados nulos, eliminação de colunas com baixa significância estatística e tratamento de outliers.

Bases Teóricas dos Métodos 📘
Utilizamos métodos de ciência de dados, incluindo técnicas de visualização e modelagem preditiva. Os modelos selecionados foram: Regressão Linear, Extra-Trees, Random Forest e Gradient Boosting.

Cálculo da Acurácia 📏
A acurácia dos modelos foi avaliada utilizando métricas como o coeficiente de determinação (R²) e a raiz quadrática média (RSME).

Resultados 🏆
Modelagem Preditiva 🔮
Após o tratamento da base de dados, aplicamos quatro modelos de machine learning para prever os preços de aluguel das propriedades listadas no Airbnb no Rio de Janeiro: Regressão Linear, Extra-Trees, Random Forest e Gradient Boosting.

Resultados dos Modelos 📊
Os resultados obtidos foram:

Regressão Linear: R²: 32,99%, RSME: 214,85
Extra-Trees: R²: 97,44%, RSME: 42,00
Random Forest: R²: 97,20%, RSME: 41,89
Gradient Boosting: R²: 42,11%, RSME: 199,69
Insights Extraídos das Análises 💡
A maioria dos imóveis está na faixa de preços de 0 a 400 reais.
Proprietários com múltiplos imóveis são raros.
Imóveis com mais cômodos tendem a ser mais caros.
Áreas mais caras estão concentradas em regiões específicas da cidade.
Anfitriões superhost e com mais comodidades podem cobrar mais.
Soluções 🛠️
Implementar o modelo de previsão de preços para ajudar os proprietários a precificar seus imóveis de forma competitiva.
Explorar a sazonalidade e o impacto de eventos locais nos preços para aprimorar a precisão das previsões.
Identificar novas áreas com potencial de crescimento para investimento.
Implementar técnicas de dynamic pricing para ajustar o preço em tempo real com base na demanda e nas condições de mercado.
Conclusão 📌
As análises revelaram que o preço dos imóveis no Airbnb é fortemente influenciado por fatores como o número de quartos, localização, comodidades oferecidas e a reputação do anfitrião. O modelo ExtraTrees mostrou-se eficiente na previsão de preços dos imóveis do Airbnb no Rio de Janeiro, com R² de 97,44%.

Cronograma 📅
Atividade	Data
Criação do Grupo	24/02/2024
Definição do Tema	26/02 a 05/03
Criação do Documento da Entrega 1	06/03/2024
ENTREGA DA ETAPA 1	11/03/2024
Análise Exploratória de Dados	26/03 a 01/04
Criação do Documento da Entrega 2	03/04/2024
ENTREGA DA ETAPA 2	09/04/2024
Elaboração da Proposta Analítica	22/04 a 26/04
Criação do Documento da Entrega 3	28/04/2024
ENTREGA DA ETAPA 3	30/04/2024
Elaboração da Análise Preditiva	02/05 a 09/05
Criação do Documento da Entrega 4	11/05/2024
ENTREGA DA ETAPA 4	14/05/2024
Criação do Relatório Final	14/05 a 19/05
ENTREGA DO RELATÓRIO FINAL	20/05/2024
Referências 📚
Airbnb Open Data

Visualizações com Plotly

Machine Learning com Sklearn

Acesso ao vídeo da apresentação do projeto no Youtube

Contato dos Componentes do Grupo 📬
André Dalle Vedove Canassa - TIA: 10415817 - E-mail: andredalle@gmail.com
Kaymmi Antunes Costa Silva - TIA: 10415640 - E-mail: kaymmiacs@gmail.com
Matheus Gomes - TIA: 10408179 - E-mail: matheuscsgomes7@gmail.com
Valdo Alvim da Rocha Junior - TIA: 10414936 - E-mail: valdoarj@gmail.com
Este é o documento detalhado para o trabalho da equipe na análise de dados do Airbnb no Rio de Janeiro, com enfoque no desenvolvimento de um modelo preditivo de preços.
