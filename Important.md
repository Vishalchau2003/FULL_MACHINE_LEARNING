# 🧠 Machine Learning Notes: Outliers & Scaling

## 🔹 1. Outliers in Machine Learning

### ✅ What are outliers?
Outliers are data points that are:
- Extremely large or small
- Unrealistic or incorrect
- Far away from normal data distribution

### 📌 Example

pickup_longitude = -1183 ❌ (invalid)
fare_amount = 5000 ❌ (unrealistic)
---

## ❌ Why outliers are harmful

- Model tries to fit these incorrect values
- Learns wrong patterns
- Reduces accuracy
- Increases error (especially in regression)

---

## ✅ Why removing outliers helps

- Model focuses on real patterns
- Improves generalization
- Reduces noise
- Gives better predictions

---


# 2. dir(model)


👉 Returns:
all methods
attributes
internal functions
---



## 🔹 3. Workflow Efficiency & Project Setup

### 📌 Use Data Samples
When working with large datasets, use a small subset (e.g., 1%) initially.  
This helps you:
- Iterate faster  
- Debug quickly  
- Test ideas without long computation time  

---

### 📌 Create a Project Outline
Before coding, create a structured plan for your notebook:
- Data loading  
- Data cleaning  
- Feature engineering  
- Model training  
- Evaluation  

This ensures you don’t miss important steps.

---

### 📌 Experiment Tracking
Maintain a record of:
- Hyperparameters used  
- Model performance  
- Observations  

This helps you:
- Avoid repeating experiments  
- Identify what works best  

---

## 🔹 4. Data & Model Handling

### 📌 Save Preprocessed Data
Store cleaned and processed data using formats like **Parquet**.

Benefits:
- Faster loading  
- Avoid reprocessing  
- Modular workflow (separate notebooks)

---

### 📌 Save Trained Models
Always save trained models (e.g., `.joblib`, `.pkl` files).

Benefits:
- Reuse without retraining  
- Faster inference  
- Easy deployment  

---

## 🔹 5. Strategy for Improvement

### 📌 Focus on Feature Engineering
Instead of only tuning hyperparameters:
- Create meaningful features  
- Use domain knowledge  

👉 A few strong features can outperform heavy tuning.

---

### 📌 Iterative Approach
Build models step-by-step:
1. Add a feature  
2. Train model  
3. Evaluate performance  
4. Decide to keep/remove  

---

### 📌 Qualitative Checks
Don’t rely only on metrics like RMSE or Accuracy.

Also:
- Inspect predictions manually  
- Check if results make real-world sense  

---

## 🔹 6. Key Learning Habit

### 📌 Copy-Paste & Reverse Engineer Method
- Study good notebooks (Kaggle/Jovian)  
- Copy the code  
- Break it down line-by-line  
- Understand the logic  

👉 This is one of the fastest ways to learn practical ML.

---

# 🚀 Final Takeaway

> Build → Test → Analyze → Improve → Repeat

Consistency and structured workflow matter more than complex models.
