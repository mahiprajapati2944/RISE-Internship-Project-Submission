# RISE-Internship-Project-Submission
# Email Spam Detection using Machine Learning

## 📌 Project Overview
This project is part of the RISE Internship Program by Tamizhan Skills. The goal is to detect whether a given message is spam or not using Machine Learning techniques and provide a simple GUI for interaction.

## 🔍 Problem Statement
Spam messages are a major issue in communication systems. This project aims to classify SMS messages into 'spam' or 'ham' (not spam) using NLP and a Naive Bayes classifier.

## 📁 Dataset
- Name: SMS Spam Collection Dataset
- Source: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
- Format: CSV file with two columns — label (`ham`/`spam`) and text (SMS content)

## 🧠 ML Model
- Algorithm: Multinomial Naive Bayes
- Preprocessing: Lowercasing, Stopwords removal, TF-IDF vectorization
- Accuracy: ~98%

## 🖥 GUI Application (Tkinter)
- Users can input any message into the text box.
- Click the 'Check Spam' button to classify the message.
- The result (Spam or Not Spam) will be displayed below.

## 💡 Requirements
- Python 3.x
- Libraries: pandas, scikit-learn, nltk, tkinter

## OUTPUT
![image](https://github.com/user-attachments/assets/d2771038-e520-4162-8a64-427c5b4dfd89)
![image](https://github.com/user-attachments/assets/dcd924bb-dec5-47d3-9613-f7dfaa2ee62a)


Install required libraries:

## ▶️ Running the App
1. Download or clone this repository.
2. Place `spam.csv` in the same folder as the Python file.
3. Run the GUI script:


## 📦 Files Included
- `Project code.ipynb` – Main Tkinter GUI with spam detection
- `spam.csv` – Dataset file
- `Email_Spam_Detection_Project_Report.docx` – Project report
- `Email_Spam_Detection_Presentation.pptx` – Presentation slides
- `README.txt` – This file

## 🙌 Credits
Created by Mahi Prajapati under the RISE Internship by Tamizhan Skills.

