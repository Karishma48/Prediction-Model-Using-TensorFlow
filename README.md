# Prediction-Model-Using-TensorFlow
I recently worked on a machine learning project where I built a churn prediction model using TensorFlow, and I’m excited to share a quick overview of the process!

🔹 Step-by-step workflow:

Libraries & Data
Imported pandas and train_test_split from sklearn.
Loaded churn dataset from GitHub using pandas.

Data Preprocessing
Cleaned the data by removing unnecessary columns like Customer ID and Churn.

Applied pd.get_dummies() to convert categorical variables.
Converted all categorical data into boolean values using a lambda function.
Separated features and target variable into X and Y.

Splitting Data
Used train_test_split with an 80/20 ratio for training and testing sets.
Model Development with TensorFlow
Installed TensorFlow and imported necessary modules: Sequential, Dense, load_model, and accuracy_score.

Built and compiled the model with appropriate parameters.
Trained (fit), predicted (predict), and evaluated the model. (Note: This part took a bit of time due to processing.)

Results & Insights
Achieved 100% accuracy, which suggests a high chance of overfitting, but the model made correct predictions on the test set.

Finally, I saved the trained model for future use.

📸 I’ve attached screenshots for better clarity, and you can also check out the full video demo via my Google Drive: https://lnkd.in/g8R29T_a

🔗 I’m constantly exploring more in ML and AI — would love to hear your thoughts or suggestions on improving this model or avoiding overfitting in similar projects.
