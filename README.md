# Hotel Sentiment Analysis using Machine Learning

This project explores hotel reviews to automatically determine if a review expresses a positive or negative sentiment. Leveraging machine learning and natural language processing (NLP), we aim to extract valuable insights from textual data and gain a deeper understanding of customer experiences.

## Project Overview

The project follows a structured approach to sentiment analysis, encompassing the following key stages:

### 1. Data Collection and Understanding
- **Dataset**: Hotel reviews with numerical ratings serve as the foundation for training machine learning models.

### 2. Data Cleaning and Preparation
- **Text Normalization**: Convert all text to lowercase, removing special symbols and HTML tags.
- **Stop Word Removal**: Eliminate common, non-informative words (e.g., "the," "a," "is").
- **Stemming and Lemmatization**: Reduce words to their root forms (e.g., "running" to "run").

### 3. Exploratory Data Analysis (EDA)
- **Rating Distribution**: Visualize the frequency of different ratings to understand customer satisfaction trends.
- **Common Word Analysis**: Identify frequent words in positive and negative reviews to reveal keywords.
- **Word Cloud Visualization**: Create word clouds to highlight prominent terms and themes.

### 4. Feature Engineering
- **TF-IDF Vectorization**: Convert text into numerical representations. TF-IDF calculates a weight for each word, emphasizing words that are frequent in specific reviews but less common overall.

### 5. Model Training and Evaluation
- **Decision Tree**: A tree-like model that makes decisions based on feature values.
- **Logistic Regression**: A linear model predicting sentiment probabilities.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem.
- **Random Forest**: An ensemble method combining multiple decision trees.
- **Support Vector Machine (SVM)**: A model that finds an optimal hyperplane for classification.

  Each model is trained on a portion of the data and evaluated on a separate portion. Performance metrics include accuracy, precision, recall, and F1-score.

### 6. Ensemble Learning
- **Voting Classifier**: Combines predictions from multiple models to potentially enhance accuracy.

### 7. Model Deployment and Application
- **Chosen Model**: Logistic Regression is selected for deployment. The model is saved to predict sentiment in new reviews without retraining.

## Benefits and Applications

- **Customer Feedback Analysis**: Automatically analyze large volumes of reviews to understand customer sentiment.
- **Reputation Management**: Quickly identify and address negative reviews to improve service quality.
- **Targeted Marketing**: Tailor marketing campaigns based on sentiment analysis to highlight positive features and address areas needing improvement.
- **Competitive Analysis**: Analyze competitor reviews to identify strengths and weaknesses.

By applying machine learning and NLP, this project offers a practical approach to understanding customer sentiment in the hospitality industry.
