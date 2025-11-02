![Bank Churn Analysis](https://github.com/user-attachments/assets/cc81ba95-5af0-4e38-8918-3086ce3920f0)

# 🏦 Bank Customer Churn Analysis (Excel Dashboard)

## 📍 Project Context
This project analyses customer churn data from a European bank with over 10,000 customer records. The goal is to uncover patterns in churn behaviour, identify high-risk segments, 
and provide actionable insights to improve customer retention. The dashboard enables business users to explore churn trends by geography, demographics, and product usage.

## 📂 Dataset Background
The dataset comes from the [Maven Analytics Data Playground – Bank Customer Churn](https://mavenanalytics.io/data-playground/bank-customer-churn?order=date_added%2Cdesc&search=bank+churn), 
featuring account information for 10,000 customers at a European bank. It includes details on:

- **Credit Score & Balance:** Financial health indicators  
- **Product Count & Active Status:** Engagement metrics  
- **Geography & Gender:** Demographic segmentation  
- **Churn Flag:** Indicates whether a customer has exited the bank  

### 🔍 Recommended Analysis Questions  
- What attributes are more common among churners than non-churners? Can churn be predicted using the variables in the data?  
- What do the overall demographics of the bank's customers look like?  
- Is there a difference between German, French, and Spanish customers in terms of account behaviour?  
- What types of segments exist within the bank's customers?

## ❓ Problem Statement
How can a bank reduce customer churn by identifying key risk factors and understanding the profiles of customers most likely to leave?

This analysis is useful for customer success teams, product managers, and data analysts focused on improving retention and customer lifetime value.

## 💡 Key Insight
- Customers with fewer products and lower credit scores are more likely to churn.  
- Germany has the highest churn rate among the three countries analysed.  
- Inactive members and customers with low balances show higher churn tendencies.  
- Customers with 3+ products are significantly more loyal.  

## 🛠️ Tools Used  
- **Excel Pivot Tables:** Summarised churn by geography, gender, and product count.  
- **Power Query:** Cleaned and transformed raw data.  
- **Advanced Formulas:** Calculated KPIs like churn rate and average balance.  
- **Conditional Formatting & Charts:** Visualised churn trends and customer segments.  

## 🔄 Process Walkthrough 
- Cleaned and loaded data using Power Query.  
- Defined KPIs: Total Customers, Churn Rate, Avg. Balance, Avg. Credit Score.  
- Created pivot tables to analyse churn by geography, gender, and product count.  
- Built an interactive dashboard with slicers and KPI cards for dynamic filtering.  

## 📊 Dashboard Highlights  
![Bank Customer Churn Dashboard](https://github.com/user-attachments/assets/aeceeece-b161-43d4-b9ec-b7abf6044de5)
This visual summarises key metrics and allows dynamic filtering by geography, gender, product count, and churn status.

## 📈 Pivot Table Logic  
![Bank Customer Churn Pivot Table](https://github.com/user-attachments/assets/62147903-b78a-4fab-b088-39c363bc4074)
The backend view supports dashboard insights and shows how KPIs were calculated using pivot tables and formulas.


## 🏆 Key Findings

- **Total Customers Analysed:** 10,000  
- **Overall Churn Rate:** 20.37%  
- **Highest Churn Country:** Germany (814 churned out of 1,695 customers)  
- **Gender Split:** Fairly balanced – 45% Female, 55% Male  
- **Tenure Impact:** In their first year, around 62% of customers left the bank. By the tenth year,
  churn dropped to just 21%, showing that long-term customers are far more likely to stay.  
- **Product Usage:** The majority of customers hold only 1 product (5,084), while only 60 hold 4 products.  
- **Multi-Product Loyalty:** Customers with more than 2 products show significantly lower churn.  
- **Balance Distribution:** France holds the highest total balance (€31.33M), followed by Germany and Spain.  
- **Average Credit Score:** 651  
- **Average Balance per Customer:** €76,485.89  

## 🧠 Reflections

- **Churn Risk Factors:** Low tenure, low product count, and low credit scores are strong indicators of churn risk.  
- **Geographic Strategy:** Germany requires targeted retention efforts due to its high churn rate despite holding the excellent balance.  
- **Product Bundling Opportunity:** Encouraging customers to adopt more products may improve loyalty and reduce churn.  
- **Demographic Insights:** Gender distribution is balanced, but churn patterns may vary subtly across segments.  
- **Tenure-Based Campaigns:** Onboarding and engagement strategies for new customers (0–1 year tenure) could reduce early churn.  
- **Data-Driven Decisions:** These insights can guide customer success teams in prioritising outreach and tailoring retention strategies.  

## ⚠️ Limitations  
- No customer feedback or satisfaction data included.  
- No time-series data to track churn over time.  
- No income or transaction-level behaviour available.  

## 🔮 Next Steps  
- Integrate churn data with customer support logs to explore service-related churn.  
- Add time-based data to analyse churn trends over months or quarters.  
- Segment customers by lifetime value for prioritised retention strategies.  

## 📘 What I Learned 
- Built dynamic dashboards using Excel slicers and KPI cards.  
- Learned how demographic and behavioural filters reveal churn patterns.  
- Strengthened Power Query and pivot table skills for business-focused analysis.  

## 🚀 Final Thoughts
This project demonstrates how Excel dashboards can uncover churn drivers and support data-driven retention strategies in the banking sector.

## 📬 Contact
For questions or collaboration, feel free to reach out:
📧 Email: sudiprai969@gmail.com  
🔗 [LinkedIn – Sudeep Rai](https://www.linkedin.com/in/sudeeprai)  

---

> 💡 Full code and dashboard available in this repository.  
> Open to feedback, suggestions, or contributions!
