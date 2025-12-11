# Drug Prediction Using Decision Tree

## Project Overview
This project implements a **Decision Tree Classifier** to predict the most appropriate drug for a patient based on medical attributes such as age, sex, blood pressure, cholesterol level, and the sodium-to-potassium (Na_to_K) ratio.

The aim of this project is to demonstrate how **machine learning can support medical decision-making** using an interpretable and high-performing classification model.

---

## Dataset Description
- **Dataset Name:** Drug200 Dataset  
- **Source:** Kaggle  
- **Total Samples:** 200  
- **Features:**
  - Age (numeric)
  - Sex (categorical)
  - Blood Pressure (categorical)
  - Cholesterol (categorical)
  - Na_to_K (numeric)
- **Target Variable:**
  - Drug Type (drugA, drugB, drugC, drugX, drugY)

---

## Machine Learning Algorithm
- **Algorithm Used:** Decision Tree Classifier  
- **Criterion:** Gini Index  
- **Tuned Maximum Depth:** 4  

### Why Decision Tree?
- High interpretability  
- Handles both numerical and categorical data  
- Easy to visualise  
- Suitable for medical decision-support systems  

---

## Project Workflow
1. Data Loading & Exploration  
2. Categorical Feature Encoding  
3. Train–Test Split (70% Training, 30% Testing)  
4. Baseline Decision Tree Training  
5. Hyperparameter Tuning using GridSearchCV  
6. Final Model Training  
7. Performance Evaluation  
8. Cross-Validation  
9. Feature Importance Analysis  
10. Decision Tree Visualisation  
11. New Patient Prediction  
12. Model Explainability (Decision Path)

---

## Model Performance
- **Final Test Accuracy:** 98.33%  
- **Mean Cross-Validation Accuracy:** 98.5%  
- **Standard Deviation:** 0.03  

The model demonstrates **excellent generalisation performance** with minimal overfitting.

---

## Key Outputs & Visualisations
The following outputs are included in the project folder:
- `confusion_matrix.png` → Multiclass confusion matrix  
- `feature_importance.png` → Feature importance bar chart  
- `depth_vs_accuracy.png` → Overfitting analysis  
- `decision_tree.png` → Decision Tree visualisation  
- `cross_validation_scores.csv` → Cross-validation results  
- `new_patient_prediction.csv` → New patient prediction output  
- `index.html` → Project webpage  

---

## New Patient Prediction
The model can predict the most suitable drug for a new patient using:
- Age  
- Sex  
- Blood Pressure  
- Cholesterol  
- Na_to_K ratio  

The system also provides:
- **Probability confidence for each drug**
- **Exact decision path followed by the tree**

---

## Ethics & Limitations
- This model is intended **only for educational purposes**
- It **must not be used in real medical practice without clinical validation**
- The dataset is small and simplified
- Incorrect predictions in real-world healthcare could have serious consequences
- Dataset bias may be present

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  
- HTML (for project webpage)

---

## Author Details
- **Student Name:** ___________________  
- **Student ID:** ___________________  
- **Course:** Machine Learning  

---

## Conclusion
This project successfully demonstrates the application of a Decision Tree classifier in a medical drug prediction scenario. The high prediction accuracy, strong cross-validation performance, and full model interpretability highlight the effectiveness of Decision Trees for healthcare-related classification tasks.

---

## License
This project is released under the MIT License.
