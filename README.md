# Analise-de-Sentimentos-e-Temas-em-Tweets sobre Política Brasileira durante as Eleições de 2018
O presente estudo explorou um conjunto de dados de tweets coletados durante as eleições brasileiras de 2018, com o objetivo de analisar o sentimento do público em relação aos candidatos e os principais temas de discussão. Através de técnicas de Processamento de Linguagem Natural (PLN), o estudo buscou identificar padrões de sentimento (positivo, negativo e neutro) nos tweets, bem como os tópicos mais relevantes abordados pelos usuários.

Conclusão
O resultado indica que, embora existam outras classes de sentimentos no dataset (Positivo e Negativo), o modelo não conseguiu aprender a diferenciá-las adequadamente. Isso pode ser causado por diversos fatores, como:

Desequilíbrio entre as classes, onde a maioria dos tweets é Neutro, fazendo com que o modelo tenda a classificar todas as entradas dessa forma.
Problemas no pré-processamento, que podem ter removido informações importantes necessárias para identificar sentimentos distintos.
Hiperparâmetros inadequados ou modelo subajustado, limitando a capacidade de aprendizado em detectar padrões de Positivo e Negativo.
Apesar da presença de múltiplas classes, o modelo está classificando todos os tweets como Neutro, resultando em métricas perfeitas apenas para essa classe, mas não refletindo a verdadeira performance do modelo.

Próximos Passos:
Em um próximo trabalho, vamos:

Corrigir o desequilíbrio de classes, aplicando técnicas como oversampling, undersampling ou ajustando pesos das classes no modelo.
Revisar o pipeline de pré-processamento, garantindo que as características relevantes para a análise de sentimentos sejam preservadas.
Aprimorar o modelo com técnicas mais robustas, como o ajuste de hiperparâmetros e o uso de modelos mais complexos (por exemplo, BERT).
Utilizar métricas adicionais como a matriz de confusão e análise individual das classes para garantir uma avaliação mais precisa.
Dessa forma, garantiremos que o modelo consiga capturar melhor as nuances dos diferentes sentimentos presentes no dataset. 🚀
