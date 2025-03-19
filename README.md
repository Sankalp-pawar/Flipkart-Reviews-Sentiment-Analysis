Sentiment Analysis of Flipkart Reviews
📌 Overview
This project focuses on analyzing customer reviews from Flipkart and classifying them as positive or negative using machine learning techniques. It involves data preprocessing, visualization, and model training using a Decision Tree Classifier.

🛠️ Libraries Used
Pandas – Data manipulation and handling
Scikit-learn – Machine learning models, accuracy evaluation, and TF-IDF vectorization
Matplotlib & Seaborn – Data visualization
WordCloud – Generating word clouds to highlight important words
NLTK – Natural language processing (stopwords, tokenization)
📂 Dataset

The dataset consists of Flipkart customer reviews along with ratings. To make sentiment classification easier, ratings are categorized as follows:
✅ Positive (1) – Rating of 5
❌ Negative (0) – Ratings of 4 or below

🔍 Data Preprocessing Steps

To clean and prepare the text data:
✔ Convert text to lowercase
✔ Remove punctuation and special characters
✔ Tokenize words using NLTK
✔ Remove stopwords (e.g., "the", "is", "and")
✔ Convert text into numerical features using TF-IDF Vectorization

📊 Exploratory Data Analysis (EDA)

We use visualizations to understand data distribution:
📌 Count Plot: Displays the distribution of ratings in the dataset
📌 WordCloud: Highlights the most frequent words in positive and negative reviews

🏗️ Model Training & Evaluation

We use Decision Tree Classifier to predict sentiments.
📌 Train-Test Split: 67% training, 33% testing
📌 Accuracy Score: 92.47% on training data
📌 Confusion Matrix: Helps in evaluating true positives and false negatives

📈 Results & Future Improvements

🔹 The Decision Tree Classifier performs well, achieving high accuracy
🔹 Further improvements can be made by:
✔ Experimenting with Random Forest, Naïve Bayes, or SVM
✔ Collecting a larger dataset for better model generalization
✔ Fine-tuning TF-IDF parameters to capture important words better
