# README for Transfer Learning with VGG16

## English Version

### Overview
This project demonstrates how to use transfer learning with the VGG16 model to classify images of cats and non-cats. The code preprocesses the dataset, trains a model, and evaluates its performance.

### Requirements
- Python 3.11.11
- TensorFlow
- Keras
- OpenCV
- Matplotlib
- NumPy
- PIL

### Dataset
- The dataset should be organized in the following structure:
  ```
  dataset/
      ├── cat/
      ├── others/
      └── test/
  ```
- The `cat` folder contains images of cats, while the `others` folder contains images of non-cats.

### Steps
1. **Preprocessing Images**: The code checks for images with 2 channels and converts them to RGB or removes them if they are corrupted.
2. **Creating Datasets**: The dataset is split into training and validation sets.
3. **Model Creation**: A VGG16 model is loaded without the top layer, and custom layers are added for classification.
4. **Training**: The model is trained for 5 epochs.
5. **Saving the Model**: The trained model is saved for future use.
6. **Testing**: The model is tested with new images from the `test` folder.

### Usage
- To run the code, ensure that the dataset is correctly structured and execute the Jupyter Notebook.

---

## Versão em Português

### Visão Geral
Este projeto demonstra como usar transferência de aprendizado com o modelo VGG16 para classificar imagens de gatos e não-gatos. O código pré-processa o conjunto de dados, treina um modelo e avalia seu desempenho.

### Requisitos
- Python 3.11.11
- TensorFlow
- Keras
- OpenCV
- Matplotlib
- NumPy
- PIL

### Conjunto de Dados
- O conjunto de dados deve ser organizado na seguinte estrutura:
  ```
  dataset/
      ├── cat/
      ├── others/
      └── test/
  ```
- A pasta `cat` contém imagens de gatos, enquanto a pasta `others` contém imagens de não-gatos.

### Etapas
1. **Pré-processamento de Imagens**: O código verifica imagens com 2 canais e as converte para RGB ou as remove se estiverem corrompidas.
2. **Criação de Conjuntos de Dados**: O conjunto de dados é dividido em conjuntos de treinamento e validação.
3. **Criação do Modelo**: Um modelo VGG16 é carregado sem a camada superior, e camadas personalizadas são adicionadas para classificação.
4. **Treinamento**: O modelo é treinado por 5 épocas.
5. **Salvando o Modelo**: O modelo treinado é salvo para uso futuro.
6. **Testando**: O modelo é testado com novas imagens da pasta `test`.

### Uso
- Para executar o código, certifique-se de que o conjunto de dados esteja estruturado corretamente e execute o Jupyter Notebook.
