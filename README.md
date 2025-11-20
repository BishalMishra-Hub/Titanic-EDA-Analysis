<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0072ff,100:00c6ff&height=200&section=header&text=Titanic%20EDA%20Project&fontSize=45&fontColor=ffffff&animation=fadeIn" />

### 📊 **Exploratory Data Analysis on the Titanic Dataset**
#### *Understanding human behavior, survival patterns, and socio-economic influence through data.*

---

<img src="https://img.shields.io/badge/Domain-Data%20Analysis-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Tech-Python-yellow?style=for-the-badge" />
<img src="https://img.shields.io/badge/Notebook-Google%20Colab-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
<img src="https://img.shields.io/badge/Level-Intermediate-blueviolet?style=for-the-badge" />

</div>

---

# 📌 Table of Contents
- [📘 Project Overview](#-project-overview)
- [📂 Dataset Details](#-dataset-details)
- [📈 Analysis Workflow](#-analysis-workflow)
- [🔍 Key Insights](#-key-insights)
- [📊 Visual Highlights](#-visual-highlights)
- [🧹 Data Cleaning](#-data-cleaning)
- [📁 Repository Structure](#-repository-structure)
- [🛠 Tech Stack](#-tech-stack)
- [👨‍💻 About Me](#-about-me)

---

# 📘 Project Overview

This project is my deep-dive into the **Titanic dataset**, one of the most iconic datasets in data science.

> 📌 *“My goal was to explore, visualize, and extract meaningful insights that reveal the story behind passenger survival.”*

This project strengthened my skills in:
- Data cleaning  
- Exploratory analysis  
- Data visualization  
- Understanding feature relationships  
- Presenting insights clearly  

---

# 📂 Dataset Details

| Feature | Description |
|--------|-------------|
| Survived | 0 = Died, 1 = Survived |
| Pclass | Passenger class |
| Sex | Gender |
| Age | Age of passenger |
| Fare | Ticket fare paid |
| SibSp | Siblings/spouses aboard |
| Parch | Parents/children aboard |
| Embarked | Port of boarding |
| Cabin | Cabin number (mostly missing) |

Dataset Size: **891 rows**

---

# 📈 Analysis Workflow

<details>
<summary><strong>1️⃣ Loading & Inspecting Data</strong></summary>

- Loaded data in Pandas  
- Checked dataset structure  
- Verified missing values  
- Looked at duplicates  

</details>

<details>
<summary><strong>2️⃣ Univariate Analysis</strong></summary>

- Age distribution  
- Fare distribution  
- Passenger class breakdown  
- Gender count  
- Survival count  

</details>

<details>
<summary><strong>3️⃣ Bivariate Analysis</strong></summary>

- Survival vs Gender  
- Survival vs Pclass  
- Age vs Survival  
- Fare vs Survival  

</details>

<details>
<summary><strong>4️⃣ Multivariate Analysis</strong></summary>

- Correlation matrix  
- Heatmap  
- Pairplot  

</details>

<details>
<summary><strong>5️⃣ Data Cleaning</strong></summary>

- Filled missing Age with median  
- Filled missing Embarked with mode  
- Dropped Cabin (too many nulls)  

</details>

---

# 🔍 Key Insights

### 🌟 Women had a much higher survival rate.  
### 🌟 1st class passengers survived the most.  
### 🌟 Higher fare meant higher survival chances.  
### 🌟 Younger passengers survived more.  
### 🌟 Cabin feature was unusable — too many missing values.  
### 🌟 Fare & Pclass showed strong negative correlation.  

These findings reveal clear socio-economic patterns on the Titanic.

---

# 📊 Visual Highlights

✔ Age and Fare distributions  
✔ Gender-based survival comparison  
✔ Class-wise survival rates  
✔ Correlation heatmap  
✔ Multi-feature pairplot  

---

# 🧹 Data Cleaning

Steps I performed:
- Replaced missing Age with median  
- Replaced missing Embarked with mode  
- Dropped Cabin due to 687 null values  
- Rechecked dataset consistency  

This ensured a clean dataset for analysis.

---

# 📁 Repository Structure

Titanic-EDA-Analysis/
│── task5_train_EDA.ipynb
│── datasets_11657_16098_train.csv
│── Titanic_EDA_Report.pdf
│── README.md

---


---

# 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Data analysis |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Static plots |
| **Seaborn** | Statistical plots |
| **Google Colab** | Notebook environment |

---

# 👨‍💻 About Me

**Bishal Kumar Mishra**  
*Aspiring Data Analyst | Data Engineer | ML Enthusiast*

I enjoy exploring datasets, uncovering insights, and turning numbers into meaningful stories.

⭐ If you like this project, please consider starring the repo! ⭐

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=150&section=footer" />

</div>


