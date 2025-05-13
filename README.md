# Student-Dropout-Prediction

This project predicts the likelihood of a student dropping out from an e-learning platform using machine learning models.

## Dataset
The dataset (learning_data.csv) includes the following features:

- student_id: Unique identifier for the student
- age: Age of the student
- gender: Gender of the student (Male / Female / Other)
- course_type: Course type (Digital Marketing / Python / UI/UX)
- session_count: Total number of sessions attended
- avg_session_duration: Average session duration (in minutes)
- quiz_attempts: Number of quiz attempts made
- assignments_submitted: Number of assignments submitted
- satisfaction_rating: Satisfaction rating (1 to 5)
- dropout: Target variable (1 if dropped out, 0 if completed)

## Requirements
To install the necessary dependencies, run:
''' pip install -r requirements.txt '''

## Steps to Run the Project
1. Clone this repository:
   ''' git clone https://github.com/yourusername/student-dropout-prediction.git '''
2. Train and evaluate the models:
   ''' python main.py '''

## Models Used
1. Logistic Regression
2. Random Forest
3. Naive Bayes
4. Support Vector Classifier (SVC)
5. XGBoost

## Evaluation
Models are evaluated using:

1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. ROC-AUC Score
