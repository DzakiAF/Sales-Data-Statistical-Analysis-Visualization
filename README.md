# 📊📈 **E-Commerce Product Sales Analysis with Statistical Inference**  

---

## 🧾 **Project Overview**

This project is an end-to-end **Exploratory Data Analysis (EDA)** and **Statistical Inference** of e-commerce product sales data. It covers data distribution analysis, normality testing, and hypothesis testing, alongside insightful visualizations.

---

## 🛠️ **Tools and Libraries Used**

- Python (Jupyter Notebook)
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scipy.stats`, `statsmodels`

---

## 🔍 **Key Analyses**

### 1️⃣ Exploratory Data Analysis (EDA)
- 🏆 Top 5 Most Sold Products  
- 📊 Sales Distribution by Category  
- 🔁 Most Returned Products by Category  
- 📈 Monthly Sales Trend  

### 2️⃣ Statistical Summary
- ⚖️ **Skewness & Kurtosis**  
- 📐 **Normality Tests** (Shapiro-Wilk, D’Agostino)  
- 🔍 Visual Inspection (Histogram, Q-Q Plot)

### 3️⃣ Inferential Statistics
- 🧪 **Two-Sample Independent T-Test**  
- 🧪 **Mann-Whitney U Test**  
- ✅ Testing if price differences between regions (e.g. Jabodetabek vs non-Jabodetabek) are statistically significant

---

## 📊 **Visualizations**

- 📦 Bar Plot: Top 5 Products Sold  
- 🧁 Pie Chart: Sales by Category  
- 📉 Bar Chart: Most Returned Products  
- 📆 Line Chart: Sales Trend Over Time  
- 📈 Histogram & Q-Q Plot for Distribution Check  

---

## 💡 **Insights**

- Categories with high return rates may indicate customer dissatisfaction or mismatched expectations  
- The dataset shows **right skewness** and **positive kurtosis** → non-normal distribution  
- Some variables **do not pass** normality test → non-parametric testing applied  
- **Significant price differences** found across region groups  

---

## 🧠 **What I Learned**

- Importance of checking data distribution before statistical testing  
- How to choose between parametric vs non-parametric tests  
- Combining visual insights with statistical rigor  

---

## 🚀 **How to Run the Project**

```bash
git clone https://github.com/YourUsername/your-repo-name.git
cd your-repo-name
jupyter notebook h8dsft_Milestone1_dzaki_ahmad_fardian.ipynb
