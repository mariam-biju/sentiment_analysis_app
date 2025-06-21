# 🧠 Sentiment Analysis App

This project analyzes the **sentiment of movie reviews** using Natural Language Processing (NLP) and machine learning.  
It classifies text as either **positive** or **negative**, based on real user reviews.

---

## 🔍 Project Overview

- ✅ Text cleaning and preprocessing  
- ✅ TF-IDF vectorization  
- ✅ Multiple model training (Logistic Regression, Naive Bayes, SVM)  
- ✅ Confusion matrix and word importance visualization  
- ✅ Interactive sentiment prediction with custom input  

---

## 📁 Notebooks Included

| Notebook                              | Description                                         |
|--------------------------------------|-----------------------------------------------------|
| `01_data_loading.ipynb`              | Load and explore raw IMDB review data              |
| `02_preprocessing.ipynb`             | Clean, lowercase, remove stopwords, etc.           |
| `03_model_training.ipynb`            | Train Logistic Regression, Naive Bayes, and SVM    |
| `04_evaluation_visualization.ipynb`  | Accuracy, confusion matrix, top words              |
| `05_interactive_demo.ipynb`          | Enter your own review and get prediction           |

---

## 🔤 Dataset Used

- **Source**: UCI / Kaggle IMDB Sentiment Dataset  
- **Classes**: `positive`, `negative`  
- **Samples**: ~50,000 movie reviews  

---

## 🧪 Models Trained

- 📌 Logistic Regression  
- 📌 Multinomial Naive Bayes  
- 📌 Support Vector Machine (Linear SVM)  

**TF-IDF Vectorizer** with 5,000 max features was used for feature extraction.

---

## 📊 Evaluation

- Confusion matrix shows model accuracy and misclassifications  
- Accuracy ~ **85% to 91%** across models  
- Top predictive words identified for both classes (positive & negative)

---

## 🖥️ Try It Yourself

Run this inside `05_interactive_demo.ipynb`:

```python
Review: "I loved this movie, it was absolutely fantastic!"
Output: ✅ Positive Sentiment

