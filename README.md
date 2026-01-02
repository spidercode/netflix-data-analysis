# 🎬 Netflix Movies & TV Shows Data Analysis

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset to understand content trends, distribution, and patterns over time.

The workflow follows **industry-standard AI/Data Engineering practices**, where:
- Raw data is cleaned and processed once
- Cleaned data is reused for visualization and analysis
- Logic is separated across notebooks for clarity and reproducibility

---

## 🎯 Objectives
- Analyze Netflix content released since 2000
- Compare Movies vs TV Shows over time
- Identify trends in content growth
- Visualize insights using Python

---

## 📂 Project Structure
netflix-data-analysis/
│
├── data/
│ └── titles.csv
│ └── titles_final.csv
│
├── notebooks/
│ ├── 01_eda.ipynb
│ └── 02_visualization.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

## 🧪 Dataset
- **Source:** Kaggle – Netflix Movies and TV Shows
- **Format:** CSV
- **Description:** Metadata about Netflix movies and TV shows including release year, country, rating, duration, and type.

> **Note:**  
> The raw dataset should be placed in `data/`.

---

## 🔄 Workflow

### 1️⃣ Exploratory Data Analysis (`01_eda.ipynb`)
- Load raw dataset
- Inspect data structure and quality
- Handle missing values
- Perform data cleaning
- Create derived features (e.g., `IsMovie`)
- Save cleaned dataset as: data/titles_final.csv

### 2️⃣ Visualization & Insights (`02_visualization.ipynb`)
- Load cleaned dataset
- Generate visualizations:
- Movies vs TV Shows over time
- Content growth trends
- Distribution analysis
- Draw insights without modifying data

---

## 📊 Sample Insights
- Netflix content production increased significantly after 2015
- Movies consistently outnumber TV shows
- Strong growth trend in both content types since 2000

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code

---

## ▶️ How to Run the Project

1. Clone the repository:
 ```bash
 git clone <your-repo-url>
 cd netflix-data-analysis
 ```

2. Create and activate a virtual environment:
 ```bash
 python -m venv .venv
 .venv\Scripts\activate
 ```

3. Install dependencies:
 ```bash
 pip install -r requirements.txt
 ```

4. Run notebooks in order:
 - 01_eda.ipynb
 - 02_visualization.ipynb


## 🚀 Future Improvements

1. Feature engineering for ML models
2. Predict content type (Movie vs TV Show)
3. Recommendation system use-cases
4. Convert cleaning logic into reusable Python modules

## 👤 Author
### Hardik S
AI Engineering Enthusiast | Full stack .NET Developer transitioning to AI/ML