
# 🚖 Uber vs Lyft Comparative Analysis  

A **data-driven study** comparing **Uber** and **Lyft** pricing strategies, user switching behavior, and market demand trends. This project applies **statistical methods** to uncover insights into ride-sharing competition and customer decision-making.  

---

## 📌 Project Overview  
Ride-sharing has transformed urban transportation by offering affordable and flexible travel options. However, companies like Uber and Lyft face challenges such as:  
- Intense competition & price wars  
- Highly **price-sensitive customers**  
- Demand volatility due to time, location, and surge pricing  
- Balancing **profitability vs affordability**  

This study investigates:  
1. Whether price differences significantly influence user choice.  
2. How demand and distance affect ride pricing.  
3. Data-driven recommendations for improving customer retention.  

---

## 🎯 Objectives  
- Examine **price differences** between Uber and Lyft.  
- Analyze how pricing impacts **user switching behavior**.  
- Investigate **demand distribution** by distance ranges.  
- Recommend **competitive pricing & retention strategies**.  

---

## 📊 Dataset Description  
The dataset (Boston, MA – Nov–Dec 2018) contains ~650,000 rides with the following fields:  

- **cab_type** – Uber or Lyft  
- **price** – Ride fare (USD)  
- **distance** – Trip length (miles)  
- **time_stamp** – Ride request time  
- **surge_multiplier** – Surge factor applied  
- **source / destination** – Pickup & drop-off locations  
- **ride_type** – e.g., UberX, Lyft Lux  
- **id** – Unique ride identifier  

---

## 🔬 Methodology  

### Hypotheses Tested  
1. **Distribution of Users** (Uber vs Lyft) → Chi-Square Test  
2. **Price Differences** → Two-Sample T-Test  
3. **Price Impact on User Choice** → Logistic Regression  
4. **Distance & Fare Relationship** → Correlation + ANOVA  

### Statistical Methods  
- ✅ **Chi-Square Test** – To analyze user distribution differences  
- ✅ **Two-Sample T-Test** – To compare average fares  
- ✅ **Logistic Regression** – To measure effect of price on user choice  
- ✅ **ANOVA** – To analyze fare variations across distance ranges  

---

## 📈 Key Results  

- **Chi-Square Test:** Strong evidence that Uber and Lyft users are distributed differently.  
- **T-Test:** Uber fares are **lower on average ($15.8)** vs Lyft **($17.4)**, difference is statistically significant.  
- **Regression:** Price influences user choice, but effect size is small.  
- **Distance Analysis:**  
  - Most common trips: **1–3 miles (64% of rides)**  
  - Lyft consistently charges higher fares across all distances.  
  - Weak to moderate correlation (0.345) between distance and fare.  
- **ANOVA:** Fare differences between Uber and Lyft by distance are **not statistically significant**.  

---

## ✅ Recommendations  

- **For Lyft:**  
  - Justify higher fares with **premium features**.  
  - Offer discounts for **short-distance trips** (1–3 miles).  

- **For Uber:**  
  - Emphasize **affordability** in marketing.  
  - Introduce **loyalty programs** to retain users.  

- **For Both:**  
  - Differentiate services beyond pricing (e.g., quality, availability).  
  - Incorporate factors like **surge pricing, ride type, time of day** for optimized pricing strategies.  

---

## 👨‍💻 Contributors  
- **Aamena Zakir Shaikh** (NF1005115)  
- **Bui Ngoc Mai Khanh** (NF1002800)  
- **Anisha K C** (NF1001648)  
- **Heta Chavda** (NF1014555)  
- **Krishna Patel** (NF1017043)  

Course: **DAMO-500-2: Principles of Analytics**  
Instructor: **Abbas Hamze**
