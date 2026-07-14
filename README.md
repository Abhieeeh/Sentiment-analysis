# Sentiment Analysis

A machine learning project that classifies emotions in text using classic NLP techniques and supervised learning models.

## Objective

Develop and compare machine learning models to classify text samples into emotion categories: **anger**, **fear**, and **joy**.

## Dataset

The dataset (`Dataset/`) contains text comments labeled with an emotion:

| Column | Description |
|---|---|
| `Comment` | Raw text sample |
| `Emotion` | Label — anger, fear, or joy |

## Project Workflow

1. **Preprocessing**
   - Lowercasing, punctuation/number removal
   - Tokenization (NLTK)
   - Stopword removal
   - Lemmatization

2. **Feature Extraction**
   - TF-IDF vectorization to convert text into numerical features

3. **Model Development**
   - Naive Bayes (`MultinomialNB`)
   - Support Vector Machine (`LinearSVC`)

4. **Model Evaluation**
   - Accuracy, F1-score (macro)
   - Confusion matrix and classification report per model

## Repository Structure

```
Sentiment-analysis/
├── Dataset/          # Raw dataset
├── Notebook/
│   └── model.ipynb   # Full pipeline: preprocessing → features → models → evaluation
└── README.md
```

## Requirements

```
pandas
scikit-learn
nltk
matplotlib
seaborn
```

## How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/Abhieeeh/Sentiment-analysis.git
   ```
2. Open `Notebook/model.ipynb` in Jupyter or VS Code
3. Run all cells in order

## Results

| Model | Accuracy | F1-Score (macro) |
|---|---|---|
| Naive Bayes | — | — |
| SVM | — | — |

*(Fill in with your final scores after running the notebook.)*

## Author

[Abhieeeh](https://github.com/Abhieeeh)
