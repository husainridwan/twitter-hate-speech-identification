# HATE SPEECH IDENTIFICATION
### Problem Statement
The problem is to develop a machine learning model that can accurately classify tweets into one of three categories: based on the judgments of CrowdFlower users. This model will be trained using the provided dataset and then used to predict the class labels for new, unseen tweets.
hate speech
offensive language
neither.

### Objectives
##### 1. Data Understanding and Preprocessing:
Explore the dataset to understand its structure, features, and distributions.
Preprocess the text data by tokenizing the tweets, removing stop words, and applying any necessary text normalization techniques.
Encode any categorical features into a suitable format for machine learning algorithms.

##### 2. Feature Engineering:
Extract relevant features from the tweet content (e.g., bag-of-words representation, TF-IDF vectors).
Consider incorporating additional features provided in the dataset (e.g., count, hate_speech, offensive_language, neither) into the feature set.

##### 3. Model Training and Evaluation:
Split the dataset into training and testing sets.
Select appropriate machine learning models (e.g., classifiers such as logistic regression, decision trees, or more advanced models like neural networks) for multi-class classification.
Train the models on the training data and evaluate their performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score) on the testing data.
##### 4. Documentation and Reporting:
Document the entire process, including data preprocessing steps, feature engineering, model selection criteria, and evaluation results.
Prepare a report summarizing the findings, insights, and the performance of the trained model.
Present the results in a clear and understandable format, including visualizations if necessary.
##### Data Description
count = number of CrowdFlower users who coded each tweet (min is 3, sometimes more users coded a tweet when judgments were determined to be unreliable by CF).
hate_speech = number of CF users who judged the tweet to be hate speech.
offensive_language = number of CF users who judged the tweet to be offensive.
neither = number of CF users who judged the tweet to be neither offensive nor non-offensive.
class = class label for majority of CF users. 0 - hate speech 1 - offensive language 2 - neither
tweet = raw tweet text

##### Importing necessary libraries
%pip install -r requirements.txt
