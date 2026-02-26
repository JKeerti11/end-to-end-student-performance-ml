🎓 End-to-End Student Performance ML Project

A production-ready Machine Learning project that predicts student performance using a modular pipeline architecture, model training framework, and Flask-based web deployment.

🚀 Project Overview

This project builds a complete Machine Learning pipeline to predict student performance based on demographic and academic features.

It covers:

📊 Exploratory Data Analysis (EDA)

🧹 Data Preprocessing & Feature Engineering

🤖 Model Training & Evaluation

💾 Model & Preprocessor Serialization

🌐 Flask Web Application Deployment

🔄 CI/CD with GitHub Actions

📦 Production-ready project structure

This project follows industry-level ML Engineering practices.

🏗️ Project Architecture
Data → Data Ingestion → Data Transformation → Model Training
     → Model Selection → Model Saving → Prediction Pipeline
     → Flask Web App → User Prediction

📊 Dataset Information

The dataset contains student information such as:

Gender

Race/Ethnicity

Parental level of education

Lunch type

Test preparation course

Reading score

Writing score

🎯 Target Variable:

Math score (or overall performance)

🧠 Machine Learning Workflow
1️⃣ Data Ingestion

Reads dataset

Splits into training & testing sets

Saves processed CSV files

2️⃣ Data Transformation

Handles missing values

Encodes categorical variables

Scales numerical features

Creates preprocessing pipeline

Saves preprocessor.pkl

3️⃣ Model Training

Trains multiple regression models

Compares performance

Selects best model

Saves model.pkl

4️⃣ Prediction Pipeline

Loads trained model

Loads preprocessor

Accepts user input

Returns prediction

🌐 Web Application

Built using Flask.

Users can:

Enter student details

Submit form

Get predicted performance instantly

Run locally:

python app.py

Open in browser:

http://localhost:5000
⚙️ Installation & Setup
Step 1: Clone Repository
git clone https://github.com/your-username/end-to-end-student-performance-ml.git
cd end-to-end-student-performance-ml
Step 2: Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows
Step 3: Install Dependencies
pip install -r requirements.txt
Step 4: Run Application
python app.py
🔄 CI/CD Integration

This project uses GitHub Actions for automated:

Build checks

Dependency installation

Environment validation

Workflow file:

.github/workflows/main_studentssperformance3.yml
🧩 Technologies Used

Python 3.10+

Pandas

NumPy

Scikit-learn

CatBoost

Flask

GitHub Actions

HTML/CSS

🏆 Key Highlights

✅ Modular ML pipeline architecture
✅ Custom logging and exception handling
✅ Separation of training and prediction pipelines
✅ Model serialization with Pickle
✅ Flask web deployment
✅ CI/CD integration
✅ Industry-standard folder structure

📌 Future Improvements

Docker containerization

Cloud deployment (AWS/Render)

MLflow experiment tracking

Unit testing

Model monitoring

💼 Resume Description

Built a production-ready end-to-end machine learning pipeline to predict student performance using modular architecture, automated preprocessing, model selection, and Flask-based deployment with CI/CD integration.

👤 Author

Keerti
Aspiring ML Engineer
