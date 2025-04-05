# 🤖 ML Resume Analyzer

The **ML Resume Analyzer** is a machine learning project that classifies resumes into job categories like Data Science, HR, Web Development, and more. It uses Natural Language Processing (NLP) to extract insights from resumes and then applies machine learning algorithms for classification.

---

## 📌 Features

- Clean and preprocess resume text using NLP techniques
- Extract important keywords and skills
- Classify resumes into job categories
- Visualize category distribution and skill frequency
- Easy to modify or expand for additional categories

---

## 🗃️ Dataset

The dataset used is in the Jupyter notebook `UpdatedResumeDataSet.ipynb`. It contains:

- `Resume`: Raw resume text
- `Category`: Job category label (e.g., Data Science, HR)

---

## 🧠 ML Workflow

1. **Data Cleaning**
   - Remove HTML tags, stop words, punctuation, numbers
   - Lemmatization

2. **Text Vectorization**
   - TF-IDF to convert text into numerical format

3. **Model Training**
   - Classification using models like Logistic Regression, SVM, or Random Forest

4. **Model Evaluation**
   - Accuracy, confusion matrix, classification report

---

## 📦 Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt
