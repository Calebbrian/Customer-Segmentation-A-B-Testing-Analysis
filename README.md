# Customer Segmentation & A/B Testing Analysis

This project applies **K-Means clustering** for customer segmentation and conducts an **A/B test** to evaluate marketing campaign effectiveness.  
The goal is to uncover customer behavior patterns, measure campaign performance, and generate actionable business insights.



##  Tools & Libraries
- **Python**
- **Pandas, NumPy** – Data handling
- **Matplotlib** – Visualization
- **Scikit-learn** – K-Means clustering, scaling
- **SciPy** – Statistical testing (Chi-square, Welch t-test)

---

## Key Steps
1. **Data Loading & Cleaning**  
   - Dataset with 10,000 customers.  
   - No missing values detected.  

2. **Customer Segmentation (K-Means)**  
   - 4 distinct customer groups identified based on age, income, amount spent, and product category.  

3. **Segment Profiling**  
   - Segment 0: Affluent professionals with high income and spending.  
   - Segment 1: Older, price-sensitive customers.  
   - Segment 2: Young customers with future potential but low current spending.  
   - Segment 3: Middle-income but surprisingly high spenders.  

4. **A/B Testing**  
   - Compared Campaign A vs Campaign B for Click-Through Rate (CTR) and Revenue.  
   - Statistical validation using Chi-square, confidence intervals, Welch t-test, and Cohen’s d.  

---

## 📊 Key Insights
- **Campaign Effectiveness**: No significant difference in CTR or revenue between Campaign A and B.  
- **Segment Insights**:  
  - Segment 0 & 3 are the most valuable (high spending).  
  - Segment 1 is highly price-sensitive.  
  - Segment 2 requires innovative engagement strategies.  
- **Strategic Recommendation**: Future campaigns should be redesigned and **personalized by segment** instead of generic A/B tests.  

---

## 🚀 Business Impact
- Enables **targeted marketing** instead of one-size-fits-all campaigns.  
- Helps optimize **resource allocation** by focusing on high-value customers.  
- Provides clear **next steps for experimentation and personalization**.  


## 👤 Author
- **Calebbrian**  
- Data Analyst | Python & SQL Enthusiast | Business Insights  

---
