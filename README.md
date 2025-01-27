# Chatgpt Review Sentiment Analysis 🤖

## ✍🏻 Proposal
### Overview 

This project aims to perform sentiment analysis on user reviews of ChatGPT to understand the overall user sentiment and extract meaningful insights. The dataset consists of four columns:
* Review id: Unique identifier for each review
* Review: User-generated review text
* Ratings: Numerical rating (e.g., 1-5)
* Review date: Date when the review was posted

### Objectives
* Data Exploration & Visualization:
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
* Create visualizations for:
    * Distribution of ratings and review lengths.
    * Trends in ratings over time.
    * Common words in high-rating vs. low-rating reviews using word clouds.
* Analyze correlations between ratings and sentiment classification.
* Identify potential biases in ratings and sentiment distribution.
* Summarize EDA findings.

### Week 6: Implementing Sentiment Analysis
* Choose a pre-trained NLP model or libraries (e.g. spaCy and transformer models).
* Implement initial sentiment classification on review text.
* Compare sentiment predictions with numerical ratings for validation.
* Evaluate model performance (accuracy, F1-score).
* Interpret results and extract key insights.

### Week 7:  Fine-tuning & Identify Biases
* Fine-tune or optimize sentiment classification (if needed, explore another model).
* Detect potential patterns or biases in user feedback (e.g. OpenAI API and prompt engineering).
* Interpret results and extract key insights.

### Week 8: Finalizing Results & Report Draft
* Finalize all visualizations and insights.
* Draft report sections.
* Get feedback and make adjustments.

### Week 9: Final Review 
* Review and refine the final report.
