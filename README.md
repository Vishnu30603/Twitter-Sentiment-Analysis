# Twitter Sentiment Analysis
This project focuses on detecting hate speech in tweets, specifically identifying tweets with racist or sexist sentiments. It utilizes Natural Language Processing (NLP) techniques to preprocess and analyze the text data. The goal is to train models using a labeled dataset to predict the labels of tweets in the test dataset.
# Dataset
The dataset used in this project consists of 31,962 labeled tweets provided in a CSV file format. Each line in the CSV file contains a tweet ID, its corresponding label, and the tweet text. The labels are binary, with '1' indicating a tweet containing racist or sexist content, and '0' indicating a tweet without such content.
# Exploratory Data Analysis
Exploratory Data Analysis (EDA) is conducted to gain insights into the dataset. It involves analyzing the distribution of labels, identifying common patterns or trends, and visualizing the data. EDA helps in understanding the characteristics of the dataset and guides further analysis.
# Preprocessing
Several preprocessing steps are applied to clean and prepare the tweets. This includes removing usernames and stopwords and performing tokenization and stemming to simplify the text data for analysis.
# Model Training and Evaluation
The dataset is split into a training set and a test set. The training set is used to train various models using the Bag of Words approach. The machine learning model is trained and evaluated based on its performance in predicting the labels of tweets in the test dataset. Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated to assess the model's performance. In addition, k-fold cross-validation is applied, where the training set is divided into k subsets, and the model is trained and evaluated multiple times on different combinations of subsets. This helps to assess the model's performance more robustly and reduces the impact of random data splits.
# Results
The results obtained from the trained models are presented, including the evaluation metrics and any significant findings or observations. 
# Dependencies
The project relies on the following libraries:                                                                                          
1.NumPy                                                                                                                                 
2.Pandas                                                                                                                                
3.Matplotlib                                                                                                                            
4.Seaborn                                                                                                                               
5.Scikit-learn                                                                                                                          
6.Regular expressions                                                                                                                   
7.Natural Language Toolkit                                                                                                              
8.String                                                                                                                               
Make sure to have these libraries installed before running the project.
