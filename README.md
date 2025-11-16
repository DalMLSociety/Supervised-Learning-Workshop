# 🎓 **Dalhousie Machine Learning Society: Intro to Supervised Learning Workshop**

Welcome to the **DalMLSociety Intro to Supervised Learning** workshop series!  
This 3-part, hands-on series introduces key supervised learning concepts through theory, visualization, and implementation of real ML models in Python and Google Colab.

## 🧑‍🏫 **Meet the Team**

| **Role**               | **Name**   | **Program**                                                        |
| ---------------------- | ---------- | ------------------------------------------------------------------ |
| Instructor & Developer | Shuvro Pal | PhD – _Computer Science_, Dalhousie University                     |
| Instructor & Developer | Aditya Lad | MACS – _Applied Computer Science_, Dalhousie University            |
| Instructor & Developer | Kai Patel  | BCS – _Computer Science (2nd Year)_, Dalhousie University          |
| Developer              | Anand Lo   | BACS – _Applied Computer Science (4th Year)_, Dalhousie University |

## 🧭 **Workshop Overview**

| **Session**                                                                      | **Focus**                                                                                                                             | **Duration** |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| **Workshop 1:** Foundations of Supervised Learning                               | Key concepts, regression vs classification, understanding core algorithms                                                             | 3 h          |
| **Workshop 2:** Implementing Algorithms                                          | Preprocessing, pipelines, regression + classification models, metrics + visualization                                                 | 3 h          |
| **Workshop 3:** End-to-End ML Project – Spotify Track Popularity and Deliverable | Full walkthrough of an ML project pipeline, model implementation, evaluation, and interpretability; Time to work on your own project! | 3 h          |

### ⭐ By the end of the series, participants will be able to:

- Explain the **workflow** of supervised learning (data > model > evaluation).
- Implement and tune classification and regression models such as **Linear Regression**, **Logistic Regression**, **k-NN**, and **Random Forest**.
- Understand and apply **evaluation metrics** like RMSE, MAE, F1, and ROC to evaluate performance and interpret results.
- Build a **reproducible ML pipeline** on real data using **scikit-learn**.

## 📂 **Repository Structure**

```
Supervised-Learning-Workshop/
│
├── deliverable/                     # Notebooks and datasets for completing deliverable
│   ├── data/
│   │   ├── dataset1.csv             # Dataset for Deliverable 1 (Customer Churn)
│   │   ├── dataset2.csv             # Dataset for Deliverable 2 (Credit Risk)
│   │   └── dataset3.csv             # Dataset for Deliverable 3 (Housing Prices)
│   │
│   ├── 01_dataset1_student.ipynb    # Deliverable notebook 1
│   ├── 02_dataset2_student.ipynb    # Deliverable notebook 2
│   └── 03_dataset3_student.ipynb    # Deliverable notebook 3
│
├── notebooks/                       # Workshop demonstration notebooks
│   ├── data/
│   │   └── spotify-dataset.csv      # Dataset used in the Spotify regression project
│   │
│   ├── 1_algorithms.ipynb           # Intro notebook covering implementing relevant SL algorithms
│   └── 2_spotify_project.ipynb      # PROJECT: Predicting Spotify track popularity
│
├── LICENSE.txt                      # Open-source MIT license
└── README.md                        # This file
```

## 📚 **Resources**

