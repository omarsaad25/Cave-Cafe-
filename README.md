<<<<<<< HEAD
# Cave Café Analysis

## Project Overview
Analyzed café sales data using Python to identify rush hours, busiest days, and seasonal trends.


---

## Objectives

- Identify peak traffic periods across **month, week, day, and hour**
- Segment customer activity into **day vs. night shifts**
- Analyze holiday effects and table utilization
- Build regression models to forecast café demand
- Translate insights into **business strategies**

---

## Key Insights

### Rush Hour Behavior
- **Top hours:** 22:00 and 20:00 dominate revenue and order volume
- **Day shift peaks:** 15:00 and 17:00
- **Action:** Optimize staffing and product offerings around these verified peak hours

### Shift Performance
- **Night shift leads** in revenue: 173.6k vs 52.6k for day shift
- **Action:** Prioritize promotions, staffing, and menu variety for evening traffic

### Weekly & Monthly Patterns
- **Consistent rush:** Week 4 of each month averages ≈312 orders
- **Holiday surges:**  
  - April Week 1 (+118 orders) → Eid al-Fitr  
  - June Week 2 (+104 orders) → Eid al-Adha
- **Top months:** April and May
- **Action:** Align campaigns with holiday calendars and end-of-month demand

### calendar Effects
- **Top weekdays by orders:** Friday & Saturday  
- **Top weekdays by revenue:** Friday & Thursday  
- **Action:** Launch weekend bundles and Thursday specials to maximize returns

### Table Utilization
- **Most used tables:** 1, 8, 3, 6, 14 — especially during 21:00–22:00
- **Action:** Balance table load and consider layout adjustments to reduce bottlenecks

---

## Regression Modeling

The notebook `first_reg_model.ipynb` introduces a regression model to forecast café activity based on time features. It includes:
- Feature engineering from timestamp data
- Model training and evaluation
- Saved model (`.pkl`) for reproducible predictions

---

## Tools & Libraries

- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebooks

---

## Next Steps

- Automate daily demand forecasting
- Integrate predictions into business dashboards
- Expand analysis to include product-level sales and customer segmentation
- Optimize table layout and shift scheduling based on utilization data

\- `Cave cafe rush hour.docx`: Documentation of steps and findings



>>>>>>> e357485 (Add README with project overview and insights)
