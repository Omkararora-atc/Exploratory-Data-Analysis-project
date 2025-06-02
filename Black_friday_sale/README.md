# 🛍️ Black Friday Sale EDA
**Exploring Consumer Behavior | Data-Driven Insights | Visual Storytelling**

<div align="center">
  <img src="https://img.shields.io/badge/Pandas-Data%20Science-blue?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge&logo=matplotlib" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Graphics-blueviolet?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-yellow?style=for-the-badge&logo=jupyter" />
</div>

---

## 🏬 Project Overview

**Black Friday Sale EDA** dives into a massive retail dataset to uncover what drives consumer purchases during one of the largest shopping events of the year. Through intuitive data cleaning, smart visual analytics, and insightful storytelling, this project offers a panoramic view of user demographics, product preferences, and spending trends.

---

## 📂 Folder Contents

| File                    | Description                                               |
|-------------------------|-----------------------------------------------------------|
| `Analysis.ipynb`        | 📓 Jupyter Notebook with step-by-step EDA & visuals       |
| `BlackFriday.csv`       | 🗂️ Raw Black Friday purchase dataset                      |

---

## 📋 Dataset Snapshots

The dataset includes **537,577** transactions with these features:

| Feature                  | Description                        |
|--------------------------|------------------------------------|
| `User_ID`                | Unique user identifier             |
| `Product_ID`             | Unique product identifier          |
| `Gender`                 | Gender of user (`M`/`F`)           |
| `Age`                    | Age group (`0-17`, `18-25`, etc.)  |
| `Occupation`             | Occupation code                    |
| `City_Category`          | City type (`A`, `B`, `C`)          |
| `Stay_In_Current_City_Years` | Years in current city           |
| `Marital_Status`         | Marital status (`0`, `1`)          |
| `Product_Category_1`     | Main product category              |
| `Purchase`               | Purchase amount (INR)              |

*Note: Columns with excessive missing data were dropped for clarity.*

---

## 🌟 Highlights & Insights

- **Data Cleaning:**  
  - Reduced noise by removing columns with heavy missing data.
  - Verified completeness of core features.

- **Demographics At a Glance:**  
  - 👥 **5,891 unique users** | 🎁 **3,623 unique products**
  - **Age Groups:** `0-17`, `18-25`, `26-35`, `36-45`, `46-50`, `51-55`, `55+`

- **Gender Distribution:**  
  ![Pie chart of gender distribution](#)
  - 👨 Male: **405,380** (75.4%)  
  - 👩 Female: **132,197** (24.6%)

- **Shopping Trends:**  
  - Highest purchases from age group **26-35**
  - City type and occupation significantly influence spending
  - Product Category 1 dominates sales

- **Visual Storytelling:**  
  - Lively pie charts, barplots, and heatmaps
  - All code and plots are beginner-friendly & reproducible

---

## 🚀 Quickstart

1. **Clone this repo** and open the [`Analysis.ipynb`](Analysis.ipynb) notebook.
2. **Run cells** for guided EDA, visualization, and actionable insights.
3. **Tweak or extend**: Add your own questions or visualizations!

```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv('BlackFriday.csv')
df.drop(['Product_Category_2', 'Product_Category_3'], axis=1, inplace=True)
df['Gender'].value_counts().plot.pie(autopct='%1.1f%%', startangle=90, colors=['#FF9999', '#66B3FF'])
plt.title('Gender Distribution')
plt.show()
```

---

## 📊 Sample Visuals

<p align="center">
  <img src="https://raw.githubusercontent.com/Omkararora-atc/Exploratory-Data-Analysis-project/main/assets/gender_dist.png" alt="Gender Distribution Pie Chart" width="320"/>
  <img src="https://raw.githubusercontent.com/Omkararora-atc/Exploratory-Data-Analysis-project/main/assets/age_purchases.png" alt="Purchases by Age Group" width="320"/>
</p>
<sub>*Sample output images - generate by running the notebook!*</sub>

---

## 🧠 Key Takeaways

- **Male shoppers** dominate the Black Friday dataset.
- **Young adults (26-35 years)** are the biggest spenders.
- **Urban cities** and certain occupations drive higher purchase volumes.
- The dataset is **clean, large, and ready** for deep-dive analytics or machine learning!

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📚 Dataset Source

> **Kaggle Black Friday Competition:**  
> [Black Friday Dataset](https://www.kaggle.com/datasets/mehdidag/black-friday)

---

## 🙌 Author

- **Omkar Arora**  
  [GitHub Profile](https://github.com/Omkararora-atc)

---

## 📜 License

This project is for educational and research purposes only.

---

<div align="center">

✨ **Jump in, explore, and uncover the story behind the sales!** ✨

</div>