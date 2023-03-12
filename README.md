# aprendizado-maquina

## Objetivo

Uma análise em Python da performance de diferentes algoritmos em relação à tarefa de identificar a edibilidade de cogumelos, utilizando da metodologia de K-Fold Cross Validation para segmentar os dados. A identificação deve ser feita a partir de uma base de dados contendo características sobre os cogumelos (cor do chapeu, forma do chapeu, cor do caule, etc) e deve dizer se o cogumelo é comestível ou se é venenoso. 

## Metodologia

Escolhemos os algoritmos KNN, Floresta Aleatória, e regressão linear. O objetivo desta análise é verificar a performance dos diferentes algoritmos, usando das métricas de acurácia, sensibilçidade, precisão e F1-measure para analisar tais performances.

A partir do banco de dados mushroom.csv, separamos os dados em cinco folds, garantindo que cada fold tenha um número o mais balanceado de instancias comestíveis e venenosas. Após isso, para cada algoritmo, verificamos diversas vezes a performance dos modelos. Isto é feito designando um dos folds como sendo para teste, treinando o modelo nos outros folds, e depois usando o fold de teste para verificar a performance do algoritmo.

## Resultados e análise

Os resultados e análise dos resultados pode ser verificado no PDF disponbilizado no repositório.

## Instruções de uso

O código fonte encontra-se presente no notebook "AM - Mushroom.ipynb".

Para executá-lo, basta abrir o arquivo com Jupyter Notebooks e executar as células em sequência.

Assegure-se de ter uma instalação de versão o menos 3.0 de Python, e os pacotes sklearn, pandas e seaborn instalados.
