# QR-Based Phishing URL Detection Using ML

## Introduction

For this project, I have worked on detecting phishing URLs hidden inside QR codes using Machine Learning. Nowadays, QR codes are used everywhere for payments, websites, advertisements, and many other purposes. However, attackers can also create QR codes that redirect users to phishing websites. The aim of this project is to identify whether the URL hidden inside a QR code is legitimate or malicious.

## About the Project

The project starts by loading QR code images and multiple phishing URL datasets. I have combined the datasets and performed data cleaning and preprocessing. After understanding the data through visualizations and analysis, I extracted several useful URL features such as URL length, number of dots, hyphens, slashes, digits, and HTTPS usage. 
These features were then used to train a Machine Learning model that can classify URLs as phishing or legitimate.

## Dataset Used

For this project, I used QR code images along with phishing URL datasets collected from different sources. The phishing datasets contained both legitimate and malicious URLs. After combining and cleaning the datasets, I created a balanced dataset for training the model.
The final dataset contained around 48,000 URLs.

## Exploratory Data Analysis

Before training the model, I performed exploratory data analysis to better understand the dataset. I visualized the distribution of phishing and legitimate URLs, analyzed URL lengths, and studied how different URL features varied between safe and malicious websites.
This step helped me to understand which features could be useful for classification.

## Machine Learning Approach

I used a Random Forest Classifier because it is simple, effective, and performs well on structured data. The dataset was split into training and testing sets using an 80:20 ratio.
After training the model, I evaluated its performance using the accuracy score and the classification report.

## Results

The model achieved very high accuracy on the test dataset and was able to correctly classify most phishing and legitimate URLs.

The final workflow of the project is:
QR Code → URL Extraction → Feature Extraction → Machine Learning Prediction → Safe / Phishing Result

## Challenges Faced

One of the main challenges was combining multiple datasets and making sure that the labels were consistent. Another challenge was understanding which URL features would be useful for detecting phishing websites.
I also spent time verifying that the QR images and labels matched correctly before using them in the project.

## Future Improvements

* Add real-time QR code scanning using a webcam
* Experiment with Deep Learning models
* Build a mobile application version

## Conclusion

This project helped me to understand the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation. It also introduced me to a real-world cybersecurity problem and how Machine Learning can be used to solve it.
