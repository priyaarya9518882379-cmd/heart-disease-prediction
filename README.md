# Heart Disease Prediction Using Machine Learning

Project Overview

This project is a Machine Learning-based prediction application built using Python and Streamlit. It uses a trained Logistic Regression model to generate predictions based on user-provided health parameters.

The application provides a simple interactive interface where users can enter relevant details and view the model's prediction.

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit

Machine Learning Model

- Algorithm: Logistic Regression
- Feature scaling using a saved scaler
- Saved model and expected input columns for prediction

Project Structure

- "app.py" – Streamlit application.
- "heart.csv" – Dataset.
- "LogisticRegression_heart.pkl" – Trained Logistic Regression model.
- "scaler.pkl" – Saved feature scaler.
- "columns.pkl" – Expected input columns.
- "requirements.txt" – Required Python libraries.

How to Run Locally

1. Clone this repository.

2. Install the dependencies:
   
   "pip install -r requirements.txt"

3. Run the Streamlit application:
   
   "streamlit run app.py"

Disclaimer

This project is developed for educational purposes only. Its predictions are not a medical diagnosis and should not be used as a substitute for professional medical advice.

Author

Priyanka Arya

GitHub: https://github.com/priyaarya9518882379-cmd
