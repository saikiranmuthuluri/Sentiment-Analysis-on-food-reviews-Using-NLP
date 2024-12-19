# Sentiment-analysis-on-food-reviews-using-NLP

**Project Overview :**

This project performs sentiment analysis on Amazon food reviews using Natural Language Processing (NLP) and Machine Learning techniques. The main objective is to classify customer reviews as Positive, Negative, or Neutral sentiments based on the review text. The project involves key tasks such as data preprocessing, sentiment labeling, model building, evaluation, and insightful visualizations.

**Project Workflow**

**1. Data Preprocessing**
   
Cleaning and processing the review text by removing unwanted characters, special symbols, stopwords, and extra spaces.
Tokenizing the text and converting it into a suitable format for model training.

Using TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction to transform text data into numerical vectors. 
                                                    
**2. Sentiment Labelling**

Reviews with Score ≥ 4 are labeled as Positive.
Reviews with Score = 3 are labeled as Neutral.
Reviews with Score ≤ 2 are labeled as Negative.
This labeling simplifies the multi-class classification problem.

**3. Model Building**

Built classification models to predict sentiment using the following machine learning algorithms:

Logistic Regression
Naive Bayes (Multinomial)
The data was split into training and testing sets using an 80/20 split.

**4. Model Evaluation**

The models were evaluated using standard performance metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

This ensured the selection of the best-performing model.

**5. Visualizations**

To gain insights from the dataset and model results, the following visualizations were created:

Distribution of Review Scores

Sentiment Proportions (Pie Chart)

Word Cloud for Positive Sentiments

Word Cloud for Negative Sentiments

Top 20 Most Frequent Words in Reviews

Helpfulness Ratio Distribution

Review Length Analysis

Top 10 Reviewers by Number of Reviews

Number of Reviews Per Year

Corelation heat map for numerical features

Top 10 Most Reviewed Products

Trend of Reviews Over Time (Line Chart)

Sentiments Across Scores (Stacked Bar Chart)

Scatter and Bubble Plots for various relationships

**Technologies Used**

**Programming Language**: Python

**Libraries:**

NLP: nltk, re (Regular Expressions), stopwords

**Data Analysis:** pandas, numpy

**Data Visualization:** matplotlib, seaborn

**Machine Learning:** sklearn (Logistic Regression, SVM, Naive Bayes, Random Forest)

**Result:**

The models were successfully built and evaluated, with Logistic Regression and SVM providing strong performance across all metrics. The results demonstrate the effectiveness of NLP techniques in analyzing textual data and extracting meaningful sentiments.
