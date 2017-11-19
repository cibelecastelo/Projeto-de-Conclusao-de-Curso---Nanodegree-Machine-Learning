# Projeto-de-Conclusao-de-Curso---Nanodegree-Machine-Learning
Projeto de Conclusão de Curso

O projeto apresenta o problema e solução para a competição Porto Seguro’s Safe Driver Prediction que está disponível no site Kaggle¹, que é uma plataforma para modelagens preditivas e competições analíticas. Estas competições são colocadas por empresas e pesquisadores com o objetivo de produzir os melhores modelos para prever os dados. 
 
A competição escolhida é hospedada pela Porto Seguro: uma das melhores e maiores empresas de seguros no Brasil. Esta empresa oferece seguros para ramos diversos que incluem seguros para veículos, viagens, vida, aluguel, capitalização, eventos, etc. Além disso, possui mais de 14 mil funcionários e mais de 15 milhões de clientes em todo o brasil. 
 
Nada arruína a emoção de comprar um carro novinho mais rapidamente do que ver a sua nova conta do seguro. A picada é ainda mais dolorosa quando você sabe que você é um bom motorista. Não parece ser justo que você tenha que pagar tanto se você tem sido cauteloso na estrada por anos. 
 
A Porto Seguro, uma das maiores empresas de seguro de carro e casa, completamente concorda. As imprecisões nas previsões de sinistros da companhia de seguros de automóveis aumentam o custo do seguro para bons condutores e reduzem o preço para maus condutores. 
 
Nesta competição, você é desafiado a construir um modelo que prevê a probabilidade de um motorista acionar o seguro de veículo no próximo ano. A Porto Seguro tem utilizado Machine Learning nos últimos 20 anos, e eles estão olhando para a comunidade de Machine Learning da Kaggle para explorar novos métodos mais poderosos. Uma previsão mais precisa irá permitir que eles sigam adaptando seus preços com a esperança que a cobertura do seguro automóvel  seja mais acessível para mais motoristas. 
Necessário instalação da biblioteca missingno para rodar os gráficos de Porto_Seguro_AnaliseDeDados.ypynb
Executar no prompt de comando:
pip install missingno 

O repositório é composto pelos seguintes arquivos:

train_Porto_Seguro.csv: é o conjunto de dados de treinamento. Cada linha do conjunto de dados corresponde a um titular do seguro e a coluna “target” significa se um sinistro foi preenchido ou não. 

test_Porto_Seguro.csv: é o conjunto de teste.

Porto_Seguro_AnaliseDeDados - Exploração de Dados.

Porto_Seguro_DecisionTree - Implementação do modelo com utilização do algoritmo Decision Tree.

Porto_Seguro_RandomForest - Implementação do modelo com utilização do algoritmo
RandomForest.

