# Email Spam Classification

Kaggle Dataset - https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

The SMS Spam Collection is a set of SMS-tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged according to being ham (legitimate) or spam.

Libraries - nltk 

The following tasks were performed in the **sms-spam-detection.ipynb** file

## 1. Data cleaning
- Dropped the column null values
- Dropped for duplicate rows
- Encoded the target variable
  
## 2. Exploratory Data Analysis
- Visualized Spam and Not Spam dataset and found the data was imbalanced
- NLTK Punkt sentence tokenizer is used to calculate the number of characters, number of words, and number of sentences in the **text** feature.
- After adding the above three features, the dataset is visualized. The correlation Matrix shows a high correlation between the three new features. Therefore, only one feature among them is used for further pre-processing task.




# 3. Text Preprocessing
# 4. Model building
# 5. Evaluation
# 6. Improvement
# 7. Website
# 8. Deploy

