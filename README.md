# Email Spam Detection using Machine Learning

## Project Overview
This project is a machine learning-based Email Spam Detection system that classifies messages as *Spam* or *Not Spam (Ham)*. It uses Natural Language Processing (NLP) techniques to convert text into numerical features and a Naive Bayes classifier for prediction.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Google Colab

## Dataset
The project uses the spam.csv dataset containing labeled text messages classified as:
- *Ham* – Legitimate messages
- *Spam* – Unwanted or promotional messages

## Project Workflow
1. Load and explore the dataset
2. Clean and preprocess the data
3. Convert text into numerical features using TF-IDF
4. Split the dataset into training and testing sets
5. Train a Multinomial Naive Bayes model
6. Evaluate the model using accuracy and classification metrics
7. Test the model with custom user messages

## Example Prediction

Input:
Congratulations! You won a free prize. Click here to claim now.

Output:
Result: SPAM

## Files in This Repository
- Email_Spam_Detection.ipynb – Complete machine learning notebook
- spam.csv – Dataset used for training and testing
- README.md – Project documentation

## How to Run
1. Open Email_Spam_Detection.ipynb in Google Colab.
2. Upload the spam.csv dataset.
3. Run all cells in order.
4. Enter a custom message when prompted.
5. The model will classify the message as *SPAM* or *NOT SPAM*.

## Author
*Sinchana G M*
