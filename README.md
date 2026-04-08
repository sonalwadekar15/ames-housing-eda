# 🏠 Ames Housing — Exploratory Data Analysis

A beginner-to-intermediate EDA project built to develop hands-on understanding of core data analytics concepts using the Ames Housing dataset.

---

## 📌 Objective

To perform a thorough Exploratory Data Analysis (EDA) on the Ames Housing dataset, covering data understanding, visualisation, preprocessing, and feature engineering — and to document insights that could support a house price prediction model.

---

## 📂 Project Structure

```
ames-housing-eda/
│
├── data/
│   └── AmesHousing.csv
├── EDA_Ames_Housing.ipynb
└── README.md
```

---

## 📊 Dataset

- **Source:** [Ames Housing Dataset — Kaggle](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- **Records:** 2,930 rows
- **Features:** 82 columns (numeric + categorical)
- **Target Variable:** `SalePrice`

---

## 🗂️ EDA Workflow

### Day 1 — Introduction to EDA
- Classification of data types
- Reading data from CSV
- Understanding variables (shape, dtypes, head)
- Descriptive statistics
- Measures of central tendency (mean, median, mode)
- Distribution of data
- Measures of dispersion (range, variance, std dev, IQR)

### Day 2 — Analysis Through Visualisation
- Understanding the business problem
- Data type conversion
- Bivariate analysis (Quantitative–Quantitative, Quantitative–Categorical, Categorical–Categorical)
- Missing value treatment
- Outlier treatment

### Day 3 — Data Preprocessing
- Z-score
- Interquartile Range (IQR)
- Feature engineering basics

### Day 4 — Feature Engineering
- Handling non-numeric data (encoding)
- Feature scaling
- Data transformation

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualisation |
| Seaborn | Statistical visualisation |
| Scikit-learn | Preprocessing & scaling |
| Jupyter Notebook | Interactive development |

---

## 💡 Key Insights

- 27 columns had missing values; high-missing columns (Pool QC, Alley, Fence) were dropped; others filled using median/mode.
- Gr Liv Area vs SalePrice showed a moderate-strong positive correlation of 0.71 — larger homes command higher prices.
- Most expensive neighbourhoods: NridgHt, NoRidge, StoneBr | Cheapest: BrDale, NPkVill.
- Outliers detected and treated using IQR method and Z-score; capping and dropping applied as appropriate.
- New features created: House Age, Total Bath, Total SF — reduced redundancy and improved interpretability.
- Log transformation on SalePrice and Yeo-Johnson on Gr Liv Area significantly reduced skewness.
- Dataset is now clean and ready for machine learning modelling.

---

## 🚀 How to Run

1. Clone this repository
2. Place `AmesHousing.csv` inside the `data/` folder
3. Open `EDA_Ames_Housing.ipynb` in Jupyter Notebook
4. Run cells sequentially

---

## 👩‍💻 Author

**Sonal**  
Aspiring Data Analyst | PGP in Data Science & GenAI — Great Learning  
LinkedIn : www.linkedin.com/in/sonalwadekar
GitHub : https://github.com/sonalwadekar15
