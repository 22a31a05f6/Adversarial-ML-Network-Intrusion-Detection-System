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
Network_Intrusion_GitHub
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

GitHub has a file size limit. Therefore, the large dataset and trained machine learning model files are hosted on Google Drive.

## Dataset Folder

Download the complete dataset from:

**Google Drive**

https\://drive.google.com/drive/folders/1lTk71OTx4jJjP-arrPHCSUg5WY\_XQkqf?usp=sharing

---

## Multi-Class Trained Model and CICIDS Folder

Download **nids\_multiclass\_model.pkl** and the **cicids** folder from the following Google Drive links respectively.

### nids\_multiclass\_model.pkl

https\://drive.google.com/file/d/1Eg8XXZ74o50f7rKyArAGSREGStr2Vcdb/view?usp=sharing

### cicids Folder

https\://drive.google.com/drive/folders/126mIx6GXmvbFWptlhcDBqWb9Bu5zmcc7?usp=sharing

---

## After Downloading

Place the downloaded files inside:

```text
ml_models/
│
├── dataset/
├── cicids/
└── nids_multiclass_model.pkl
```

The project will **not** work correctly unless these files are placed inside the **ml\_models** folder.

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YourGitHubUsername/Network_Intrusion_GitHub.git
```

```bash
cd Network_Intrusion_GitHub
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
