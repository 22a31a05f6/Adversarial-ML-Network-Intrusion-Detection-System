# Adversarial Machine Learning Attacks Against Network Intrusion Detection System

## Project Overview

This project presents a web-based **Network Intrusion Detection System (NIDS)** integrated with **Machine Learning** and **Adversarial Machine Learning** techniques. The system detects malicious network traffic, classifies different attack types, and demonstrates how adversarial attacks can affect machine learning-based intrusion detection models.

The project is developed using **Python, Django, Machine Learning, HTML, CSS, JavaScript, Bootstrap, and SQLite**.

---

# Features

- User Registration and Login
- Admin Login
- Upload Network Traffic Dataset
- Machine Learning Attack Detection
- Adversarial Attack Detection
- Multiple Machine Learning Algorithms
- Attack Classification
- Performance Comparison Graphs
- Accuracy Analysis
- Confusion Matrix Visualization
- Result Dashboard
- Responsive Web Interface

---

# Technologies Used

## Backend

- Python
- Django

## Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

## Machine Learning

- Scikit-Learn
- Pandas
- NumPy
- Matplotlib

## Database

- SQLite

---

# Project Structure

```text
Adversarial-ML-Network-Intrusion-Detection-System
│
├── admins/
├── users/
├── templates/
├── static/
├── ml_models/
├── Network_Intrusion/
├── manage.py
├── requirements.txt
├── README.md
├── screenshots_of_live_project.pdf
├── docs/
└── .gitignore
```

---

# Large Files

Some trained machine learning models and datasets are not included in this repository because they exceed GitHub's file size limit.

The repository contains the complete source code, project structure, training scripts, and configuration files required to understand and reproduce the project.

To execute the project successfully, place the required trained models and datasets inside the `ml_models` directory before running the application.

Required directory structure:

```text
ml_models/
│
├── dataset/
├── cicids/
├── model.pkl
├── deploy_model.pkl
└── nids_multiclass_model.pkl
```
---

# Installation

## Clone Repository

```bash
git clone https://github.com/22a31a05f6/Adversarial-ML-Network-Intrusion-Detection-System.git
```

```bash
cd Adversarial-ML-Network-Intrusion-Detection-System
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv myvenv
```

Activate the virtual environment:

```bash
myvenv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Apply Database Migrations

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

---

## Start Development Server

```bash
python manage.py runserver
```

---

## Open Browser

Visit:

```text
http://127.0.0.1:8000/
```

---

## Important

Some trained machine learning models and datasets are not included in this repository because they exceed GitHub's file size limit.

Before running the project, make sure the required datasets and trained model files are placed inside the `ml_models` directory.

---

# Project Workflow

1. User Registration
2. User Login
3. Upload Network Traffic Dataset
4. Feature Extraction
5. Machine Learning Prediction
6. Adversarial Attack Analysis
7. Attack Classification
8. Display Results
9. Performance Comparison
10. Accuracy Evaluation

---

# Machine Learning Models Used

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Neural Network
- Multi-Class Classification Model

---

# Dataset

The project uses publicly available Network Intrusion Detection datasets for training and testing the machine learning models.

---

# Research Domain

- Cyber Security
- Machine Learning
- Deep Learning
- Adversarial Machine Learning
- Network Intrusion Detection System

---

# Project Output

The system provides:

- Attack Detection
- Attack Classification
- Prediction Results
- Accuracy Comparison
- Graphical Visualization
- Performance Evaluation

---

# Future Enhancements

- Real-Time Packet Monitoring
- Deep Learning Based Detection
- Explainable Artificial Intelligence (XAI)
- Cloud Deployment
- Live Network Traffic Analysis
- Advanced Adversarial Defense Mechanisms

---

# Author

**Nikhitha Sowmya Polisetty**

Bachelor of Technology (B.Tech)
Computer Science and Engineering

---

# License

This project is developed for **educational and research purposes**.

---

# Acknowledgements

- Django Framework
- Python Community
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- NSL-KDD Dataset
- CICIDS Dataset
- Research Papers on Adversarial Machine Learning
