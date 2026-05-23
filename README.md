#  Coffee Shop Sales Analysis Dashboard

## Overview
This project analyzes coffee shop transactional data to uncover insights related to:
- Sales performance
- Customer purchasing behavior
- Peak business hours
- Product performance
- Store-wise revenue trends

An interactive Power BI dashboard was created to support data-driven business decisions.

---

##  Dashboard Preview
<p align="center">
  <img src="https://github.com/user-attachments/assets/bb0ed82c-6f69-481f-8356-44600813597c" alt="Project Screenshot" width="900" />
</p>

---

---

## Key Insights
- Peak sales occur between **8 AM – 10 AM**
- Coffee category contributes the highest share of revenue
- Hell’s Kitchen is the top-performing store location
- Weekday sales are higher than weekend sales

---

---

##  Tools & Technologies
- Power BI
- DAX
- Excel / CSV
- Data Visualization
- Data Cleaning

---

##  DAX Measures Used

```DAX
Total Sales = SUM(coffee_shop_sales[Total_bill])

Footfall = DISTINCTCOUNT(coffee_shop_sales[transaction_id])

Avg Bill Per Person =
DIVIDE([Total Sales], [Footfall], 0)

Hour = HOUR(coffee_shop_sales[transaction_time])
```
---

##  Business Impact
The dashboard helps businesses:
- Optimize staffing during peak hours
- Improve inventory planning
- Identify top-performing products
- Analyze store performance
- Support strategic sales decisions

---

##  Author
- Your Name - Mani Kaur
- LinkedIn Profile: [Mani Kaur](https://www.linkedin.com/in/mani-kaur9857)
- GitHub Profile: [GitHub](https://github.com/Mani-Kaur)

