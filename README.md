# 🏎️ Formula 1 Data Analysis

This repository explores Formula 1 racing data through three main notebooks. **Please check the files with .ipynb extension too see the work**  
The project covers **circuit overtaking analysis**, **pit stop performance evaluation**, and **predictive modeling**.  

---

## 📂 Contents

### 1️⃣ Circuit Analysis  
**`1-circuit_analysis.ipynb`**  
- Analyzes Formula 1 circuits to determine where drivers experience the **least or most position changes** between start and finish.  
- Focuses on post-2011 races with reliable datasets.  
- Identifies circuits like **Monaco** and **Albert Park** as hardest to overtake, while others show higher variability.  
- Includes visualization of circuits ranked by average overtaking difficulty.  

### 2️⃣ Pit Stop Analysis  
**`2-Pitstop Analysis.ipynb`**  
- Investigates the impact of **pit stop performance** on race results.  
- Filters post-2011 races where pit stop data is available.  
- Examines correlations between stop duration, number of stops, and final race position.  

### 3️⃣ Predictive Modeling  
**`3-model.ipynb`**  
- Prepares cleaned race datasets for **machine learning models**.  
- Focuses on completed races (status = finished).  
- Builds predictive approaches to estimate race outcomes using historical race and pit stop data.  

---

## 🚀 Skills Demonstrated
- **Data Wrangling & Cleaning** (pandas, numpy)  
- **Exploratory Data Analysis (EDA)** with matplotlib/seaborn  
- **Sports Analytics** applied to Formula 1 data  
- **Data Visualization** of race performance metrics  
- **Predictive Modeling** for outcome estimation  

---

## ⚙️ Requirements
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
