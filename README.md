# ChatGPT Review Sentiment Analysis 🤖

## ✍🏻 Proposal 
### Overview
This project aims to perform sentiment analysis on user reviews of ChatGPT to understand the overall user sentiment and extract meaningful insights. The dataset consists of four columns:
* Review id: Unique identifier for each review
* Review: User-generated review text
* Ratings: Numerical rating (e.g., 1-5)
* Review date: Date when the review was posted

### Objectives
Data Exploration & Visualization:
* Analyze distributions of ratings and review lengths.
* Identify trends in sentiment over time using review dates.
* Explore correlations between ratings and sentiment classification.

Sentiment Analysis:
* Use a pre-trained NLP model to classify sentiment.
* Compare sentiment classification with numerical ratings for validation.
* Identify common themes or topics in negative and positive reviews using word clouds or topic modeling (e.g., LDA).
* Detect potential biases or patterns in user feedback.

### Expected Outcomes
* A structured dataset with sentiment labels for each review.
* Insights on ChatGPT’s reception based on sentiment trends and user ratings.
* Visualizations showcasing review trends, sentiment distribution, and word clouds.
* A written summary of findings, including limitations and future improvements.



## 🎯 To Do List
### Week 4: Data Preparation & Cleaning
* Load and inspect the dataset (check for missing values and duplicates).
* Clean the text data (remove special characters, stopwords, etc).
* Convert ratings into categorical labels (e.g., Positive, Neutral, Negative) for sentiment comparison.
* Explore data by descriptive statistics.

### Week 5: Exploratory Data Analysis  & Visualization
* Distributions of features:
    * Ratings
    * Review lengths
* Word Clouds of the Reviews
    * Display a word cloud of the reviews
    * The most frequent words used in reviews for each rating category
* Temporal Trends
    * Ratings over time
    * Number of reviews over time
* Sentiment Analysis
    * Transform ratings into sentiment categories
    * Distribution of Sentiment 
    * Sentiment Distribution Over Time
* EDA Summary

### Week 6: Implementing Sentiment Analysis
* Transform the data for model training
  - Label encoding
  - TF-IDF Conversion
* Address imbalanced dataset (Issues from the previous part)
  - Oversample the Negative and Neutral Classes
  - Weighted classification
* Select and Train Sentiment Models
* Evaluate Model Performance

### Week 7:  Fine-tuning & Identify Biases
* Fine-tuning the best performance model
* Examine misclassified samples
* Compare predicted and actual sentiment categories

### Week 8: Finalizing Results & Report Draft
* Finish Limitation & Insights section
* Finalize all visualizations and insights.
* Get feedback and make adjustments.

### Week 9: Final Review 
* Review and refine the final report.
