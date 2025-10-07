# 🍲 Cajun-Creole Restaurant Revenue Optimization using AI & ML

### Using Synthetic Restaurant Data to Predict Revenue and Find Menu Optimization Strategies

---

## 🎯 Project Overview
This project applies **AI and Machine Learning** to a synthetic Cajun-Creole restaurant dataset to predict **daily revenue** and uncover **menu, pricing, and customer behavior insights**.  
Built entirely in **Python (Google Colab)** using **free resources**, it demonstrates how data-driven decision-making can optimize restaurant performance — inspired by my background in hospitality management.

---

## 🧩 Framework: STAR + Problem/Solution

### **Situation**
The restaurant industry faces narrow profit margins and unpredictable sales influenced by weather, promotions, and customer sentiment.  
Restaurants often rely on intuition rather than data to make decisions about pricing, menu design, and marketing.

### **Task**
Develop an **AI-powered model** that learns from synthetic sales data to:
- Predict daily restaurant revenue,  
- Identify the most profitable dishes, and  
- Recommend actionable strategies to increase revenue and reduce waste.

### **Action**
1. **Data Generation:** Created a 10,000-row synthetic dataset simulating Cajun-Creole restaurant operations (menu items, pricing, promotions, weather, seasons, and reviews).  
2. **Data Cleaning & EDA:** Explored patterns in pricing, profit, waste, and customer behavior using Pandas and Matplotlib.  
3. **Machine Learning Modeling:**  
   - Built a **Linear Regression model** with an **R² = 0.89**, explaining 89% of revenue variation.  
   - Engineered features such as promotions, weather, and seasonality to improve prediction.  
4. **Insight Development:** Translated results into real-world strategies for menu design, promotions, and waste management.

### **Result**
- **Model Accuracy:** R² = 0.89, MAE = 9.11  
- **Business Insights:**  
  - Quantity sold and price drive the most revenue.  
  - Promotions increase sales volume but can impact profit margins.  
  - High customer ratings directly correlate with increased revenue.  
  - Seasonal and weather effects offer marketing opportunities (e.g., comfort dishes in winter).

---

## 🧠 Hypothesis: Problem & Solution

| Problem | Hypothesis | Solution (Result) |
|----------|-------------|------------------|
| Menu pricing and promotions are inconsistent. | If we train a model on historical menu, price, and promo data, we can predict daily revenue with accuracy. | The Linear Regression model achieved **R² = 0.89**, confirming data-driven pricing can outperform intuition. |
| Waste and profit margins are difficult to balance. | If waste, cost, and sales are analyzed together, we can find underperforming dishes. | Analysis identified menu items with high waste and low profit — candidates for removal or rework. |
| Weather and seasonality impact demand unpredictably. | If we include weather and season as features, we can capture natural demand cycles. | Weather features improved model stability, suggesting future demand forecasting opportunities. |

---

## 📊 Key Metrics
| Metric | Value |
|:--|--:|
| Mean Absolute Error (MAE) | 9.11 |
| Mean Squared Error (MSE) | 169.91 |
| R² Score | 0.89 |

---

## 💼 Strategic Recommendations
- Focus marketing efforts on **high-rating, high-profit dishes**.  
- Use predicted revenue to **plan inventory and staffing** for high-demand seasons.  
- Re-engineer **low-profit, high-waste items** for sustainability.  
- Introduce **data-driven menu pricing** for optimal margins.  

---

## 🧰 Tech Stack
- **Python (Google Colab)**  
- **Libraries:** Pandas, NumPy, Faker, Scikit-learn, Matplotlib  
- **ML Model:** Linear Regression  
- **Dataset:** Fully synthetic, ethically generated  

---

## 🪄 Next Steps
- Add Random Forest and XGBoost for non-linear relationships.  
- Predict **Profit** instead of **Revenue** for a strategic business model.  
- Add **Sentiment Analysis** on *Customer_Review* using NLP.  
- Build a simple **Looker Studio dashboard** to visualize findings.  

---

## 🧾 Author
**Lionel Sylvester**  
AI & Cloud Data Analyst | Data Storyteller | Former Hospitality Leader  
📍 *Bridging restaurant experience with data-driven insights*  
 
