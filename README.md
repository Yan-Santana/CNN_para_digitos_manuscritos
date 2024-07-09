### Code Description

In this project, I developed convolutional neural networks (CNNs) for handwritten digit classification using the LeNet and AlexNet models. The dataset used was MNIST (Modified National Institute of Standards and Technology).

#### Part 1: Model Creation, Training, and Testing
1. **Model Creation**: I implemented the LeNet and AlexNet architectures using deep learning frameworks. I configured the convolutional, pooling, and fully connected layers as specified for each model.
2. **Training**: I trained both models with the MNIST dataset. I used optimization techniques and appropriate loss functions to maximize the accuracy of digit classification.
3. **Testing**: I evaluated the performance of the trained models using the MNIST test set, measuring accuracy and other performance metrics.

#### Part 2: Feature Analysis of Images with Clustering
1. **Feature Extraction**: For each image in the training and test sets, I discarded the last classification layer of the networks and used the output values of the penultimate layer as a feature vector.
2. **Feature Visualization**: I used the TSNE technique with 3 components to visualize the extracted features from the images.
3. **Clustering Application**:
   - I applied the Kmeans and Hierarchical clustering algorithms to the extracted features to identify data groups.
   - I analyzed the relationship between the identified groups and the digit classes.

#### Part 3: Analysis of Confusing Examples
1. **Identification of Confusing Examples**: I analyzed the examples of a group that are very close to examples from different classes.
2. **Visualization of Confusing Examples**: I plotted the images of these confusing examples to visually identify the reasons why examples from different classes are close.
3. **Discussion of Results**: I discuss the results obtained with the clustering techniques, including justifications for the parameters used and the visual analysis of the confusing examples.

#### Conclusion
The project presents a comprehensive approach to the creation, training, and analysis of convolutional neural networks for handwritten digit classification, followed by an in-depth analysis of the extracted features and the groups identified with clustering techniques. The analyses and discussions provide valuable insights into the performance of the models and the nature of the data used.

### References
[0] [LeNet](https://en.wikipedia.org/wiki/LeNet) 

[1] [AlexNet](https://en.wikipedia.org/wiki/AlexNet)  

[2] MNIST ([Modified National Institute of Standards and Technology](https://en.wikipedia.org/wiki/MNIST_database))



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


### Descrição do Código

Neste trabalho, desenvolvi redes neurais convolucionais (CNNs) para a classificação de dígitos manuscritos utilizando os modelos LeNet e AlexNet. O dataset utilizado foi o MNIST (Modified National Institute of Standards and Technology).

#### Parte 1: Criação, Treinamento e Teste dos Modelos
1. **Criação dos Modelos**: Implementei as arquiteturas LeNet e AlexNet utilizando frameworks de deep learning. Configurei as camadas convolucionais, de pooling e totalmente conectadas conforme especificado para cada modelo.
2. **Treinamento**: Treinei ambos os modelos com o dataset MNIST. Utilizei técnicas de otimização e funções de perda adequadas para maximizar a precisão da classificação dos dígitos.
3. **Teste**: Avaliei o desempenho dos modelos treinados utilizando o conjunto de teste do MNIST, medindo a precisão e outras métricas de desempenho.

#### Parte 2: Análise das Features das Imagens com Clustering
1. **Extração das Features**: Para cada imagem do conjunto de treino e teste, descartei a última camada de classificação das redes e utilizei os valores de resposta da penúltima camada como um vetor de características.
2. **Visualização das Features**: Utilizei a técnica TSNE com 3 componentes para visualizar as features extraídas das imagens.
3. **Aplicação de Clustering**:
   - Apliquei os algoritmos de clustering Kmeans e Hierárquico nas features extraídas para identificar grupos de dados.
   - Analisei a relação entre os grupos identificados e as classes dos dígitos.

#### Parte 3: Análise dos Exemplos Confusos
1. **Identificação de Exemplos Confusos**: Analisei os exemplos de um grupo que estão muito próximos de exemplos de diferentes classes.
2. **Visualização dos Exemplos Confusos**: Plotei as imagens desses exemplos confusos para identificar visualmente as razões pelas quais exemplos de diferentes classes estão próximos.
3. **Discussão dos Resultados**: Discuto os resultados obtidos com as técnicas de clustering, incluindo as justificativas para os parâmetros utilizados e a análise visual dos exemplos confusos.

#### Conclusão
O trabalho apresenta uma abordagem completa para a criação, treinamento e análise de redes neurais convolucionais para a classificação de dígitos manuscritos, seguido por uma análise aprofundada das features extraídas e dos grupos identificados com técnicas de clustering. As análises e discussões fornecem insights valiosos sobre o desempenho dos modelos e a natureza dos dados utilizados.

### Referências
[0] [LeNet](https://en.wikipedia.org/wiki/LeNet) 

[1] [AlexNet](https://en.wikipedia.org/wiki/AlexNet)  

[2] MNIST ([Modified National Institute of Standards and Technology](https://pt.wikipedia.org/wiki/Banco_de_dados_MNIST))
