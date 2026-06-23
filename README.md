# SMS Spam Classifier

A Machine Learning web application that classifies SMS messages as **Spam** or **Not Spam (Ham)**. The application preprocesses SMS text, converts it into numerical features using text vectorization, and predicts the message category using a trained machine learning model.

## Features

* Classifies SMS messages as Spam or Ham.
* Cleans and preprocesses text data.
* Converts text into numerical features using vectorization.
* Compares multiple machine learning algorithms.
* Uses the best-performing model for prediction.
* Provides real-time predictions through a Streamlit web interface.

## Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* NLTK
* Pickle

## Project Structure

```text
sms-spam-classifications/
│
├── app.py                 
├── model.pkl               
├── vectorizer.pkl          
├── spam.csv                
├── nltk.txt               
├── requirements.txt        
├── setup.sh                
├── Procfile                
└── README.md               
``` 

## Machine Learning Algorithms Evaluated

* Support Vector Classifier (SVC)
* K-Nearest Neighbors (KNN)
* Multinomial Naive Bayes (MNB)
* Decision Tree Classifier
* Logistic Regression
* Random Forest Classifier
* AdaBoost Classifier
* Bagging Classifier
* Extra Trees Classifier
* Gradient Boosting Classifier
* XGBoost Classifier

## Final Model

The final deployed model uses **Multinomial Naive Bayes (MNB)** because it achieved the best performance for SMS spam classification after evaluating multiple algorithms.

## How It Works

1. User enters an SMS message.
2. The text is cleaned and preprocessed using NLP techniques.
3. The vectorizer converts the text into numerical features.
4. The trained model predicts whether the message is Spam or Ham.
5. The prediction is displayed on the screen.

## Example

Input:

```text
Congratulations! You have won a free iPhone. Click here to claim.
```

Output:

```text
Spam
```

Input:

```text
Hey, are we meeting at 6 PM today?
```

Output:

```text
Not Spam (Ham)
```

## Author

**Vaibhav Vala**
