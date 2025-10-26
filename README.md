# 🎬 Movie Rating Prediction using Random Forest

## 📊 Project Overview
This project predicts **IMDb movie ratings** based on various movie attributes such as **Genre, Runtime, Revenue, Votes, and Metascore**.  
A **Random Forest Regressor** model is used within a **Scikit-learn pipeline** that handles data preprocessing, encoding, and training automatically.  
The project demonstrates an end-to-end **machine learning regression workflow** — from cleaning data to evaluating and visualizing results.

---

## 🧠 Objectives
- Clean and preprocess the movie dataset  
- Handle missing values and categorical data using **OneHotEncoder**  
- Train a **Random Forest Regressor** to predict movie ratings  
- Evaluate the model using **RMSE, MAE, and R² Score**  
- Visualize predictions and feature importances  

---

## 🧰 Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## ⚙️ Steps Performed
1. **Data Cleaning & Preprocessing**
   - Converted numeric columns properly
   - Filled missing values using median strategy
   - One-hot encoded the categorical `Genre` column  

2. **Model Training**
   - Split the dataset into training and testing sets (80/20)
   - Used **RandomForestRegressor** with 200 trees for robust performance  

3. **Model Evaluation**
   - Metrics calculated:  
     - RMSE (Root Mean Squared Error)  
     - MAE (Mean Absolute Error)  
     - R² Score  
   - Visualized **Actual vs Predicted** IMDb ratings  

4. **Feature Importance**
   - Extracted and plotted top 10 important features  
   - Helps identify which factors influence IMDb ratings the most  

---

## 📈 Results
- The model achieved strong predictive performance on unseen data.  
- The scatter plot shows that predicted ratings closely align with actual ratings.  
- The feature importance plot reveals which features most impact rating predictions (e.g., votes, metascore, revenue).  

---

## 🖼️ Visualizations
1. **Actual vs Predicted IMDb Ratings**
   ![Prediction Scatter Plot](example_scatter.png)

2. **Top 10 Important Features**
   ![Feature Importance](example_importance.png)

---

## 📁 Files
- `movie.csv` — Movie dataset  
- `Movie Rating.py` — Python script  
- `README.md` — Documentation  

---

## ✨ Author
**Fatima**  
📧 Data Science Enthusiast | 🎥 Machine Learning Learner  
