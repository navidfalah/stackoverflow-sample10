# 🚀 Multi-Label Classification of Stack Overflow Tags with BERT

## 📌 Overview
This project utilizes a BERT-based transformer model to classify Stack Overflow questions into multiple relevant tags. The dataset consists of questions and their associated tags, and the goal is to predict the correct set of tags for each question.

## 📊 Dataset
- `Questions.csv` 📝: Contains Stack Overflow questions with metadata.
- `Tags.csv` 🔖: Contains tags assigned to each question.

## ⚙️ Installation
```bash
pip install transformers torch pandas numpy matplotlib scikit-learn iterative-stratification datasets
```

## 🔄 Workflow
1. **Data Preprocessing** 🛠️
   - Load and clean text data.
   - Merge questions with their associated tags.
   - Convert tags into a multi-label binary matrix.
2. **Model Setup** 🤖
   - Fine-tune a BERT-based model for multi-label classification.
   - Tokenize text data.
3. **Training & Evaluation** 📈
   - Train using stratified data splits.
   - Evaluate using metrics like precision, recall, and F1-score.

## ▶️ Usage
Run the Jupyter Notebook step by step to train and evaluate the model.

## 🎯 Results
The model predicts relevant tags for each Stack Overflow question. Enhancements can be made with hyperparameter tuning, data augmentation, and additional feature engineering.

## 👤 Author
Developed by Navid Falah.

