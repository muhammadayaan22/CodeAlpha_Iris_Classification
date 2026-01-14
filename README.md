# 🌼 Iris Flower Classification — Machine Learning Project

## 📌 Overview
This project focuses on classifying Iris flower species using machine learning.  
The goal is to predict whether a flower belongs to **Setosa**, **Versicolor**, or **Virginica** based on four measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

This is a classic beginner-friendly dataset perfect for learning classification, data visualization, and model evaluation.

---

## 📊 Dataset Description

The Iris dataset consists of:

- **150 samples**
- **3 species**
- **4 numerical features**
- No missing values and balanced classes

Each species has 50 samples.

---

## 🔎 Exploratory Data Analysis (EDA)

The following visualizations were created:

### ✔ Species Count Plot
Shows distribution of samples per species.

### ✔ Pairplot
Displays relationships between all pairs of features with species coloring.

### ✔ Correlation Heatmap
Shows correlation strength between numerical features.

### ✔ Boxplots & Violin Plots
Visual comparison of feature ranges across species.

### ✔ Scatter Plots
Shows visual separation of species using key features.

### ✔ KDE Density Plots
Shows smooth distribution curves for each feature.

### ✔ Feature Distribution Histograms
Visualizes the spread of sepal and petal measurements.

### ✔ Confusion Matrix (after training)
Displays classification performance visually.

---

## 🤖 Model Used

### ✔ Random Forest Classifier
Chosen because:

- Easy to train
- High accuracy
- Handles small datasets well
- Resistant to overfitting

### Steps Included:

- Label encoding (Species → 0/1/2)
- Train-test split (80/20)
- Training RandomForestClassifier
- Predicting test data
- Accuracy score calculation
- Classification report
- Confusion matrix visualization

---

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | **95% – 100%** |
| Precision | High |
| Recall | High |
| F1 Score | High |

Performance may slightly vary depending on the random state.

---

## 🎯 Feature Importance

From the trained model, the most important features were:

1. **Petal Length**
2. **Petal Width**
3. Sepal Length
4. Sepal Width

Petal measurements provide the strongest separation between species.

---

## 🧪 Prediction Function

A custom function was created to predict the species based on user input:

- Petal Length
- Petal Width
- Sepal Length
- Sepal Width

This makes the notebook interactive for users.

---

## 📝 Conclusion

This project successfully demonstrates:

- Data preprocessing  
- Exploratory data analysis  
- Visualization of patterns  
- Machine learning model development  
- Evaluation with accuracy and confusion matrix  
- Feature importance understanding  

The model achieved excellent accuracy due to the clear and natural separation between Iris species based on petal measurements.

---

## 📂 Project Structure


---

## 🔗 Credits

Dataset Source: Kaggle  
Project Developed For: CodeAlpha Data Science Internship

