# ❤️ Heart Disease Prediction

This project is a **Machine Learning pipeline** to predict the presence of heart disease based on various clinical and demographic features. It includes preprocessing, training multiple models, evaluating performance, and comparing results.

---

## 📊 Dataset

The dataset contains medical records with features such as:

- Age, Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- ECG results
- Max Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- Slope of Peak Exercise
- And others...

Target column: `HeartDisease`  
- 1 = Patient has heart disease  
- 0 = No heart disease

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handling missing data
   - Encoding categorical variables
   - Feature scaling

2. **Model Training**
   - Training multiple ML models using pipelines

3. **Evaluation**
   - 5-fold cross-validation
   - Test set accuracy
   - Classification reports

4. **Visualization**
   - Feature distributions
   - Categorical value counts

---

## 🤖 Models Used

- Logistic Regression  
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree  
- Random Forest  
- Naive Bayes  
- Gradient Boosting  
- XGBoost *(optional)*

Each model is evaluated using:
- Cross-validation accuracy
- Test accuracy
- Precision / Recall / F1-score

---

## 📈 Example Results

| Model         | CV Accuracy (Mean) | Test Accuracy |
|---------------|--------------------|----------------|
| LogisticReg   | 0.85               | 0.87           |
| SVC (Linear)  | 0.86               | 0.88           |
| Random Forest | 0.87               | 0.90           |
| ...           | ...                | ...            |

> Full results and reports are shown in the output.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/AhmeddAladdin/NTI_SummerTraining_ML_Final_project.git
cd NTI_SummerTraining_ML_Final_project

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook or script
jupyter notebook main.ipynb
# or
python main.py
