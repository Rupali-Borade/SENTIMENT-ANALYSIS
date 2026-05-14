# SENTIMENT-ANALYSIS
COMPANY:CODTECH IT SOLUTIONS
NAME:RUPALI BORADE
INTERN ID:CTIS3470
DOMAIN:DATA ANALYTICS
DURATION:16 WEEKS
MENTOR:NEELA SANTOSH

#DESCRIPTION
This project focuses on performing Sentiment Analysis on textual data using Natural Language Processing (NLP) techniques and Machine Learning. The main objective of this task is to classify text data such as tweets or reviews into different sentiment categories like positive, negative, and neutral.

The project begins with importing the required Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, NLTK, and Scikit-learn. These libraries are used for data handling, visualization, preprocessing, and model building. The dataset used in this project contains tweet data along with sentiment labels.

Initially, the dataset is loaded and explored to understand its structure, size, and sentiment distribution. Basic data visualization techniques are applied to analyze the frequency of positive, negative, and neutral sentiments. Bar charts are used to visually represent sentiment distribution in the dataset.

The next step involves text preprocessing, which is one of the most important stages in Natural Language Processing. The raw text data contains unnecessary elements such as URLs, special characters, hashtags, mentions, and stopwords that can reduce model performance. These unwanted elements are removed using regular expressions and NLTK preprocessing techniques. Stemming is also applied to reduce words to their root forms, improving text consistency.

After preprocessing, the cleaned text data is converted into numerical form using TF-IDF (Term Frequency-Inverse Document Frequency) Vectorization. TF-IDF helps in transforming textual data into meaningful numerical features that can be understood by machine learning algorithms.

The dataset is then divided into training and testing sets using train-test split methodology. A Logistic Regression model is used for sentiment classification because it is simple, efficient, and performs well on text classification tasks.

The trained model is evaluated using different performance metrics such as accuracy score, classification report, and confusion matrix. These evaluation techniques help measure how effectively the model predicts sentiments. Visualization of the confusion matrix is also performed to analyze prediction performance in detail.

Additionally, a custom prediction function is implemented to test user-defined text inputs. This allows the model to predict sentiments for new tweets or reviews entered by the user.

The project successfully demonstrates how Natural Language Processing and Machine Learning can be used together to analyze public opinions and emotions from textual data. Sentiment Analysis has real-world applications in social media monitoring, customer feedback analysis, product reviews, and business decision-making.

Overall, this project provides practical experience in text preprocessing, feature extraction, machine learning model implementation, and sentiment prediction using Python and NLP techniques.

#OUTPUT
<img width="1250" height="283" alt="Image" src="https://github.com/user-attachments/assets/13647f13-6b6c-49e1-a7b7-b92d4c099148" />
<img width="831" height="435" alt="Image" src="https://github.com/user-attachments/assets/6751db0d-5014-47c7-9a4c-591e804405d5" />
<img width="582" height="178" alt="Image" src="https://github.com/user-attachments/assets/97237b84-1462-4f82-8dc8-44e605af3996" />
<img width="966" height="369" alt="Image" src="https://github.com/user-attachments/assets/e10aa9ad-b550-4462-ae91-8f871b71cf2a" />
<img width="686" height="434" alt="Image" src="https://github.com/user-attachments/assets/f8ddd653-9586-4c89-bda0-57edc5f9d6e5" />
