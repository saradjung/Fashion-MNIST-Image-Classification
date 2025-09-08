# Fashion-MNIST-Image-Classification and Model Comparision.

This project implements and compares multiple CNN models on Fashion-MNIST dataset (https://github.com/zalandoresearch/fashion-mnist) which contains 70,000 grayscale images of 10 fashion categories (shirts, shoes, bags, etc.)

The goal is to classify clothing item into their respective categories using PyTorch.

##Project Overview:
- Preprocess the Fashion-MNIST dataset  
- Train and evaluate multiple models:
  - **Model 0**: Simple Linear Classifier  
  - **Model 1**: Multi-Layer Perceptron (MLP)  
  - **Model 2**: Convolutional Neural Network (CNN)  
- Compare results using accuracy, confusion matrix  
- Visualize predictions on sample test images


##RESULTS:

##Dataset Samples:
![image.png](attachment:3278f5e6-5129-4d2a-b786-a656f9a00310:image.png)

###Model performance:
![image.png](attachment:4c9d890f-6644-4273-b3b0-a7f28dfb9ee8:image.png)

###Confusion Matrix: (best model)
<img width="662" height="650" alt="image" src="https://github.com/user-attachments/assets/d63f2593-22ec-4684-a110-d7a17ae57319" />

###SAmple Predictions:
<img width="907" height="735" alt="image" src="https://github.com/user-attachments/assets/0c856000-5bab-4436-b90d-a6b63597d794" />


##  How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/saradjung/Fashion-MNIST-Image-Classification.git
   cd Fashion-MNIST-Image-Classification
2. Install dependencies.
   ``bash
   pip install -r requirements.txt

3. Run the notebook:
   ``bash
   jupyter notebook classificationFashion.ipynb

