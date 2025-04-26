
# Iris Flower Classification 🌸

This project develops a machine learning model to classify Iris flowers into three species — Setosa, Versicolor, and Virginica — based on their sepal and petal measurements.

---

## 📚 Dataset

The dataset contains:
- **Features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target**:
  - Species (Iris-setosa, Iris-versicolor, Iris-virginica)

The dataset is loaded from a CSV file (`iris.csv`).

---

## 🛠️ Project Steps

1. **Upload and Load Dataset**
   - Dataset is uploaded manually on Colab using `files.upload()`.
   
2. **Data Exploration**
   - Displaying the first few rows.
   - Viewing dataset info and statistical description.
   
3. **Data Visualization**
   - **Pairplot** to understand feature relationships.
   - **Correlation heatmap** (only numerical features) to understand feature correlations.

4. **Preprocessing**
   - Dropping the target column (`species`) from features.
   - Standardizing the feature values using **StandardScaler**.
   - Splitting data into **training (80%)** and **testing (20%)** sets.

5. **Feature Importance**
   - Using **Random Forest** to identify the most influential features affecting species classification.
   - Plotting feature importance graphically.

6. **Model Selection and Training**
   - Training a **Support Vector Machine (SVM)** classifier with a linear kernel.

7. **Model Evaluation**
   - **Accuracy Score**
   - **Classification Report** (Precision, Recall, F1-Score)
   - **Confusion Matrix** visualization

---

## 🧪 Model Performance

- The model achieved **high accuracy** on the test set.
- Metrics like precision, recall, and F1-score for all three species are excellent, indicating strong classification capability.

---

## 📈 Visualization Samples

- **Pairplot** of the features colored by species.
- **Correlation heatmap** to show feature interdependence.
- **Feature importance bar plot** from Random Forest.
- **Confusion matrix** of model predictions.

---

