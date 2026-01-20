# 👁️ MNIST: Digit Recognizer (Study Project)

[![en](https://img.shields.io/badge/lang-en-red.svg)](#-english-description)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](#-descrição-em-português)

---

<a name="english-description"></a>
## 🇺🇸 English Description

### Project Overview
This project focuses on the **"Hello World" of Computer Vision**: the MNIST dataset.
The goal is to build a Machine Learning model capable of correctly identifying handwritten digits (from 0 to 9) based on pixel intensity.

### 🔢 The Data
* **Source:** Scikit-Learn (`fetch_openml('mnist_784')`).
* **Volume:** 70,000 images.
* **Dimensions:** Each image is **28x28 pixels**.
* **Features:** The dataset is "flattened", meaning each image is represented as a single row of **784 numbers** (pixels), where 0 is white and 255 is black.

### 🛠️ Workflow (Current Status)
- [x] **Data Loading:** Fetching raw data from OpenML.
- [x] **Visualization:** Reshaping the 784-pixel array back into a 28x28 grid to see the actual image.
- [ ] **Preprocessing:** Normalization and Splitting (Train/Test).
- [ ] **Modeling:** Training a Classifier (SGD, Random Forest, or Neural Network).
- [ ] **Evaluation:** Checking Accuracy and Confusion Matrix.

### 💻 Technologies
* **Python 3.x**
* **Scikit-Learn:** Data fetching and Modeling.
* **Matplotlib:** Image visualization.
* **NumPy:** Matrix manipulation.

---

<a name="descrição-em-português"></a>
## 🇧🇷 Descrição em Português

### Visão Geral do Projeto
Este projeto foca no **"Hello World" da Visão Computacional**: o dataset MNIST.
O objetivo é construir um modelo de Machine Learning capaz de identificar corretamente dígitos escritos à mão (de 0 a 9) com base na intensidade dos pixels.

### 🔢 Os Dados
* **Fonte:** Scikit-Learn (`fetch_openml('mnist_784')`).
* **Volume:** 70.000 imagens.
* **Dimensões:** Cada imagem tem **28x28 pixels**.
* **Features:** O dataset é "achatado" (flattened), o que significa que cada imagem é representada como uma única linha de **784 números** (pixels), onde 0 é branco e 255 é preto.

### 🛠️ Fluxo de Trabalho (Status Atual)
- [x] **Carregamento:** Buscar dados brutos do OpenML.
- [x] **Visualização:** Reformatar o array de 784 pixels de volta para uma grade 28x28 para ver a imagem real.
- [ ] **Pré-processamento:** Normalização e Divisão (Treino/Teste).
- [ ] **Modelagem:** Treinar um Classificador (SGD, Random Forest ou Rede Neural).
- [ ] **Avaliação:** Checar Acurácia e Matriz de Confusão.

### 💻 Tecnologias
* **Python 3.x**
* **Scikit-Learn:** Busca de dados e Modelagem.
* **Matplotlib:** Visualização de imagens.
* **NumPy:** Manipulação de matrizes.

---

### 🚀 How to Run / Como Rodar

1. **Clone the repo / Clone o repositório:**
   ```bash
   git clone [https://github.com/smartielo/digit-recognizer.git](https://github.com/smartielo/digit-recognizer.git)
   ```
   

2. **Install requirements / Instale os requisitos:**
    ```bash
    pip install numpy matplotlib scikit-learn pandas
    ```
   
---
