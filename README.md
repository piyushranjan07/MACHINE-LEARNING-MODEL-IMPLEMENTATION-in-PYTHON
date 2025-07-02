# MACHINE-LEARNING-MODEL-IMPLEMENTATION-in-PYTHON
this is fourth project of my first summer internship in python programming 

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PIYUSH RANJAN

*INTERN ID*: CT04DN870

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION OF PROJECT*: In the digital age, email and SMS have become common modes of communication. While this has significantly improved communication efficiency, it has also introduced an increase in unsolicited messages, commonly known as spam. These messages may include unwanted advertisements, scams, or phishing attempts, and filtering them automatically is a critical application of machine learning. The purpose of this project is to develop a predictive model using Python and Scikit-learn to classify text messages as spam or ham (non-spam), demonstrating the power of Natural Language Processing (NLP) in real-world applications. This project, which is part of my Python internship. The main goal of the task is to implement a machine learning model capable of classifying or predicting outcomes from a dataset. For this, the SMS Spam Collection Dataset was chosen — a publicly available dataset that contains over 5,000 SMS messages labeled as either “spam” or “ham.” The project was implemented in Python using the Scikit-learn library for model building, along with Pandas, Matplotlib, and Seaborn for data processing and visualization. The entire development was done using Jupyter Notebook, and later tested in VS Code for script-based execution. The first step was to import the dataset and conduct basic data analysis. The data was cleaned and preprocessed by converting the text labels (“spam” and “ham”) into binary numerical format (1 for spam and 0 for ham). This was followed by splitting the dataset into training and testing sets using the train_test_split function from Scikit-learn. Next, the text data was converted into numerical form using CountVectorizer, a technique from NLP that transforms text into a matrix of token counts. This step is critical, as machine learning models cannot process raw text directly. After vectorization, the model was trained using the Multinomial Naive Bayes algorithm, which is commonly used for text classification tasks due to its simplicity and effectiveness. After training, the model's performance was evaluated using the classification report and confusion matrix. The classification report provided metrics such as precision, recall, F1-score, and accuracy. The model achieved a high accuracy, correctly identifying most of the spam and ham messages. A confusion matrix was also plotted using the Seaborn library to visually analyze the performance of the model. It showed the number of true positives, false positives, true negatives, and false negatives, giving a better understanding of where the model performs well and where it may need improvement. One of the most valuable aspects of this project was the real-world applicability. Spam detection is used by almost every email service provider, messaging app, and online platform. Building a simple but effective version of this tool helped strengthen my understanding of text preprocessing, feature extraction, and classification models. It also introduced me to evaluation techniques that are crucial in assessing the success of machine learning algorithms. In conclusion, this project successfully demonstrates how machine learning can be used to automate the task of spam detection. It combines the principles of data preprocessing, feature engineering, model training, and performance evaluation. This project helped reinforce my theoretical knowledge of NLP and provided hands-on experience with Scikit-learn. It is a valuable addition to my learning portfolio and represents my ability to build and evaluate a working ML model using Python.

*SMS SPAM DATASET*:![Image](https://github.com/user-attachments/assets/6b9bc76d-73ad-4cf0-b7b3-55704aff39e0)

*OUTPUT*:![Image](https://github.com/user-attachments/assets/ad17201a-f737-41c9-864d-f64c2437efe1)
  ![Image](https://github.com/user-attachments/assets/c31cd7e8-d727-4671-bcbd-2681906e4078)
  
