# 🌥️ Cloud Computing for Data Science — Lecture 32

> **Week 7 Lab Materials** | A beginner-friendly introduction to cloud computing and machine learning in the cloud using Google Colab.

![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)
![Language](https://img.shields.io/badge/Language-Python%203-blue)
![Level](https://img.shields.io/badge/Level-Beginner-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📖 About This Repository

This repo contains lecture notes and a hands-on lab for **Lecture 32: Cloud Computing for Data Science**, part of a Week 7 module on Big Data, Cloud & Final Project Kick-off.

Students will learn **what cloud computing is, why data scientists use it, and how to train a real ML model in the cloud — for free** — using Google Colab.

---

## 🎯 Learning Objectives

By the end of this lab, you will be able to:

- Explain what cloud computing is and why data scientists need it.
- Compare AWS SageMaker, Google Colab, and Azure ML.
- Launch a Jupyter Notebook in the cloud using Google Colab.
- Enable a free GPU and verify it with `nvidia-smi`.
- Mount Google Drive from a Colab notebook.
- Install Python libraries in a cloud environment.
- Train a scikit-learn model on the cloud.
- Save and reload a trained model from Google Drive.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `LECTURE_Cloud_Computing_for_Data_Science.md` | Full lecture notes with concepts, real-life examples, and a comparison of cloud platforms. |
| `Lab_Cloud_Jupyter_Setup.ipynb` | Hands-on Colab notebook with commented Python code. Students should open this in Colab. |
| `README.md` | This file. |

---

## 🚀 Quick Start — Running the Lab

### Option 1: Open Directly in Google Colab (recommended)

1. Go to [Google Colab](https://colab.research.google.com/).
2. Click **File → Upload notebook** and select `Lab_Cloud_Jupyter_Setup.ipynb`.
3. Click **File → Save a copy in Drive** so you can edit and save your progress.
4. Follow the steps inside the notebook — each cell has instructions and comments.

### Option 2: Open from GitHub

1. Visit this repo on GitHub.
2. Click the notebook file (`Lab_Cloud_Jupyter_Setup.ipynb`).
3. Click the "Open in Colab" badge (or prepend `https://colab.research.google.com/github/` to the GitHub URL).

---

## 🛠️ What the Lab Covers

The lab is broken into **9 clear steps**, each heavily commented so beginners can follow along:

1. **Check the machine** Google gave us (CPU, RAM, disk).
2. **Enable the free GPU** and verify with `nvidia-smi`.
3. **Mount Google Drive** to save files permanently.
4. **Install a Python library** (`yellowbrick`) in the cloud.
5. **Load a real dataset** (Iris flowers).
6. **Visualize the data** with seaborn.
7. **Train a Random Forest classifier** in the cloud.
8. **Save the trained model** to Google Drive.
9. **Load the model** and predict on new data.

Plus a **bonus challenge section** for homework.

---

## 💡 Real-Life Examples Covered in the Lecture

- 🎬 **Netflix** uses AWS SageMaker for movie recommendations.
- 💉 **Moderna** designed the mRNA COVID vaccine using AWS cloud simulations.
- 📱 **Instagram** serves personalized reels from cloud GPUs.
- 🤝 **LinkedIn** detects fake profiles with Azure ML.
- 🎓 **Students in Pakistan (and globally)** train world-class models on Colab for ₨ 0.

---

## 📋 Prerequisites

- A **Google account** (Gmail works).
- Basic Python knowledge (variables, functions, lists).
- No prior cloud experience needed — we start from zero.
- No installation required — **everything runs in your browser**.

---

## 📝 Submission Instructions (for Students)

1. Complete all 9 steps in the notebook.
2. Attempt at least 2 of the 5 bonus challenges.
3. Rename your notebook: `Lab32_Cloud_YourName_RollNumber.ipynb`.
4. Save to Google Drive.
5. Share the Drive link via the class portal.

---

## 🤝 For Instructors

Feel free to fork this repo and adapt the materials for your own class.

**Timing suggestion:**
- Lecture portion: ~30 minutes
- Live demo of opening Colab and enabling GPU: ~10 minutes
- Students run the lab themselves: ~30–40 minutes
- Q&A and bonus challenges: remaining time

---

## 📚 Further Reading

- [Google Colab Introduction](https://colab.research.google.com/notebooks/intro.ipynb)
- [AWS SageMaker Documentation](https://docs.aws.amazon.com/sagemaker/)
- [Azure ML Documentation](https://learn.microsoft.com/en-us/azure/machine-learning/)
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)

---

## 📜 License

MIT License — free to use, share, and modify for educational purposes.

---

## 🙏 Acknowledgments

- Dataset: Iris dataset (R. A. Fisher, 1936), bundled with scikit-learn.
- Platform: Google Colaboratory.
- Inspiration: Students who want to become data scientists without expensive hardware. 💪

---

*Happy coding, and welcome to the cloud!* ☁️🚀
