## 🌸 IRIS Flower Classification

### 📌 Task Overview

This project is a machine learning classification task that aims to identify the species of Iris flowers (Setosa, Versicolor, or Virginica) based on their **sepal and petal measurements**. It’s a beginner-friendly dataset ideal for understanding key ML concepts like preprocessing, model training, and evaluation.

---

### 👨‍💻 Author

* **Name:** Tushar Surja
* **Batch:** June 2025, B33
* **Domain:** Data Science

---

### 🎯 Project Objective

To build a machine learning model that accurately classifies Iris flowers using supervised learning algorithms, specifically a **Random Forest Classifier**.

---

### 📁 Dataset

The dataset used is **IRIS.csv**, which contains:

* Features: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
* Target: `species` (Setosa, Versicolor, Virginica)

---

### 🧪 Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

### ⚙️ Workflow

1. **Import Libraries**
   All required Python libraries for data manipulation, visualization, and machine learning are imported.

2. **Load the Dataset**
   The CSV file is loaded and inspected using `head()`.

3. **Data Preprocessing**

   * Label encoding is used to convert species names to numerical values.

4. **Train-Test Split**

   * Dataset is split (80% training / 20% testing) using `train_test_split`.

5. **Model Training**

   * A `RandomForestClassifier` is trained on the training data.

6. **Model Evaluation**

   * Performance is evaluated using `accuracy_score` and `classification_report`.

7. **Feature Importance**

   * Visualized using a bar plot to show which features most influenced the predictions.

---

### 📊 Results

* The Random Forest Classifier provided high classification accuracy with detailed precision, recall, and F1-score metrics across all classes.

---

### ✅ Conclusion

This project demonstrates a complete pipeline for a classification task—from data loading and preprocessing to model training, evaluation, and result visualization—ideal for beginners in machine learning.
