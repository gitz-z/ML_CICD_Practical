# PreprocessingCICD

Name: Zhang Zhida  
Module: Machine Learning II  
Practical: Week 13 – CI/CD Pipeline  

---

## 📌 Project Description

This project demonstrates the implementation of a Continuous Integration / Continuous Deployment (CI/CD) workflow using GitHub Actions for a machine learning preprocessing pipeline.

The objective is to automate testing and validation of preprocessing scripts whenever code is pushed to the repository.

---

## 📂 Project Structure

PreprocessingCICD  
├── src/  
│   ├── preprocess.py  
│   ├── preprocess_pipeline.py  
│   └── __init__.py  
├── tests/  
│   └── test_preprocess.py  
├── configs/  
│   └── preprocess.yaml  
├── data/  
│   ├── raw/  
│   └── processed/  
├── requirements.txt  

---

## ⚙️ Setup Instructions

1. Install dependencies:

2. Run preprocessing:

3. Run tests:

---

## 🔁 CI/CD Workflow

This repository uses GitHub Actions to:

- Automatically install dependencies
- Execute preprocessing
- Run unit tests using pytest
- Validate code integrity on every push

The workflow ensures reliable and reproducible preprocessing in an ML pipeline.

---

## 🚀 Purpose of CI/CD in ML

The CI/CD pipeline ensures:

- Code quality control
- Automated validation
- Early error detection
- Reproducibility of preprocessing steps
- Alignment with ML Ops best practices

- Workflow Status: ✅ Passing
