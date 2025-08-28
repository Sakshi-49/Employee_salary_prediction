# Employee_salary_prediction

🔮 AI Salary Oracle

Python Streamlit Scikit-learn XGBoost

A sophisticated web application built with Streamlit that predicts employee salaries using a powerful XGBoost machine learning model. This project demonstrates an end-to-end data science workflow, from model training to a polished, interactive, and deployable web application.
Live Application: 🚀 View the Deployed App Here!

AI Salary Oracle Screenshot
✨ Key Features

    Interactive UI with Glassmorphism: A stunning and modern user interface built with Streamlit and custom CSS, featuring a "glassmorphism" design for a professional look and feel.
    Powerful XGBoost Model: Utilizes a highly accurate XGBoost Regressor model to provide reliable salary predictions.
    Dynamic Salary Range Prediction: Instead of a single value, the app predicts a realistic salary range, better communicating the model's confidence.
    Animated & Engaging UX: Incorporates Lottie animations for a more engaging and responsive user experience.
    Model Performance Insights: Users can view the model's evaluation plot and R² score in a clean, expandable section.
    Fully Deployable: The project is structured with all necessary files (requirements.txt, etc.) for seamless deployment on platforms like Streamlit Community Cloud.

🛠️ Tech Stack & Libraries

    Core Language: Python
    Web Framework: Streamlit
    Machine Learning: Scikit-learn, XGBoost
    Data Manipulation: Pandas
    Model Persistence: Joblib
    Animations: Streamlit Lottie

🚀 How to Run Locally

To get a local copy up and running, follow these simple steps.
Prerequisites

    Python 3.9+
    Git

Installation & Setup

Clone the repository:

git clone https:https://github.com/Abhishek-Hiremath49/Employee_salary_prediction


Create and activate a virtual environment:

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
.\venv\Scripts\activate

Install the required packages:

pip install -r requirements.txt

Running the Application

Once the dependencies are installed, run the Streamlit app with this command:

streamlit run app.py

🧠 The Machine Learning Pipeline

The predictive power of this application comes from a carefully constructed machine learning pipeline.

    Algorithm: XGBoost Regressor was chosen for its high performance and robustness.
    Features: The model is trained on the following features:
        Age
        Gender
        Education Level
        Job Title
        Years of Experience
    Preprocessing:
        Categorical features (Gender, Education Level, Job Title) are encoded using LabelEncoder.
        Numerical features are scaled using StandardScaler to ensure the model performs optimally.
    Performance: The model achieved an R² Score of 94.58% on the held-out test set, indicating that it explains a very high percentage of the variance in salary data.
    Persistence: The entire pipeline, including the trained model, encoders, and scaler, is saved into a single salary_predictor.pkl file using joblib for easy and error-free loading during inference.

🤝 Contact

Created with passion by Abhishek. Let's connect!
