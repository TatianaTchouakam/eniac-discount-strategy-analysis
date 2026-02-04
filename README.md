# ⚡ ENIAC — Discount Strategy Analysis  
## Business & Data Analysis (Python | Google Colab)

---

## 🎯 Business Context
ENIAC is a **premium electronics retailer** facing a strategic debate:

- **Marketing** aims to increase sales through discounts  
- **Investors** aim to protect revenue, margins, and brand value  

The objective of this project is to evaluate whether **discounts are an effective strategy**
to increase revenue **while preserving profitability and premium positioning**.

---

## 🧹 Data Preparation & Cleaning
Before any analysis, the dataset was thoroughly **cleaned and standardized**.

Key steps included:
- Handling missing values and inconsistencies
- Removing invalid or incomplete orders
- Standardizing date and price formats
- Creating consistent product categories
- Keeping only **completed and reliable orders**

This ensured that all insights and conclusions are based on **high-quality data**.

---

## 🧠 Business Questions & Insights

### **BQ1 — How are products priced and distributed across categories?**
**What we found**
- Product volume is concentrated in **low-price categories**
- Revenue is dominated by **a small number of high-value categories**

**Why it matters**  
ENIAC’s revenue depends more on **value-driving products** than on sales volume alone.

---

### **BQ2 — Are discounts widely used at ENIAC?**
**What we found**
- **97% of products** are sold with a discount
- Discounts are **structural**, not exceptional

**Why it matters**  
Systematic discounting can weaken ENIAC’s **premium brand perception**.

---

### **BQ3 — Do higher discounts increase revenue?**
**What we found**
- Higher discounts increase the **number of orders**
- Total revenue is **highest and most stable at low discounts (0–10%)**
- Larger discounts do **not** generate revenue uplift

**Why it matters**  
More orders do not necessarily mean more value.

---

### **BQ4 — How do discounts impact margins?**
**What we found**
- **0–10% discounts** → ~95% average margin
- **10–20% discounts** → margin decreases
- **20%+ discounts** → margin drops sharply (~44%)

**Why it matters**  
Aggressive discounts significantly **reduce profitability**.

---

### **BQ5 — Are sales driven by discounts or seasonality?**
**What we found**
- Revenue peaks align with **Black Friday** and **Christmas**
- Peaks are driven by **seasonality**, not permanent high discounts

**Why it matters**  
Targeted campaigns outperform continuous discounting strategies.

---

## 🧱 Data Quality & Data Collection Improvements
During the analysis, several data quality limitations were identified.  
While these issues were addressed through data cleaning, they highlight opportunities
to improve ENIAC’s data collection process.

| What we observed in the data | Why this is a problem | How data collection should be improved | Business benefit |
|-----------------------------|----------------------|----------------------------------------|------------------|
| Product data was disorganized, incomplete, or inconsistent, with missing or non-standardized categories | Significant manual effort is required before analysis, slowing decision-making | Standardize product categories at the point of data collection | Faster analysis and reduced operational data-preparation costs |
| Discounts were applied without information about promotions or campaigns | Sales peaks cannot be clearly explained | Collect promotion metadata (campaign name, type, start/end dates) | Clear attribution of sales performance to campaigns |
| Orders contained only a single timestamp | Limited visibility into seasonality, delays, and customer journey | Capture full order lifecycle (created, paid, shipped, delivered) | More accurate operational and seasonal analysis |
| Revenue and margins were not stored as KPIs | Recalculations increase the risk of errors | Store validated revenue and margin at order level | Reliable KPIs for pricing and profitability decisions |
| No customer, country, or sales channel data | No segmentation or customer behavior analysis possible | Collect customer segments, countries, and sales channels | Better forecasting, targeting, and strategic decisions |

---

## 💡 Strategic Recommendations
- Use **low discounts (0–10%)** as the default pricing strategy
- Avoid frequent aggressive discounts (**20%+**)
- Apply strong discounts **only during targeted seasonal campaigns**
- Improve data structure and validation at the source
- Reinforce service quality to support **premium positioning**

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib)
- **Google Colab / Jupyter Notebook**
- Business-oriented data analysis  

---

## 📎 Deliverables
- Python notebooks (data cleaning, categorization, analysis)
- Business presentation: *ENIAC Discount Strategy Analysis*


