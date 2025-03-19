# Sentiment Analysis of Flipkart Reviews 🛒📊  

This project focuses on analyzing customer reviews from Flipkart and classifying them as **positive** or **negative** using machine learning techniques. It involves **data preprocessing, visualization, and model training** using a Decision Tree Classifier.

---

## 📌 Project Overview  

The goal of this project is to classify customer reviews as **positive or negative** based on **text analysis** and **sentiment classification techniques**. The dataset consists of customer reviews along with their ratings.

---

## 🛠 Tech Stack  

- **Programming Language**: Python 🐍  
- **Libraries Used**: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn  
- **Feature Engineering**: TF-IDF Vectorization  
- **Model Used**: Decision Tree Classifier 🌳  

---

## 📂 Dataset  

- **Dataset Name**: Flipkart Reviews Dataset  
- **Features Include**: Customer reviews, Ratings (1–5)  
- **Target Variable**:  
  - ✅ **Positive (1)** → Rating of **5**  
  - ❌ **Negative (0)** → Ratings **4 or below**  

---

## 🔍 Data Preprocessing  

To clean and prepare the text data:  

- ✅ Convert text to **lowercase**  
- ✅ Remove **punctuation and special characters**  
- ✅ Tokenize words using **NLTK**  
- ✅ Remove **stopwords** (e.g., "the", "is", "and")  
- ✅ Convert text into **numerical features** using **TF-IDF Vectorization**  

---

## 📊 Exploratory Data Analysis (EDA)  

We use visualizations to understand the dataset:  

- 📌 **Count Plot**: Displays the distribution of ratings in the dataset  
- 📌 **WordCloud**: Highlights the most frequent words in positive and negative reviews  

---

## 🏆 Model Training & Evaluation  

- 🏋️ We train a **Decision Tree Classifier** for sentiment prediction  
- 📌 **Train-Test Split**: 67% training, 33% testing  
- 📌 **Accuracy Score**: **92.47%** on training data  
- 📌 **Confusion Matrix**: Helps evaluate true positives and false negatives  

---

## 📈 Results & Future Improvements  

- 🔹 The **Decision Tree Classifier performs well**, achieving **high accuracy**  
- 🔹 Future improvements:  
  - ✅ Experiment with **Random Forest, Naïve Bayes, or SVM**  
  - ✅ Collect a **larger dataset** for better model generalization  
  - ✅ Fine-tune **TF-IDF parameters** to improve feature extraction  

---

## 🚀 How to Run  

1️⃣ **Clone the repository**:  
```sh
git clone https://github.com/your-repo.git
