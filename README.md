# 🏥 Healthcare Disease Classification System

An end-to-end Machine Learning + MLOps healthcare disease classification system built using FastAPI, Streamlit, PostgreSQL, Docker, Prometheus, GitHub Actions, and Weights & Biases.

This project demonstrates the complete lifecycle of an ML system including:

- Data ingestion
- Model training
- Hyperparameter tuning
- Experiment tracking
- API deployment
- Monitoring
- Frontend integration
- CI/CD automation
- Containerization

---

# 🌐 Live Deployment

## 🚀 Frontend (Streamlit)

🔗 https://health-prediction-system-frontend.onrender.com/

---

## 🚀 Backend API (FastAPI)

🔗 https://health-prediction-system-j3rs.onrender.com/

---

## 📄 Swagger API Documentation

🔗 https://health-prediction-system-j3rs.onrender.com/docs

---

## 📄 ReDoc API Documentation

🔗 https://health-prediction-system-j3rs.onrender.com/redoc

---

# 📌 Project Objective

The objective of this project is to build a production-ready healthcare disease prediction system using modern MLOps practices.

The system accepts patient clinical information such as:

- Age
- Gender
- Symptoms
- Symptom Count

and predicts the most probable disease using trained machine learning models.

---

# 🧠 Features

✅ Neon PostgreSQL database integration  
✅ Scikit-learn ML pipeline  
✅ Hyperparameter tuning using GridSearchCV  
✅ Weights & Biases experiment tracking  
✅ FastAPI backend deployment  
✅ Streamlit frontend dashboard  
✅ Docker containerization  
✅ Prometheus monitoring  
✅ GitHub Actions CI/CD workflows  
✅ Pytest unit testing  
✅ Flake8 & Pylint code quality checks  
✅ Render deployment  

---

# 🏗️ System Architecture

```text
                ┌────────────────────┐
                │ Healthcare Dataset │
                └─────────┬──────────┘
                          │
                          ▼
               ┌─────────────────────┐
               │ Neon PostgreSQL DB  │
               └─────────┬───────────┘
                         │
                         ▼
               ┌─────────────────────┐
               │ Data Loader Script  │
               └─────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ ML Training Pipeline │
              └─────────┬────────────┘
                        │
         ┌──────────────┴──────────────┐
         ▼                             ▼
┌─────────────────┐         ┌──────────────────┐
│ Model Artifacts │         │ Weights & Biases │
└────────┬────────┘         └──────────────────┘
         │
         ▼
┌──────────────────────┐
│ FastAPI Backend API  │
└─────────┬────────────┘
          │
          ▼
┌──────────────────────┐
│ Streamlit Frontend   │
└─────────┬────────────┘
          │
          ▼
┌──────────────────────┐
│ End Users / Doctors  │
└──────────────────────┘
```

---

# 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Backend API | FastAPI |
| Frontend | Streamlit |
| Database | Neon PostgreSQL |
| Monitoring | Prometheus |
| Experiment Tracking | Weights & Biases |
| Containerization | Docker |
| CI/CD | GitHub Actions |
| Deployment | Render |
| Testing | Pytest |
| Code Quality | Flake8, Pylint |

---

# 📂 Project Structure

```text
ML_project/
│
├── src/
│   ├── data_loader.py
│   ├── train.py
│   ├── tune_model.py
│   ├── upload_to_postgres.py
│
├── models/
│   ├── best_model.joblib
│   ├── pipeline.joblib
│   └── preprocessor.joblib
│
├── tests/
│   ├── test_api.py
│   ├── test_model.py
│   └── test_validation.py
│
├── .github/workflows/
│   ├── backend.yml
│   └── frontend.yml
│
├── docker-compose.yml
├── Dockerfile
├── prometheus.yml
├── streamlit_app.py
├── requirements.txt
├── README.md
└── config.yaml
```

# 📊 Models Used

The following ML models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

# 📈 Experiment Tracking

Weights & Biases (W&B) was used to track:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Hyperparameters
- Model artifacts


### Features

- Interactive UI
- Patient clinical information form
- Real-time disease prediction
- API integration

---

### Final Pylint Score

```text
8.79/10
```

---

# ☁️ Deployment

| Component | Platform |
|---|---|
| FastAPI Backend | Render |
| Streamlit Frontend | Render |


# 📌 Future Improvements

- Improve model accuracy
- Add deep learning models
- Add authentication
- Add patient history tracking
- Integrate real hospital datasets
- Deploy using Kubernetes
- Add Grafana dashboards

---

# 👨‍💻 Author

## Insiya Munawer

This project is developed for academic and learning purposes.
