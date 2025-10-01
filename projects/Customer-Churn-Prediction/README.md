# Customer Churn Prediction  

Have you ever wondered why some customers leave a service while others stay loyal?  
This project explores that question by building a machine learning model that can **predict when a customer is likely to churn (leave the service)**.  

  I used the **Telco Customer Churn dataset** from [Kaggle][(https://www.kaggle.com/code/farazrahman/telco-customer-churn-logisticregression?select=WA_Fn-UseC_-Telco-Customer-Churn.csv)], which includes details like customer contracts, monthly charges, and how long they’ve been with the company.  

---

## 🌟 Why This Project Matters  
In business, keeping existing customers is often **cheaper than finding new ones**.  
If companies can predict churn before it happens, they can take action — like offering discounts, better contracts, or personalized support — to encourage customers to stay.  

This project shows how data can give businesses that power.  

---

## 🔎 What I Did  
1. **Explored the data** to see patterns:  
   - Customers with month-to-month contracts were more likely to churn.  
   - Long-term customers tended to stay longer.  
   - Higher monthly charges often meant a higher chance of leaving.  

2. **Built models** to predict churn:  
   - Started with Logistic Regression as a baseline.  
   - Improved results using a Random Forest Classifier.  

3. **Evaluated results** using accuracy, precision, recall, and ROC-AUC to ensure the model was useful, not just accurate.  

---

## 📊 Results in Simple Words  
- The Random Forest model performed better than Logistic Regression.  
- The model could **successfully flag customers at high risk of leaving**.  
- Insights:  
  - 📌 Customers on **month-to-month contracts** were most likely to churn.  
  - 📌 Customers with **higher monthly bills** had a higher chance of leaving.  
  - 📌 **Tenure** (how long they’ve been with the company) played a big role — newer customers were less loyal.  

---

## 🖼️ Visuals  
I’ve included some key visuals to make the findings clear:  

- Distribution of churned vs. retained customers  
- ROC curve to show prediction strength  
- Feature importance (which customer factors matter most)  

---

## 🚀 How You Could Use This  
- A telecom company could identify customers at risk and **reach out with retention offers**.  
- Marketing teams could design **targeted campaigns** for high-risk groups.  
- Customer support could **prioritize at-risk customers** when they call in.  

---

## 🔮 What’s Next  
If I had more time, I would:  
- Fine-tune the model with hyperparameter tuning.  
- Use SMOTE to balance churn vs. non-churn customers.  
- Deploy a simple web app so anyone can test the model by entering customer details.  

---

## 🛠️ How to Explore the Project  
- Clone the repository  
- Open the Jupyter Notebook in the `notebooks/` folder  
- Run the cells to see the full analysis and models in action  

```bash
git clone https://github.com/revativiradiya/portfolio.github.io.git
cd projects/customer-churn/notebooks
jupyter notebook churn_prediction.ipynb
