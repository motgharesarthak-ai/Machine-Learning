# Day 5 - Feature Scaling

## 🎯 Objective

Learn how to scale numerical features using Standardization and Normalization to improve machine learning model performance.

---

## 📂 Dataset

Student Performance Dataset

---

## 📚 Topics Covered

- Feature Scaling
- Standardization (StandardScaler)
- Normalization (MinMaxScaler)
- Comparing scaled and original data
- Visualizing feature distributions

---

## 🛠 Libraries Used

- Pandas
- Matplotlib
- Scikit-learn

---

## 📋 Tasks Performed

- Loaded the processed dataset
- Selected numerical features
- Applied StandardScaler
- Applied MinMaxScaler
- Compared original and scaled values
- Visualized the `absences` feature before and after scaling
- Saved standardized and normalized datasets

---

## 📊 Observations

### Original Data
- The `absences` feature is right-skewed, with most students having few absences and a small number having many absences.

### After Standardization
- The data is centered around a mean close to 0 with a standard deviation close to 1.
- The distribution shape remains unchanged.

### After Normalization
- All values are scaled to the range 0–1.
- The relative order and distribution remain unchanged.

---

## 🔄 Standardization vs Normalization

| Standardization | Normalization |
|-----------------|---------------|
| Mean ≈ 0 | Values between 0 and 1 |
| Standard deviation ≈ 1 | Preserves relative proportions |
| Uses StandardScaler | Uses MinMaxScaler |

---

## 🚀 Skills Practiced

- Data Preprocessing
- Feature Scaling
- StandardScaler
- MinMaxScaler
- Data Visualization

---

## 📖 Next Topic

Train-Test Split
