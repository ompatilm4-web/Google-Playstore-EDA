<div align="center">

<!-- Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4285F4,50:34A853,100:EA4335&height=200&section=header&text=Google%20Play%20Store%20EDA&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Exploratory%20Data%20Analysis%20%7C%20Data%20Science%20Project&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/ompatilm4-web/Google-Playstore-EDA?style=flat-square&color=34A853&label=Repo%20Size"/>
  <img src="https://img.shields.io/github/last-commit/ompatilm4-web/Google-Playstore-EDA?style=flat-square&color=4285F4&label=Last%20Commit"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square"/>
</p>

<!-- Animated Typing -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=4285F4&center=true&vCenter=true&width=600&lines=Uncovering+Insights+from+Google+Play+Store+Data;Analyzing+3M%2B+App+Records;Data+Cleaning+%7C+EDA+%7C+Visualization;Ratings+%7C+Categories+%7C+Pricing+Trends" alt="Typing SVG" />
</a>

</div>

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [📂 Repository Structure](#-repository-structure)
- [📊 Dataset Description](#-dataset-description)
- [🔍 Key Analysis Areas](#-key-analysis-areas)
- [📈 Key Insights](#-key-insights)
- [🛠️ Tech Stack](#️-tech-stack)
- [⚙️ Setup & Installation](#️-setup--installation)
- [🚀 How to Run](#-how-to-run)
- [📋 Results Summary](#-results-summary)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👤 Author](#-author)

---

## 📖 Project Overview

<p align="justify">
This project performs a comprehensive <strong>Exploratory Data Analysis (EDA)</strong> on the <strong>Google Play Store</strong> dataset. The goal is to uncover hidden patterns, trends, and actionable insights from millions of app records — spanning categories, ratings, pricing, installs, and user reviews. Through rigorous data cleaning and visualization, this analysis provides a data-driven understanding of the Android app ecosystem.
</p>

> 💡 **Why this matters?** The Google Play Store hosts over 3 million apps. Understanding what drives ratings, downloads, and user satisfaction can help developers and businesses make smarter product decisions.

---

## 🎯 Objectives

- ✅ Clean and preprocess raw Play Store data (handle nulls, duplicates, type errors)
- ✅ Analyze the distribution of apps across categories
- ✅ Explore the relationship between ratings, reviews, installs, and pricing
- ✅ Identify top-performing categories and app types (Free vs. Paid)
- ✅ Perform sentiment analysis on user reviews
- ✅ Derive actionable business insights through rich visualizations

---

## 📂 Repository Structure

```
Google-Playstore-EDA/
│
├── 📁 Data/
│   ├── googleplaystore.csv          # Main dataset (app-level data)
│   └── googleplaystore_user_reviews.csv  # User reviews dataset
│
├── 📁 Notebook/
│   └── Google_Playstore_EDA.ipynb   # Main analysis notebook
│
├── 📄 Report.md                     # Analysis report
├── 📄 requirements.txt              # Python dependencies
└── 📄 README.md                     # Project documentation
```

---

## 📊 Dataset Description

| Feature | Description |
|---|---|
| `App` | Name of the application |
| `Category` | App category (e.g., GAME, TOOLS, EDUCATION) |
| `Rating` | Average user rating (out of 5.0) |
| `Reviews` | Number of user reviews |
| `Size` | Size of the app |
| `Installs` | Number of installs (bucketed) |
| `Type` | Free or Paid |
| `Price` | Price of the app in USD |
| `Content Rating` | Target audience (e.g., Everyone, Teen, Mature 17+) |
| `Genres` | App genre(s) |
| `Last Updated` | Date the app was last updated |
| `Current Ver` | Current version of the app |
| `Android Ver` | Minimum Android version required |

---

## 🔍 Key Analysis Areas

<table>
<tr>
<td width="50%">

### 🧹 Data Cleaning
- Handling missing values in `Rating`, `Size`, `Content Rating`
- Fixing inconsistent data types (Reviews, Installs, Price)
- Removing duplicate entries
- Standardizing size units (MB/KB)

</td>
<td width="50%">

### 📊 Univariate Analysis
- Rating distribution across all apps
- Category-wise app count
- App type distribution (Free vs. Paid)
- Content rating breakdown

</td>
</tr>
<tr>
<td width="50%">

### 🔗 Bivariate Analysis
- Rating vs. Number of Reviews
- Installs vs. Category
- Price vs. Rating correlation
- Size vs. Installs relationship

</td>
<td width="50%">

### 💬 Sentiment Analysis
- Positive, Negative, Neutral review classification
- Sentiment polarity by category
- Subjectivity vs. Polarity scatter analysis

</td>
</tr>
</table>

---

## 📈 Key Insights

> 🔎 Here are some of the most impactful findings from the analysis:

- 📱 **Family** and **Game** categories dominate the Play Store in terms of app count
- ⭐ Most apps maintain a rating between **4.0 – 4.5**, suggesting a healthy ecosystem
- 💰 **Free apps** significantly outperform **Paid apps** in total installs
- 🏆 **Communication** and **Social** apps have the highest median install counts
- 📉 Very high or very low prices are negatively correlated with ratings
- 💬 User reviews are predominantly **positive** in sentiment across most categories
- 🔄 Apps that receive **frequent updates** tend to have **higher ratings**

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
</p>

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation & analysis |
| `numpy` | Numerical computing |
| `matplotlib` | Static visualizations |
| `seaborn` | Statistical data visualization |
| `plotly` | Interactive charts |
| `textblob` | Sentiment analysis on user reviews |
| `warnings` | Suppressing runtime warnings |

---

## ⚙️ Setup & Installation

### Prerequisites

- Python 3.10 or higher
- pip or conda package manager
- Jupyter Notebook / JupyterLab

### Clone the Repository

```bash
git clone https://github.com/ompatilm4-web/Google-Playstore-EDA.git
cd Google-Playstore-EDA
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

```bash
# Launch Jupyter Notebook
jupyter notebook

# Open the analysis notebook
# Navigate to: Notebook/Google_Playstore_EDA.ipynb
# Run All Cells: Kernel → Restart & Run All
```

> ⚠️ **Note:** Make sure the dataset files are present in the `Data/` directory before running the notebook.

---

## 📋 Results Summary

| Analysis | Finding |
|---|---|
| Top Category | Family (most apps) |
| Avg. Rating | ~4.17 / 5.0 |
| Free vs. Paid | ~92% apps are Free |
| Best Rated Category | Health & Fitness |
| Most Installed Category | Communication |
| Review Sentiment | ~63% Positive |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork** the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

<div align="center">

**Om Patil**

[![GitHub](https://img.shields.io/badge/GitHub-ompatilm4--web-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ompatilm4-web)

*If you found this project helpful, please consider giving it a ⭐ star!*

</div>

---

<!-- Animated Footer -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:EA4335,50:FBBC05,100:34A853&height=120&section=footer&animation=fadeIn" width="100%"/>
</div>