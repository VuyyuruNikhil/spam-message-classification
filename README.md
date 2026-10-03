SMS Spam Message Classification Dataset
📌 About the Dataset

This repository contains a small SMS Spam Classification dataset stored in the spam.csv file. The dataset consists of text messages labeled as either ham (normal/non-spam messages) or spam (unwanted or suspicious messages).

The dataset is designed for beginners who want to understand text classification, spam detection, Natural Language Processing (NLP), and machine learning.

📂 Dataset Information

The spam.csv file contains 6 SMS messages divided equally between the two categories:

3 Ham messages – Normal messages
3 Spam messages – Unwanted or suspicious messages
Columns
Column	Description
v1	Classification label: ham or spam
v2	The actual SMS message
🏷️ Classification Labels
Ham

A ham message is a normal and legitimate SMS that is not considered spam.

Examples from the dataset include:

"Hi how are you"
"Let's meet tomorrow"
"Are you coming to class"
Spam

A spam message is an unwanted or suspicious message that may contain promotional content, fake prizes, or requests that could potentially be unsafe.

Examples from the dataset include messages about:

Winning a lottery
Free contest entries
Winning cash and entering an OTP
🎯 Purpose of the Dataset

The main purpose of this dataset is to provide a simple example for studying SMS spam detection. It can be used to demonstrate how text messages can be categorized into different classes based on their content.

💡 Possible Uses

This dataset can be used for:

SMS spam detection
Text classification
Natural Language Processing (NLP)
Machine learning practice
Data preprocessing
Exploratory data analysis
Building a basic spam classifier
🛠️ Technologies That Can Be Used

The dataset can be analyzed and processed using Python and libraries such as:

Python
Pandas
NumPy
Scikit-learn
NLTK
📊 Dataset Structure
spam.csv
│
├── v1 → Message category
│       ├── ham
│       └── spam
│
└── v2 → SMS message text
🚀 Future Improvements

Although this is a small educational dataset, it can be extended by adding more SMS examples. A larger dataset can then be used to train and evaluate machine learning models such as:

Naive Bayes
Logistic Regression
Support Vector Machines
Decision Trees
⚠️ Note

This dataset contains only 6 sample messages and is intended primarily for educational and demonstration purposes. Because of its small size, it should not be used to build a reliable real-world spam detection system.

📄 File Included
spam.csv – Contains the labeled SMS messages.
👩‍💻 Project Category

Machine Learning | Natural Language Processing | Text Classification|spam detection
