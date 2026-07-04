
---

# 🚗 Vehicle Insurance Claim Prediction MLOps Platform

> **An end-to-end Production-Ready MLOps Pipeline** built using **Python, MongoDB, AWS, Docker, GitHub Actions, CI/CD, and Machine Learning** that automates the complete lifecycle from **data ingestion** to **cloud deployment**.

---

## 📌 Project Overview

Traditional Machine Learning projects usually end after training a model.

This project goes several steps further by implementing a **complete production-grade MLOps architecture** capable of:

* Automated Data Ingestion
* Data Validation
* Feature Engineering
* Model Training
* Model Evaluation
* Model Registry
* Model Versioning
* Cloud Storage
* Prediction Pipeline
* Docker Containerization
* Continuous Integration
* Continuous Deployment
* AWS Cloud Deployment

The entire workflow is designed following modular software engineering practices, making the project scalable, maintainable, and production-ready.

---

# 🏗 Complete Architecture

```text
MongoDB Atlas
       │
       ▼
Data Ingestion
       │
       ▼
Data Validation
       │
       ▼
Data Transformation
       │
       ▼
Model Training
       │
       ▼
Model Evaluation
       │
       ▼
Model Registry (AWS S3)
       │
       ▼
Prediction Pipeline
       │
       ▼
Flask Web App
       │
       ▼
Docker Container
       │
       ▼
GitHub Actions
       │
       ▼
AWS EC2 Deployment
```

---

# ✨ Key Features

### 📥 Data Ingestion

* Fetches dataset directly from **MongoDB Atlas**
* Converts MongoDB documents into Pandas DataFrame
* Creates train-test split automatically
* Stores artifacts for downstream pipeline

---

### ✅ Data Validation

* Schema Validation
* Missing Value Validation
* Data Drift Detection
* Column Validation
* Numerical Feature Validation
* Categorical Feature Validation

---

### 🔄 Data Transformation

* Feature Engineering
* Missing Value Imputation
* Feature Scaling
* Encoding
* Pipeline Serialization
* Transformation Object Saving

---

### 🤖 Model Training

Multiple algorithms can be trained and compared.

Supports:

* Random Forest
* Gradient Boosting
* XGBoost
* CatBoost
* Extra Trees
* Decision Tree
* AdaBoost
* Linear Models

Automatic Best Model Selection based on evaluation metrics.

---

### 📊 Model Evaluation

Instead of replacing models blindly,

the project:

* Downloads previous production model
* Compares new model performance
* Uses Threshold Based Validation
* Registers model only if performance improves

This mimics a real production ML workflow.

---

### ☁ AWS Model Registry

Models are automatically:

* Uploaded to AWS S3
* Version Controlled
* Retrieved during prediction
* Managed without manual intervention

---

### 🔮 Prediction Pipeline

Production prediction pipeline supports:

* Single Prediction
* Batch Prediction
* Real-time Inference

---

### 🌐 Flask Web Application

Interactive web interface allowing users to

* Upload input
* Predict Insurance Claim
* Trigger Training Pipeline
* View Prediction Results

---

### 🐳 Dockerized Deployment

Entire application is containerized using Docker ensuring

* Environment consistency
* Easy deployment
* Platform independence

---

### ⚙ CI/CD Pipeline

Fully automated deployment using

GitHub Actions

Workflow:

```text
Code Push
     │
     ▼
GitHub Actions
     │
     ▼
Build Docker Image
     │
     ▼
Push Image to AWS ECR
     │
     ▼
Deploy on EC2
     │
     ▼
Updated Application
```

No manual deployment required.

---

# 🛠 Tech Stack

## Programming

* Python
* HTML
* CSS

---

## Machine Learning

* Scikit-Learn
* Pandas
* NumPy

---

## Database

* MongoDB Atlas

---

## Cloud

* AWS EC2
* AWS S3
* AWS ECR
* AWS IAM

---

## MLOps

* Docker
* GitHub Actions
* CI/CD
* Model Registry
* Environment Variables
* Logging
* Exception Handling

---

## Backend

* Flask

---

## Version Control

* Git
* GitHub

---

# 📂 Project Structure

```text
Vehicle-Insurance-Project/

│
├── artifacts/
├── notebooks/
├── src/
│
├── components/
│     ├── Data Ingestion
│     ├── Data Validation
│     ├── Data Transformation
│     ├── Model Trainer
│     ├── Model Evaluation
│     ├── Model Pusher
│
├── configuration/
├── constants/
├── entity/
├── pipeline/
├── aws_storage/
├── utils/
│
├── static/
├── templates/
│
├── app.py
├── demo.py
├── requirements.txt
├── Dockerfile
├── setup.py
├── pyproject.toml
└── README.md
```

---

# ⚙ Pipeline Workflow

```text
MongoDB
   │
   ▼
Data Ingestion
   │
   ▼
Data Validation
   │
   ▼
Data Transformation
   │
   ▼
Model Trainer
   │
   ▼
Model Evaluation
   │
   ▼
AWS S3 Model Registry
   │
   ▼
Prediction Pipeline
```

---

# 🔐 Environment Variables

Required environment variables

```bash
MONGODB_URL

AWS_ACCESS_KEY_ID

AWS_SECRET_ACCESS_KEY

AWS_DEFAULT_REGION

ECR_REPO
```

---

# ☁ AWS Services Used

* IAM
* EC2
* S3
* ECR

---

# 🐳 Deployment Pipeline

```text
Developer

↓

GitHub Repository

↓

GitHub Actions

↓

Docker Build

↓

Push Docker Image

↓

AWS ECR

↓

EC2 Pulls Latest Image

↓

Application Deployment
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone <repo_url>
```

---

### Create Environment

```bash
conda create -n vehicle python=3.10

conda activate vehicle
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Run Training

```bash
python demo.py
```

---

### Run Application

```bash
python app.py
```

---

# 📈 Engineering Highlights

✔ Modular Pipeline Architecture

✔ Production-ready Folder Structure

✔ Config Driven Development

✔ Artifact Based Pipeline

✔ Object-Oriented Design

✔ Cloud Model Registry

✔ Automatic Model Comparison

✔ Automated Deployment

✔ Logging System

✔ Custom Exception Handling

✔ Dockerized Infrastructure

✔ Continuous Integration

✔ Continuous Deployment

✔ AWS Cloud Deployment

✔ Environment Variable Management

---

# 📚 Software Engineering Concepts Demonstrated

* Clean Code Principles
* Modular Architecture
* Separation of Concerns
* Dependency Management
* Configuration Management
* Pipeline Design Pattern
* Artifact Management
* Model Versioning
* Cloud Integration
* CI/CD Automation
* Containerization
* Production Deployment

---

# 🎯 Recruiter Highlights

This project demonstrates hands-on experience with:

| Category             | Skills Demonstrated                              |
| -------------------- | ------------------------------------------------ |
| Machine Learning     | End-to-End ML Pipeline                           |
| MLOps                | Production Workflow                              |
| Backend              | Flask                                            |
| Cloud                | AWS (EC2, S3, ECR, IAM)                          |
| Database             | MongoDB Atlas                                    |
| DevOps               | Docker, GitHub Actions                           |
| CI/CD                | Automated Deployment                             |
| Software Engineering | OOP, Modular Design, Logging, Exception Handling |

---

# 👨‍💻 Author

**Ayush**

Aspiring **Machine Learning Engineer | MLOps Engineer**

Focused on building production-grade AI systems using Machine Learning, Cloud Computing, and DevOps practices.

---

