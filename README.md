Sentiment Analysis of Flipkart Reviews
📌 Overview
This project aims to analyze customer reviews from Flipkart and classify them into positive and negative sentiments using machine learning techniques. We preprocess the text, visualize key insights, and train a Decision Tree Classifier for sentiment prediction.

🛠️ Libraries Used
Pandas – Handling and processing datasets
Scikit-learn – Machine learning models, vectorization, and evaluation
Matplotlib & Seaborn – Data visualization
WordCloud – Generating word clouds for analysis
NLTK – Text preprocessing (stopwords, tokenization)
📂 Dataset
The dataset consists of Flipkart product reviews, including customer ratings. We convert these ratings into binary sentiment labels:

Positive (1) – Ratings of 5
Negative (0) – Ratings of 4 or below
🔍 Data Preprocessing
To prepare the text for analysis, we:

Convert text to lowercase
Remove punctuation
Tokenize words using NLTK
Remove stopwords
Apply TF-IDF vectorization
📊 Exploratory Data Analysis
Distribution of Ratings: A count plot shows how many reviews belong to each rating category.
WordCloud: Frequently used words in positive and negative reviews are visualized.
🏗️ Model Training & Evaluation
We use Decision Tree Classifier to classify reviews into sentiments.

Train-Test Split: 67% training, 33% testing
Accuracy Score: Achieved 92.47% on training data
Confusion Matrix: Evaluates model performance
📈 Results & Future Scope
The model performs well with high accuracy, but it can be improved by:

Trying Random Forest, Naïve Bayes, or SVM for better performance
Collecting larger datasets for better generalization
Fine-tuning TF-IDF parameters
