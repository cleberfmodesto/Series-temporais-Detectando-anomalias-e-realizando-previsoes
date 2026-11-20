# Séries temporais: Detectando anomalias e realizando previsões

A rede de restaurantes está enfrentando dificuldades no planejamento do negócio. Em alguns dias, a quantidade de clientes é muito baixa, resultando em pessoas atendentes ociosas. Em outros dias, a quantidade de clientes é muito alta, tornando insuficiente a quantidade de pessoas atendentes para atender toda a demanda.

Como cientistas de dados, podemos ajudar essa rede de restaurantes a planejar melhor o negócio e alocar a quantidade ideal de pessoas atendentes para a quantidade de clientes ao longo dos dias.

Essa rede de restaurantes coleta informações sobre a quantidade de clientes que visitam os restaurantes ao longo dos dias e armazena essas informações em um arquivo CSV.

Vamos utilizar o Notebook Jupyter e a linguagem Python para analisar esses dados e extrair insights para ajudar essa rede de restaurantes a planejar melhor o negócio.

Conclusão
Conseguimos fazer diversas análises, a previsão e a detecção de anomalias para cada um dos restaurantes. Inclusive, construímos uma tabela de previsão que vai ser utilizada para as próximas duas semanas para que a rede de restaurantes consiga fazer um planejamento melhor do seu antendimento.

Fizemos uma previsão para os próximos 14 dias porque, se fizéssemos para um período muito extenso, como para o próximo mês ou próximos dois meses, começaríamos a ter uma perda de desempenho.

Isso porque essa previsão é feita com base em toda a série temporal, mas o padrão dos dados é modificado ao longo do tempo.

Então, o ideal é: após fazer essa previsão, continuar coletando os dados reais da quantidade de clientes e, depois das duas semanas, construir um novo modelo de previsão e enviar esses relatórios para a rede de restaurantes poder atualizar os dados.

O que aprendemos?
Ao longo das aulas, tivemos o desafio de aprimorar o gerenciamento de uma rede de restaurantes. Conseguimos analisar os dados e encontrar pontos de melhoria para a alocação de garçons no atendimento aos clientes. Sem dúvida, essa habilidade é muito útil no mercado de trabalho em tarefas que envolvam séries temporais.

Utilizamos a visualização de dados para entender os mesmos, empregando técnicas de extração de médias móveis para suavizar a série temporal. Também buscamos entender a sazonalidade da série temporal, utilizando autocorrelação. Comprovamos os resultados com a decomposição das séries temporais.

Detectamos anomalias a partir de duas estratégias diferentes: através dos valores distantes da média e também a partir dos resíduos dessa decomposição da série temporal.

Ao final, construímos um projeto para prever a quantidade de clientes que visitarão os restaurantes nos próximos 14 dias, o que é bastante útil no momento de realizar o planejamento desses estabelecimentos.

Com tudo que foi apresentado durante o curso, você já é capaz de criar projetos de análise de séries temporais, realizando previsões com modelos de Machine Learning (Aprendizado de Máquina) e também fazendo detecção de anomalias.
