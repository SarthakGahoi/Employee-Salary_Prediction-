Employee Salary Classification – Machine Learning Project
In this project, we developed a machine learning model that predicts whether an employee earns more than 50K based on demographic and job-related attributes. This end-to-end system includes data preprocessing, model training, evaluation, and deployment using Streamlit for an interactive user experience.

Features
Predicts employee income class: >50K or ≤50K
Trained on real-world structured data using a Random Forest Classifier
Handles categorical data via Label Encoding
Evaluated with accuracy and classification metrics (~86% accuracy)
Deployed using Streamlit with support for:
Single-entry form inputs
Batch CSV file uploads
Easy-to-use UI for HR and business users

Tools & Technologies Used
Python 3.8+
Jupyter Notebook
Libraries:
pandas, numpy, scikit-learn, seaborn, matplotlib, joblib, streamlit

Project Structure
bash
Copy
Edit
├── app.py                             # Streamlit web app
├── best_model.pkl                     # Trained ML model
├── Data_edunet.csv                    # Input dataset
├── Final_Employee_Salary_Prediction.ipynb  # Complete Jupyter notebook
├── README.md                          # Project documentation

How It Works
Load and clean the dataset (Data_edunet.csv)
Encode categorical columns (e.g., education, occupation)
Split data into training/testing sets
Train a Random Forest Classifier
Save model using joblib
Deploy via Streamlit app for real-time prediction

Sample Prediction
Input:
{'age': 35, 'education': 'Masters', 'occupation': 'Exec-managerial', 'hours-per-week': 50, 'experience': 10}
Prediction Output:
>50K

How to Run
Run Notebook:
bash
Copy
Edit
jupyter notebook Final_Employee_Salary_Prediction.ipynb
Launch Web App:
bash
Copy
Edit
streamlit run app.py

Author
Sarthak Gahoi 



