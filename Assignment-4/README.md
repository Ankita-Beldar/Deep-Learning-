---

# NLP Preprocessing and Text Classification

## 📌 Objective

The objective of this project is to implement Natural Language Processing (NLP) preprocessing techniques and build a text classification model using machine learning algorithms.

---

## 📊 Dataset

This project uses the **AG News Dataset**, which contains news articles categorized into four classes:

* 🌍 World
* ⚽ Sports
* 💼 Business
* 💻 Sci/Tech

The dataset consists of:

* 120,000 training samples
* 7,600 testing samples

Each record contains:

* Title
* Description

---

## ⚙️ NLP Preprocessing Techniques

The following preprocessing steps were applied to clean and prepare the text data:

* 🔹 Tokenization (splitting text into words)
* 🔹 Lowercasing (converting text to lowercase)
* 🔹 Removal of special characters
* 🔹 Stopword removal (removing common words like *is, the, and*)
* 🔹 Lemmatization (converting words to their base form)

---

## 🔢 Text Vectorization

Text data was converted into numerical format using:

* ✔ TF-IDF (Term Frequency-Inverse Document Frequency)
* ✔ CountVectorizer

These techniques help machine learning models understand textual data.

---

## 🤖 Machine Learning Model

A **Multinomial Naive Bayes** classifier was used for text classification.

### Steps:

* Train the model using training data
* Predict categories on test data

---

## 📈 Model Evaluation

The model was evaluated using the following metrics:

* ✔ Accuracy
* ✔ Precision
* ✔ Recall
* ✔ F1-score
* ✔ Confusion Matrix

### 🔥 Result:

* Achieved accuracy of approximately **89%**

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib & Seaborn

---

## 📌 Conclusion

This project demonstrates how NLP techniques can be used to preprocess text data and build an effective machine learning model for classification tasks. The model achieved good accuracy and can be further improved using advanced techniques.

---

