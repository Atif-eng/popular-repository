# 🖥️ The Open Source Matrix: GitHub Repo Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Library](https://img.shields.io/badge/Library-WordCloud-orange?style=for-the-badge)
![Insight](https://img.shields.io/badge/Insight-Python_Dominance-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview
**"Decoding the DNA of Open Source."**

This project performs a deep-dive analysis of the **Top 500 GitHub Repositories** to understand what makes a project go viral. We investigate the relationship between **Stars, Forks, and Issues**, and identify which programming languages rule the ecosystem.

Using **Data Visualization** and **Machine Learning**, we predict a repository's "Star Power" based on its engagement metrics.

**Author:** Muhammad Atif

## 📂 Dataset
The analysis covers the 500 most popular repositories on GitHub.
- **Key Metrics:** `Stars`, `Forks`, `Open Issues`.
- **Categorical Data:** `Language` (e.g., Python, JavaScript), `Topics` (Tags).
- **Target Variable:** **Stars** (Predicting popularity).

## 🛠 Tech Stack
- **Language:** Python
- **Data Engineering:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`, `wordcloud`
- **Machine Learning:** `scikit-learn` (Random Forest Regressor)

## 📊 Methodology: The "Viral Score"

### 1. The Language Wars ⚔️
We visualized the distribution of languages across the top 500 repos.
- **Winner:** **Python** dominates the list, driven heavily by AI/ML libraries and educational resources.
- **Runner Up:** **JavaScript/TypeScript**, powering the web development ecosystem.

### 2. The "Resource" Phenomenon 📚
Our analysis revealed a unique trend:
- **Software Repos:** Have high Forks (people using the code).
- **Resource Repos:** (e.g., *free-programming-books*) Have massive Stars but fewer Forks.
- **Insight:** Developers use GitHub as a **Library** (reading) just as much as a **Workshop** (coding).

### 3. Star Prediction Model 🌟
We trained a **Random Forest Regressor** to predict how many Stars a repo *should* have based on its Forks and Issues.
- **R² Score:** High accuracy, proving that "Forks" are the strongest predictor of "Stars" (Usage leads to Appreciation).

## 🔍 Key Visuals

### ☁️ Topic Word Cloud

A visual representation of the most common tags. Keywords like `learning`, `awesome-list`, and `interview` appear frequently, highlighting the demand for educational content.

### 📈 Feature Importance
The Machine Learning model identified the key drivers of popularity:
1.  **Forks** (The #1 Factor)
2.  **Open Issues** (Community Engagement)
3.  **Language Popularity**

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/github-repo-analysis.git](https://github.com/your-username/github-repo-analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn wordcloud
    ```
3.  **Run the Notebook:**
    Open `top-github-rpositories-analysis.ipynb` to see the visualizations.

## 🤝 Contributing
Want to analyze the "Impact of Readme Length" on Stars? Feel free to fork and add that feature!

---
_Created by Muhammad Atif_