- ### 🖥️ Slides:

  - [Supervised Learning Workshop – Google Slides](https://docs.google.com/presentation/d/17zIH9_ZeNpZkui3ULUjs6WjWcbYg4DAImDtfnnm8eAM/edit?usp=sharing)

- ### 📖 Recommended Readings and Learning:
  - ....will be added

## 🔧 **Setup Instructions**

### 🧑‍💻 Run in Google Colab

Open directly in Colab — no installation required:

- [Day 2 Notebook – Algorithms](https://colab.research.google.com/github/DalMLSociety/Supervised-Learning-Workshop/blob/main/notebooks/1_algorithms.ipynb)
- [Day 3 Notebook – Spotify Project](https://colab.research.google.com/github/DalMLSociety/Supervised-Learning-Workshop/blob/main/notebooks/2_spotify_project.ipynb)

**NOTE:** When running [Day 3 Notebook – Spotify Project](https://colab.research.google.com/github/DalMLSociety/Supervised-Learning-Workshop/blob/main/notebooks/2_spotify_project.ipynb) in Google Colab, you must upload the dataset (`./notebooks/data/spotify-dataset.csv`):

1. Download and save the `spotify-dataset.csv` locally.
2. When prompted in Colab during the setup, upload the CSV you saved.

## 📒 **Deliverable**

The deliverable includes completing **one of three** different machine learning problems:

1. `Customer Churn` – Predict which telecom customers will leave the service (**binary classification**)
2. `Credit Risk` – Predict likelihood a loan applicant will default (**binary classification**)
3. `Housing Prices` – Predict house sale price (**regression**)

Each dataset contains **real-world data challenges** (e.g., missing values, outliers, duplicates)
that make them ideal for practicing data cleaning, preprocessing, and model building.

---

### Instructions

1. Choose one of the notebooks and download its corresponding dataset from this repo.

   - All datasets are located in the `./deliverable/data/` directory.

2. Open the notebook in Google Colab:

   - 📘 [Deliverable 1 – Dataset 1 Notebook (Customer Churn)](https://colab.research.google.com/github/DalMLSociety/Supervised-Learning-Workshop/blob/main/deliverable/01_dataset1.ipynb)
   - 📙 [Deliverable 2 – Dataset 2 Notebook (Credit Risk)](https://colab.research.google.com/github/DalMLSociety/Supervised-Learning-Workshop/blob/main/deliverable/02_dataset2.ipynb)
   - 📗 [Deliverable 3 – Dataset 3 Notebook (Housing Prices)](https://colab.research.google.com/github/DalMLSociety/Supervised-Learning-Workshop/blob/main/deliverable/03_dataset3.ipynb)

3. Follow the instructions in each notebook:

   - Load and explore the data
   - Handle missing values and outliers
   - Clean and preprocess features
   - Train machine learning models
   - Evaluate performance
   - Create visualizations
   - Briefly summarize your findings

4. Save your figures into the correct `content/figures/` subfolder **inside Colab**.

   > ⚠️ Important: If your Colab session idles too long, it may restart. \
   >  You will need to re-upload your dataset and re-run your notebook before saving figures again.

The notebooks provide structure and guidance but leave the implementation up to you. \
This is intentional - you'll learn more by working through the problems yourself.

### 📤 Submission!

Once you have completed your notebook:

1. **Download your notebook and figures** from Google Colab

   - `File → Download → Download .ipynb`
   - Download `figures_dataset#.zip` from the left side pane

2. **Upload your completed notebook here:**

   [Submission Form](https://airtable.com/appGZ1Cp7fr2YNekA/pagsuGiP3ZtSPovtP/form)

### 📣 Certification & Participation

To receive a **DalMLSociety Supervised Learning Certificate**, submit one of the three deliverable notebooks by:

      ⏰ November 23, 2025 @ 11:59 PM Atlantic Time

## 🌐⚡ **DalMLSociety & Feedback:**

If you have any questions or want to get involved, feel free to reach out to us at 📧 dmls@dal.ca.

### 👉 Stay Connected

- 💬 [Join the Discord Community](https://discord.gg/47Pyqyhnuu)
- 🧾 [Apply for DMLS Roles 2025–26](https://airtable.com/appbzvXorTGCwSsy9/pagtWdxjYq0FJOosY/form)
- 💼 [Follow us on LinkedIn](https://www.linkedin.com/company/dalmlsociety/?viewAsMember=true)
- 📸 [Follow us on Instagram](https://www.instagram.com/dalmlsociety)
- 🌍 [Visit our Website](http://dmls.dsu.dal.ca)

## 📌 **License**

This repository is licensed under the MIT License. Feel free to use and modify as needed.
