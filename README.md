# Sms_Data

#SMS Data Analysis (Spam vs Non-Spam, Debit and Credit Analysis)

Overview
This repository contains a comprehensive analysis of SMS data focused on spam classification, transaction analysis (debit and credit), and text analysis. The primary objectives were to clean and preprocess SMS data, classify messages as spam or non-spam using machine learning, and extract key insights from non-spam SMS content. The analysis includes finding the most common words, calculating total debits and credits, identifying frequent senders, and analyzing SMS activity and transaction data.

##Features
Data Cleaning:

The SMS dataset was cleaned to handle missing values, format issues, and irrelevant data points.
Spam vs Non-Spam Classification:

Using machine learning techniques, SMS messages were classified into spam and non-spam categories.
Non-spam messages were stored in the non_spam_data variable for further analysis.
Text Analysis:

Extracted the most common words in non-spam SMS content.
Calculated text length distribution to understand the structure of non-spam SMS messages.
Transaction Analysis:

Total Debit and Credit Calculations: Calculated the total debited and credited amounts from the messages.
Debit and Credit Ratio: Analyzed the ratio of debit and credit transactions and visualized it in pie charts.
Saving vs Expenditure: Analyzed saving vs expenditure based on the debit and credit transactions.
Sender and Transaction Insights:

Top 5 Most Frequent Senders in Non-Spam Data: Identified the senders with the most frequent non-spam messages.
Number of Debit and Credit Transactions to Banks: Analyzed debit and credit transactions sent to various banks.
SMS Activity Analysis:

SMS Activity by Hour of Day: Analyzed SMS activity to understand peak times of SMS activity.
Categorization of Messages:

Messages were categorized into Transaction, Promotion, and Notification using keyword patterns.
A bar plot was generated to visualize the distribution of messages across categories.
Insights
Here are some valuable insights derived from the analysis:

Spam vs Non-Spam Messages:

Through machine learning, non-spam messages were clearly separated from spam messages.
Most non-spam messages are related to important financial or transactional communications (e.g., debits, credits).
Most Common Words in Non-Spam SMS:

Key phrases such as "credited," "received," and "withdrawn" were frequently used in non-spam messages, indicating financial transactions.
Debit and Credit Analysis:

Total Debits: A significant portion of the debits came from transaction-related messages, such as payments, withdrawals, and purchases.
Total Credits: Credit transactions primarily included deposits or refunds.
The debit-to-credit ratio helped to visualize the overall transaction trend.
The Savings vs Expenditure chart highlighted how much money was being spent compared to saved or deposited amounts.
Top 5 Most Frequent Senders:

The analysis identified the top 5 senders based on message frequency, indicating which banks or service providers are sending the most transactional messages.
SMS Activity Over Time:

The SMS Activity by Hour chart revealed peak times for receiving SMS messages, which could help in understanding user behavior or transaction patterns during specific times of the day.
Transaction Insights:

The Number of Debit and Credit Transactions to Banks analysis helped understand where the most significant financial activities were happening, such as identifying specific banks involved in higher numbers of transactions.
Categorization of Messages:

The message categorization revealed that promotional and transactional messages dominate non-spam content, with a small portion consisting of notifications.
Setup
##Clone this repository:

git clone https://github.com/your-username/sms-data-analysis.git
Install the required dependencies:

pip install -r requirements.txt
Make sure you have the SMS data in the correct format (CSV or similar) and adjust the file path in the script accordingly.

##Files
sms_data_analysis.py: Main script for cleaning, classifying, and analyzing the data.
requirements.txt: List of required Python packages.
data_cleaned.csv: Cleaned data file (if applicable).
README.md: This file.
Future Improvements
Enhance the spam classification model using advanced NLP techniques (e.g., sentiment analysis, deep learning).
Implement additional transaction categorization (e.g., by transaction type like payment, refund, etc.).
Integrate the analysis with a web dashboard for real-time monitoring.
License
This project is licensed under the MIT License - see the LICENSE file for details.
