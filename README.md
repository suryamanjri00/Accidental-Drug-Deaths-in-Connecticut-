# 📊 Accidental Drug Deaths in Connecticut (2012–2022) – Statistical Analysis

![Project Banner](https://img.shields.io/badge/Status-In%20Progress-blue)  
*An exploratory data analysis project investigating accidental drug-related deaths in Connecticut over 11 years.*

---

## 🧠 Project Overview

This project analyzes **Accidental Drug-Related Deaths in Connecticut (2012–2022)** using Python. It aims to uncover trends in drug usage, demographic patterns, and geographic distributions through statistical analysis and visualizations.

**Key Questions Explored:**
- What are the most commonly involved drugs in accidental deaths?
- How do drug-related deaths vary by age, gender, and race?
- Are there notable time-based or location-based patterns?
- Which drug combinations are most frequent?

---

## 📁 Dataset

- **Source**: [CT Data Portal](https://data.ct.gov)
- **File Name**: `Accidental_Drug_Related_Deaths_2012-2022.csv`
- **Rows**: 10,654  
- **Columns**: 48 (demographics, cause of death, drug mentions, geolocation)

---

## 📌 Features Analyzed

- **Demographics**: Age, Sex, Race, Ethnicity
- **Location**: City, County, State of Injury, Death, and Residence
- **Drugs**: Heroin, Cocaine, Fentanyl, Benzodiazepines, etc. (22 substances)
- **Date-Based Trends**: Yearly/Monthly fatalities

---

## ⚙️ Tools Used

- **Python 3.11**
- `pandas`, `numpy`: Data cleaning & preprocessing  
- `matplotlib`, `seaborn`: Data visualization  
- `scipy.stats`: Statistical summaries  
- `openpyxl`: Excel output
- `jupyter notebook`: Development environment

---

## 📈 Analysis Highlights

- Cleaned and converted drug-related columns into binary numeric format.
- Explored age distribution: Mean = 44, Median = 43, Mode = 36.
- Visualized gender and race distributions using pie and bar charts.
- Built a **log-scaled bar chart** showing frequency of each drug mention.
- Conducted statistical summaries and hypothesis insight based on age and drug type combinations.

---

## 📊 Sample Visualizations

- 📌 Distribution of Age  
- 📌 Deaths by Gender (Pie Chart)  
- 📌 Race-wise Fatality Count  
- 📌 Drug Mentions (Log Scaled Horizontal Bar Chart)  
- 📌 Death Trends Over Time (Line Chart)

All charts are saved as `.png` files under the project root for easy reuse.

---

## 🧼 Data Cleaning

- Replaced blanks in numeric columns with `0`
- Replaced blanks in object columns with `"Not given"`
- Removed duplicates
- Converted 22 drug columns to binary (1 for "Y", 0 otherwise)

---

## 🚀 Getting Started

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scipy openpyxl

# Run the notebook
jupyter notebook
```

Make sure the dataset `Accidental_Drug_Related_Deaths_2012-2022.csv` is in the project folder.

---

## 📌 Folder Structure

```
├── Accidental_Drug_Related_Deaths_2012-2022.csv
├── main_notebook.ipynb
├── first_10_rows_output.xlsx
├── /visuals
│   ├── Distribution_of_Age.png
│   ├── Individuals_by_Race.png
│   ├── Drugs_Analysis_Graph.png
│   └── ...
└── README.md
```

---

## 📚 References

- [CT Open Data Portal – Drug Deaths](https://data.ct.gov/Health-and-Human-Services/Accidental-Drug-Related-Deaths-2012-2022/rybz-4hxf)
- [CDC: Opioid Overdose](https://www.cdc.gov/drugoverdose/index.html)

---

## 👩‍💻 Author

**Your Name**  
Data Science Student | Python Enthusiast  
📧 your.email@example.com  
📍 Connecticut, USA
