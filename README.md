# Sentiment-analysis-NLP
Company Name: CODTECH IT SOLUTIONS

Name: HARINI N

Intern ID: CT04DL783

Domin name: MACHINE LEARNING

Duration : 4 WEEKS

Mentor Name: NEELA SANTHOSH

DESCRIPTION:

Sentiment Analysis of Tourist Place Descriptions
In this we come to know how to use Natural Language Processing (NLP) techniques to perform sentiment analysis using a dataset about tourist places. Although the dataset did not contain actual user reviews, it included a column called “Significance”, which had short descriptions of each location. We used this column as a substitute for customer reviews to practice sentiment analysis.

1. Data Preprocessing
The first step was to clean and prepare the text data. Raw text often contains unnecessary elements that can confuse a machine learning model. To clean the text, we followed these steps:
Convert to lowercase: So that words like "India" and "india" are treated the same.
Remove punctuation and numbers: These are usually not useful for understanding sentiment.
Remove stopwords: Common words like "the", "is", and "and" don’t carry much meaning.
Lemmatization: This reduces words to their root form. For example, "visited", "visiting", and "visit" all become "visit".
This made our text simpler and more meaningful for analysis.

2. Feature Extraction with TF-IDF
Once the text was cleaned, we needed to turn it into numbers that a machine learning model can understand. We used a method called TF-IDF (Term Frequency-Inverse Document Frequency). TF-IDF gives higher importance to words that are unique and meaningful in each description, and lower importance to common words.
This step converted the text into a matrix of numbers (called features), which we used to train the model.


4. Creating Sentiment Labels
Since our dataset didn’t include actual user sentiments (like positive or negative reviews), we created dummy sentiment labels. We randomly assigned "positive" or "negative" tags to each row, just to simulate how a real sentiment classification model would work. In a real project, we would use actual labeled data.

5. Training the Model
We used a machine learning algorithm called Logistic Regression. It is a popular model used for binary classification problems like predicting whether a review is positive or negative.
We split our data into training and testing sets — 80% for training the model and 20% for testing it. The model learned from the training data and then tried to predict the sentiment of the test data.

6. Evaluating the Model
After training, we tested the model and checked how well it performed. Since the labels were randomly created, the results were not meaningful in terms of real accuracy. However, this step showed the complete process of how a sentiment analysis system works.

Conclusion
Even though the dataset didn’t contain real customer reviews, this project showed the full process of performing sentiment analysis using NLP:
Preprocessing text
Converting it into TF-IDF vectors
Training a logistic regression model
Predicting sentiment
In the future, this process can be applied to real customer reviews from tourism websites, helping businesses understand what people think about different destinations.

OUTPUT 

![Image](https://github.com/user-attachments/assets/92cf7129-5e69-46e1-a744-c17362772a3f)
![Image](https://github.com/user-attachments/assets/f6f5edda-7c65-4289-a91b-4066ed3fe508)
![Image](https://github.com/user-attachments/assets/7f6fbd7c-3fab-48bd-af84-d4df4de061d3)
![Image](https://github.com/user-attachments/assets/be238b5d-a200-4722-baf5-6551a5de1297)
![Image](https://github.com/user-attachments/assets/19997bc4-92d3-4a12-a04d-71be11686ddd)
