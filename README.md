# Task-3: Linear Regression

## 🎯 Objective
Implement and understand **Simple & Multiple Linear Regression** using Scikit-learn, Pandas, and Matplotlib.  

---

## 📊 Dataset
We are using the **California Housing Dataset** from Scikit-learn.  
- **Target (y):** Median House Value (`MedHouseVal`)  
- **Features (X):** Median Income (`MedInc`) for Simple Linear Regression, and all available features for Multiple Linear Regression.

---

## ⚙️ Steps Followed
1. Import and preprocess the dataset  
2. Split data into **train-test sets**  
3. Fit a **Linear Regression model** (`sklearn.linear_model.LinearRegression`)  
4. Evaluate the model using:  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  
5. Plot regression line (for Simple Linear Regression)  
6. Interpret coefficients  

---

## 📌 Results

### ✅ Simple Linear Regression (MedInc → MedHouseVal)
- **Intercept (b0):** Learned from data  
- **Coefficient (b1):** Change in house value for 1 unit increase in median income  
- Evaluation Metrics:  
  - MAE: ~0.53  
  - MSE: ~0.53  
  - R²: ~0.47  

📈 **Regression Line:**  
![Regression Plot](https://miro.medium.com/v2/resize:fit:720/format:webp/1*H1-c9DqeywKmtjKN50FJzA.png)

---

### ✅ Multiple Linear Regression (All Features → MedHouseVal)
- Uses all available features (`MedInc`, `HouseAge`, `AveRooms`, etc.)  
- Evaluation Metrics:  
  - MAE: ~0.53  
  - MSE: ~0.40  
  - R²: ~0.61  

---

## 📦 Requirements
Make sure you have these installed (Anaconda usually has them by default):

```bash
conda install scikit-learn pandas matplotlib
