# Healthy Snack Recommendation System  

🥗 This project builds a **recommendation system for healthy snacks**, helping users discover better snack choices based on their preferences and similarity to other users.  

---

## 🌟 Why This Project Matters  
Choosing healthy snacks can be overwhelming when there are so many options.  
By applying **machine learning (collaborative filtering)**, we can suggest snacks that users are more likely to enjoy while keeping nutrition in mind.  

---

## 🔎 What I Did  
1. **Data Preparation**  
   - Collected and cleaned snack dataset (nutritional values, ratings, categories).  
   - Created a user-item interaction matrix.  

2. **Exploratory Data Analysis**  
   - Distribution of snack ratings.  
   - Popular healthy vs. less-healthy snacks.  
   - Correlations between snack categories.  

3. **Modeling**  
   - Implemented **Collaborative Filtering** (User-based & Item-based).  
   - Used **cosine similarity** to find similar snacks.  
   - Built a function that returns top-N recommendations for a given user or snack.  

4. **Evaluation**  
   - Compared recommendation accuracy using metrics like Precision@K and Recall@K.  
   - Tested recommendations on sample users.  

---

## 📊 Example Output  

**Input:** User A likes almonds, protein bars  
**Recommendation:**  
- Trail Mix (high protein, low sugar)  
- Greek Yogurt  
- Baked Chickpeas  

---

## 🔮 Future Improvements  
- Add content-based filtering (using nutritional values).  
- Build a hybrid system combining popularity + personalization.  
- Deploy as a simple web app where users can search and get snack suggestions.  

---

## 🚀 How to Run  
Clone this repo and open the notebook:  

```bash
git clone https://github.com/revativiradiya/portfolio.github.io.git
cd projects/healthy-snack/notebooks
jupyter notebook snack_recommendation.ipynb
