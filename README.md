# 🎓 Student Performance Predictor

A machine learning project designed to predict student performance based on demographics, study habits, and socioeconomic factors. It features a full ML pipeline including model training, experiment tracking, data versioning, deployment, and a user-friendly web app.

![Demo of Web App](assets/student-performance-demo.gif) <!-- Replace this with your actual GIF path -->

---

## 🚀 Features

- ✅ **Data Cleaning & Preprocessing**  
  Handles missing values, outliers, and standardizes input features for consistent model performance.

- 📊 **Data Visualization**  
  Visual insights using **Matplotlib** and **Seaborn** to explore correlations and distributions.

- 🤖 **Machine Learning Models**  
  Trained 9 different models including:
  - Random Forest
  - Support Vector Machine (SVM)
  - XGBoost
  - Gradient Boost
  - And more using Scikit-learn

- 📈 **MLflow Integration**  
  Integrated **MLflow** for experiment tracking and comparison of model performance and hyperparameters.

- 🧪 **DVC (Data Version Control)**  
  Used **DVC** for managing datasets, model versions, and pipeline stages for full reproducibility.

- 🔄 **Prediction Pipeline**  
  Built a reusable and efficient pipeline that loads input data, preprocesses it, and generates predictions using trained models.

- 🌐 **Flask Web App**  
  Deployed a **Flask** application for users to input student data and receive real-time performance predictions.

- 📦 **Dockerized Application**  
  Containerized using **Docker** to ensure consistency across development, testing, and production environments.

- ⚙️ **CI/CD Deployment**  
  Set up **GitHub Actions** for automated testing and deployment workflows. Application is deployed on **AWS** upon push to main.

---





---

## 🧰 Tech Stack

| Category             | Tools / Libraries                                |
|----------------------|---------------------------------------------------|
| **Programming**      | Python, HTML, CSS, JavaScript                     |
| **Data Analysis**    | Pandas, NumPy, Matplotlib, Seaborn                |
| **Machine Learning** | Scikit-learn, XGBoost, DVC, MLflow                |
| **Web Framework**    | Flask                                             |
| **Deployment**       | Docker, GitHub Actions, AWS                       |
| **Version Control**  | Git, GitHub                                       |
| **Experiment Tracking** | MLflow                                         |
| **Containerization** | Docker                                            |

---

## 📂 Project Structure

```bash
student-performance-predictor/
│
├── data/                      # Raw and processed datasets
├── models/                    # Trained ML models
├── app/                       # Flask app source code
│   ├── templates/
│   ├── static/
│   └── app.py
├── src/                       # Scripts for EDA, training, and preprocessing
├── dvc.yaml                   # DVC pipeline configuration
├── Dockerfile                 # Docker config
├── requirements.txt
├── .github/workflows/         # CI/CD workflows
└── README.md
