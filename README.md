# 🇺🇸 Market Analysis & Customer Income Prediction | Power BI

---

## 📌 Executive Summary
This project delivers a data-driven solution for a retail clothing chain facing declining sales.  
By combining internal customer and purchase data with U.S. Census income statistics, a **linear regression model** was built to estimate customer income potential and design a **targeted marketing strategy** across mass, mid-range, and premium product segments.

The focus of the analysis is not only on visualization, but on **business interpretation and decision-making**.

---

## 💼 Business Problem
The company lacks direct information about customer income, making personalized marketing inefficient.  
At the same time, sales performance is declining and marketing efforts must become more targeted.

The business wants to promote three products:
- **Mass Market:** Shirt ($25)
- **Mid-Range:** Sweater ($100)
- **Premium:** Leather Bag ($1000)

---

## 🧠 Analytical Approach
1. **Data Integration:** Combined customer and purchase data with U.S. Census income data at the state level.
2. **Predictive Modeling:** Applied linear regression to model the relationship between average income and customer sales.
3. **Income Prediction:** Estimated individual customer income based on purchasing behavior.
4. **Segmentation:** Grouped customers into income ranges to support targeted marketing decisions.
5. **Strategy Design:** Mapped customer segments to optimal products and regions.

---

## 🛠 Tech Stack & Methods
- **Power BI**
- **Power Query** for data cleaning and transformation
- **DAX** for calculated columns and measures
- **Linear Regression** implemented manually (slope *m* and intercept *b*)

### Regression Results
- **Model:** y = mx + b  
- **Correlation (R):** 0.88  
- **R²:** 0.78  

These results indicate a strong positive relationship between income and purchasing behavior.

---

## 📊 Key Insights

- Most customers are located in **California, Florida, and Texas**, primarily within **Low** and **Mid Income** segments.
- The states with the **highest predicted income** are **District of Columbia, Maryland, and Massachusetts**, each exceeding an average of **$115,000**.
- Higher-income states demonstrate **stronger purchasing activity**, confirmed by the regression model.
- The core customer demographic falls within the **30–50 age range**, representing a stable middle-market audience.
- While premium customers are fewer in number, they represent **high-margin opportunities**.

---

## 🚀 Marketing Strategy

| Segment | Key States | Product | Strategy |
|------|-----------|--------|---------|
| **Premium** | DC, Maryland, Massachusetts | Leather Bag ($1000) | Focus on exclusivity and high-margin campaigns |
| **Mid-Market** | New York, Illinois, Colorado | Sweater ($100) | Cross-selling and seasonal promotions |
| **Mass Market** | California, Florida, Texas | Shirt ($25) | Volume-based campaigns and broad accessibility |

---

## 📊 Dashboard Visualizations

### 1. Average Income by State
![Average Income by State](https://github.com/Amirski77/Market-Income-analysis-PowerBI/blob/main/avereage_income.png)

*Figure 1. Average household income by U.S. state.  
High-income regions highlight strong potential for premium product targeting.*

---

### 2. Analysis Summary & Marketing Overview
![Report Summary](https://github.com/Amirski77/Market-Income-analysis-PowerBI/blob/main/report_summary_slide.png)

*Figure 2. Executive summary slide answering key business questions and outlining the marketing strategy.*

---

### 3. Customer Distribution & Predicted Income Dashboard
![Dashboard Summary](https://github.com/Amirski77/Market-Income-analysis-PowerBI/blob/main/dashboard_summary..png)

*Figure 3. Customer distribution by state and income segment, combined with predicted income levels.*

---

### 4. Customer Demographics & Income Segmentation
![Customer Demographics](https://github.com/Amirski77/Market-Income-analysis-PowerBI/blob/main/customer_demographics.png)

*Figure 4. Customer age distribution and income range segmentation.  
The majority of customers fall within the 30–50 age range and Low–Mid income groups.*

---

### 5. Relationship Between Average Income and Sales
![Regression Analysis](https://github.com/Amirski77/Market-Income-analysis-PowerBI/blob/main/regression_analysis.png)

*Figure 5. Linear regression model showing a strong positive relationship between income and sales  
(R = 0.88, R² = 0.78).*

---

## 📂 Project Files
- (https://github.com/Amirski77/Market-Income-analysis-PowerBI/blob/main/Project%204%20Rashidov%20Amir.pbix) — Full interactive Power BI dashboard  
- `images/` — Dashboard screenshots used in this README  

---

## 👤 Author
**Amir Rashidov**  
Data Analyst | Power BI | Business Analytics  

📫 Open to internships and junior analyst roles  
🔗 LinkedIn:www.linkedin.com/in/amir-r-673789203

