# 🎓 Student Marks Predictor 📈

A simple and accurate Linear Regression project that predicts student marks based on their study hours using Python and Scikit-Learn.

---

##  Objective

To predict student marks based on the number of hours they study using a **simple linear regression model**.

---

##  Concepts Used

- Data Cleaning (handling missing values)
- Data Visualization (scatter plot)
- Linear Regression (model training)
- Evaluation Metrics:
  - R² Score
  - MAE, MAPE
  - MSE, RMSE

---

## 📂 Dataset

- **File:** `student_marks.csv`
- **Columns:**
  - `study_hours`: Number of hours a student studied
  - `student_marks`: Actual marks scored

---

## 🛠️ Tools & Libraries

- `Python 3`
- `Pandas`
- `NumPy`
- `Matplotlib`
- `Scikit-learn`

---

## 🔄 Workflow

1. **Import libraries**
2. **Load and inspect dataset**
3. **Handle missing values**
4. **Visualize data**
5. **Prepare features and labels**
6. **Train-test split**
7. **Train Linear Regression model**
8. **Evaluate the model**
9. **Visualize predictions**
10. **Calculate metrics:**
    - Mean Absolute Error (MAE)
    - Mean Absolute Percentage Error (MAPE)
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - R² score

---

## 📊 Model Performance

| Metric | Value      |
|--------|------------|
| R² Score | 0.9465 |
| MAE     | ~0.97     |
| MAPE    | ~1.24%    |
| Accuracy| ~98.75%   |
| MSE     | ~1.36     |
| RMSE    | ~1.16     |

✅ The model predicts student marks with **high accuracy**.

---

## 📈 Visualization

- Scatter Plot of Study Hours vs Marks
- Regression Line for both training and test data
- Prediction vs Actual comparison table

---

##  Sample Prediction

```python
lr.predict([[40]]) 
# Predict student marks based on study hours
lr.predict([[40]])   # Output: ~206.32 marks
lr.predict([[10]])   # Output: ~89.59 marks
lr.predict([[7]])    # Output: ~77.92 marks
lr.predict([[5.5]])  # Output: ~72.06 marks
lr.predict([[2]])    # Output: ~58.47 marks
lr.predict([[0]])    # Output: ~50.69 marks  (intercept only, no study)



