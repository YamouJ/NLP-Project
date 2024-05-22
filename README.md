# Analyzing Movie Reviews 
In an effort to analyze a dataset of movie reviews, I employed various text analytical methods. I defined eight distinct functions for feature extraction, divided the dataset into training and test sets, and evaluated each machine learning model's performance based on accuracy, precision, recall, and F1 scores to identify the best performer for classification and prediction.

### Table of Contents

1. - [Introduction](#analyzing-movie-reviews)
2. - [Dataset Description](#dataset-description)
3. - [Research Question](#research-question)
4. - [Text Preprocessing](#text-preprocessing)
5. - [Text Analytic Methods](#text-analytic-methods)
6. - [Results and Findings](#results-and-findings)
7. - [Practical Implications](#practical-implications)
8. - [Conclusion](#conclusion)
     
## Project Overview 
---
### Dataset Description: 
The dataset utilized in this analysis is the Movie Reviews Corpora from the NLTK Corpus, comprising 2,000 movie reviews sourced from the internet movie database. Each review, stored as a text file, is labeled with either positive or negative sentiment. Understanding the textual attributes that influence sentiment classification can provide valuable insights into customer preferences, opinions, and perceptions regarding movies. This information can be utilized by movie studios, distributors, and streaming platforms to better understand audience preferences and tailor their content accordingly, thus enhancing customer insights.

### Research Question: 
Our inquiry aims to identify textual features influencing the classification of movie reviews into positive or negative sentiment categories. This investigation is pivotal for understanding the linguistic nuances distinguishing positive and negative expressions in reviews, thereby shedding light on how emotions and sentiments are conveyed through language. Enhanced Marketing Strategies: Movie studios and distributors can leverage sentiment analysis of reviews to devise more effective marketing strategies. By identifying the key positive attributes that resonate with audiences, they can highlight these aspects in promotional materials to attract more viewers.

### Text Preprocessing: 
To ensure data accuracy and quality, comprehensive preprocessing steps were executed. These included converting all text to lowercase for consistency and reduced vocabulary size, removing non-alphanumeric characters, punctuation marks, numbers, and symbols. Additionally, common but semantically insignificant words such as "the", "is", "and", etc., were eliminated. Insights from sentiment analysis can inform decision-making processes related to content creation and curation. Movie producers can identify successful themes, genres, or storytelling techniques that elicit positive reactions from audiences and incorporate them into future productions.

### Text Analytic Methods: 
Various text analytic methods were employed, encompassing the extraction of the 2000 Most Frequent Words, 2000 most frequent bigrams, 2000 Most Frequent Trigrams, 1000 Most Frequent Words in Positive Reviews not present in Negative Reviews, and vice versa. Moreover, Unique Words Contained in the Positive/Negative Lexicon Database, Frequency of Emotional Language in Positive and Negative Reviews, Topic Models, and TF-IDF were analyzed. The dataset was divided into training and test sets, with 70% used for training and the remaining 30% for testing. A range of machine learning models including Naive Bayes (Gaussian and Bernoulli), Logistic Regression, Nearest Neighbors, Random Forest, Decision Tree, Support Vector Machine (with kernels: Linear, Polynomial, Radial Basis Function (RBF), and Sigmoid), Neural Net, and AdaBoost were evaluated. For ease of access, a model list containing the models and their functions was created. Performance evaluation of each model was conducted using a classification report, assessing accuracy, precision, recall, and F1-score.

### Results and Findings

In analyzing model performance, I aimed to identify the most accurate predictor among various models. Comparing the results, Naive Bayes and Support Vector Machines emerged as consistently superior in accuracy. These findings emphasize the reliability of these models across diverse features, aiding in informed model selection and potential refinements


### Practical implications:

- #### Improved Customer Insights:

  - Gain deeper understanding of audience preferences and perceptions.
  - Tailor content to meet audience demands more effectively.
  -  Enhanced Content Creation and Curation:

-  #### Identify successful themes and storytelling techniques from customer feedback for future productions.
  -  Incorporate positive attributes into new content to resonate with audiences.
  -  Strategic Marketing Development:

- #### Highlight key positive attributes in promotional materials to attract viewers.
  -  Address negative attributes in marketing campaigns to mitigate potential backlash.
  -  Market Research and Competitor Analysis:

- #### Utilize tools to identify emerging trends in the industry.
  -  Assess competitive positioning and benchmark performance against industry standards.
  -  Enhanced User Experience on Streaming Platforms:

- #### Leverage insights to deliver personalized recommendations to users.
  -  Increase engagement and satisfaction through relevant content suggestions.
  -  Quality Assessment and Feedback Analysis:

- #### Gauge audience reactions to films for quality assessment.
  -  Identify areas for improvement and make informed decisions for future projects.
  
- #### Risk Mitigation and Crisis Management:
  -  Monitor sentiment trends to detect negative sentiments or controversies early.
  -  Implement timely interventions to mitigate reputational risks.
 
### Conclusion
In conclusion, by defining eight distinct features for extraction and evaluating them across various machine learning models, I was able to observe differences in language usage between positive and negative reviews, as well as gain insights into model performance across multiple features. My analysis revealed that model performance varied significantly depending on the feature. For instance, Gaussian Naive Bayes and Bernoulli Naive Bayes models performed exceptionally well on certain features but poorly on others. Conversely, Decision Tree and Random Forest models (with the exception of feature 6) consistently demonstrated poor performance across all features. Notably, for feature 5, all models achieved near-perfect accuracy, indicating high performance. However, this near-perfect accuracy suggests the potential issue of overfitting, warranting further investigation.


