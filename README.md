# 📰 Fake News Detection using NLP

A Machine Learning and Natural Language Processing project that detects whether a news article is **Real or Fake** based on its textual content.

The project uses **NLP preprocessing, TF-IDF feature extraction, and machine learning classification algorithms** to analyze and classify news articles.

## 🚀 Project Overview

Fake news can spread rapidly through digital platforms and make it difficult for users to distinguish reliable information from misleading content.

This project builds an automated **Fake News Detection system** using Natural Language Processing and Machine Learning.

### Workflow

```text
News Dataset
     ↓
Data Cleaning
     ↓
NLP Preprocessing
     ↓
TF-IDF Vectorization
     ↓
Machine Learning Models
     ↓
Model Evaluation
     ↓
Fake / Real Prediction
```

## 🧠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Natural Language Processing (NLP)
* Machine Learning

## 🔍 NLP Techniques

The project performs the following text-processing steps:

* Lowercase conversion
* URL and punctuation removal
* Tokenization
* Stopword removal
* Lemmatization
* TF-IDF vectorization
* Unigram and Bigram feature extraction

## 🤖 Machine Learning Models

Multiple classification algorithms are evaluated:

* Logistic Regression
* Multinomial Naive Bayes
* Linear Support Vector Machine (SVM)

The models are compared using standard classification metrics, and the best-performing model is selected for final predictions.

## 📊 Model Evaluation

The project evaluates the models using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC

Visualizations are also included to understand the dataset and model performance.

## 🎯 Prediction

The final system can take custom news text and predict:

```text
REAL
or
FAKE
```

along with a confidence score for the prediction.

> **Note:** This project is a text-based classification system. It predicts patterns associated with fake or real news based on the training data; it does not independently verify the factual truth of a claim.

## 📁 Project Structure

```text
DLMA/
│
├── Fake_News_Detection.ipynb
├── README.md
└── dataset/
    └── news.csv
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/sanjanaa6/DLMA.git
cd DLMA
```

Install the required libraries:

```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
Fake_News_Detection.ipynb
```

## 📌 Key Learning Outcomes

Through this project, the following concepts are demonstrated:

* Natural Language Processing
* Text preprocessing
* Feature extraction using TF-IDF
* Supervised Machine Learning
* Binary text classification
* Model comparison
* Performance evaluation
* Error analysis

## 👩‍💻 Author

**Sanjana**

GitHub: [@sanjanaa6](https://github.com/sanjanaa6)

---

⭐ If you find this project useful, consider giving the repository a star!
