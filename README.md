# Heart-disease-Prediction-NN.
This project aims to develop a neural network model for predicting heart disease using the Cleveland Heart Disease dataset. The model demonstrates a 90% accuracy in classifying heart disease cases and explores advanced techniques like factor analysis for feature reduction.

### Project Overview
The goal of this project is to predict the presence of heart disease in patients using a neural network model. The focus is on leveraging machine learning techniques, particularly neural networks, to classify heart disease cases based on various patient attributes, contributing to better healthcare diagnostics. To enhance the dataset, Principal Component Analysis (PCA), a dimension reduction technique, is applied, improving the model's performance and reducing complexity.

### Dataset
The Cleveland Heart Disease dataset consists of 303 patient records with 14 features, including:
- **Age**: The patient's age
- **Sex**: Gender (1 = male, 0 = female)
- **Cholesterol**: Serum cholesterol levels
- **Target**: The presence (1) or absence (0) of heart disease

The dataset was preprocessed by handling missing values, scaling the features, and removing outliers. PCA was applied to reduce the dimensionality of the data, ensuring the model processes more compact and informative features.

### Models Used
The model is built using Keras, featuring:
- **Input Layer**: 4 neurons
- **Hidden Layers**: Three layers with 5, 5, and 3 neurons, all using ReLU activation
- **Output Layer**: 1 neuron with Sigmoid activation
- **Optimizer**: Adam optimizer
- **Loss Function**: Binary Crossentropy

Through the application of PCA, the dataset's dimensions were reduced, enhancing the neural network's efficiency. Various experiments with different architectures and activation functions (like LeakyReLU and Tanh) were explored to optimize performance. The model achieved an accuracy of 90.16%.
