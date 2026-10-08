
# 🔬 Diabetic Retinopathy Detection

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)](https://jupyter.org)
[![ML](https://img.shields.io/badge/Machine-Learning-green?style=for-the-badge&logo=tensorflow)](https://tensorflow.org)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)]()



> **An AI-powered system to detect and classify Diabetic Retinopathy from retinal fundus images using Deep Learning.**

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Demo & Resources](#-demo--resources)
- [Dataset](#-dataset)
- [Tech Stack](#-tech-stack)
- [Model Architecture](#-model-architecture)
- [Results](#-results)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Report](#-report)
- [Team](#-team)
- [License](#-license)

---

## 🧠 About the Project

Diabetic Retinopathy (DR) is a diabetes complication that affects the eyes and can lead to blindness if undetected. This project leverages **Deep Learning and Computer Vision** to automatically detect and classify the severity of DR from retinal fundus images.

### 🎯 Objectives
- Automate early detection of Diabetic Retinopathy
- Classify DR into severity levels (No DR / Mild / Moderate / Severe / Proliferative DR)
- Achieve high accuracy with minimal false negatives
- Provide an explainable AI pipeline for medical interpretability

---

## 🎥 Demo & Resources

| Resource | Link |
|----------|------|
|
| 🎬 **Explanation Video** | [Watch on Google Drive 🔗](https://drive.google.com/your-video-link-here) |
| 📄 **Project Report (PDF)** | [View Report 🔗](./Report.pdf) |




## 📂 Dataset

- **Source:** [Kaggle - APTOS 2019 Blindness Detection](https://www.kaggle.com/c/aptos2019-blindness-detection)
- **Total Images:** ~3,662 retinal fundus images
- **Classes:**

| Label | Severity |
|-------|----------|
| 0 | No DR |
| 1 | Mild |
| 2 | Moderate |
| 3 | Severe |
| 4 | Proliferative DR |

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)

### ⚙️ Training Configuration
| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Learning Rate | 1e-4 |
| Batch Size | 32 |
| Epochs | 30 |
| Loss Function | Categorical Crossentropy |
| Image Size | 224 × 224 |

---

## 📈 Results

| Metric | Score |
|--------|-------|
| ✅ Training Accuracy | ~94% |
| ✅ Validation Accuracy | ~89% |
| ✅ Quadratic Weighted Kappa | ~0.87 |
| ✅ AUC-ROC | ~0.95 |

> *Update these with your actual model results from the notebook.*

---

## 📁 Project Structure
---

## 🚀 Getting Started

### Prerequisites
```bash
Python >= 3.8
pip or conda
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/sirigosika/Diabetic_Retinopathy_Detection.git

# 2. Navigate to the project folder
cd Diabetic_Retinopathy_Detection

# 3. Install required libraries
pip install tensorflow keras opencv-python numpy pandas matplotlib scikit-learn jupyter

# 4. Launch Jupyter Notebook
jupyter notebook final_ML_project.ipynb
```

---

## 📄 Report

The detailed project report covering methodology, experiments, and analysis is available:

It includes:
- Problem Statement & Motivation
- Literature Review
- Methodology & Model Design
- Experimental Results
- Conclusion & Future Scope

---

## 👥 Team

| Name | GitHub |
|------|--------|
| **Sirigosika** | [@sirigosika](https://github.com/sirigosika) |
| **DivyavardhanSingh** | [@divyavardhansingh](https://github.com/divyavardhansingh) |
| **RidhamChaudhary** | [@ridham ](https://github.com/ridham) |

> *Update with your actual team member names and profiles.*

---

## 📃 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### ⭐ If you found this project helpful, please give it a star!

Made with ❤️ for advancing medical AI

