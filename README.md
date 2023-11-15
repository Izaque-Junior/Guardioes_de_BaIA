# Guardioes_de_BaIA
O projeto tem por objetivo comparar aplicações de modelos de aprendizado de máquina para apontar caminhos de tratamento de dados, nomalização e aprendizado não supervisionado que possam ser mais eficientes para prever a expectativa de vida, com base no dataset da Organização Mundial da Saúde(OMS).

Na etapa de tratamento dos dados são aplicadas diferentes abordagens de tratar dados faltantes (NaN): remover as linhas com NaN, preenchê-las com a mediana, remover colunas com NaN. Também é realizado o processo de normalização em cada dataset resultante do procedimento anterior.

Posteriormente, a dimensionalidade desses dados serão reduzidas a fim de reduzir o custo computacional das operações que serão realizadas em seguida.

Para a aplicação dos modelos regressores, optou-se por otimizar os hiperparâmetros com base em um dos datasets, sabendo que para futuras comparações, seria ideal que o modelo fosse otimizado para cada dataset que será executado.

Finalmente, os modelos de **K-NN, árvore de decisão e floresta aleatória** são implementados para a previsão do target, sendo possível comparar os respectivos RMSEs.



Instruções: O código foi feito e executado no Jupyter Notebook, onde estarão maiores orientações ao usuário sobre a execução do código.

Período de desenvolvimento: Outubro e Novembro de 2023.

Autores: Alice Barbarino, Iasodara Lima, Izaque da Silva e Maria Eduarda Crist.

