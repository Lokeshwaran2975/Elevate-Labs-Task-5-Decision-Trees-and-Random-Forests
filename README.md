# Elevate-Labs-Task 5: Decision Trees and Random Forests 

## 📌 Objective
Explore and implement tree-based models for classification using Decision Tree and Random Forest classifiers.

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Graphviz / PlotTree

---

## 📂 Dataset
Uploaded CSV file: `heart.csv` 
- Features: Numeric or categorical
- Target: Last column

---

## 🔍 Steps Performed
1. **Data Preprocessing**
   - Loaded the dataset using pandas
   - Split features and target
   - Handled categorical encoding (if required)

2. **Decision Tree Classifier**
   - Trained with controlled depth (`max_depth=3`)
   - Visualized using `plot_tree`
   - Evaluated using accuracy & classification report
   - Cross-validated with 5 folds

3. **Random Forest Classifier**
   - Trained with 100 trees
   - Evaluated with accuracy and classification report
   - Plotted feature importances
   - Cross-validated with 5 folds

---

## 📊 Results

| Model          | Accuracy            | Cross-Validation Accuracy |
|----------------|---------------------|---------------------------|
| Decision Tree  | 0.7804878048780488  | 0.83                      |
| Random Forest  | 0.9853658536585366  | 0.997                     |

📌 Random Forest showed better performance due to ensemble learning and reduced overfitting.

---

## 📈 Visuals
- Decision Tree Visualization

  ![Decision Tree](https://github.com/user-attachments/assets/4cdde734-18aa-4990-bd05-aff8e6b76c26)

- Random Forest Feature Importances

  ![Feature Importances from Random Forest](https://github.com/user-attachments/assets/74036c5a-4c5b-453d-9ec6-a8444b4aa7f1)


---

## 💡 Key Learnings
- Tree-based models are interpretable and powerful
- Limiting depth avoids overfitting in decision trees
- Random Forest improves performance by averaging multiple trees
- Feature importance helps in model interpretability

---

## 📁 Files in the Repository

- `Task 5 Decision Trees and Random Forests.ipynb` — Jupyter Notebook with code and visualizations
- `README.md` — Project overview and documentation
- `decision tree.png`
- `feature importances from Random Forest.png`
---
