Este repositório contém um projeto completo de Análise de Dados focado em entender como os prazos de entrega e os atrasos logísticos impactam a satisfação dos clientes em um e-commerce. O projeto abrange desde o tratamento de dados brutos com Python até a visualização estratégica através de um dashboard interativo.

Objetivo do Projeto:

Investigar a jornada do consumidor cruzando dados de pedidos e avaliações de clientes para responder a perguntas de negócio cruciais:

Como o tempo de entrega afeta a nota dada pelo cliente?

Quais estados possuem os maiores índices de atraso?

Qual é a correlação estatística entre o cumprimento do prazo estimado e a reputação da marca?

Tecnologias e Ferramentas Utilizadas:

Linguagem: Python

Manipulação de Dados: Pandas, NumPy

Visualização de Dados (Python): Plotly, Matplotlib, Seaborn

Business Intelligence: Dashboard interativo

Ambiente de Desenvolvimento: Jupyter Notebook / Google Colab

Principais Funcionalidades e Etapas:

ETL e Limpeza de Dados: Cruzamento de tabelas (df_avaliacoes e df_pedidos) através de joins, tratamento de valores nulos e manipulação de datas (timestamps) para calcular o tempo real de entrega versus o tempo estimado.

Análise Estatística: Aplicação de métodos estatísticos para analisar a distribuição das notas de avaliação (utilizando boxplots e cálculos de dispersão) e a média de dias para a chegada dos produtos.

Dashboard Interativo com Mapa do Brasil: Criação de um painel de BI que permite filtrar os dados por estado (UF). O painel exibe:

Total de pedidos e total de atrasos.

Média de atraso e avaliação média por região.

Gráficos de barras e linhas comparando o volume de atrasos e as notas atribuídas em cada estado.

Uma tabela dinâmica com os comentários reais dos consumidores.

Agradecimentos:

Um agradecimento especial a Pedro Rodriguez pela colaboração e parceria fundamental durante o desenvolvimento deste projeto. A troca de ideias foi essencial para alcançar o nível de detalhe e qualidade nas análises e visualizações aqui apresentadas.


https://github.com/psilva0/Atraso_de_Pedidos/blob/main/dashcerto.mp4
