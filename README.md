IA
==
Aula
Guião

1 Outubro.
O objectivo final deste trabalho passa por explorar um conjunto de dados (dataset) de elevadas cardinalidade e dimensionalidade, e construir e analisar o desempenho de vários classificadores que possam predizer qual a classe a que uma nova instância pertence. Paralelamente a escolha das características usadas na identificação e a extração de novo conhecimento sobre os relacionamentos entre elas também será valorizado. A meio do semestre cada grupo deve apresentar um relatório com a descrição do andamento dos trabalhos e do estudo já efectuado. No final do semestre cada grupo deve elaborar um relatório técnico com a descrição das experiências realizadas e resultados obtidos.

Construa um programa em C que aceite o nome de um ficheiro de texto contendo o dataset em formato CSV. Implemente funções para ler os dados para uma matriz numérica (de preferência dinâmica) e listar o conteúdo da matriz no ecran.Acrescente as funções necessárias para calcular a média e a variância de cada um dos atributos do dataset. Guarde estes valores num novo ficheiro.

7 Outubro
Modifique o programa anterior acrescentando as funções necessárias para dividir de forma aleatória o dataset normalizado em dois conjuntos: um de treino (com 70% das instâncias do conjunto de dados) e outro de teste (com os restantes 30%).
Apresente as frequências relativas de cada classe no dataset original e nos outros dois agora criados.

14 Outubro
Modifique o programa anterior acrescentando uma função que faça a normalização estatística do conjunto de treino e o guarde num novo ficheiro (apenas com dados normalizados) no formato CSV.

21 Outubro
Para o conjunto de treino, calcule a média e a variância de cada um dos atributos dentro de cada uma das classes que pretende identificar. Implemente um classificador Naïve-Bayes. Execute várias vezes o classificador, com diferentes conjuntos de treino, e calcule a taxa média de acertos.

28 Outubro
Implemente um classificador K-NN. Execute várias vezes o classificador, com diferentes conjuntos de treino, e calcule a taxa média de acertos.

4 Nov
Faça os ajustes necessários à sua aplicação para poder implementar um esquema de validação cruzada (10 conjuntos) estratificada. Apresente a matriz de confusão para os seus classificadores e calcule os valores de Taxa de Erro, Exatidão (accuracy), Taxa de Positivos (precision), Sensibilidade (Recall) e F-measure.

11 Nov
Instale o software de análise de dados WEKA. Converta o dataset com que está a trabalhar para o formato ARFF. Compare os resultados do classificador Naïve-Bayes e K-NN disponibilizados pelo WEKA com os obtidos pelas suas próprias ferramentas.

18 Nov
Avaliação. Cada grupo deve apresentar os dois melhores classificadores que conseguiu desenvolver. A classificação dependerá da correção e clareza do código e também da qualidade dos classificadores quando confrontados com um ficheiro de dados para teste disponibilizado pelo docente. Qualquer fraude implica reprovação.
