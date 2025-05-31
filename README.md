# 🔍 Plagiarism Detector using Machine Learning

This project builds a machine learning model that detects plagiarism between two pieces of text using TF-IDF vectorization and similarity comparison.

## 📁 Dataset

- Used a dataset containing original and plagiarized text pairs
- Format: `source_text`, `plagiarized_text`, `label`

## 🔧 Features

- Preprocessing: Lowercasing, removing stopwords
- TF-IDF vectorization of both text columns
- Cosine similarity used as a feature
- Trained with Logistic Regression

## 📈 Output

- Model Accuracy, Precision, Recall, and F1-score
- Shows how well the model can classify plagiarized vs. original

## 🛠 Tools Used

- Python
- Jupyter Notebook
- Pandas, Sklearn, Numpy, Matplotlib

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
