# Day 6 - Train-Test Split

## 🎯 Objective

Learn how to split a dataset into training and testing sets before building a machine learning model.

---

## 📂 Dataset

Student Performance Dataset

---

## 📚 Topics Covered

- Features (X)
- Target Variable (y)
- Train-Test Split
- Training Dataset
- Testing Dataset
- Importance of random_state

---

## 🛠 Libraries Used

- Pandas
- Scikit-learn

---

## 📋 Tasks Performed

- Loaded the processed dataset
- Selected features (X)
- Selected target variable (G3)
- Split the dataset into training and testing sets
- Compared different train-test ratios
- Explored the effect of changing random_state

---

## 📊 Results

### 80:20 Split

- Training Data: 316 samples
- Testing Data: 79 samples

### 70:30 Split

- Training Data: 276 samples
- Testing Data: 119 samples

---

## 📌 Observations

- The dataset was successfully divided into training and testing sets.
- An 80:20 split provides more data for model training while reserving enough data for evaluation.
- Increasing the test size to 30% decreases the amount of training data.
- Changing the random_state changes which samples are selected for training and testing, but not the total number of samples.

---

## 🚀 Skills Practiced

- Dataset Splitting
- Feature Selection
- Target Variable Selection
- Data Preparation
- Scikit-learn

---

## 📖 Next Topic

Linear Regression
