# FlyRank Machine Learning Internship

> Hands-on Machine Learning, Search Intelligence, and SEO Analytics using real-world anonymized search performance data.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![DuckDB](https://img.shields.io/badge/DuckDB-SQL-yellow)
![Status](https://img.shields.io/badge/Internship-In%20Progress-success)

---

# Overview

This repository contains my work throughout the **FlyRank Machine Learning Internship**.

The internship focuses on applying machine learning and data analysis techniques to real-world SEO and search performance datasets while following responsible ML practices.

The project emphasizes:

- Problem framing before modeling
- Exploratory Data Analysis (EDA)
- Feature engineering
- Honest model evaluation
- Search intelligence
- Large-scale analytics using DuckDB
- Decision-support rather than prediction claims

---

# Internship Progress

## 01— Search Data Discovery

### Objectives

- Explore the anonymized SEO dataset
- Understand search performance metrics
- Test hypotheses using data
- Learn how to make evidence-based observations

### Completed

- Loaded the starter dataset
- Investigated relationships between impressions, CTR, and ranking
- Explored content performance across multiple dimensions
- Practiced careful interpretation of results

---

## 02 — First Machine Learning Model

### Objectives

- Build an interpretable baseline
- Compare rule-based methods with ML models

### Completed

- Implemented a baseline scoring rule
- Built Decision Tree classifiers
- Compared Precision@20 and Precision@50
- Improved model performance by tuning tree depth
- Learned about data leakage

---

## 03 — Working with the Full Warehouse

### Objectives

- Work with production-scale datasets
- Learn SQL feature engineering
- Use DuckDB with Hugging Face datasets

### Completed

- Connected to FlyRank's warehouse
- Loaded large Parquet datasets
- Used DuckDB SQL queries
- Built feature engineering pipeline
- Added query-level signals
- Trained Random Forest classifier
- Generated evaluation reports

---

## 01 — Research Question & Project Framing
### Objectives

Frame a machine learning problem before building a model.

### Selected Lane

**Content Refresh Prioritization**

Research Question:

> Which content pages should an SEO editor review first for a possible content refresh?

The project focuses on supporting SEO editors by ranking pages based on historical search-performance signals.

Instead of predicting Google's algorithm, the goal is to provide a decision-support system that helps prioritize content review.

---

# Skills Learned

## Machine Learning

- Classification
- Decision Trees
- Random Forest
- Feature Engineering
- Model Evaluation
- Precision@K
- Train/Test Splits
- Data Leakage Detection

---

## Data Analysis

- Exploratory Data Analysis
- Correlation Analysis
- Ranking Problems
- Signal Validation
- Business Problem Framing

---

## SQL & Data Engineering

- DuckDB
- SQL Aggregations
- Feature Construction
- Large Dataset Processing
- Hugging Face Datasets

---

## Python Libraries

- Pandas
- NumPy
- Scikit-learn
- DuckDB
- Matplotlib

---

# Repository Structure

```
.
├── data/
├── docs/
├── notebooks/
│   ├── 01_first_discovery.ipynb
│   ├── 02_your_first_readable_model.ipynb
│   └── 03_working_with_the_full_release.ipynb
│
├── outputs/
├── scripts/
├── work/
│   └── notebooks/
│       └── w01_research_question.ipynb
│
└── README.md
```

---

# Current Capstone Direction

**Project Title**

Content Refresh Prioritization using Historical Search Signals

### Decision

Help SEO editors decide which pages should be reviewed first.

### Output

A ranked list of content pages.

### Action

Review and update selected content.

### Success Metric

Precision@K

### Why Machine Learning?

Machine learning can combine multiple historical search signals that are difficult to capture with a single rule, helping prioritize content review more effectively.

---

# Responsible AI & Data Usage

This repository uses the anonymized datasets provided by FlyRank for educational purposes.

No private client information is included.

Results should be interpreted as:

- Observational
- Directional
- Decision-support

This project does **not** claim to predict Google's ranking algorithm or guarantee future search performance.

---

# Technologies

- Python
- SQL
- DuckDB
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- Hugging Face Datasets
- Git
- GitHub

---

# Internship Status

| Phase | Status |
|--------|--------|
| 01 – Data Discovery | ✅ Completed |
| 02 – Readable Models | ✅ Completed |
| 03 – Full Warehouse | ✅ Completed |
| 04 – Research Framing | ✅ Completed |
| Capstone Project | 🚧 In Progress |

---

# Author

**Seif Shady**

Computer Science Graduate  
Faculty of Computers and Artificial Intelligence  
Cairo University

GitHub

https://github.com/seifeldinshadyy

---

# Acknowledgements

Thanks to **FlyRank** for providing the internship program, anonymized datasets, and practical machine learning exercises focused on search intelligence and responsible AI.
