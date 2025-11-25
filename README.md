# One-Piece-Character-Classifier
Trabalho Final da Matéria de Inteligência Computacional do Mestrado - PPGCC

## Descrição
Este projeto tem como objetivo a classificação de personagens do anime One Piece, utilizando técnicas abordadas na disciplina de Inteligência Computacional. O trabalho propõe um modelo treinado para reconhecer 18 personagens diferentes com base em suas características visuais.

Foi utilizado um conjunto de dados contendo aproximadamente 650 imagens por personagem, totalizando mais de 11 mil amostras. O desenvolvimento contou com bibliotecas de aprendizado de máquina e visão computacional, como TensorFlow, Scikit-learn e OpenCV.

Para fins de comparação, foram avaliados desde descritores de textura clássicos (GLCM e LBP) até técnicas avançadas baseadas em CNNs. Foram empregados os modelos pré-treinados ResNet50, MobileNetV3 e EfficientNetB0 para a extração de features. Esses dados alimentaram os classificadores k-NN, SVM, MLP, Random Forest e Decision Tree.

Visando a otimização do modelo, aplicou-se um Algoritmo Genético para a redução e seleção das melhores características. Por fim, o projeto foi concluído com a implementação de uma combinação de classificadores (Ensemble), utilizando as regras de Soma, Produto e Voto Majoritário para consolidar os resultados.

## Dataset
O dataset utilizado para treinar o modelo é composto por imagens de diversos personagens do anime One Piece. O dataset se chama "One Piece image classifier" feito por Ibrahim Serouis e pode ser encontrado no seguinte repositório do Kaggle: [One Piece image classifier](https://www.kaggle.com/datasets/ibrahimserouis99/one-piece-image-classifier).


## Tecnologias Utilizadas
- Python
- Jupyter Notebook
- TensorFlow
- Scikit-learn
- Scikit-image
- OpenCV
- NumPy
- Pandas
- Matplotlib

## Estrutura do Projeto
- `dataset/Data/Data`: Contém o dataset de imagens dos personagens.
- `notebooks/`: Contém os notebooks Jupyter utilizados para desenvolvimento e experimentação.
- `models/`: Contém os modelos treinados.
- `README.md`: Este arquivo de documentação do projeto.
