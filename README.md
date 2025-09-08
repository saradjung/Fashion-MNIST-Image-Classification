# Fashion-MNIST-Image-Classification and Model Comparision.

This project implements and compares multiple CNN models on Fashion-MNIST dataset (https://github.com/zalandoresearch/fashion-mnist) which contains 70,000 grayscale images of 10 fashion categories (shirts, shoes, bags, etc.)

The goal is to classify clothing item into their respective categories using PyTorch.

## Project Overview:
- Preprocess the Fashion-MNIST dataset  
- Train and evaluate multiple models:
  - **Model 0**: Simple Linear Classifier  
  - **Model 1**: Multi-Layer Perceptron (MLP)  
  - **Model 2**: Convolutional Neural Network (CNN)  
- Compare results using accuracy, confusion matrix  
- Visualize predictions on sample test images


## RESULTS:

## Dataset Samples:
<img width="860" height="692" alt="image" src="https://github.com/user-attachments/assets/6579153e-7024-4835-99de-9d22de8a946f" />


### Model performance:
<img width="677" height="170" alt="image" src="https://github.com/user-attachments/assets/e4b258a2-963a-46a8-8504-acd8282afbcb" />


### Confusion Matrix: (best model)
<img width="662" height="650" alt="image" src="https://github.com/user-attachments/assets/d63f2593-22ec-4684-a110-d7a17ae57319" />

### Sample Predictions:
<img width="907" height="735" alt="image" src="https://github.com/user-attachments/assets/0c856000-5bab-4436-b90d-a6b63597d794" />


##  How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/saradjung/Fashion-MNIST-Image-Classification.git
   cd Fashion-MNIST-Image-Classification
2. Install dependencies.
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook classificationFashion.ipynb

