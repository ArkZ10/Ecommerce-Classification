# NLP Text Classification for E-commerce Dataset

This repository contains code for a text classification project focused on an e-commerce dataset. The goal is to classify product descriptions into different categories using Natural Language Processing (NLP) techniques and machine learning models.

## Project Structure

- `Ecommerce_Model.ipynb`: Jupyter Notebook containing the entire workflow from data preprocessing to model training and evaluation.
- `Ecommerce_Model.py`: Python file containing the entire code for the model.
- `ecommerceDataset.csv`: Dataset used for training the model.
- `README.md`: This file, providing an overview of the project.

## Dataset

The dataset (`ecommerceDataset.csv`) consists of two columns:
- `category`: Product category.
- `text`: Product description.

### Data Preprocessing

- Data cleaning and preprocessing steps include handling missing values, text normalization (lowercasing), and removal of stopwords.

### Model Building

- The model architecture includes an Embedding layer followed by LSTM layers for sequence processing.
- Tokenization and padding are used to prepare text data for input into the model.

### Training and Evaluation

- The model is trained using `sparse_categorical_crossentropy` loss and `Adam` optimizer.
- Training progress and validation metrics (accuracy) are monitored.
- Early stopping is implemented to prevent overfitting.

## Instructions

To run the notebook (`Ecommerce_Model.ipynb`):
1. Clone the repository:
   ```bash
   git clone https://github.com/ArkZ10/NLP-Dicoding.git
   ```
2. Open the notebook in Jupyter or Google Colab and execute each cell sequentially.

## Usage

You can use the trained model to predict categories for new product descriptions. Example texts are provided in the notebook for testing predictions.

## Dependencies

Python 3
Libraries: pandas, numpy, tensorflow, keras, sklearn, nltk, seaborn, matplotlib

## Author

[Yeftha Joshua](https://github.com/ArkZ10)
